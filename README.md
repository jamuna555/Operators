# Operators
Arithmetic and Bitwise


class ArthmeticAdd
{
	public static void main(String args[])
	 	{
			int a=20;
			int b=30;
	        int c=a+b;//add values of either side of the operator
			System.out.println(c);// o/p:50
		}
}

class ArthmeticSub
{
	public static void main(String args[])
		{
			int a=50;
			int b=40;
			int c=a-b;//Subract the right hand operand from left side operand
						System.out.println(c);// o/p:10
		}
	
}

class ArthmeticDiv
{
		public static void main(String args[])
		{
			int a=100;
			int b=60;
			int c=a/b;//Divide the left hand operand from right side operand, o/p: quotient value
						System.out.println(c);// o/p : 
		}
}

class ArthmeticMod
{
		public static void main(String args[])
		{
			int a=100;
			int b=60;
			int c=a%b;//Divide the left hand operand from right side operand and o/p gives remainder value
						System.out.println(c);
		}
}

class ArthmeticInc
{
	public static void main(String args[])
	{
	int a=100;
	int b=60;
	int c=a++; // post increment: value is first assigned to old value and increment the value
	int d=++b; //Pre increment :Value is Incremented First and then incremented value is assigned
	int e=a;		System.out.println(c);// o/p : 100
						System.out.println(d);// o/p : 61
						System.out.println(e);

		}
}
class ArthmeticDecre
{
		public static void main(String args[])
		{
			int a=100;
			int b=60;
			int c=a--;// Post increment the variable "a" 
			int d=--b;//Pre increment the variable "b"
						System.out.println(c); // o/p: 100
						System.out.println(d); // o/p:59
		}
}
