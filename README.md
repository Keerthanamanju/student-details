import java.util.Scanner;

public class StudentDetails {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Input: Student Details
        System.out.print("Enter Student Name: ");
        String name = scanner.nextLine();

        System.out.print("Enter Student Age: ");
        int age = scanner.nextInt();

        System.out.print("Enter Student Grade: ");
        String grade = scanner.next();

        System.out.print("Enter Marks in 3 Subjects: ");
        int marks1 = scanner.nextInt();
        int marks2 = scanner.nextInt();
        int marks3 = scanner.nextInt();

        // Calculate Total and Average
        int totalMarks = marks1 + marks2 + marks3;
        double averageMarks = totalMarks / 3.0;

        // Display Student Details
        System.out.println("\nStudent Details:");
        System.out.println("Name: " + name);
        System.out.println("Age: " + age);
        System.out.println("Grade: " + grade);
        System.out.println("Marks: " + marks1 + ", " + marks2 + ", " + marks3);
        System.out.println("Total Marks: " + totalMarks);
        System.out.println("Average Marks: " + averageMarks);

        scanner.close();

OUTPUT:


PS C:\Users\MY\OneDrive\Pictures\Documents\java emc 1>  
Enter Student Name: kayana'
Enter Student Age: 18
Enter Student Grade: 10
Enter Marks in 3 Subjects: 80 90 86

Student Details:
Name: kayana'
Age: 18
Grade: 10
Marks: 80, 90, 86
Total Marks: 256
Average Marks: 85.33333333333333
PS C:\Users\MY\OneDrive\Pictures\Documents\java emc 1>
