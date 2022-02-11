package p9;
public class Reverse
{
	 static int n,r,x,z;
    static void findReverse()
    {
    	System.out.println("reverse of the numbers");
    	for(n=10;n<=100;n++)
		{
		x=0;
		z=n;
			while(z>0)
			{
				r=z%10;
				x=x*10+r;
				z=z/10;
			}
			System.out.println(x);
    }
    }
	static void ispalindrome() {
		System.out.println("palindrome numbers are");
		for(n=10;n<=100;n++)
		{
		x=0;
		z=n;
			while(z>0)
			{
				r=z%10;
				x=x*10+r;
				z=z/10;
			}
			if(n==x)
				System.out.println(n);
		}
	}
static void displaypalindromeNos()
	{
		System.out.println("lets check for palindrome number");
		for(n=10;n<=100;n++)
		{
		x=0;
		z=n;
			while(z>0)
			{
				r=z%10;
				x=x*10+r;
				z=z/10;
			}
			if(n==x)
				System.out.println("number is palindrome");
			else
				System.out.println("Not a palindrome");
	}
	}
	public static void main(String[] args) {

findReverse();
ispalindrome();	
displaypalindromeNos();	

	}
}
