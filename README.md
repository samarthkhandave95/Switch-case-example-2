# Switch-case-example-2
switch case using java
import java.util.Scanner;

public class switchexample {
    public static void main(String[] args) {

        //int x = 10;
        Scanner scanner = new Scanner(System.in);
        String result = null;
        int x = scanner.nextInt();
        if (x > 10)
            System.out.println("invalid input");
        else {
            switch (x) {
                case 1:

                    result = "I";
                    break;
                case 2:
                    result = "II";
                    break;
                case 3:
                    result = "III";
                    break;
                case 4:
                    result = "IV";
                    break;
                case 5:
                    result = "v";
                    break;
                case 6:
                    result = "vI";
                    break;
                case 7:
                    result = "VII";
                    break;


                default:
                System.out.println("invalid input");
            }
            System.out.println("Your number is " + result);
        }
    }
}
