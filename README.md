# java-array-sum
public class ArraySum {
    public static void main(String[] args) {
        int[] numbers = {1, 2, 3, 4, 5}; // You can change the numbers in the array
        int sum = calculateSum(numbers);
        System.out.println("Sum of the array elements is: " + sum);
    }

    public static int calculateSum(int[] arr) {
        int sum = 0;
        for (int num : arr) {
            sum =+num;
        }
        return sum;
    }
}
