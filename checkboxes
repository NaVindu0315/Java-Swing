package components;

import javax.swing.*;
import java.awt.*;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;
import java.util.jar.JarFile;

public class CheckBoxes extends JFrame implements ActionListener {
    JButton button = new JButton("Submit");
    JCheckBox checkBox = new JCheckBox();

    ImageIcon doo;
    ImageIcon boo;
    public CheckBoxes(){

        doo = new ImageIcon("dudu.png");
        boo = new ImageIcon("bubu.png");
        button.addActionListener(this);
        JCheckBox checkBox = new JCheckBox();
        checkBox.setText("umesh ponnayekd");
        checkBox.setFocusable(false);
        checkBox.setFont(new Font("Consolas",Font.PLAIN,35));
        checkBox.setIcon(doo);
        checkBox.setSelectedIcon(boo);


        this.add(checkBox);
        this.add(button);






        this.setDefaultCloseOperation(EXIT_ON_CLOSE);
        this.setLayout(new FlowLayout());
        this.pack();
        this.setVisible(true);
    }

    @Override
    public void actionPerformed(ActionEvent e) {
        if(e.getSource()==button)
        {
            System.out.println(checkBox.isSelected());
        }
    }
}
