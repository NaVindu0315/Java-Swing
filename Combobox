package components;

import javax.swing.*;
import java.awt.*;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;

public class ComboBoxes extends JFrame implements ActionListener  {



      JComboBox combbox;
    public ComboBoxes(){

        //combbox.addActionListener(this);
        String[] animals = {"Pakaya","Ponnaya","wesa ponnaya umesh"};
        combbox = new JComboBox(animals);
        this.add(combbox);
        combbox.addActionListener(this);



        this.setDefaultCloseOperation(EXIT_ON_CLOSE);
        this.setLayout(new FlowLayout());
        this.pack();
        this.setVisible(true);
    }
    @Override
    public void actionPerformed(ActionEvent e) {

        if (e.getSource()==combbox)
        {
          System.out.println(combbox.getSelectedIndex());
        }

    }
}
