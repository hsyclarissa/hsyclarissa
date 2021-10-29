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

