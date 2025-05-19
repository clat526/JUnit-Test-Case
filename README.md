This is a JUnit Test Case project which involves testing code to see if it works and making sure there are no errors.
The technologies used are Eclipse IDE and Java.
My two favorite parts of this project is testing the code with Eclipse and writing the code for the tests.
Code Snippets: 
package com.promineotech;

import java.util.Random;

public class TestDemo {
	public int addPositive(int a, int b) {
		if(a > 0 && b > 0) {
			return a + b;
		} else {
			throw new IllegalArgumentException("Both parameters must be positive");
		}
	
	}
   int randomNumberSquared() {
	   int squared = getRandomInt();
	   return squared * squared;
   }
	
	
	int getRandomInt() {

	    Random random = new Random();

	    return random.nextInt(10) + 1;

   
	}
 public int addNegative(int a, int b) {
	 if(a < 0 && b < 0) {
		 return a + b;
	 } else {
		 throw new IllegalArgumentException("Both parameters must be negative");
	 }
  
 }
}
Installation and instructions: To use this project you must install Eclipse IDE and you should be able to run and test the source code.
Contact info: calebalatnie7@gmail.com
