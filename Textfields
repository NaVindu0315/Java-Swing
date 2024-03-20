package components;

import javax.swing.*;
import java.awt.*;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;

public class TextFields extends JFrame implements ActionListener {
    JTextField textField = new JTextField();
    JButton jbtn = new JButton("Submit");

    public TextFields(){
        this.setDefaultCloseOperation(EXIT_ON_CLOSE);
        this.setLayout(new FlowLayout());
        this.pack();
        this.setVisible(true);


        textField.setPreferredSize(new Dimension(250,40));
        textField.setFont(new Font("Consolas",Font.PLAIN,35));
        textField.setForeground(Color.GREEN);
        textField.setBackground(Color.black);
        textField.setCaretColor(Color.white);
        textField.setText("username");





        jbtn.addActionListener(this);


        this.add(jbtn);
        this.add(textField);
        this.pack();
        this.setVisible(true);
    }


    @Override
    public void actionPerformed(ActionEvent e) {
    if(e.getSource()==jbtn)
    {

        System.out.println("welcome "+textField.getText());
        //once clciked
        jbtn.setEnabled(false);
        textField.setEditable(false);
    }
    }
}
