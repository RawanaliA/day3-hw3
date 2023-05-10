# day3-hw3
 import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
       // to print Fizz Buzz
        Scanner s = new Scanner(System.in);
        for (int i = 1; i <= 100; i++) {
            if (i % 3 == 0 & i % 5 == 0)
                System.out.println("FizzBuzz");
            else if (i % 5 == 0)
                System.out.println("Buzz");
            else if (i % 3 == 0)
                System.out.println("Fizz");

            else
                System.out.println(i);
        }
//solve 2
        String blogName = "The quick brown fox";
        String reversedString = "";
        for (int i = blogName.length() - 1; i >= 0; i--) {
            reversedString = reversedString + blogName.charAt(i);
        }
        System.out.println("The reversed string of the '" + blogName + "' is: " + reversedString);


        //solve3اللوجيك صح بس اعدله اكثر
        System.out.println("Enter postive number");
        int user = s.nextInt();
        for (int i = 1; i <= 10; i++) {
            if (i > 0) {
                System.out.println("The Multiplucation of " +user+"*"+i+"="+ user * i);

            }
        }
        System.out.println("enter the factorial number you want ");
        int fact = s.nextInt();
        for (int i = 0; i <= fact; i++) {
            int num = fact * i;
            System.out.println("the factorial of " + fact + " is " + num);
        }
        //solve 5
        System.out.println("Enter the number one ");
        int n1 = s.nextInt();
        System.out.println("Enter the power of that number ");
        int n2 = s.nextInt();
        int power = 1;
        if (n2 >= 1) {
            for (int i = 1; i <= n2; i++) {

                power = power * n1;

            }

            System.out.println(power);

        }

        //solve n6يبغى اذا دخل مجموعه من الاعداد يطبع لي الموجبه والسالبعه

        int InputNums = 0, Odd = 0, Even = 0, loop = 0, enterByU;
        Scanner s1 = new Scanner(System.in);
        System.out.print("How many numbers you want to input: ");
       enterByU = s1.nextInt();

        while(loop<= enterByU)
        {
            loop++;
            System.out.print("Please input a number : ");
           InputNums = s1.nextInt();
            if (InputNums % 2 == 0)
            {
                Even = Even + InputNums;
            }
            else
            {
                Odd = Odd + InputNums;
            }
            if(loop == enterByU)
            {
                break;
            }
        }
        if (loop == enterByU)
        {
            System.out.println("Sum of odd numbers is : " + Odd);
            System.out.println("Sum of Even numbers is : " + Even);}

        //if InputNums is smaller than 0 there has been some error in the code
//        if (InputNums < 0)
//        {
//            System.out.print("Invalid input");
//            System.exit(0);
//        }
        // Solve 7
        System.out.println(" Enter positive integer:");
        int num1 = s.nextInt();
        for (int j = 1; j <= num1; j++) {

            if (num1 % j == 1)

                System.out.print("its a prime !");

            else {
                System.out.println("its Not a prime !");
                break;
            }
        }
        //solve 8
        Scanner c = new Scanner(System.in);
        int number,
                countP = 0,
                countN = 0,
                countZ= 0;

        char choice;

        do
        {
            System.out.print("Enter the number ");
            number = c.nextInt();

            if(number > 0)
            {
                countP++;
            }
            else if(number < 0)
            {
                countN++;
            }
            else
            {
                countZ++;
            }
            System.out.print("Do you want to continue y/n? ");
            choice = c.next().charAt(0);

        }while(choice=='y' || choice == 'Y');

        System.out.println("Positive numbers: " + countP);
        System.out.println("Negative numbers: " + countN);
        System.out.println("Zero numbers: " + countZ);

//solve 9
        for (int week = 1; week <= 4; week++) {
            System.out.println("week" + week + ":");
            for (int day = 1; day <= 7; day++)
                System.out.println("day" + day);
        }

        //solve 10
        System.out.println("Enter a String");
//        Scanner s1=new Scanner(System.in);
        String myString = s1.next();
        StringBuffer buffer = new StringBuffer(myString);
        buffer.reverse();
        String data = buffer.toString();
        if(myString.equals(data)){
            System.out.println("The String you entered is palindrome");
        } else {
            System.out.println("The String you entered is not palindrome");
        }

    }}









   
