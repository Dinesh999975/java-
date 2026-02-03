package dinesh;

import java.util.Scanner;

public class DigitSeparation {

	public static void main(String[] args) {
		System.out.println("enter the number: ");
		Scanner sc=new Scanner(System.in);
		int n =sc.nextInt();
		int count=0;
		int temp=n; 
		int t=0;
		
		while(n>0) {
			n/=10;
			count++;
		}
		t=(int)Math.pow(10, count-1);
		
		while(temp>0) {
			int quo=temp/t;
			System.out.println(quo);
			temp%=t;
			t/=10;
		}
	    

	}

}
