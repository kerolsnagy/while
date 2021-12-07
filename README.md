# while
package com.company;

import jdk.swing.interop.SwingInterOpUtils;

import java.util.Scanner;

public class Main
{
    public static void main (String args[])
    {
        int count=1;

        while (++count <= 5)
        {
            System.out.println("hi # " + count);
            //count-=2;

        }
        System.out.println("count = " + count);

    }
}
