# taksimetre
//patika.dev taksimetre ödev

import java.util.Scanner;
public class main {
    public static void main (String[]args){
        double km;
        double perKm= 2.20,total, startprice= 10;
        Scanner inp = new Scanner (System.in);
        System.out.println("Kaç km yol gittiniz?");
        km = inp.nextInt();
        total = ((perKm*km) + startprice);
        total = (total < 20) ? 20 : total;
        System.out.print("Ücretiniz:" + total);
    }
}
