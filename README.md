# Agecheck
using this code check user is minor or major and can vote or not
package mypackage;

import java.util.Scanner;

public class Agecheck01 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc=new Scanner(System.in);
		System.out.print("Enter your age:");
		int age=sc.nextInt();
         if(age>=18) {
        	 System.out.print("major, Can vote");
        	 
         }else if(age==0) {
        	 System.out.print("Invalid age:");
        	 
         }else {
        	 System.out.print("Minor, Can't vote:"); 
         }sc.close();
	}

}
