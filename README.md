# String-palindrome
package com.payil.poly;

import java.util.Scanner;

public class Palindrome {

	public static void main(String[] args) {
		System.out.println("Enter a word:");
		Scanner s = new Scanner(System.in);
		String st=s.next();
		String stringrev="";
		for(int i=st.length()-1;i>=0;--i){
			stringrev+=st.charAt(i);
			//System.out.print(stringrev);
			
		}
		if(st.equals(stringrev)){
			System.out.println("the given word is a palindrome");}
			else 
				System.out.println("The given word is not a palindrome");
		
		
		// TODO Auto-generated method stub

	}

}
