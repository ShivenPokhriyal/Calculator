![image](https://github.com/ShivenPokhriyal/Calculator/assets/171858786/1650f588-2bf2-4951-8b2a-39219bb5bdf8)

import java.util.*;
public class calculator {
    public static void main (String[]args){
        Scanner sc = new Scanner (System.in);
        System.out.println("enter a:");
        int a = sc.nextInt();
        System.out.println("enter b:");
        int b = sc.nextInt();
        System.out.println("enter operator:");
        char operator = sc.next().charAt(0);

        switch(operator){
            case '+' :System.out.println(a+b);
                break;
            case '-' :System.out.println(a-b);
                break;
            case '*' :System.out.println(a*b);
                break;
            case '/' :System.out.println(a/b);
                break;

        }

    }
}
