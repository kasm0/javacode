# javacode
java kurs puzzle gama

import javax.swing.*;
class class8{

    public static void main(String[] args) {
        

        JFrame f1= new JFrame("puzzle");
        f1.setSize(520,650);
        
        f1.setLayout(null);
         f1.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);

JButton b1= new JButton("");
JButton b2= new JButton("");
JButton b3= new JButton("");
JButton b4= new JButton("");
JButton b5= new JButton("");
JButton b6= new JButton("");
JButton b7= new JButton("");
JButton b8= new JButton("");
JButton b9= new JButton("");
JButton b10= new JButton("");
JButton b11= new JButton("");
JButton b12= new JButton("");
JButton b13= new JButton("");
JButton b14= new JButton("");
JButton b15= new JButton("");
JButton b16= new JButton("");
JButton b17= new JButton("");
JButton b18= new JButton("");
JButton b19= new JButton("");
JButton b20= new JButton("");
JButton b21= new JButton("");
JButton b22= new JButton("");
JButton b23= new JButton("");
JButton b24= new JButton("");



JButton empty = new JButton("");
        JButton shuffle=new JButton("SUFFLE");
        JButton reset=new JButton("RESET");

//set icon


b1.setIcon(new ImageIcon( "C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_1.png"));
b2.setIcon(new ImageIcon("C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_2.png"));
b3.setIcon(new ImageIcon("C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_3.png"));
b4.setIcon(new ImageIcon("C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_4.png"));
b5.setIcon(new ImageIcon("C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_5.png"));
b6.setIcon(new ImageIcon("C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_6.png"));
b7.setIcon(new ImageIcon("C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_7.png"));
b8.setIcon(new ImageIcon("C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_8.png"));
b9.setIcon(new ImageIcon("C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_9.png"));
b10.setIcon(new ImageIcon("C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_10.png"));
b11.setIcon(new ImageIcon( "C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_11.png"));
b12.setIcon(new ImageIcon( "C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_12.png"));
b13.setIcon(new ImageIcon( "C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_13.png"));
b14.setIcon(new ImageIcon( "C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_14.png"));
b15.setIcon(new ImageIcon( "C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_15.png"));
b16.setIcon(new ImageIcon( "C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_16.png"));
b17.setIcon(new ImageIcon( "C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_17.png"));
b18.setIcon(new ImageIcon( "C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_18.png"));
b19.setIcon(new ImageIcon( "C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_19.png"));
b20.setIcon(new ImageIcon( "C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_20.png"));
b21.setIcon(new ImageIcon( "C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_21.png"));
b22.setIcon(new ImageIcon( "C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_22.png"));
b23.setIcon(new ImageIcon( "C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_23.png"));
b24.setIcon(new ImageIcon( "C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_24.png"));
//b25.setIcon(new ImageIcon( "C:/Users/ALYA/OneDrive/Desktop/Pic/Pic/piece_25.png"));

f1.add(b1);
f1.add(b2);
f1.add(b3);
f1.add(b4);
f1.add(b5);
f1.add(b6);
f1.add(b7);
f1.add(b8);
f1.add(b9);
f1.add(b10);
f1.add(b11);
f1.add(b12);
f1.add(b13);
f1.add(b14);
f1.add(b15);
f1.add(b16);
f1.add(b17);
f1.add(b18);
f1.add(b19);
f1.add(b20);
f1.add(b21);
f1.add(b22);
f1.add(b23);
f1.add(b24);
f1.add(empty);
f1.add(shuffle);
f1.add(reset);







b1.setBounds(0,0,100,100);
b2.setBounds(100,0,100,100);
b3.setBounds(200,0,100,100);
b4.setBounds(300,0,100,100);
b5.setBounds(400,0,100,100);
b6.setBounds(0,100,100,100);
b7.setBounds(100,100,100,100);
b8.setBounds(200,100,100,100);
b9.setBounds(300,100,100,100);
b10.setBounds(400,100,100,100);
b11.setBounds(0,200,100,100);
b12.setBounds(100,200,100,100);
b13.setBounds(200,200,100,100);
b14.setBounds(300,200,100,100);
b15.setBounds(400,200,100,100);
b16.setBounds(0,300,100,100);
b17.setBounds(100,300,100,100);
b18.setBounds(200,300,100,100);
b19.setBounds(300,300,100,100);
b20.setBounds(400,300,100,100);
b21.setBounds(0,400,100,100);
b22.setBounds(100,400,100,100);
b23.setBounds(200,400,100,100);
b24.setBounds(300,400,100,100);
empty.setBounds(400,400,100,100);
shuffle.setBounds(30,530, 100, 50);
reset.setBounds(390, 530, 100, 50);

shuffle.addActionListener(e->{
    b17.setBounds(0,0,100,100);//17
b2.setBounds(100,0,100,100);//2
b13.setBounds(200,0,100,100);//13
b22.setBounds(300,0,100,100);//22
b3.setBounds(400,0,100,100);//3
b6.setBounds(0,100,100,100);//6
b8.setBounds(100,100,100,100);//7
b7.setBounds(200,100,100,100);//8
b9.setBounds(300,100,100,100);//9
b10.setBounds(400,100,100,100);//10
b18.setBounds(0,200,100,100);//18
b21.setBounds(100,200,100,100);//21
b12.setBounds(200,200,100,100);//12
b16.setBounds(300,200,100,100);//16
b14.setBounds(400,200,100,100);//14
b20.setBounds(0,300,100,100);//20
b24.setBounds(100,300,100,100);//24
b15.setBounds(200,300,100,100);//15
b19.setBounds(300,300,100,100);//19
b5.setBounds(400,300,100,100);//5
b23.setBounds(0,400,100,100);//23
empty.setBounds(100,400,100,100);
b1.setBounds(200,400,100,100);//1
b4.setBounds(300,400,100,100);//4
b11.setBounds(400,400,100,100);//11

});


reset.addActionListener(e->{
b1.setBounds(0,0,100,100);
b2.setBounds(100,0,100,100);
b3.setBounds(200,0,100,100);
b4.setBounds(300,0,100,100);
b5.setBounds(400,0,100,100);
b6.setBounds(0,100,100,100);
b7.setBounds(100,100,100,100);
b8.setBounds(200,100,100,100);
b9.setBounds(300,100,100,100);
b10.setBounds(400,100,100,100);
b11.setBounds(0,200,100,100);
b12.setBounds(100,200,100,100);
b13.setBounds(200,200,100,100);
b14.setBounds(300,200,100,100);
b15.setBounds(400,200,100,100);
b16.setBounds(0,300,100,100);
b17.setBounds(100,300,100,100);
b18.setBounds(200,300,100,100);
b19.setBounds(300,300,100,100);
b20.setBounds(400,300,100,100);
b21.setBounds(0,400,100,100);
b22.setBounds(100,400,100,100);
b23.setBounds(200,400,100,100);
b24.setBounds(300,400,100,100);
empty.setBounds(400,400,100,100);
});



b1.addActionListener(e -> {
    int b1x = b1.getBounds().x;
    int b1y = b1.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b1x - emptyx) == 100 && b1y == emptyy) || (Math.abs(b1y - emptyy) == 100 && b1x == emptyx)) {
        b1.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b1x, b1y, 100, 100);
    }
});

b2.addActionListener(e -> {
    int b2x = b2.getBounds().x;
    int b2y = b2.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b2x - emptyx) == 100 && b2y == emptyy) || (Math.abs(b2y - emptyy) == 100 && b2x == emptyx)) {
        b2.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b2x, b2y, 100, 100);
    }
});

b3.addActionListener(e -> {
    int b3x = b3.getBounds().x;
    int b3y = b3.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b3x - emptyx) == 100 && b3y == emptyy) || (Math.abs(b3y - emptyy) == 100 && b3x == emptyx)) {
        b3.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b3x, b3y, 100, 100);
    }
});

b4.addActionListener(e -> {
    int b4x = b4.getBounds().x;
    int b4y = b4.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b4x - emptyx) == 100 && b4y == emptyy) || (Math.abs(b4y - emptyy) == 100 && b4x == emptyx)) {
        b4.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b4x, b4y, 100, 100);
    }
});

b5.addActionListener(e -> {
    int b5x = b5.getBounds().x;
    int b5y = b5.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b5x - emptyx) == 100 && b5y == emptyy) || (Math.abs(b5y - emptyy) == 100 && b5x == emptyx)) {
        b5.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b5x, b5y, 100, 100);
    }
});

b6.addActionListener(e -> {
    int b6x = b6.getBounds().x;
    int b6y = b6.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b6x - emptyx) == 100 && b6y == emptyy) || (Math.abs(b6y - emptyy) == 100 && b6x == emptyx)) {
        b6.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b6x, b6y, 100, 100);
    }
});

b7.addActionListener(e -> {
    int b7x = b7.getBounds().x;
    int b7y = b7.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b7x - emptyx) == 100 && b7y == emptyy) || (Math.abs(b7y - emptyy) == 100 && b7x == emptyx)) {
        b7.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b7x, b7y, 100, 100);
    }
});

b8.addActionListener(e -> {
    int b8x = b8.getBounds().x;
    int b8y = b8.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b8x - emptyx) == 100 && b8y == emptyy) || (Math.abs(b8y - emptyy) == 100 && b8x == emptyx)) {
        b8.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b8x, b8y,100, 100);
    }
});

b9.addActionListener(e -> {
    int b9x = b9.getBounds().x;
    int b9y = b9.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b9x - emptyx) == 100 && b9y == emptyy) || (Math.abs(b9y - emptyy) == 100 && b9x == emptyx)) {
        b9.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b9x, b9y, 100, 100);
    }
});

b10.addActionListener(e -> {
    int b10x = b10.getBounds().x;
    int b10y = b10.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b10x - emptyx) == 100 && b10y == emptyy) || (Math.abs(b10y - emptyy) == 100 && b10x == emptyx)) {
        b10.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b10x, b10y, 100, 100);
    }
});

b11.addActionListener(e -> {
    int b11x = b11.getBounds().x;
    int b11y = b11.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b11x - emptyx) == 100 && b11y == emptyy) || (Math.abs(b11y - emptyy) == 100 && b11x == emptyx)) {
        b11.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b11x, b11y, 100, 100);
    }
});

b12.addActionListener(e -> {
    int b12x = b12.getBounds().x;
    int b12y = b12.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b12x - emptyx) == 100 && b12y == emptyy) || (Math.abs(b12y - emptyy) == 100 && b12x == emptyx)) {
        b12.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b12x, b12y, 100, 100);
    }
});

b13.addActionListener(e -> {
    int b13x = b13.getBounds().x;
    int b13y = b13.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b13x - emptyx) == 100 && b13y == emptyy) || (Math.abs(b13y - emptyy) == 100 && b13x == emptyx)) {
        b13.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b13x, b13y, 100, 100);
    }
});

b14.addActionListener(e -> {
    int b14x = b14.getBounds().x;
    int b14y = b14.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b14x - emptyx) == 100 && b14y == emptyy) || (Math.abs(b14y - emptyy) == 100 && b14x == emptyx)) {
        b14.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b14x, b14y, 100, 100);
    }
});

b15.addActionListener(e -> {
    int b15x = b15.getBounds().x;
    int b15y = b15.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b15x - emptyx) == 100 && b15y == emptyy) || (Math.abs(b15y - emptyy) == 100 && b15x == emptyx)) {
        b15.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b15x, b15y, 100, 100);
    }
});

b16.addActionListener(e -> {
    int b16x = b16.getBounds().x;
    int b16y = b16.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b16x - emptyx) == 100 && b16y == emptyy) || (Math.abs(b16y - emptyy) == 100 && b16x == emptyx)) {
        b16.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b16x, b16y, 100, 100);
    }
});

b17.addActionListener(e -> {
    int b17x = b17.getBounds().x;
    int b17y = b17.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b17x - emptyx) == 100 && b17y == emptyy) || (Math.abs(b17y - emptyy) == 100 && b17x == emptyx)) {
        b17.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b17x, b17y, 100, 100);
    }
});

b18.addActionListener(e -> {
    int b18x = b18.getBounds().x;
    int b18y = b18.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b18x - emptyx) == 100 && b18y == emptyy) || (Math.abs(b18y - emptyy) == 100 && b18x == emptyx)) {
        b18.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b18x, b18y, 100, 100);
    }
});

b19.addActionListener(e -> {
    int b19x = b19.getBounds().x;
    int b19y = b19.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b19x - emptyx) == 100 && b19y == emptyy) || (Math.abs(b19y - emptyy) == 100 && b19x == emptyx)) {
        b19.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b19x, b19y, 100, 100);
    }
});

b20.addActionListener(e -> {
    int b20x = b20.getBounds().x;
    int b20y = b20.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b20x - emptyx) == 100 && b20y == emptyy) || (Math.abs(b20y - emptyy) == 100 && b20x == emptyx)) {
        b20.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b20x, b20y, 100, 100);
    }
});

b21.addActionListener(e -> {
    int b21x = b21.getBounds().x;
    int b21y = b21.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b21x - emptyx) == 100 && b21y == emptyy) || (Math.abs(b21y - emptyy) == 100 && b21x == emptyx)) {
        b21.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b21x, b21y, 100, 100);
    }
});

b22.addActionListener(e -> {
    int b22x = b22.getBounds().x;
    int b22y = b22.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b22x - emptyx) == 100 && b22y == emptyy) || (Math.abs(b22y - emptyy) == 100 && b22x == emptyx)) {
        b22.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b22x, b22y, 100, 100);
    }
    });

b23.addActionListener(e -> {
    int b23x = b23.getBounds().x;
    int b23y = b23.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b23x - emptyx) == 100 && b23y == emptyy) || (Math.abs(b23y - emptyy) == 100 && b23x == emptyx)) {
        b23.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b23x, b23y, 100, 100);
    }
});




b24.addActionListener(e -> {
    int b24x = b24.getBounds().x;
    int b24y = b24.getBounds().y;
    int emptyx = empty.getBounds().x;
    int emptyy = empty.getBounds().y;

    if ((Math.abs(b24x - emptyx) == 100 && b24y == emptyy) || (Math.abs(b24y - emptyy) == 100 && b24x == emptyx)) {
        b24.setBounds(emptyx, emptyy, 100, 100);
        empty.setBounds(b24x, b24y, 100, 100);
    }
});





f1.setVisible(true);
    }
}
