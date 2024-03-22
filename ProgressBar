package components;

import javax.swing.*;
import java.awt.*;

public class ProgressBars extends JFrame {
    JProgressBar bar = new JProgressBar();

    public ProgressBars(){
    bar.setValue(0);
    bar.setBounds(0,0,420,50);
    bar.setFont(new Font("MV Boli",Font.BOLD,25));
    bar.setForeground(Color.RED);
    bar.setBackground(Color.BLACK);


        this.add(bar);
        this.setSize(500,500);
        this.setDefaultCloseOperation(EXIT_ON_CLOSE);
        this.setLayout(null);
       /// this.pack();
        this.setVisible(true);
        fill();
    }
     public void fill(){
        int counter = 0;
        while (counter<=100)
        {
            bar.setValue(counter);
            try
            {
                Thread.sleep(50);
            }
            catch (InterruptedException e)
            {
                e.printStackTrace();
            }
            counter +=1;

        }
        bar.setString("DOne");
    }
}
