package components;

import javax.swing.*;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;
import java.io.File;

public class FileChoosers extends JFrame implements ActionListener {


    JButton btn;
    public FileChoosers(){

    btn = new JButton("select FIle");
    btn.addActionListener(this);

    this.add(btn);



        this.setSize(500,500);
        this.setDefaultCloseOperation(EXIT_ON_CLOSE);
        //this.setLayout(null);
        /// this.pack();
        this.setVisible(true);
    }

    @Override
    public void actionPerformed(ActionEvent e) {
    if (e.getSource()==btn)
    {

        JFileChooser fileChooser = new JFileChooser();
        fileChooser.setCurrentDirectory(new File("."));
        int response = fileChooser.showOpenDialog(null);
        if (response == JFileChooser.APPROVE_OPTION)
        {
            File file = new File(fileChooser.getSelectedFile().getAbsolutePath());
            System.out.println(file);

        }
    }
    }
}
