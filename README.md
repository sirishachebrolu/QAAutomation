# stringProblem

Define a Java class to solve this problem:<br>
Given a String and a Character, remove all instances of the Character in the String

Solve this two ways:<br>
1. Iterate through the String, one character at a time<br>
2. Find a method in the String class that can solve this in one line<br>

Write methods for each solution.

Afterwards, write a TestNG or JUnit class for each solution which tests these methods.<br>
Include both positive and negative cases for validations.

1.public class test {
  
@test
public static String rmCharacter(String str, char c){
		    StringBuffer sbf = new StringBuffer(str.length());
		    sbf.setLength(str.length());
		    int counter = 0;
		    for (int i=0; i<str.length(); i++){
		        char chr = str.charAt(i);
		        if(chr != c) sbf.setCharAt(counter++, chr);
		    }
		    return sbf.toString();
		}
}

2. String line = "sirisha";
   line = line.replace("i", "");

 
 

 
 

 
 
 
 
 
 
 
 
