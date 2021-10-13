# java8
code for java 8 features

public class Demo {
	public static void main(String[] args) {
		try {
			System.out.println((10/0));
			
		}
		catch(ArithmeticException e) {
			System.out.println("error");
		}
	}

}
