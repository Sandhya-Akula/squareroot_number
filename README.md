package Pack1;
import java.util.*;
public class File4
 {
public static void main(String[] args)
 {
Scanner sc = new Scanner(System.in);
System.out.println("enter number");
int n = sc.nextInt(); 
float sqrt , t=0;
sqrt = n/2; 
if (n == 1)
System.out.println("Square root of "+n+" is "+n);
else
{
while(sqrt != t) 
{
t = sqrt;
sqrt = (n/t + t)/2;
}
System.out.println("Square root of "+n+" is "+sqrt);
}
}
}
