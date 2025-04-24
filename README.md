public class Pr3a
{
	public static void main(String[] args)
	{
	   try
	   {
		int result=divide(10,0);
		System.out.println("Result:"+result);
	   }
	   catch(ArithmeticException e)
	   {
		System.err.println("Error: Division by Zero");
	   }
	}
	public static int divide(int a,int b)
	{
	   return a/b;
	}
}
