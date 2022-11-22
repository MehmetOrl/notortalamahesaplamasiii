import java.util.Scanner;
public class IlkHello {
    public static void main(String[] args) {
        int mat,fiz,kim,turkce,tarih,muzik;


**java
        Scanner Input =new Scanner(System.in);
        System.out.print("Matemaik Notunuz Giriniz.:");
        mat= Input.nextInt();
        System.out.print("Fizik Notunuz Giriniz.:");
        fiz= Input.nextInt();
        System.out.print("Kimya Notunuz Giriniz.:");
        kim= Input.nextInt();
        System.out.print("Turkce Notunuz Giriniz.:");
        turkce= Input.nextInt();
        System.out.print("Tarih Notunuz Giriniz.:");
        tarih= Input.nextInt();
        System.out.print("Muzik Notunuz Giriniz.:");
        muzik= Input.nextInt();
        int toplam =mat+fiz+kim+turkce+tarih+muzik;
        double ortalama= toplam/6.0;
        System.out.println("Toplamlari.:"+toplam);
        System.out.println("ortalamasi.:"+ortalama);
        boolean s1=ortalama>=60;

        String str=s1?"geçti":"kaldi";
        System.out.println(str);







    }
}
