# Java-program
import java.util.Scanner;
public class Demofile {

	public static void main(String[] args){
	int length, width, area, perimeter;
	Scanner sc = new Scanner(System.in);
	System.out.println("Enter the length of the Recatangle");
	length = sc.nextInt();
	System.out.println("Enter the width of the Rectangle");
	width = sc.nextInt();
	area = length*width;
	perimeter = 2*(length+width);
	System.out.println("Enter the area of the Rectangle:" +area);
	System.out.println("Enter the perimeter of the Rectangle:" +perimeter);	

	}

}
