# Assignment2
import java.util.Scanner;
public class JavaDataTypes {
    
    public static void main(String[] args){
        Scanner in = new Scanner(System.in);
        System.out.print("Enter a integer between 0 and 1000 : ");
        int num = in.nextInt();
        int sum_of_digits = (num%10) + ((num/10)%10)+(num/100);
    }


   public static int addAllDigits(int inputNumber){
        
    int result = addAllDigits(350);
     System.out.println(result); 
        return 0;
       
   }
}
