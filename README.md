# Chapter1Lab
#Question 1 Code:




##import java.util.Scanner;

public class Main {
    public static Scanner scanner = new Scanner(System.in);

    public static String getInput(String prompt) {
        System.out.print(prompt);
        return scanner.nextLine();
    }

    public static int getIntInput(String prompt) {
        System.out.print(prompt);
        return scanner.nextInt();
    }

    public static void main(String[] args) {

        int myint= getIntInput("Enter temperture in Fahrenheit:");
        int celci= (myint-32) * 5/9;
        System.out.println(myint);
        System.out.println(celci);
        return;
        // Example usage:
        // String name = getInput("What's your name? ");
        // int age = getIntInput("What's your age? ");
        // System.out.println("Hello " + name + ", you are " + age + " years old.");
    }
}
