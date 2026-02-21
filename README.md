package numberProblems;
import java.util.*;

public class PerfectOrAbundantOrDeficient {
	static int factorial(int n) {
		int sum = 0;
		for(int i=1;i<=n/2;i++) {
			if(n%i==0) {
				sum+=i;
			}
		}
		return sum;
	}
	public static void main(String[] args) { 
		Scanner sc = new Scanner(System.in);
		System.out.println("Enter the no: ");
		int a = sc.nextInt();
		
		if(a==factorial(a)) {
			System.out.println(a+" is a perfect number");
		}
		else if(factorial(a)<a) System.out.println(a+" is Deficient");
		else System.out.println(a+" is a Abundant");
	}

}
