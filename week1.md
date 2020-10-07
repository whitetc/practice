# Heading

this is my markdown file.  
I made this today.  
This is my paragraph.  
Codeblock below.

```Java
class Main {
  public static void main(String[] args) {
   System.out.println(2%1);
    
  }
}
```
[this is a link](www.yahoo.com)

```Java
import java.time.LocalDateTime;
import java.util.Scanner;   // This will import just the Scanner class
import java.util.*;   // This will import the entire java.util package
import java.time.LocalDate;
class Main {
  public static void main(String[] args) {
    Scanner s1 = new Scanner(System.in);
    System.out.println("Enter your first name");
    String firstName = s1.next();
    System.out.println("Enter your last name");
    String lastName = s1.next();
    System.out.println("Your name is " + firstName +" "+ lastName);
    System.out.println("What is your email address");
    String email = s1.next();
    System.out.println("Your email address is   " + email);
    LocalDateTime myObj = LocalDateTime.now(); 
    System.out.println("Today's date and time is " + myObj); 
  }
}
```
