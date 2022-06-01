public class MyClass {
    public static void main(String args[]) {
      int x=factorialRecursive(5);

      System.out.println("result=" + x );
    }

public static int factorialRecursive(int n)
{
    if (n == 1) 
        return 1;

    else
        return n*factorialRecursive(n-1);
}}
