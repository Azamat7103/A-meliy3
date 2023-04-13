# A-meliy3
Bala tuwilg'annan baslap er-jetemen degenge shekem massa ha'm boyin esaplaw
import java.util.Scanner;
public class Main {  
 public static void main(String[] args) {
 Scanner in = new Scanner (System.in);
  int m ,a,n,sm,a1,n1;
  System.out.println("tuwilģandaģi massasin kiritiń: ? ");
    m=in.nextInt();
    System.out.println(" tuwilģandaģi massasi " + m + " kg. ");
    System.out.println(" bir ayda qansha  kg massa jiynaydi: ? ");
    a=in.nextInt();
    System.out.println(" bir ayda "  +  a + " gram massa jiynaydi");
    System.out.println("neshe aydiń massasin esaplaw kerek: ? ");
    n=in.nextInt();
    System.out.print( n+ " ayda  ");
 System.out.println(m+(a*n) + " kg massa boladi. ");
 System.out.println(" tuwilģandaģi boyi qansha sm: ? ");
    sm=in.nextInt();
 System.out.println("tuwilģandaģi boyi " + sm + " sm. ");
 System.out.println(" bir ayda neshe sm ósedi: ? ");
    a1=in.nextInt();
System.out.println(" bir ayda " + a1 + " sm ósedi. ");
    System.out.println("neshe ayda óskenin esaplaw kerek:  ? ");
    n1=in.nextInt();
    System.out.print(n1 + "  ayda ");
    System.out.println(sm+(a1*n1) + " sm ósken boladi. ");
 }
}
