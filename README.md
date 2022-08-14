# Asal-Sayi-Bulan-Program-2
Java dilinde "Recursive" metot kullanarak, kullanıcıdan alınan sayının "Asal" sayı olup olmadığını bulan programı yazın.


    import java.util.Scanner;

    public class Main {

    static void number(int a) {
        int b = 0, y = 0;
        if (a == 2 || a == 3 || a == 5 || a == 7 || a == 11) {

            System.out.println(a + " Sayısı asaldır ");

        }
        else if (a % 2 == 0 || a % 3 == 0 || a % 5 == 0 || a % 7 == 0) {
            System.out.println(a + " Sayısı asal değildir ! ");
        } else {
            System.out.println(a + " Sayısı asaldır ");
        }

    }


    public static void main(String[] args) {
        Scanner inp = new Scanner(System.in);

        System.out.print("Sayı giriniz :");
        int a = inp.nextInt();

      number(a);

     }
    }
![image](https://user-images.githubusercontent.com/107626332/184525051-8b3928d3-9992-49cd-9424-77859aa8c0f3.png)

https://app.patika.dev/ahmetfurkan
