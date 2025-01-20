# Total-number-of-odd-numbers-1-100-
Total Number of Odd Numbers (1-100)

public class CountOddNumbers {
    public static void main(String[] args) {
        int count = 0;
        for (int i = 1; i <= 100; i += 2) {
            count++;
        }
        System.out.println("Total number of odd numbers between 1 and 100: " + count);
    }
}

Output

Total number of odd numbers between 1 and 100: 50
