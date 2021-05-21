interface A
{
	void display();
}
interface B
{
	public void show();
}
class C implements A , B
{
	public void display()
	{
		System.out.println("Im from A");
	}
	public void show()
	{
		System.out.println("Im from B");
	}
}
class Jala 
{
	public void show()
	{
		System.out.println("Im definition of abstact method");
	}
	public static void main(String[] args){ 
			 C c = new C();
			 c.show();
			 c.display();
		
	}
}
