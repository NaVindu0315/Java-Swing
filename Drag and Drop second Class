package DRGDROP;

import javax.swing.*;
import java.awt.*;
import java.awt.event.MouseAdapter;
import java.awt.event.MouseEvent;
import java.awt.event.MouseMotionAdapter;

public class DragClass extends JPanel{


    ImageIcon image = new ImageIcon("dudu.png");
   final int WIDTH = image.getIconWidth();
   final int HEIGHT = image.getIconHeight();
    Point imageCorner ;
    Point prevpt;
    DragClass(){

        imageCorner = new Point(0,0);
        ClickListner clickListner = new ClickListner();
        DragListner dragListner = new DragListner();
        this.addMouseListener(clickListner);
        this.addMouseMotionListener(dragListner);

    }

    public void paintComponent(Graphics g){

        super.paintComponent(g);
        image.paintIcon(this,g,(int) imageCorner.getX(),(int)imageCorner.getY());

    }

    private  class ClickListner extends MouseAdapter{
            public  void mousePressed(MouseEvent e)
            {
                prevpt = e.getPoint();
            }
    }

    private  class DragListner extends MouseMotionAdapter
    {
        public void mouseDragged(MouseEvent e)
        {
            Point currenpt = e.getPoint();
            imageCorner.translate(
                    (int)(currenpt.getX()-prevpt.getX()),
                    (int)(currenpt.getY()-prevpt.getY())
            );
            prevpt = currenpt;
            repaint();

        }
    }
}
