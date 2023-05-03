# day3-hw3
  //1-Write a program that prints the numbers from 1 to 100 such that:
        Scanner s = new Scanner(System.in);
        int a = s.nextInt();
        for (int i = 1; i <= 100; i++) {
            if (i % 3 == 0 & i % 5 == 0) {
                System.out.println("FizzBuzz");
            } else if (i % 5 == 0) {
                System.out.println("Buzz");
            } else if (i % 3 == 0) {

                System.out.println("Fizz");
            }

        }

        //solve2
        String reverse = "The quick brown fox";
        String re2 = "";
        out.printf("orignail string"+reverse);
        for (int i = 0; i <= reverse.length(); i++) {
            re2 = reverse.charAt(i)+re2;
            //re2 = ch + re2;

        }
        out.println("Reversed word: " + re2);
    }
    
    //3.Write a program that prompts the user to input a positive integer. It should
    // then print the multiplication table of that number.
        System.out.println("enter postive number");
    int user = s.nextInt();
        for(int i = 1;i<=10;i++)
        {
        if (i > 0) {
            System.out.println("The result is" + user * i);

        }
    }
    //4.Write a program to find the factorial value of any number entered through the keyboard.صحيح وطلع الاوت بوت
        System.out.println("enter the factorial");
    int fact = s.nextInt();
        for(int i = 0;i<=fact;i++)
    {
        int num = fact * i;
        System.out.println("the factorial of" + num);
    }

    //5.Two numbers are entered through the keyboard. Write a program to
    // find the value of one number raised to the power of another.
    int th3,fo4;
    int fnum = s.nextInt();
        System.out.println("enter first num");
    int snum = s.nextInt();
        System.out.println("etrer second num");
    th3=1;
    fo4=snum;
        while(snum!=0){
        th3=th3*fnum;
        snum=snum-1;

    }
        System.out.println(("%d raised to the power %d: %d" + fnum,snum,th3);
}}

    //6.Write a program that reads a set of integers, and then prints the sum of the even and odd integers.

        System.out.println("ENTER THE Number. ");

        int n1 = sc.nextInt();

        System.out.println("ENTER THE POWER FOR THAT Number.");

        int n2 = sc.nextInt();

        int power = 1;

        if (n2 >= 1) {

        for (int i = 1; i <= n2; i++) {

        power = power * n1;

        }

        System.out.println(power);

        }
    }
}
//  7.Write a program that prompts the user to input a positive integer.

        System.out.print("\fEnter positive integer:");
        int num = s.nextInt();
        for(int i=1;i<=num;i++) {


        if (num % i ==1)

        System.out.print("its a prime !");

        else {
        System.out.print("its a prime !");

        }

    //8.Write a program to enter the numbers till the user wants
    // and at the end it should display the count of positive, negative and zeros entered.
        System.out.println("Enter numbers");
    int num8 = s.nextInt();
        for(int i = 0;i <=num8;i++)
    {
        int count = 0;
        if (num8 % 2 == 0) {
            count += num8;
            System.out.println("postive num:" + count);
        }
        if (num8 % 2 == 1) {
            count += num8;
            System.out.println("postive num:" + count);
        } else {
            System.out.println("postive num:" + count);
        }


    }

    //9.Use a for loop to print headings for four weeks (Weeks 1 - 4).
    // Then use another for loop to print the days (Days 1 -7) for each week.

        for(int week=1;week<=4;week++){
        out.println("week"+week+":");
        for(int day=1;day<=7;day++)
        out.println("day"+day);
        }}

        //10.Write a program thats check if the word is a palindrome or not.
        out.printf("Enter a string:");
        String pal = s.next();
        String oraginal_p = pal;
        int re3 = 0;
        for (int i = 0; i <= pal.length(); i++) {
        char ch = pal.charAt(i);
        re3 = ch + re3;

        }
        if(oraginal_p = re3){
        out.println(oraginal_p+"it is a palindrome number");
        }
        else {
        out.println(oraginal_p+"it is NOT a palindrome number");
        }
        }

        }
