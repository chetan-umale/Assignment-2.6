Q1-Write a program to accepts two numbers from stdin and find all the odd as well as even
numbers present in between them.

import java.util.Scanner;


public class acad {
	public static void main(String args[])
	{
		int a,b;
		Scanner s = new Scanner(System.in);
		
		a=s.nextInt();
		b=s.nextInt();
		
		System.out.println("odd numbers : ");
		
		for(int i=a+1;i<b;i++)
		{
			if(i%2!=0)
			{
				System.out.print(i+" ");
			}
		}
		
		System.out.println("\neven numbers : ");
		
		for(int i=a+1;i<b;i++)
		{
			if(i%2==0)
			{
				System.out.print(i+" ");
			}
		}
		
	}
	
	

}




Q2-Joe is scared to go to school. When her dad asked the reason, joe said she is unable to
complete the task given by her teacher. The task was to find the “first 10 multiples” of the
number entered from stdin




import java.util.Scanner;


public class acad {
	public static void main(String args[])
	{
		int a,b;
		Scanner s = new Scanner(System.in);
		System.out.println("Input :");
		a=s.nextInt();
		
		
		
		System.out.println("output :" );
		for(int i=1;i<=10;i++)
		{
			
			
				System.out.println(a+" x "+i+" = "+a*i);
			
		}
		
		
		
	}
	
	

}





Q3-Write a program consisting method sum() and demonstrate the concept of method
overloading using this method





import java.util.Scanner;


public class acad {
	public static void main(String args[])
	{
		int a,b,c;
		
		
		acad obj = new acad();
		
	
		Scanner s = new Scanner(System.in);
		System.out.println("enter 2 numbers");
		a=s.nextInt();
		b=s.nextInt();
		
		System.out.println("sum 1 : " +obj.add(a, b) );
		
		System.out.println("enter 3 numbers");
		a=s.nextInt();
		b=s.nextInt();
		c=s.nextInt();
		
		
		System.out.println("sum 2 : "+obj.add(a, b, c) );
		
		
	}
	
	
	public int add(int x,int y)
	{
		return x+y;
	}
	
	public int add(int x,int y,int z)
	{
		return x+y+z;
	}	

}



