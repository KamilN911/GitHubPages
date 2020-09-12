### Table of contents

1. [Java Project](https://github.com/KamilN911/GitHubPages/new/master#java-project)
2. fawefub cwdc wecui wecu wc
3. waic weicnw cwieciweci w
4. weofinw cwencoin wce 
5. aweoinwc wec wecnio nweci nw 

![java logo](https://s2.glbimg.com/DyDQQTZSF1oEiO8kawMIxP72KzQ=/290x417/s.glbimg.com/jo/g1/f/original/2011/08/22/22-java-300.jpg)

# Java Project

#### some example of java code

``` java
public class JavaExample {
    public static void main(String[] args) {
        int num1 = 15, num2 = 2;
        int quotient = num1 / num2;
        int remainder = num1 % num2;
        System.out.println("Quotient is: " + quotient);
        System.out.println("Remainder is: " + remainder);
    }
}
```

#### Another sample of code

``` java
import java.util.Scanner;
class JavaExample
{
   public static void main(String[ ] arg)
   {
	boolean isVowel=false;;
	Scanner scanner=new Scanner(System.in);
	System.out.println("Enter a character : ");
	char ch=scanner.next().charAt(0); 
	scanner.close();
	switch(ch)
	{
	   case 'a' :
	   case 'e' :
    	   case 'i' :
	   case 'o' :
	   case 'u' :
	   case 'A' :
	   case 'E' :
	   case 'I' :
	   case 'O' :
	   case 'U' : isVowel = true;
	}
	if(isVowel == true) {
	   System.out.println(ch+" is  a Vowel");
	}
	else {
	   if((ch>='a'&&ch<='z')||(ch>='A'&&ch<='Z'))
		System.out.println(ch+" is a Consonant");
	   else
		System.out.println("Input is not an alphabet");		
        }
   }
}
```
