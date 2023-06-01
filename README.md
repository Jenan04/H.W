# H.W
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 */

package com.mycompany.arry;

import java.util.Scanner;

/**
 *
 * @author HP
 */
public class Arry {

    public static void main(String[] args) {
      //1. Write a java program:ask the user to input the name and the age and print them
        
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Enter the name: ");
        String name = scanner.nextLine();
        
        System.out.print("Enter the age: ");
        int age = scanner.nextInt();
        
        System.out.println("Your name is: " + name + ", your age is: " + age);
        //2. Write a java program:ask the user to input two numbers and arrange it: Descending, Ascending
         
        System.out.print("Enter the first number: ");
        int num1 = scanner.nextInt();
        
        System.out.print("Enter the second number: ");
        int num2 = scanner.nextInt();
        
        if (num1 > num2) {
            System.out.println(num1 + " is greater than " + num2);
        } else if (num1 < num2) {
            System.out.println(num1 + " is smaller than " + num2);
        } else {
            System.out.println(num1 + " is equal to " + num2);
        }
    //3.Java program to get user input for name and age:
         System.out.print("Enter the third number: ");
        int num3 = scanner.nextInt();
        
        System.out.print("Enter the fourth number: ");
        int num4 = scanner.nextInt();
        
        int sum = num1 + num2 + num3 + num4;
        double average = (double) sum / 4;
        
        System.out.println("The sum is: " + sum + ", the average is: " + average);
    //4.
    System.out.print("Enter the number: ");
        int number = scanner.nextInt();
        
        if (number % 2 == 0) {
            System.out.println("It's even");
        } else {
            System.out.println("It's odd");
        }
    //5.
    System.out.print("Enter the username: ");
        String username = scanner.nextLine();
        
        if (username.equals("true")) {
            System.out.print("Enter the password: ");
            String password = scanner.nextLine();
            
            if (password.equals("true")) {
                System.out.println("Hello");
            } else {
                System.out.println("Incorrect password");
            }
        } else {
            System.out.println("Incorrect username");}
     //6.Java program to perform arithmetic operations based on user input:
         System.out.print("Enter the first number: ");
        double num = scanner.nextDouble();
        
        System.out.print("Enter the second number: ");
        double numm = scanner.nextDouble();
        
        System.out.println("Choose the operation:");
        System.out.println("1. +");
        System.out.println("2. -");
        System.out.println("3. *");
        System.out.println("4. ÷");
        System.out.print("Enter your choice: ");
        int choice = scanner.nextInt();
        
        double result;
        
        switch (choice) {
            case 1:
                result = num + numm;
                System.out.println("The result is: " + result);
                break;
            case 2:
                result = num - numm;
                System.out.println("The result is: " + result);
                break;
            case 3:
                result = num * numm;
                System.out.println("The result is: " + result);
                break;
            case 4:
                if (numm != 0) {
                    result = num / numm;
                    System.out.println("The result is: " + result);
                } else {
                    System.out.println("Cannot divide by zero!");
                }
                break;
            default:
                System.out.println("Invalid choice!");
        }
       //7.  Java program to calculate the result and remainder of division
                System.out.print("Enter the first number: ");
        int numb = scanner.nextInt();
        
        System.out.print("Enter the second number: ");
        int num22 = scanner.nextInt();
        
        int result1 = numb / num22;
        int remainder = numb % num22;
        
        System.out.println("The result is: " + result1);
        System.out.println("The remainder is: " + remainder);
        //8.Java program to swap the values of two variables:
        int a = 5;
        int b = 10;
        
        System.out.println("Before swapping:");
        System.out.println("a = " + a);
        System.out.println("b = " + b);
        
        // Swap the values without using a new variable
        a = a + b;
        b = a - b;
        a = a - b;
        
        System.out.println("After swapping:");
        System.out.println("a = " + a);
        System.out.println("b = " + b);
        //9.Java program to print the corresponding day based on user input:
        System.out.print("Enter the day (sa, su, mo, tu, we, th, fr): ");
        String input = scanner.nextLine();
        
        String day;
        
        switch (input) {
            case "sa":
                day = "Saturday";
                break;
            case "su":
                day = "Sunday";
                break;
            case "mo":
                day = "Monday";
                break;
            case "tu":
                day = "Tuesday";
                break;
            case "fr":
                day="Friday";
                break;
                
    } 
    //10.Java program to calculate the area of a rectangle:
        System.out.print("Enter the length of the rectangle: ");
        int length = scanner.nextInt();
        
        System.out.print("Enter the width of the rectangle: ");
        int width = scanner.nextInt();
        
        int area = length * width;
        
        System.out.println("The area is: " + area);
    //11.
        System.out.print("Enter the radius of the circle: ");
        double radius = scanner.nextDouble();
        
        double area1 = Math.PI * radius * radius;
        
        System.out.println("The area is: " + area1);
    //12.
        System.out.print("Enter the length of the cube: ");
        double length1 = scanner.nextDouble();
        
        double volume = length1 * length1 * length1;
        
        System.out.println("The volume is: " + volume);
    //13.
        System.out.print("Enter a string: ");
        String inpu = scanner.nextLine();
        
        int length2 = inpu.length();
        
        System.out.println("The length is: " + length2);
    //14.
        System.out.print("Enter a number: ");
        int numbe = scanner.nextInt();
        
        int result3 = Math.abs(numbe);
        
        System.out.println("The result is: " + result3);
    //15.
         System.out.print("Enter a number: ");
        int number1 = scanner.nextInt();
        
        if (number1 > 0) {
            System.out.println("The number is positive");
        } else if (number1 < 0) {
            System.out.println("The number is negative");
        } else {
            System.out.println("The number is zero");
        }
    //16.
        System.out.print("Enter a number: ");
        int number2 = scanner.nextInt();
        
        String weekday;
        
        switch (number2) {
            case 1:
                weekday = "Sunday";
                break;
            case 2:
                weekday = "Monday";
                break;
            case 3:
                weekday = "Tuesday";
                break;
            case 4:
                weekday = "Wednesday";
                break;
            case 5:
                weekday = "Thursday";
                break;
            case 6:
                weekday = "Friday";
                break;
            case 7:
                weekday = "Saturday";
                break;
            default:
                weekday = "Invalid number";
        }
        
        System.out.println("The result is: " + weekday);
    //17.
        System.out.print("Enter the year: ");
        int year = scanner.nextInt();
        
        boolean isLeapYear = false;
        
        if (year % 4 == 0) {
            if (year % 100 == 0) {
                if (year % 400 == 0) {
                    isLeapYear = true;
                }
            } else {
                isLeapYear = true;
            }
        }
        
        if (isLeapYear) {
            System.out.println("It's a leap year");
        } else {
            System.out.println("It's not a leap year");
        }
    //18.    
        System.out.print("Enter the first value: ");
        int value1 = scanner.nextInt();
        
        System.out.print("Enter the second value: ");
        int value2 = scanner.nextInt();
        
        System.out.print("Enter the third value: ");
        int value3 = scanner.nextInt();
        
        int max = Math.max(Math.max(value1, value2), value3);
        int min = Math.min(Math.min(value1, value2), value3);
        
        System.out.println("Maximum value: " + max);
        System.out.println("Minimum value: " + min);
    //19.
         System.out.print("Enter a character: ");
        char character = scanner.nextLine().charAt(0);
        
        System.out.println("The character is: " + character);
    //20.
        System.out.print("Enter your weight in kilograms: ");
        double weight = scanner.nextDouble();
        
        System.out.print("Enter your height in meters: ");
        double height = scanner.nextDouble();
        
        double bmi = weight / (height * height);
        
        if (bmi <= 20) {
            System.out.println("You should increase your weight");
        } else if (bmi > 20 && bmi <= 25) {
            System.out.println("Perfect weight");
        } else if (bmi > 25 && bmi <= 30) {
            System.out.println("You should lose some weight");
        } else {
            System.out.println("Overload");
        }
    
}
}

file2
/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 */

package com.mycompany.file2;

import java.util.Scanner;

/**
 *
 * @author HP
 */
public class File2 {
    static Scanner scanner = new Scanner(System.in);
    
    public static void multiplication(int a){
      
        for (int i = 1; i <= 10; i++) {
            for (int j = 1; j <= a; j++) {
                int product = i * j;
                System.out.println(j + "*" + i + " = " + product);
            } 
    }
    }

public static int getSumOfOddNumbers() {
        int sum = 0;
        int count = 0;
        int number = 1;
        
        while (count < 100) {
            if (number % 2 != 0) {
                sum += number;
                count++;
            }
            
            number++;
        }
        
        return sum;
    }

public static void printNumberTriangle(int rows) {
        for (int i = 1; i <= rows; i++) {
            for (int j = 1; j <= i; j++) {
                System.out.print(i + " ");
            }
            System.out.println();
        }
    }

  public static long calculateFactorial(int number) {
        if (number < 0) {
            throw new IllegalArgumentException("Factorial is not defined for negative numbers.");
        }
        
        long factorial = 1;
        
        for (int i = 1; i <= number; i++) {
            factorial *= i;
        }
        
        return factorial;
    }
    public static void reverseNumbers(int[] numbers) {
        int left = 0;
        int right = numbers.length - 1;
        
        while (left < right) {
            int temp = numbers[left];
            numbers[left] = numbers[right];
            numbers[right] = temp;
            
            left++;
            right--;
        }
    }
    
    public static int getAbsoluteValue(int number) {
        if (number < 0) {
            return -number;
        } else {
            return number;
        }
    }
    
    public static int getPower(int base, int power) {
        int result = 1;
        
        for (int i = 0; i < power; i++) {
            result *= base;
        }
        
        return result;
    }
    public static void signIn() {
        System.out.print("Enter the username: ");
        String username = scanner.nextLine();
        
        if (username.equals("Alazhar")) {
            System.out.print("Enter the password: ");
            String password = scanner.nextLine();
            
            if (password.equals("university")) {
                System.out.println("Sign In Successfully");
            } else {
                System.out.println("Invalid password. Sign in failed.");
            }
        } else {
            System.out.println("Invalid username. Sign in failed.");
        }
    }

    public static void printTrianglePattern(int rows) {
        int num;
        
        for (int i = 0; i < rows; i++) {
            num = i % 2;
            
            for (int j = 0; j <= i; j++) {
                System.out.print(num + " ");
                num = 1 - num;
            }
            
            System.out.println();
        }
    }
    
    public static void printSquareNumbers(int start, int end) {
        for (int i = start; i <= end; i++) {
            int square = i * i;
            System.out.println(square + " : " + i);
        }
    }
    public static void printAsteriskPattern() {
        for (int i = 1; i <= 5; i++) {
            for (int j = 1; j <= i; j++) {
                System.out.print("* ");
            }
            System.out.println();
        }
        
        for (int i = 4; i >= 1; i--) {
            for (int j = 1; j <= i; j++) {
                System.out.print("* ");
            }
            System.out.println();
        }
    }
    
    public static void printNumberPattern() {
        for (int i = 5; i >= 1; i--) {
            for (int j = i; j >= 1; j--) {
                System.out.print(j + " ");
            }
            System.out.println();
        }
    }
    
    public static int findMaxValue(int a, int b, int c) {
        int max = a;
        
        if (b > max) {
            max = b;
        }
        
        if (c > max) {
            max = c;
        }
        
        return max;
    }
    
    public static int findMinValue(int a, int b, int c) {
        int min = a;
        
        if (b < min) {
            min = b;
        }
        
        if (c < min) {
            min = c;
        }
        
        return min;
    }
    public static void checkNumberSign(int number) {
        if (number > 0) {
            System.out.println("It's Positive");
        } else if (number < 0) {
            System.out.println("It's Negative");
        } else {
            System.out.println("It's Zero");
        }
    }
    
     public static void printFibonacciSeries(int n) {
        int firstNum = 1;
        int secondNum = 1;
        System.out.print(firstNum + ", " + secondNum);
        
        for (int i = 3; i <= n; i++) {
            int nextNum = firstNum + secondNum;
            System.out.print(", " + nextNum);
            firstNum = secondNum;
            secondNum = nextNum;
        }
        
        System.out.println();
    }
     public static int findNextNumber(int[] sequence) {
        int sum = 0;
        for (int i = 0; i < sequence.length; i++) {
            sum += sequence[i];
        }
        
        return sum;
    }
 
    public static void main(String[] args) {
        
        //1.
           int n = 10;
        int sum = 0;

        for (int i = 1; i <= n; i++) {
            sum += i;
        }

        System.out.println("The sum is: " + sum);
        
    //2.
        System.out.print("Enter the number: ");
        int x= scanner.nextInt();
        
        int sum1 = 0;
        
        for (int i = 1; i <= x; i++) {
            System.out.print(i + " ");
            sum1 += i;
        }
        
        System.out.println("\nThe sum is: " + sum1);
    //3.
    System.out.print("Enter the number: ");
        int y = scanner.nextInt();
        
        for (int i = 1; i <= y; i++) {
            int cube = i * i * i;
            System.out.println("number" + i + ": " + cube);
        }
    //4.
      int a=scanner.nextInt();
      multiplication(a);
    //5.  
      
        System.out.println("The sum is: " +getSumOfOddNumbers() );
    //6.
     System.out.print("Enter the number of rows: ");
        int rows = scanner.nextInt();

        printNumberTriangle(rows);
        
    //7.
      System.out.print("Enter the number: ");
        int number = scanner.nextInt();
        
        long factorial = calculateFactorial(number);
        
        System.out.println("!" + number + " = " + factorial);
    
    //8.
    
    System.out.println("Enter the numbers:");
        int[] numbers = new int[5];
        
        for (int i = 0; i < 5; i++) {
            numbers[i] = scanner.nextInt();
        }
        
        System.out.println("Reversed numbers:");
        reverseNumbers(numbers);
        
        for (int i = 0; i < 5; i++) {
            System.out.print(numbers[i] + " ");
        }
    //9.
       System.out.print("Enter the number: ");
        int numbe = scanner.nextInt();
        
        int absoluteValue = getAbsoluteValue(numbe);
        
        System.out.println("Absolute value: " + absoluteValue);
    //10.    
       System.out.print("Enter the number: ");
        int base = scanner.nextInt();
        
        System.out.print("Enter the power: ");
        int power = scanner.nextInt();
        
        int result1 = getPower(base, power);
        
        System.out.println("Power: " + result1);
        
    //11.
      signIn();
    //12.
      printTrianglePattern(5);
    //13.
       printSquareNumbers(1, 100);
    //14.
     printAsteriskPattern();
    //15.
      printNumberPattern();
    //16.
      System.out.print("Enter The First Number: ");
        int num1 = scanner.nextInt();
        
        System.out.print("Enter The Second Number: ");
        int num2 = scanner.nextInt();
        
        System.out.print("Enter The Third Number: ");
        int num3 = scanner.nextInt();
        
        int max = findMaxValue(num1, num2, num3);
        int min = findMinValue(num1, num2, num3);
        
        System.out.println("The Max Value is: " + max);
        System.out.println("The Min Value is: " + min);
        
    //17.
     System.out.print("Enter The Number: ");
        int number3 = scanner.nextInt();
        checkNumberSign(number3);
    //18.
      int c = 10;
        printFibonacciSeries(c);
    
    //19.
    int[] sequence = {1, 1, 1, 3, 5, 9, 17, 31};
        int nextNumber = findNextNumber(sequence);
        System.out.println("The next number = " + nextNumber);
    }
}

