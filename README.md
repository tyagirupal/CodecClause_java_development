# CodecClause_java_development
import java.util.Scanner;

public class ResumeBuilder {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.println("Online Resume Builder");
        System.out.println("---------------------");

        // Personal Information
        System.out.println("Enter your name:");
        String name = scanner.nextLine();

        System.out.println("Enter your email address:");
        String email = scanner.nextLine();

        System.out.println("Enter your phone number:");
        String phone = scanner.nextLine();

        System.out.println("Enter your address:");
        String address = scanner.nextLine();

        System.out.println("\n");

        // Education
        System.out.println("Education");
        System.out.println("---------------------");

        System.out.println("Enter your degree:");
        String degree = scanner.nextLine();

        System.out.println("Enter your university:");
        String university = scanner.nextLine();

        System.out.println("Enter your graduation year:");
        int graduationYear = scanner.nextInt();
        scanner.nextLine(); // consume the newline character

        System.out.println("\n");

        // Work Experience
        System.out.println("Work Experience");
        System.out.println("---------------------");

        System.out.println("Enter your company name:");
        String companyName = scanner.nextLine();

        System.out.println("Enter your job title:");
        String jobTitle = scanner.nextLine();

        System.out.println("Enter your job description:");
        String jobDescription = scanner.nextLine();

        System.out.println("Enter the start year:");
        int startYear = scanner.nextInt();
        scanner.nextLine(); // consume the newline character

        System.out.println("Enter the end year:");
        int endYear = scanner.nextInt();
        scanner.nextLine(); // consume the newline character

        System.out.println("\n");

        // Skills
        System.out.println("Skills");
        System.out.println("---------------------");

        System.out.println("Enter your skills (comma-separated):");
        String skills = scanner.nextLine();

        // Generate the resume
        System.out.println("\n\n");
        System.out.println("Resume");
        System.out.println("---------------------");

        System.out.println("Name: " + name);
        System.out.println("Email: " + email);
        System.out.println("Phone: " + phone);
        System.out.println("Address: " + address);

        System.out.println("\nEducation:");
        System.out.println("Degree: " + degree);
        System.out.println("University: " + university);
        System.out.println("Graduation Year: " + graduationYear);

        System.out.println("\nWork Experience:");
        System.out.println("Company: " + companyName);
        System.out.println("Job Title: " + jobTitle);
        System.out.println("Job Description: " + jobDescription);
        System.out.println("Start Year: " + startYear);
        System.out.println("End Year: " + endYear);

        System.out.println("\nSkills: " + skills);

        scanner.close();
    }
}
