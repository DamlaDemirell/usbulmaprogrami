import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int number;
        Scanner input = new Scanner(System.in);
        System.out.println("Sınır sayısını giriniz:");
        number = input.nextInt();

        System.out.println("Dördün katları:");
        for(int i = 1; i <= number; i*=4)
            {
            System.out.println(i);
            }

        System.out.println("Beşin katları:");
        for(int i = 1; i <= number; i*=5)
            {
            System.out.println(i);
            }

    }


}
