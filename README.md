# Assignment-2.1

1)
import java.util.*;
public class acad {
public static void main(String args[])
{
	
	Scanner sc=new Scanner(System.in);
	int a=6;								                
	int b=5;								                
	int sum=a+b;							              
	System.out.println(sum);				     
}
}

2)

import java.util.*;
public class acad {
public static void main(String args[])
{
	
	Scanner sc=new Scanner(System.in);
	int a=sc.nextInt();								      
	int b=sc.nextInt();								     
	int sum=a+b;									         
	System.out.println(sum);						
}
}


3)


import java.util.Scanner;

public class acad {
	public static int sum(int a,int b)		
	{
		int c = a+b;
		return c;
	}
	public static void main(String args[])
	{
		
	Scanner sc =new Scanner(System.in);
	int a = sc.nextInt();				
	int b =sc.nextInt();				
	
	System.out.println( "First number is:"+a);
	System.out.println("Second number is:"+b);
	System.out.println("Sum is:"+sum(a,b));
		
		
		
	}

}




4. import java.util.*; 
public class Main {
public static void main(String args[]) {

Scanner sc=new Scanner(System.in);
int n1=sc.nextInt();                    
int n2=sc.nextInt();    
System.out.println("The even numbers are:");
for(int i=n1;i<=n2;i++)
{
    if(i%2==0)
    {
        System.out.println(i);
    }
}
System.out.println("The odd numbers are:");
for(int j=n1;j<=n2;j++)
{
    if(j%2!=0)
    {
        System.out.println(j);
    }
}
} }

5. import java.util.*; 
public class Main { 
public static void main(String args[]) {

Scanner sc=new Scanner(System.in);
int n=sc.nextInt();                                 
int a=0;                                       
for(int i=1;i<=10;i++)
{
     a=i*n;
     System.out.println(n+"x"+i+"="+a);             
}   
} } 

6.

import java.util.Scanner;

public class acad { 
public static void sum(int a , int b)
{ 
System.out.println(a+b);
}
public static void  sum(String s1 ,String s2)       
{
    String s3 = s1+s2;
     System.out.println(s3);
}

public static void main(String args[])
{
    Scanner sc= new Scanner(System.in);

    int a = sc.nextInt();
    int b = sc.nextInt();
    String s1 = sc.next();
    String s2 = sc.next();
    sum(a,b);                   
    sum(s1,s2);                 
    }
}



7)
	Yes, it can be overloaded with same return type only if number of parameters that are passed is different for both methods.

construct a method which involves finding sum for 2 numbers
construct another method which involves finding sum for 3 numbers
here in this two methods, number of parameters passed are  different.
This method can be overloaded only if number of paramters differ from each other

LOGIC: 

import java.util.Scanner;

public class acad {
	public static int sum(int a , int b)		
    {
        return a+b;
         
    }
    public static int  sum(int a,int b,int c)  		
    {
    	int d=a+b+c;
         return d;
    }
	
	public static void main(String args[])
	{
		Scanner sc= new Scanner(System.in);
		
		int a = sc.nextInt();
		int b = sc.nextInt();
		int c=  sc.nextInt();
		int x=sum(a,b);					
		System.out.println(x);
		int y=sum(a,b,c);					
		System.out.println(y);
		}
	}





8)
import java.util.*;
public class acad {
public static void main(String args[])
{
	
	Scanner sc=new Scanner(System.in);
	int n=sc.nextInt();					              
	int b[]=new int[n];					             
	for(int i=0;i<n;i++)
	{
		b[i]=sc.nextInt();				              
	}
	Arrays.sort(b);						               
for(int i=n-1;i>=0;i--)
{
	System.out.println(b[i]);			            	
}

}}
















