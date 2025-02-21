# NestTry - Java Nested Try-Catch Example  

This Java program demonstrates **nested try-catch statements** for handling exceptions.  

## 📌 **About the Code**
The program performs the following steps:
1. **First try block**:
   - It checks the number of command-line arguments (`args.length`).
   - It attempts to divide `42` by `args.length`, which may cause a **divide-by-zero** error.
   
2. **Nested try block**:
   - If `args.length == 1`, it tries to divide a number by zero, which causes an **ArithmeticException**.
   - If `args.length == 2`, it attempts to access an invalid array index (`c[42]`), causing an **ArrayIndexOutOfBoundsException**.

## 🛠 **How to Run**
```bash
javac NestTry.java  # Compile the program
java NestTry arg1 arg2  # Run with arguments
