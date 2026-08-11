# Reverse Number in Java

A simple Java program to reverse the digits of a given number.

## 📌 Description

This program takes a number as input from the user and reverses its digits.

### Example

```text
Input:  12345
Output: 54321
```

## 💻 Technologies Used

* Java
* Scanner
* While Loop
* Modulo (`%`) Operator

## 🚀 How to Run

### 1. Compile the program

```bash
javac ReverseNumber.java
```

### 2. Run the program

```bash
java ReverseNumber
```

## 📝 Example Output

```text
Enter a number: 12345
Original Number: 12345
Reversed Number: 54321
```

Another example:

```text
Enter a number: 9876
Original Number: 9876
Reversed Number: 6789
```

## 🔢 How It Works

The program extracts the last digit using the modulo operator:

```text
digit = number % 10
```

Then it adds the digit to the reversed number:

```text
reverse = reverse * 10 + digit
```

Finally, the last digit is removed from the original number:

```text
number = number / 10
```

This process continues until the number becomes `0`.

## 📂 Project Structure

```text
reverse-number-java/
│
├── ReverseNumber.java
├── .gitignore
└── README.md
```

## 📜 License

This project is created for learning and educational purposes.
