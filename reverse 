import java.io.*;
 
class Reverse {
     
    // Function to reverse the number
    static int reverse(int n){
       
      int rev = 0; // reversed number
      int rem;   // remainder
       
      while(n>0){
          
        rem = n%10;
        rev = (rev*10) + rem;
        n = n/10;
      }
       
      return rev;
    }
     
   // Driver Function
    public static void main (String[] args) {
        int n = 9835;
         
        System.out.print("Reversed Number is "+ reverse(n));
    }
}