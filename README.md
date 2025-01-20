# Operator-
public class OperatorsDemo {
public static void main(String[] args) {
int a = 10, b = 20, c;
  System.out.println("Arithmetic Operators:");
   System.out.println("Addition (a + b): " + (a + b));
    System.out.println("Subtraction (a - b): " + (a - b));
    System.out.println("Multiplication (a * b): " + (a * b));
    System.out.println("Division (b / a): " + (b / a));
    System.out.println("Modulus (b % a): " + (b % a));
     System.out.println("\nRelational Operators:");
     System.out.println("a == b: " + (a == b));
      System.out.println("a != b: " + (a != b));
      System.out.println("a > b: " + (a > b));
      System.out.println("a < b: " + (a < b));
      System.out.println("a >= b: " + (a >= b));
      System.out.println("a <= b: " + (a <= b));
      System.out.println("\nLogical Operators:");
      boolean x = true, y = false;
      System.out.println("x && y: " + (x && y));
      System.out.println("x || y: " + (x || y));
      System.out.println("!x: " + (!x));
      System.out.println("\nAssignment Operators:");
    c = a + b;
      System.out.println("c = a + b: " + c);
    c += a;
      System.out.println("c += a: " + c);
    c -= a;
      System.out.println("c -= a: " + c);
    c *= a;
      System.out.println("c *= a: " + c);
    c /= a;
        System.out.println("c /= a: " + c);        System.out.println("\nBitwise Operators:");
    System.out.println("a & b: " + (a & b));
     System.out.println("a | b: " + (a | b));
     System.out.println("a ^ b: " + (a ^ b));
     System.out.println("~a: " + (~a));
    }
}
