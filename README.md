# AP-Assignment-5th
Write a Java program to sort an array of integers in ascending order.


import java.util.Arrays;
public class AscendingSort {
    public static void main(String[] args) {
        int[] numbers = {45, 12, 78, 34, 23};
        Arrays.sort(numbers);
        System.out.println("Sorted array in ascending order:");
        for (int num : numbers) {
            System.out.print(num + " ");
        }
    }
}
