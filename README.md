1  

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String S = scanner.nextLine();
        System.out.println("Hello, " + S);
    }
}



2=> 
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        int i = scanner.nextInt();
        long l = scanner.nextLong();
        char c = scanner.next().charAt(0);
        float f = scanner.nextFloat();
        double d = scanner.nextDouble();
        System.out.println(i);
        System.out.println(l);
        System.out.println(c);
        System.out.printf("%.2f\n", f);// %.2f =>رقمين بعد العلامه
        System.out.printf("%.5f\n", d);
    }
}


3 =>   

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
         int x = scanner.nextInt();
        int y = scanner.nextInt();
        System.out.println(x + " + " + y + " = " + (x + y));
      System.out.println(x + " * " + y + " = " + (x * y));
        System.out.println(x + " - " + y + " = " + (x - y));
    }
}


4=> 

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        int A = scanner.nextInt();
        int B = scanner.nextInt();
        int C = scanner.nextInt();
        int D = scanner.nextInt();
        int X = (A * B) - (C * D);
        System.out.println("Difference = " + X);
    }
}




5=> 

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        final double PI = 3.141592653;

        Scanner scanner = new Scanner(System.in);
        double R = scanner.nextDouble();

        double area = PI * R * R;

        System.out.printf("%.9f\n", area);//تسع ارقام بعد العلامه
    }
}


6=>

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        String n = scanner.next();
        String m = scanner.next();

       
        int lastDigitN = Character.getNumericValue(n.charAt(n.length() - 1));
        int lastDigitM = Character.getNumericValue(m.charAt(m.length() - 1));

        System.out.println(lastDigitN + lastDigitM);
    }
}


7=>

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        long N = scanner.nextLong();

        long sum = N * (N + 1) / 2;//مجموع الارقام

        System.out.println(sum);
    }
}
