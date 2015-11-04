
# Generating a random uppercase letter.
## Introduction
This assignments deals with generating and displaying a random uppercase letter using Math.random() in Java.
## Outline
``` java
// Generate a random uppercase letter
// Print the random letter
```
## References and Literature
/* Liang Java 10th Edition pg. 87 3.3
* Example on how to generate random number
* Pg. 125 Table 4.4
* Characters A to Z equals 65 to 90
* Pg. 122 4.2.5
* Example on the Random method
* Pg. 209 6.4
* Void method and method call example.
* Google search
*/

## Code
``` java
import java.util.*;
public class Work_Class {
	public static void main(String[] args) {
		Scanner input = new Scanner(System.in);
		
		System.out.println("Hello");
		
		//Generate a random number between 65 and 90
		int letter = 65 + (int)(Math.random()*26);
		
		//covert the number into a letter
		char ch = (char)letter;
		
		//display the letter
			System.out.println(ch);
	}	

	}
```

## Console Output

### Test 1
Hello
O
###Test 2
Hello
M
###Test 3
Hello
L

## Summary
In this project I was asked to generate a random letter using Math.random().
I did this by generating a random number between 65 and 90 and converting that
number into a letter by turning it into a char variable. To do this I used a 
combination of the book examples and some examples online to get a feel for what 
I needed to do. Once I an idea of what I needed to do it wasn't too difficult to 
write the code to do this. This assignment did teach some on how to work with character variables.
