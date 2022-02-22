Vücut Kitle İndeksi Hesaplama

Java ile kullanıcıdan boy ve kilo değerlerini alıp bir değişkene atayın. Aşağıdaki formüle göre kullanıcının "Vücut Kitle İndeks" değerini hesaplayıp ekrana yazdırın.
Formül = Kilo (kg) / Boy(m) * Boy(m)

import java.util.Scanner;
public class Odev6 {

    public static void main(String[] args) {

        double kilo,boy,vki ;

        Scanner input = new Scanner (System.in);
        System.out.println("Lütfen kilonuzu kg cinsinden giriniz: ");
        kilo = input.nextDouble();

        System.out.println("Lütfen boyunuzu metre cinsinden giriniz: ");
        boy = input.nextDouble();

        vki = (kilo / (boy * boy) );
        System.out.println("Vücut kitle indeksiniz: " + vki);


    }
}
