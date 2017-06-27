# FirstTestingRepository

public class ConstructorExample2 {

	int num;
	String str;
	
	ConstructorExample2(int n,String s){
		num= n ;
		str = s ;
		System.out.println("Constructor called.");
	}
		
	public static void main(string[] arg){
		
		//constructor call
		ConstructorExample2 obj= new ConstructorExample2(20,"Hello");
		
		System.out.println("num=" +obj.num);
		System.out.println("num=" +obj.str);
		
		
	}
	
}
