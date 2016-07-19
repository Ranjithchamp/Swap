# Swap
import java.util.Scanner;

public class Swap {

	public static void main(String[] args) {
		Scanner get = new Scanner(System.in);
		System.out.println("enter A value=");
		int A = get.nextInt();
		System.out.println("enter B value=");
		int B = get.nextInt();
		int c;
		c = A + B;
		B = A;
		A = c - A;
		System.out.println("A=" + A + "\nB=" + B);
	}

}
