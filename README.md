3. DISPLAY OF ODD NUMBERS BETWEEN 1 TO 100

public class OddNumbers {
    public static void main(String[] args) {
        System.out.println("Odd numbers from 1 to 100 are:");
        for (int i = 1; i <= 100; i += 2) { // Increment by 2
            if (i % 2 != 0) { // Check if the number is odd
                System.out.println(i);
            }
        }
    }
}

O/P

Odd numbers from 1 to 100 are:
1
3
5
7
9
…..
99
