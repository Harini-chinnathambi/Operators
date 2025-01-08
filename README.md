# Operators
package operators.java;
import java.util.Scanner;
public class OperatorsJava {
    public static void main(String[] args) {
                Scanner sc =new Scanner (System.in);
        System.out.println("enter the first number:");
        int a =sc.nextInt();
        System.out.println("enter the second number:"); 
        int b =sc.nextInt();
        System.out.println(" enter the third number :");
        int c =sc.nextInt();
        /** arithmetic operators 
        System.out.println ("arithmetic operators");
        System.out.println (" addition:"+(a+b));
        System.out.println ("subtraction:"+(a-b));
        System.out.println ("multiplication:"+(a*b));
        System.out.println ("division:"+(a/b));
        System.out.println ("modulus:"+(a%b));
        
       relational operator
        System.out.println ("relational operators"); 
        System.out.println ("a>b:"+(a>b));
        System.out.println ("a<b:"+(a<b));
        System.out.println ("a==b:"+(a==b));
        System.out.println ("a!=b:"+(a!=b));
        System.out.println ("a>=b:"+(a>=b));
        System.out.println ("a<=b:"+(a<=b));
        
         logical operator 
        System.out.println("logical operator");
        System.out.println("(a>b)&&(b>c):"+((a>b)&&(b>c)));
        System.out.println("(a>b)||(b>c):"+((a>b)||(b>c)));
        System.out.println("!(a<c):"+(!(a<c)));
        
        System.out.println("ternary operator ");
        String result=(a>b)?" a is greater than b":"a is not greater than b";
        System.out.println("result of(a>b):"+result);
        
        
        
        
        
    }
    
}

Output :
 enter the first number:
56
enter the second number:
7
 enter the third number :
7
arithmetic operators
 addition:63
subtraction:49
multiplication:392
division:8
modulus:0
relational operators
a>b:true
a<b:false
a==b:false
a!=b:true
a>=b:true
a<=b:false
logical operator
(a>b)&&(b>c):false
(a>b)||(b>c):true
!(a<c):true
ternary operator 
result of(a>b): a is greater than b
 
