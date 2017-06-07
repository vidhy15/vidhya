import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Positive
{
	public static void main (String[] args)
	{
		Scanner s=new Scanner(System.in);
		int n=s.nextInt();
		if(n<0)
		{
			System.out.println("Negative number");
		}
		else if(n>0)
		{
			System.out.println("Positive number");
		}
		else
		{
			System.out.println("Zero");
		}
	}
}
