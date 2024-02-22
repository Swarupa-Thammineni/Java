//Different Patterns Programs in java

import java.util.*;
public class Patterns{

public static void main(String args[]){

Patterns p = new Patterns();
Scanner sc= new Scanner(System.in);

System.out.print("enter n:");
int n=sc.nextInt();
System.out.print("enter chioce of Pattern:");
int ch=sc.nextInt();

do{
System.out.println();
System.out.println("1 -> Square hallow");
System.out.println("2 -> Number triangle");
System.out.println("3 -> Numbers");
System.out.println("4 -> Stars");
System.out.println("5 -> Stars triangle");
System.out.println("6 -> Palindrome");
System.out.println("7 -> Butterfly");
System.out.println("8 -> Pascal's triangle");
System.out.println("9 -> Diamond");
System.out.println("10 -> Rhombus");
System.out.println("Enter -1 to exit");
System.out.println();


switch(ch){

case 1:System.out.println("1- Square hallow");
       System.out.println();
       for(int i=1;i<=n;i++){
           for(int j=1;j<=n;j++){
               if(i==1||j==1||i==n||j==n)
                    System.out.print("* ");
               else
                    System.out.print("  ");
            }
            System.out.println();
        }
        break;

case 2:System.out.println("2- Number triangle"); 
       System.out.println();
       int num=1;
       for(int i=1;i<=n;i++){
           for(int j=1;j<=n-i;j++){
               System.out.print(" ");
            }
            for(int k=1;k<=i;k++){
                System.out.print(num+" ");
                num+=1;
            }
            System.out.println();
        }
        break;

case 3:System.out.println("3- Numbers");
       System.out.println();
       for(int i=1;i<=n;i++){
           for(int j=1;j<=i;j++){
               System.out.print(j+" ");
            }
            System.out.println();
        }
        break;

case 4:System.out.println("4- Stars");
       System.out.println();
       for(int i=n;i>=1;i--){
           for(int j=1;j<=n-i;j++){
               System.out.print("  ");
            }
            for(int k=1;k<=i;k++){
               System.out.print("* ");
            }
            System.out.println();
        }
        break;

case 5:System.out.println("5- Stars triangle");
       System.out.println();
       for(int i=n;i>=1;i--){
           for(int j=1;j<=n-i;j++){
               System.out.print(" ");
            }
            for(int k=1;k<=i;k++){
                System.out.print("* ");
            }
            System.out.println();
        }
        break;
case 6:System.out.println("6- Palindrome"); 
       System.out.println();
       for(int i=1;i<=n;i++){
           for(int j=1;j<=n-i;j++){
               System.out.print("  ");
           }
           for(int j=i;j>=1;j--){
               System.out.print(j+" ");
           
           }
           for(int j=2;j<=i;j++){
               System.out.print(j+" ");
           }
           System.out.println();
        }
        break; 
case 7:System.out.println("7- Butterfly");
       System.out.println();
       for(int i=1;i<=n;i++){
           for(int j=1;j<=i;j++){
               System.out.print("*");
           }
           for(int j=1;j<=2*(n-i);j++){
               System.out.print(" ");
           }
           for(int k=1;k<=i;k++){
               System.out.print("*");
           }
            System.out.println();
        }
        for(int i=n;i>=1;i--){
            for(int j=1;j<=i;j++){
               System.out.print("*");
            }
            for(int j=1;j<=n-i;j++){
                System.out.print("  ");
            }
            for(int k=1;k<=i;k++){
                System.out.print("*");
            }
            System.out.println();
        }
         break;

case 8:System.out.println("8- Pascal's triangle");
       
       System.out.println();
       for(int i=1;i<=n;i++){
           for(int j=1;j<=n-i;j++){
               System.out.print(" ");
           }
           int x=1;
           for(int k=1;k<=i;k++){
                System.out.print(x+" "); 
                x=x*(i-k)/k;
           }
           System.out.println();
        }
        break;
            
case 9:System.out.println("9- Diamond");
       System.out.println();
       for(int i=1;i<=n;i++){
           for(int j=1;j<=n-i;j++){
               System.out.print(" ");
           }
           for(int j=1;j<=2*i-1;j++){
               System.out.print("*");
           }
           System.out.println();
        }
        for(int i=n;i>=1;i--){
           for(int j=1;j<=n-i;j++){
               System.out.print(" ");
           }
           for(int j=1;j<=2*i-1;j++){
               System.out.print("*");
           }
           System.out.println();
        }
        break;
        
case 10:System.out.println("10- Rhombus");
        System.out.println();
        for(int i=1;i<=n;i++){
            for(int j=1;j<=n-i;j++){
                System.out.print(" ");
            }
            for(int k=1;k<=n;k++){
                System.out.print("* ");
             }
             System.out.println();
         }
         break;
    
default:System.out.println("Enter numbers from 1 to 10");

}

System.out.print("enter chioce of Pattern:");
ch=sc.nextInt();

}while(ch!=-1);


}
}

