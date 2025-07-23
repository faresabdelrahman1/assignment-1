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

8 =>


import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        int A = scanner.nextInt();
        int B = scanner.nextInt();

     
        double result = (double) A / B;

      
      //  System.out.println("floor " + A + " / " + B + " = " + (int) Math.floor(result));
       // System.out.println("ceil " + A + " / " + B + " = " + (int) Math.ceil(result));
       // System.out.println("round " + A + " / " + B + " = " + Math.round(result));
    }
}


9=>



import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        
        int A = scanner.nextInt();
        int B = scanner.nextInt();

       
        if (A >= B) {
            System.out.println("Yes");
        } else {
            System.out.println("No");
        }
    }
}


10=>

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

       
        int A = scanner.nextInt();
        int B = scanner.nextInt();
        if (A % B == 0 || B % A == 0) {
            System.out.println("Multiples");
        } else {
            System.out.println("No Multiples");
        }
    }
}

11=> 

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        
        int A = scanner.nextInt();
        int B = scanner.nextInt();
        int C = scanner.nextInt();

        
        int min = A;
        int max = A;

       
        if (B < min) {
            min = B;
        }
        if (B > max) {
            max = B;
        }

       
        if (C < min) {
            min = C;
        }
        if (C > max) {
            max = C;
        }

        
        System.out.println(min + " " + max);
    }
}

11=> 

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

      
        String F1 = scanner.next();
        String S1 = scanner.next();

        
        String F2 = scanner.next();
        String S2 = scanner.next();

        
        if (S1.equals(S2)) {
            System.out.println("ARE Brothers");
        } else {
            System.out.println("NOT");
        }
    }
}


12=>


import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

       
        char X = scanner.next().charAt(0);

       
        
        if (X >= '0' && X <= '9') {
            System.out.println("IS DIGIT");
        } 
        
        else if ((X >= 'A' && X <= 'Z') || (X >= 'a' && X <= 'z')) {
            System.out.println("ALPHA");
            if (X >= 'A' && X <= 'Z') {
                System.out.println("IS CAPITAL");
            } else {
                System.out.println("IS SMALL");
            }
        }
    }
}


13=>




import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        
        char X = scanner.next().charAt(0);

     
        if (X >= 'a' && X <= 'z') {
            
            char upper = (char)(X - 32);
            System.out.println(upper);
        } else if (X >= 'A' && X <= 'Z') {
            
            char lower = (char)(X + 32);
            System.out.println(lower);
        }
    }
}

