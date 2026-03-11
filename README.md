package dinesh;

import java.util.Scanner;

public class strongnum1 {
	 static int factorial(int n) {
		int product=1;
		if(n==0) return product;
		for(int i=1;i<=n;i++) {
			product*=i;
		}
		return product;
	}

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc=new Scanner(System.in);
		int n=sc.nextInt();
		int temp=n;
		int sum=0;
		
		while(n>0) {
			int rem=n%10;
			sum+=factorial(rem);
			n/=10;
			System.out.println(sum);
		}
		if(temp==sum)System.out.println(sum+" strongnum");
		else System.out.println(sum+" not Strong number");

	}

}
