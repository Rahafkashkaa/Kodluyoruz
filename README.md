# Kodluyoruz
Vücut Kitle 
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {

        double boy,kilo;
        double vke;

        Scanner input = new Scanner(System.in);
        System.out.println("Boyunuzu giriniz (metre cinsizden) : ");
        boy = input.nextDouble();

        Scanner input2 = new Scanner(System.in);
        System.out.println("Kilonuzu giriniz (kg cinsinden) : ");
        kilo = input2.nextDouble();

        vke=kilo/(boy*boy);
        System.out.println("Vücut kitle indeksiniz :" + vke);


    }
}
