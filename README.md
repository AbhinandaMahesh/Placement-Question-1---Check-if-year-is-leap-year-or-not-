# Leap Year Checker

A simple Java program that checks whether a given year is a leap year or not.

## Overview

This program determines if a specified year is a leap year based on the standard leap year rules:
- Years divisible by 4 are leap years
- Except years divisible by 100, which are not leap years
- Unless years divisible by 400, which are leap years

## Code Explanation

The program uses a straightforward conditional logic:
1. First checks if the year is divisible by 400 → leap year
2. Then checks if divisible by 100 → not a leap year  
3. Finally checks if divisible by 4 → leap year

## Usage

1. Clone the repository:
```bash
git clone https://github.com/your-username/leapyear-checker.git
```

2. Navigate to the project directory:
```bash
cd leapyear-checker
```

3. Compile the Java file:
```bash
javac leapyear.java
```

4. Run the program:
```bash
java leapyear
```

## Customization

To check a different year, modify the `year` variable in the `main` method:
```java
int year = 2024; // Change this to any year you want to check
```

## Example Output

For the current year value (2200), the output will be:
```
not leap year
```

## License

This project is open source and available under the [MIT License](LICENSE).
