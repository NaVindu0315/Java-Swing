package components;

import javax.swing.*;
import java.awt.*;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;

public class RadioButtons extends JFrame implements ActionListener {

    JRadioButton pizzabtn;
    JRadioButton hamburgerbtn;
    JRadioButton hotdogbtn;

    ImageIcon pizzaiocn;
    ImageIcon hamicon;
    ImageIcon hoticon;
    public RadioButtons(){

        pizzaiocn = new ImageIcon("dudu.png");
        hamicon = new ImageIcon("bubu.png");
        hoticon = new ImageIcon("dudu.png");

        pizzabtn = new JRadioButton("Pizza");
        pizzabtn.setIcon(pizzaiocn);
        pizzabtn.addActionListener(this);
        hamburgerbtn = new JRadioButton("Hamburger");
        hamburgerbtn.setIcon(hamicon);
        hamburgerbtn.addActionListener(this);
        hotdogbtn = new JRadioButton("Hot Dog");
        hotdogbtn.addActionListener(this);
        hotdogbtn.setIcon(hoticon);


        ButtonGroup group = new ButtonGroup();
        group.add(pizzabtn);
        group.add(hamburgerbtn);
        group.add(hotdogbtn);

        this.add(pizzabtn);
        this.add(hamburgerbtn);
        this.add(hotdogbtn);


        this.setDefaultCloseOperation(EXIT_ON_CLOSE);
        this.setLayout(new FlowLayout());
        this.pack();
        this.setVisible(true);
    }


    @Override
    public void actionPerformed(ActionEvent e) {
        if(e.getSource()==pizzabtn)
        {
            System.out.println("Pizza pako");
        }
       else if (e.getSource()==hamburgerbtn)
        {
            System.out.println("Hamburger");
        }
       else if (e.getSource()==hotdogbtn)
        {
            System.out.println("Hot dog pko");
        }

    }
}
