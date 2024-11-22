# Gym-Membership-Discount-Calculator
Gym Membership Discount Calculator

## Overview
This is a simple Java program that calculates the total cost of a gym membership after applying discounts. The program takes user inputs, such as age, membership duration, and the number of personal training sessions, and applies discounts based on the following rules:

Senior Citizen Discount: 30% discount for users aged 60 and above.
Advance Membership Discount: 15% discount if the membership is paid for 12 or more months in advance.
Personal Training Discount: 20% discount if the user signs up for more than 5 personal training sessions.
The program outputs the final membership cost after applying all applicable discounts.

### Features
User-friendly command-line interface.
Supports dynamic input for age, membership price, duration, and personal training sessions.
Automatically applies cumulative discounts based on user inputs.
Outputs the final membership cost with clear formatting.

### How to Run
Prerequisites
Java Development Kit (JDK) installed on your system (version 8 or higher recommended).
A Java IDE (e.g., IntelliJ IDEA, Eclipse, NetBeans) or a text editor with terminal access (e.g., VS Code).

### Steps to Run
Clone or download this repository.
Open the project in your Java IDE or navigate to the folder in your terminal.

#### Usage
Input:
The program prompts for the following:

Age: Enter your age (e.g., 65).
Price: Enter the base price of the gym membership (e.g., 100.00).
Months: Enter the duration of the membership in months (e.g., 12).
Personal Training Sessions: Enter the number of personal training sessions (e.g., 6).

#### Output:
The program calculates the total membership cost after applying applicable discounts and displays the result.

#### How It Works
The program first displays the discount rules using the Display() method.
It collects user inputs such as age, price, months, and personal training sessions using the Info() method.
Discounts are applied cumulatively based on the input in the calculateCost() method.
The final membership cost is displayed to the user.

##### Discount Rules
Senior Citizen Discount:
Applies a 30% discount for users aged 60 and above.
Advance Payment Discount:
Applies a 15% discount for memberships paid for 12 or more months in advance.
Personal Training Discount:
Applies a 20% discount if the user registers for more than 5 personal training sessions.

##### Future Enhancements
Add a graphical user interface (GUI) for better user experience.
Save user data and membership cost to a database or file for persistence.
Extend the program to support multiple users.
Add more membership plans and flexible discount options.

##### Author
Name: Mpumelelo
Email: mpumelelomkwanazi5@gamil.com
A third-year computer science student passionate about creating meaningful and functional software.

