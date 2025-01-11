# 6.SUM-OF-DIGITS
package sumofthedigits;

public class SumOfTheDigits {

      public static void main(String[] args) {
        // TODO code application logic here
        int num=12
                
                
                
                ,  rem=0, sum=0, temp;
        temp = num;
        while(num > 0)
                {
                    rem  =  num % 10;
                    sum  =  sum + rem;
                    num  =  num / 10;
                }
        System.out.println("sum of the digits of"+temp+"is"+sum);
    }
                    
}
    
O/P

run:
sum of the digits of12is3
BUILD SUCCESSFUL (total time: 0 seconds)
