package dinesh;

import java.util.Scanner;

public class NumPattern2 {

	public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		int n =sc.nextInt();
		
		for(int i=1;i<=n;i++) {
			for(int j=2*n-1;j>2*n-2*i;j-=2) {
				System.out.print(j+" ");
			}
			System.out.println();
		}
		
		// TODO Auto-generated method stub

	}

}
