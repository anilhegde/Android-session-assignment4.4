class A{
	private int a;
	A(){
		a=10;
		System.out.println("Class A contructor called");
	}
	
}
class B extends A{
	private int b;
	
	B(){
		
		super();
		b=20;
		System.out.println("Class B contructor called");
	}
}

class C extends B{
	private int c=30;
	
	C(){
		super();
		c=40;
		System.out.println("Class C contructor called");
	}
	
}
public class Assignment4_4 extends C {

	public static void main(String[] args) {
		Assignment4_4 obj=new Assignment4_4();
		
		
	}

}
