package components;

import javax.swing.*;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;
import java.awt.event.KeyEvent;

public class MenuButtons extends JFrame implements ActionListener {

    JMenuBar menuBar;
    JMenu filemenu =  new JMenu("Files");
    JMenu editmenu = new JMenu("Edit");
    JMenu helmenu = new JMenu("Help");

    JMenuItem loaditem = new JMenuItem("Load");
    JMenuItem saveitem = new JMenuItem("Save");

    JMenuItem exititem = new JMenuItem("exit");
    ImageIcon loadIcon;
    ImageIcon exiticon;

    public MenuButtons(){

        menuBar = new JMenuBar();

        filemenu.add(loaditem);
        filemenu.add(saveitem);
        filemenu.add(exititem);
        loaditem.addActionListener(this);
        saveitem.addActionListener(this);
        exititem.addActionListener(this);


        menuBar.add(filemenu);
        menuBar.add(helmenu);
        menuBar.add(editmenu);
        this.setJMenuBar(menuBar);
        //for keyboard shortcut
        loaditem.setMnemonic(KeyEvent.VK_L); //for load
        saveitem.setMnemonic(KeyEvent.VK_S); //save item

        loadIcon = new ImageIcon("dudu.png");
        exiticon = new ImageIcon("bubu.png");

        loaditem.setIcon(loadIcon);
        exititem.setIcon(exiticon);




        this.setSize(500,500);
        this.setDefaultCloseOperation(EXIT_ON_CLOSE);
        this.setLayout(null);
        /// this.pack();
        this.setVisible(true);
    }
    @Override
    public void actionPerformed(ActionEvent e) {
     if(e.getSource()==loaditem)
     {
         System.out.println("Paka");
     }
     else if (e.getSource()==exititem)
        {
            System.out.println("payya");
        }
        else if (e.getSource()==saveitem)
     {
         System.out.println("pnna umesh");
     }
    }
}
