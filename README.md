# java-Loops

import java.io.*;
import java.math.*;
import java.security.*;
import java.text.*;
import java.util.*;
import java.util.concurrent.*;
import java.util.function.*;
import java.util.regex.*;
import java.util.stream.*;
import static java.util.stream.Collectors.joining;
import static java.util.stream.Collectors.toList;



public class Solution {
    public static void main(String[] args) {
        Scanner sc =new Scanner(System.in);
        int N=sc.nextInt();
        int a=0;
        if(N>=2 && N<=20){
        for(int i=1;i<=10;i++){
            a=N*i;
            System.out.println(N+" x "+i+" = "+a);
        }}
    }
}
