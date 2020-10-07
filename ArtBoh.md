# Arturo's First Mark Down File 


 
*This first few lines is to showcase a few examples on using a markdown file* <br>


___This next Codeblock shows a few ways or organize a 'Main' method and its syntax___


```java
//this is a block code for this file
public class Main {
  public static void main (String [] args) {
    system.out.println ("Hello World");
    }
   }
```

>This next section is to show how a hyperlink can be embeded in the text with this text line being a block quote

[Here is a link to a cool website](google.com) 
//this is to put a link to show to a specific website
```java
public class Solution {
    public static String repeatStr(final int repeat, final String string) {
      String str = ""; 
      for (int i = 0; i < repeat; i++){
        str += string;
      } 
      
      
      return str; 
    }
}
```
```java
public class Solution {

    public static String[] stringToArray(String s) {
      String [] str; 
      str = s.split(" ");       
      return str; 
    }
}
```
=======================================================================================================================================
## OCT. 7 2020


# Codewars (Alternate Capitalization)
```java
class Solution{
    public static String[] capitalize(String s){
        char [] even = s.toCharArray();
        char [] odd = s.toCharArray();
        
        for (int i =0; i < even.length; i++){
            if (i % 2 ==0 || i ==0){
                even[i] = Character.toUpperCase(even [i]);
            }
        }
        for (int i = 0; i< odd.length; i++){
            if (i % 2 !=0){
                odd [i] = Character.toUpperCase(odd [i]);
            }
        }
        String a = String.valueOf(even);
        String b =String.valueOf(odd);
        
        String [] capital = new String [2];
        capital[0] = a;
        capital [1] = b;
      
      return capital;
    }
  }
  ```

# Name, email, date Java Program

```java
import java.time.LocalDate;
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        Scanner name = new Scanner (System.in);

        System.out.println ("Please enter your Full name: ");
        String x = name.nextLine();



            Scanner email = new Scanner (System.in);
            System.out.println ("Please Eneter your Email: ");
            String y = email.next();


        System.out.println(x);
        System.out.println(y);

        System.out.println("Today's Date is: ");

        LocalDate today = LocalDate.now();
        System.out.println(today);
    }
}
```
