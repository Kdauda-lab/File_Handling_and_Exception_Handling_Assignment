# 🖋️ File Read & Write Challenge with Error Handling 🧪

This Python program demonstrates how to read a file, modify its content, and write the result to a new file — all while handling common file-related errors.

## 🚀 Features

- Prompts the user for an input filename.
- Reads the content of the specified file.
- Applies a basic transformation (uppercase by default).
- Asks the user for an output filename and saves the modified content there.
- Includes error handling for:
  - File not found
  - Read/write permission issues

## 🧠 How It Works

The program performs the following steps:
1. **Prompt for Input File**: Asks the user to enter the name of the file to read.
2. **Read Content**: Opens the file and reads its contents.
3. **Modify Content**: Converts all text to uppercase (customizable!).
4. **Prompt for Output File**: Asks where to save the modified content.
5. **Write Content**: Writes the transformed content to the new file.

## 🛠️ Customization

Want to change how the file is modified? Edit the `modify_content()` function in the script. 
For example:
```python
def modify_content(content):
    return content.replace("old", "new")
