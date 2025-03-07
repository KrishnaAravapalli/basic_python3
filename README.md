# File Operations in Python

This project contains two Python programs:
1. **Read a File and Handle Errors** - Reads a file named `sample.txt` and handles missing file errors.
2. **Write and Append Data to a File** - Writes user input to `output.txt`, appends additional data, and then displays the final content.

## Task 1: Read a File and Handle Errors

### **Problem Statement**
- Opens and reads a file named `sample.txt`.
- Prints its content line by line.
- Handles errors gracefully if the file does not exist.

### **Code Explanation**
- Uses a `try-except` block to handle `FileNotFoundError`.
- Reads the file line by line and prints the content.
- Displays an error message if the file is missing.

### **Example Output**
**If the file exists:**
```
Reading file content
Line1: This is a simple text file.
Line2: It contains multiple lines.
```

**If the file does not exist:**
```
Error: The file sample.txt was not found.
```

---

## Task 2: Write and Append Data to a File

### **Problem Statement**
- Takes user input and writes it to `output.txt`.
- Appends additional data to the same file.
- Reads and displays the final content of the file.

### **Code Explanation**
- Takes user input and writes it to `output.txt`.
- Appends additional input to the file.
- Reads and prints the final content of the file.
- Displays success messages after writing and appending.

### **Example Output**
```
Enter some text to write to the file: Hello, this is my first line.
Data successfully written to output.txt

Enter additional text to append: This is an extra line.
Data successfully appended

Final content of output.txt:
Hello, this is my first line.
This is an extra line.
```

---

## How to Run the Programs
1. Ensure you have Python installed (Python 3+ recommended).
2. Copy the script to a file (e.g., `file_operations.py`).
3. Open a terminal or command prompt and navigate to the script’s directory.
4. Run the script using:
   ```sh
   python file_operations.py
   ```

## Author
**Krishna Aravapalli**

Feel free to contribute, suggest improvements, or report issues!

