package dinesh;

import java.util.Arrays;

public class Array {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
        int [] arr = {1,2,3,4,5,6,7,8,9,10};
        System.out.println(arr);
        
        for(int i=0;i<arr.length;i++) {
        	System.out.print(arr[i]+" ");
        }
        
        for(int ele:arr) {
        	System.out.print(ele+" ");
        }
        System.out.println(Arrays.toString(arr));

        

}}
