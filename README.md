# Java_Palindrome
Inputted number/string is palindrome or not
import java.util.*;   
class Palindrome  
{  
   public static void main(String args[])  
   {  
      String org, rev = "";  
      Scanner sc = new Scanner(System.in);   
      System.out.print("Enter a string/number :");  
      org = sc.nextLine();   
      int length = org.length();   
      for ( int i = length - 1; i >= 0; i-- )  
         rev = rev + org.charAt(i);  
      if (org.equals(rev))  
         System.out.println("Entered string/number is a palindrome.");  
      else  
         System.out.println("Entered string/number is not a palindrome.");   
   }  
}  
