# Given-two-non-negative-int-values-return-true-if-they-have-the-same-last-digit-such-as-with-27-and
Q3

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter first number:");
        int a=sc.nextInt();
        System.out.println("Enter second number:");
        int b=sc.nextInt();
        boolean c=lastDigit(a,b);
        System.out.println(c);
    }
    static boolean lastDigit(int p,int q)
    {
        if(p%10 == q%10)
            return true;
        else
            return false;
    }
}

