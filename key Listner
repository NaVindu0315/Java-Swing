package Listners;

import javax.swing.*;
import java.awt.*;
import java.awt.event.KeyEvent;
import java.awt.event.KeyListener;

public class KeyListners extends JFrame implements KeyListener {




    JLabel lbl;
    JLabel bubilbl;
    ImageIcon icon;
    ImageIcon bubi;
    public KeyListners(){
        icon = new ImageIcon("dudu.png");
        bubi = new ImageIcon("bubu.png");
         lbl = new JLabel();
         bubilbl = new JLabel();

         lbl.setBounds(0,0,100,100);
       bubilbl.setBounds(120,0,100,100);
       //  lbl.setBackground(Color.RED);
         //lbl.setOpaque(true);
        lbl.setIcon(icon);
        bubilbl.setIcon(bubi);
       // bubilbl.setIcon(bubi);
         this.add(lbl);
         this.add(bubilbl);

        this.setBackground(Color.CYAN);
        Container contentPane = this.getContentPane();
        contentPane.setBackground(Color.magenta);
        this.setSize(500,500);
        this.setDefaultCloseOperation(EXIT_ON_CLOSE);
        this.setLayout(null);
        // this.pack();
        this.setVisible(true);
        this.addKeyListener(this);
    }

    @Override
    public void keyTyped(KeyEvent e) {

            switch (e.getKeyChar())
            {
                case 'a':lbl.setLocation(lbl.getX()-10,lbl.getY());
                    break;
                case 'w':lbl.setLocation(lbl.getX(),lbl.getY()-10);
                    break;
                case 's':lbl.setLocation(lbl.getX(),lbl.getY()+10);
                    break;
                case 'd':lbl.setLocation(lbl.getX()+10,lbl.getY());
            }
    }

    @Override
    public void keyPressed(KeyEvent e) {
        switch (e.getKeyCode())
        {
            case 37: left();
                break;
            case 38: up();
                break;
            case 40: down();
                break;
            case 39: right();
        }


    }

    @Override
    public void keyReleased(KeyEvent e) {
        System.out.println("You Released key char : "+ e.getKeyChar()+ "code of code"+e.getKeyCode());
     //   System.out.println("ke");

    }

    public  void up(){
        lbl.setLocation(lbl.getX(),lbl.getY()-10);
        bubilbl.setLocation(bubilbl.getX(),bubilbl.getY()-10);
    }
    public void down()
    {
        lbl.setLocation(lbl.getX(),lbl.getY()+10);
        bubilbl.setLocation(bubilbl.getX(),bubilbl.getY()+10);
    }
    public void left()
    {
        lbl.setLocation(lbl.getX()-10,lbl.getY());
        bubilbl.setLocation(bubilbl.getX()-10,bubilbl.getY());
    }
    public void right()
    {
        lbl.setLocation(lbl.getX()+10,lbl.getY());
        bubilbl.setLocation(bubilbl.getX()+10,bubilbl.getY());
    }
}
