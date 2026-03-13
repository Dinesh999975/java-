package dinesh;

import java.util.Scanner;
import java.util.Arrays;

public class Array1 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc = new Scanner(System.in);
		System.out.println("enter the size: ");
        int size = sc.nextInt();
        
        int arr[]=new int[size];
        System.out.println("enter the elements:  ");
        
        for(int i=0;i<size;i++) {
        	arr[i]=sc.nextInt();
        	System.out.println(arr[i]+" ");
        }
        

	}

}
