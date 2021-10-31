public class AddTwoNumbers {

   public static void main(String[] args) {
        
      int num1 = 10, num2 = 11, sum;
      sum = num1 + num2;

      System.out.println("Sum of these numbers: "+sum);
   }
}

public class MulTwoNumbers {

   public static void main(String[] args) {
        
      int num1 = 10, num2 = 11, sum;
      sum = num1 * num2;

      System.out.println("Sum of these numbers: "+sum);
   }
}

import java.util.Scanner;
public class Average {
    
    public static void main(String[] args)
    {
        Scanner scan = new Scanner(System.in);
        System.out.print("Enter the first number: ");
        double num1 = scan.nextDouble();
        System.out.print("Enter the second number: ");
        double num2 = scan.nextDouble();
        System.out.print("Enter the third number: ");
        double num3 = scan.nextDouble();
        scan.close();
        System.out.print("The average of entered numbers is:" + avr(num1, num2, num3) );
    }

  public static double avr(double a, double b, double c)
    {
        return (a + b + c) / 3;
    }
}

import java.util.Scanner;
public class MulTable {
    
    public static void main(String[] args) 
    {
        Scanner s = new Scanner(System.in);
	System.out.print("Enter number:");        
	int n=s.nextInt();
        for(int i=1; i <= 10; i++)
        {
            System.out.println(n+" * "+i+" = "+n*i);
        }
    }
}

import java.util.Scanner;
public class FahToCel {
    
    public static void main(String arg[])	
	{
	    double a,c;
             	    Scanner sc=new Scanner(System.in);	   	 
	    System.out.println("Enter  Fahrenheit temperature");
                   a=sc.nextDouble(); 
	    System.out.println("Celsius temperature is = "+celsius(a));		  	  	     
	} 
	static double celsius(double f)
	{	
	return  (f-32)*5/9;
	}
}

Arrays:

import java.util.Arrays; 
public class SortArray {
public static void main(String[] args){   
    
    int[] my_array1 = {
            1789, 2035, 1899, 1456, 2013, 
            1458, 2458, 1254, 1472, 2365, 
            1456, 2165, 1457, 2456};
            
    String[] my_array2 = {};        
    System.out.println("Original numeric array : "+Arrays.toString(my_array1));
    Arrays.sort(my_array1);
    System.out.println("Sorted numeric array : "+Arrays.toString(my_array1));
    Arrays.sort(my_array2);
    }
}

import java.util.Scanner;
public class InchConMeter {

    public static void main(String[] Strings) {

        Scanner input = new Scanner(System.in);

        System.out.print("Input a value for inch: ");
        double inch = input.nextDouble();
        double meters = inch * 0.0254;
        System.out.println(inch + " inch is " + meters + " meters");

    }
}

import java.util.Scanner;
public class ArraySum {
public static void main(String[] args) {      
int my_array[] = {2,4,6,8,10};
int sum = 0;

Scanner input = new Scanner(System.in);

for (int i : my_array)
    sum += i;
System.out.println("The sum is " + sum);
}
}

import java.util.Arrays;

public class MaxandMin {

    public static void main(String[] args) {

        int largeArray[] = {802,1003,616,219,824,318,713,520,919};

        int smallest = largeArray[0];
        int largest = largeArray[0];

        for( int i = 0; i<= 8; i++)
        {
            if (largeArray [i] < smallest) smallest = largeArray[i];
            if (largeArray [i] > largest) largest = largeArray[i];
        }

            System.out.println(" The smallest value in the Array is: " + smallest);
            System.out.println(" The largest value in the Array is: " + largest);
    }

}

