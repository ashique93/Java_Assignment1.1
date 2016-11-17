# Java_Assignment1.1
Write a program to print the sum of two numbers without using + operator. Other operators have to be used.
package projectNew1;

public class Class1 {
	
	public static void main(String [] arg){
		
		
		
		System.out.println(add(16,15));
			
		}
	public static int add(int a, int b){
		
	        if(b == 0) return a;
	        int sum = a ^ b; //SUM of two integer is A XOR B
	        int carry = (a & b) << 1;  //CARRY of two integer is A AND B
	        return add(sum, carry);
	 }


	
		
	}
	
