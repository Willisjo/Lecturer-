# Lecturer-
Java

// Project: MyGradesProject
// Package: com.example
// Class: Lecturer

package com.example;

import java.util.Scanner;

public class Lecturer {
    public static void main(String[] args) {
        calculateAverageMarks();
    }

    public static void calculateAverageMarks() {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter marks for Java Programming: ");
        double javaMarks = scanner.nextDouble();

        System.out.print("Enter marks for Networking: ");
        double networkingMarks = scanner.nextDouble();

        System.out.print("Enter marks for Maths: ");
        double mathsMarks = scanner.nextDouble();

        // Calculate average marks
        double averageMarks = (javaMarks + networkingMarks + mathsMarks) / 3;

        // Output the data
        System.out.println("Marks for Java Programming is: " + javaMarks);
        System.out.println("Marks for Networking is: " + networkingMarks);
        System.out.println("Marks for Maths is: " + mathsMarks);
        System.out.println("The average is: " + averageMarks);

        scanner.close();
    }
}
		
