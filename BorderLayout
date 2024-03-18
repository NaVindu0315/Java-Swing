package layouts;

import javax.swing.*;
import java.awt.*;

public class BorderLayouts extends JFrame {

    public BorderLayouts(){

        this.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        this.setSize(750,750);
        this.setLayout(null); //to manually change the location of components defualt border layout or something
        this.setVisible(true);
        this.setLayout(new BorderLayout(10,0));


        JPanel panel1 = new JPanel();
        JPanel panel2 = new JPanel();
        JPanel panel3 = new JPanel();
        JPanel panel4 = new JPanel();
        JPanel panel5 = new JPanel();

        panel1.setBackground(Color.RED);
        panel2.setBackground(Color.green);
        panel3.setBackground(Color.yellow);
        panel4.setBackground(Color.magenta);
        panel5.setBackground(Color.blue);

        panel5.setLayout(new BorderLayout());

        panel1.setPreferredSize(new Dimension(100,50));

        panel2.setPreferredSize(new Dimension(100,100));

        panel3.setPreferredSize(new Dimension(100,100));

        panel4.setPreferredSize(new Dimension(100,100));

        panel5.setPreferredSize(new Dimension(100,100));

        ///-----sub  panels

        JPanel panel6 = new JPanel();
        JPanel panel7 = new JPanel();
        JPanel panel8 = new JPanel();
        JPanel panel9 = new JPanel();
        JPanel panel10 = new JPanel();

        panel6.setBackground(Color.black);
        panel7.setBackground(Color.darkGray);
        panel8.setBackground(Color.gray);
        panel9.setBackground(Color.lightGray);
        panel10.setBackground(Color.white);

        panel6.setPreferredSize(new Dimension(50,50));

        panel7.setPreferredSize(new Dimension(50,50));

        panel8.setPreferredSize(new Dimension(50,50));

        panel9.setPreferredSize(new Dimension(50,50));

        panel10.setPreferredSize(new Dimension(50,50));

        panel5.add(panel6,BorderLayout.NORTH);

        panel5.add(panel7,BorderLayout.WEST);
        panel5.add(panel8,BorderLayout.EAST);
        panel5.add(panel9,BorderLayout.SOUTH);
        panel5.add(panel10,BorderLayout.CENTER);



        // ------panels end


        this.add(panel1,BorderLayout.NORTH);
        this.add(panel2,BorderLayout.WEST);
        this.add(panel3,BorderLayout.EAST);
        this.add(panel4,BorderLayout.SOUTH);
        this.add(panel5,BorderLayout.CENTER);


    }
}
