# Scanner-in-array
package com.company;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {
        int i;
        Scanner s = new Scanner(System.in);
        System.out.println("Enter number of elements:");
        int  n = s.nextInt();
        int a[] = new int[3];
        System.out.println("Enetr elements:");
        for( i=0;i<=2;i++){
            a[i]=s.nextInt();
        }
        for(i=0;i<=2;i++){
            System.out.print(a[i]+" ");
        }


    }
}
