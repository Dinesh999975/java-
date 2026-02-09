package dinesh;

import java.util.Arrays;
import java.util.Scanner;

public class RotateLeftAndRight {

	public static void main(String[] args) {
		int arr[]= {1,2,3,4,5,6,7,8,9,10};
		Scanner sc=new Scanner(System.in);
		System.out.println("enter the value");
		int rotation=sc.nextInt();
		
		
		for(int n=1;n<rotation;n++) {
			
			int temp=arr[0];// 1
		for(int i=0;i<arr.length-1;i++) {
			arr[i]=arr[i+1];
		}//   {2,3,4,5,6,7,8,9,10}
		
		arr[arr.length-1]=temp;
		}
		System.out.println(Arrays.toString(arr));
		// TODO Auto-generated method stub

	}

}
