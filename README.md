package simpleinterestcal;
import java.util.Scanner;
public class Simpleinterestcal {
    public static void main(String[] args) { 
        Scanner scanner = new Scanner(System.in);
        System.out.print("Enter the principal amount: ");
        double principal = scanner.nextDouble();
        System.out.print("Enter the rate of interest (in percentage): ");
        double rate = scanner.nextDouble();
        System.out.print("Enter the time period (in years): ");
        double time = scanner.nextDouble();
        double interest = (principal * rate * time) / 100;
        System.out.println("The Simple Interest is: " + interest);
        scanner.close();
    }
}


Output
run:
Enter the principal amount: 25000
Enter the rate of interest (in percentage): 5
Enter the time period (in years): 5
The Simple Interest is: 6250.0
