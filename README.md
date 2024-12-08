# Recursion-1
To print n numbers using recursion in java
public class Recursion1 {
    public Recursion1() {
    }

    public static void printnumb(int n) {
        if (n != 0) {
            System.out.println(n);
            printnumb(n - 1);
        }
    }

    public static void main(String[] args) {
        int n = 5;
        printnumb(n);
    }
}
