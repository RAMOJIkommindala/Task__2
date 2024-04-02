import java.util.Scanner;

public class GradeCalculator {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Input marks obtained in each subject
        System.out.println("Enter marks obtained in each subject (out of 100):");
        int numOfSubjects = 0;
        int totalMarks = 0;

        while (true) {
            System.out.print("Enter marks for subject " + (numOfSubjects + 1) + " (or -1 to finish): ");
            int marks = scanner.nextInt();
            if (marks == -1) {
                break;
            }
            totalMarks += marks;
            numOfSubjects++;
        }

        // Calculate Total Marks
        System.out.println("Total Marks: " + totalMarks);

        // Calculate Average Percentage
        double averagePercentage = (double) totalMarks / numOfSubjects;
        System.out.printf("Average Percentage: %.2f%%\n", averagePercentage);

        // Grade Calculation
        char grade;
        if (averagePercentage >= 90) {
            grade = 'A';
        } else if (averagePercentage >= 80) {
            grade = 'B';
        } else if (averagePercentage >= 70) {
            grade = 'C';
        } else if (averagePercentage >= 60) {
            grade = 'D';
        } else {
            grade = 'F';
        }

        // Display Results
        System.out.println("Grade: " + grade);

        scanner.close();
    }
}
