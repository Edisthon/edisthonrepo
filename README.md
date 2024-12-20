# 25960_Hirwa_Yvan_Wednesday_Evening
# Exception Handling Demonstration

This repository provides a comprehensive demonstration of exception handling in Java through real-life scenarios. Each type of exception is encapsulated in its own class, allowing users to understand how to simulate, trigger, and handle various exceptions effectively.

## Objective

The goal of this project is to enhance the understanding of exception handling in Java by:

- Simulating specific exceptions in meaningful scenarios.
- Demonstrating how exceptions occur.
- Providing appropriate handling mechanisms using `try-catch` blocks.
- Using comments and user input to explain and interact with the code.

---

## How It Works

The project includes:

1. **Main Class** (`ExceptionHandlerMain`):

   - Acts as the entry point for users to interact with the program.
   - Provides a menu for selecting which exception to demonstrate.
   - Continuously loops, allowing multiple exceptions to be tested until the user exits.

2. **Exception Classes**:

   - Each exception type is implemented in a separate class for modularity and clarity.
   - Every class includes a `demonstrate` method to simulate a real-world scenario for the respective exception.

3. **Real-Life Scenarios**:

   - Each exception demonstration uses user input to make the simulation realistic and interactive.

---

## List of Exceptions and Their Scenarios

### 1. **IOException**

- **Scenario**: Reading a file from disk that may not exist.
- **Example**: The user is prompted to enter a file name. If the file doesn't exist, an `IOException` is caught.

### 2. **FileNotFoundException**

- **Scenario**: Attempting to open a non-existent file.
- **Example**: The user inputs a file name. If the file is missing, the program catches a `FileNotFoundException`.

### 3. **EOFException**

- **Scenario**: Reading beyond the end of a file.
- **Example**: The user inputs a file name. If the end of the file is reached unexpectedly, an `EOFException` is caught.

### 4. **SQLException**

- **Scenario**: Simulating database connection issues.
- **Example**: The user inputs database credentials. If the connection fails, a `SQLException` is caught.

### 5. **ClassNotFoundException**

- **Scenario**: Loading a missing class at runtime.
- **Example**: The user inputs a class name. If the class doesn't exist, a `ClassNotFoundException` is caught.

### 6. **ArithmeticException**

- **Scenario**: Performing invalid arithmetic operations (e.g., division by zero).
- **Example**: The user inputs two numbers. If the divisor is zero, an `ArithmeticException` is caught.

### 7. **NullPointerException**

- **Scenario**: Accessing a null reference.
- **Example**: The user enters a string. If it's empty, the program sets it to `null` and triggers a `NullPointerException`.

### 8. **ArrayIndexOutOfBoundsException**

- **Scenario**: Accessing an invalid index in an array.
- **Example**: The user inputs an index to access in a predefined array. Invalid indices trigger an `ArrayIndexOutOfBoundsException`.

### 9. **ClassCastException**

- **Scenario**: Casting an object to an incompatible type.
- **Example**: An object is deliberately cast to an incompatible type, triggering a `ClassCastException`.

### 10. **IllegalArgumentException**

- **Scenario**: Passing invalid arguments to a method.
- **Example**: The user inputs an invalid thread priority, triggering an `IllegalArgumentException`.

### 11. **NumberFormatException**

- **Scenario**: Converting an invalid string to a number.
- **Example**: The user inputs a string that cannot be parsed into a number, triggering a `NumberFormatException`.

---

## Usage Instructions

1. **Compile the Classes**:
   Compile all Java files together using:

   ```bash
   javac *.java
   ```

2. **Run the Main Program**:
   Start the program by running:

   ```bash
   java ExceptionHandlerMain
   ```

3. **Select an Exception to Demonstrate**:

   - Follow the on-screen menu to select an exception by number.
   - Input relevant data when prompted.

4. **Exit**:

   - Select option `0` to exit the program.

---

## Features

- **Interactive**: The program uses `Scanner` for dynamic user input.
- **Reusable**: Exception classes are modular and can be used in other projects.
- **Comprehensive**: Covers both checked and unchecked exceptions in Java.
- **Educational**: Includes detailed comments and scenarios to facilitate learning.

---

## File Structure

```
src/
├── IOExceptionDemo.java
├── FileNotFoundExceptionDemo.java
├── EOFExceptionDemo.java
├── SQLExceptionDemo.java
├── ClassNotFoundExceptionDemo.java
├── ArithmeticExceptionDemo.java
├── NullPointerExceptionDemo.java
├── ArrayIndexOutOfBoundsExceptionDemo.java
├── ClassCastExceptionDemo.java
├── IllegalArgumentExceptionDemo.java
├── NumberFormatExceptionDemo.java
├── ExceptionHandlerMain.java
```

---

##

---

##



