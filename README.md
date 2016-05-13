# AssignmentsRepo
Learning github

C# program to find Avg of numbers.

public static void Main(String args[])
	{
	Console.WriteLine("Enter 4 numbers");
	int a=Convert.Toint32(Console.ReadLine());
	int b=Convert.Toint32(Console.ReadLine());
	int c=Convert.Toint32(Console.ReadLine());
	int d=Convert.Toint32(Console.ReadLine());
	MyClass myClass = new MyClass();
	MyClassLocation myClassLocation = new MyClassLocation();
	int res=myClass.AvgOfNum(a,b,c,d);
	Console.WriteLine("Avg of numbers");
	}
	
  class MyClass
  {
	  public int AvgOfNum(int x,int y,int z,int k)
	  {
		  int Avg=(x+y+z+k)/4;
		  return Avg;
	  }
  }
  