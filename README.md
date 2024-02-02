# swetraj_git
public class MultiplicationTable {
    public static void main(String[] args) {
        // Specify the number for which you want to generate the multiplication table
        int number = 5;

        // Print the multiplication table for the specified number
        System.out.println("Multiplication Table for " + number + ":");
        for (int i = 1; i <= 10; i++) {
            int result = number * i;
            System.out.println(number + " * " + i + " = " + result);
        }
    }
}
