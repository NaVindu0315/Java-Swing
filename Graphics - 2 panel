package Graphics;

import javax.swing.*;
import java.awt.*;

public class Gpanel extends JPanel {
    Image image;
    Gpanel(){
        image = new ImageIcon("dudu.png").getImage();
        this.setPreferredSize(new Dimension(500,500));
    }

    public void paint(Graphics g)
    {
        Graphics2D g2D = (Graphics2D)  g;
      //  g2D.setStroke(new BasicStroke(5));
        g2D.setPaint(Color.BLUE);
       // g2D.drawLine(0,0,500,500);
       // g2D.drawRect(0,0,100,200);
     //   g2D.fillRect(0,0,100,200);
       // g2D.drawOval(0,0,100,100);
        //g2D.fillOval(0,0,100,200);

        //g2D.drawArc(0,0,100,100,90,180);
        //to draw the  image
      //  g2D.setPaint(Color.RED);
        //g2D.drawArc(0,0,100,100,0,180);
        //g2D.fillArc(0,0,100,100,0,180);

        //g2D.setPaint(Color.white);
        //g2D.fillArc(0,0,100,100,180,180);

        //int[] xpoints = {150,250,350};
      //  int[] ypoints = {300,150,350};
        //g2D.drawPolygon(xpoints,ypoints,3);

        //g2D.drawString("u R A Winner",50,50);

        g2D.drawImage(image,0,0,null);
    }
}
