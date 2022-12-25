# pwskills_java_assigment

Q1]  <!-- Q1 - Take 2 integer values in two variables x and y and print their product. (Easy) -->
<!-- Sample Input : x=2, y=4 (Both integers) -->
<!-- Sample Output : 8 -->

CODE:
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        Scanner scn = new Scanner(System.in);
        int x = scn.nextInt();
        int y = scn.nextInt();

        int product=x*y;

        System.out.println(product);
    }

}

Q2] <!-- Print the ASCII value of character ‘U’. (Easy) -->
<!-- Sample Input : already mentioned as ‘U’ -->
<!-- Sample Output : 85 -->

CODE:
import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        Scanner scn = new Scanner(System.in);
        int x = 'U';
        
        System.out.println(x);
    }

}

 Q3]  Write a Java program to take the length and breadth of a rectangle and print its area. (Easy) -->
<!-- Sample Input : 7, 4 -->
<!-- Sample Output : 28
 
CODE:

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        Scanner scn = new Scanner(System.in);
        int lenghth = scn.nextInt();
        int breath = scn.nextInt();

        int area=lenghth*breath;

        System.out.println(area);
    }

}

Q4]  Write a Java program to calculate the cube of a number. (Easy)
Sample Input : 4
Sample Output : 64
The sizeof(bool) : 1 bytes

CODE: 

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        Scanner scn = new Scanner(System.in);
        int N = scn.nextInt();

        int cube=N*N*N;

        System.out.println(cube);
    }

}

Q5] - Write a Java program to swap two numbers with the help of a third variable. 
Sample Input : 2,3
Sample Output : 3,2

CODE:

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        Scanner scn = new Scanner(System.in);
        int x = scn.nextInt();
        int y = scn.nextInt();

        int temp=x;
        x=y;
        y=temp;

        System.out.println(x+" "+y);
    }

}
