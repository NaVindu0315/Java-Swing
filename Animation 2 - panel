package Animations;

import javax.swing.*;
import java.awt.*;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;

public class Apanel extends JPanel implements ActionListener {

    final int PANEL_WIDTH = 800;
    final int PANEL_HEIGHT = 800;

    Image dudu;
    Image background;

    Timer timer;
    int xVelocity =1;
    int yVelocity = 1;
    int x=0;
    int y=0;

    Apanel(){
        this.setPreferredSize(new Dimension(PANEL_WIDTH,PANEL_WIDTH));
        this.setBackground(Color.PINK);
        dudu = new ImageIcon("mocha.PNG").getImage();
        background = new ImageIcon("bg.PNG").getImage();
        timer = new Timer(10,this);
        timer.start();




    }
    public  void paint (Graphics g)
    {
        super.paint(g);
        Graphics2D g2D = (Graphics2D) g;
        g2D.drawImage(background,x,y,null);
        g2D.drawImage(dudu,x,y,null);
    }

    @Override
    public void actionPerformed(ActionEvent e) {
        if(x>=PANEL_WIDTH-dudu.getWidth(null) ||x<0)
        {
            xVelocity = xVelocity * -1;
        }
        x =x +xVelocity;

        if (y>=PANEL_HEIGHT-dudu.getHeight(null)||y<0)
        {
            yVelocity = yVelocity * -1;
        }
        y = y+yVelocity;


        repaint();

    }
}
