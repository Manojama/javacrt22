 import java.util.*;
class div
{
	public static void main(String[] args) 
	{
		Scanner s=new scanner(system.in);
		int a,b,c;
		System.out.println("enter two nos");
		a=s.nextInt();
		b=s.nextInt();
		if (b==0)
		{
		System.out.println("Second no cannot be zero");
		b=1;
		c=a/b;
		System.out.println(c);
	}
}
}
