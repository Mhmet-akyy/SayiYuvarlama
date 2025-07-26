# SayiYuvarlama
import java.util.Scanner;

public class SayiYuvarlama {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Ondalıklı bir sayı giriniz: ");
        double sayi = scanner.nextDouble();

        int asagiYuvarlama = (int) Math.floor(sayi);     // Aşağı yuvarlama
        int yukariYuvarlama = (int) Math.ceil(sayi);     // Yukarı yuvarlama
        int enYakin = (int) Math.round(sayi);            // En yakın tam sayıya yuvarlama

        System.out.println("Aşağı Yuvarlama: " + asagiYuvarlama);
        System.out.println("Yukarı Yuvarlama: " + yukariYuvarlama);
        System.out.println("En Yakın Tam Sayı: " + enYakin);
    }
}
