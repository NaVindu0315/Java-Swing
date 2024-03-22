package components;

import javax.swing.*;
import javax.swing.event.ChangeEvent;
import javax.swing.event.ChangeListener;
import java.awt.*;
import java.awt.event.ActionListener;

public class Sliders extends JFrame implements ChangeListener {

        JPanel panel;
        JLabel label;
        JSlider slider;

    public Sliders(){

        this.setTitle("Title demo");
        panel = new JPanel();
        label = new JLabel();
        slider = new JSlider(0,100,50); //first last and starting point
        slider.setPreferredSize(new Dimension(400,200));
        slider.setPaintTicks(true);
        slider.setMinorTickSpacing(10);
        slider.setPaintTrack(true);
        slider.setMajorTickSpacing(10);
        //to make the slider verical
    slider.setOrientation(SwingConstants.VERTICAL);
        slider.setPaintLabels(true);
        slider.addChangeListener(this);


        panel.add(label);
       panel.add(slider);
       this.add(panel);

        this.setDefaultCloseOperation(EXIT_ON_CLOSE);
        this.setLayout(new FlowLayout());
        this.pack();
        this.setVisible(true);



    }
    @Override
    public void stateChanged(ChangeEvent e) {

        label.setText("c = "+slider.getValue());
    }
}
