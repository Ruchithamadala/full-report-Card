# full-report-Card


import java.util.*;
public class Main{
      public static void main (String[] args){
      Scanner sc = new Scanner(System.in);
      int a = sc.nextInt();
      if(a>=90)
      {
        System.out.println("A+ Grade");
      }
      else if(a<90 && a>=80)
      {
        System.out.println("A Grade");
      }
      else if(a<80 && a>=70)
      {
        System.out.println("B Grade");
      }
      else if(a<70 && a>=60)
      {
        System.out.println("C Grade");
      }
      else if(a<60 && a>=35)
      {
        System.out.println("D Grade");
      }
      else
      {
        System.out.println("Fail");
      }
    }
}
