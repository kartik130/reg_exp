# User Information Collector 📝

This is a simple Python script that collects user details such as Name, Date of Birth, Email ID, and Mobile Number, while validating the inputs using Regular Expressions.

## 🔍 Features

- Validates **Name** (alphabetic characters, spaces, hyphens, and apostrophes).
- Validates and formats **Date of Birth** to `dd Month yyyy` format.
- Validates **Gmail ID** (ensures it matches standard Gmail structure).
- Validates **Mobile Number** in `xxx-xxx-xxxx` format and stores it as a plain 10-digit string.

## 📦 Requirements

- Python 3.x  
  This script uses built-in modules:
  - `re` (Regular Expressions)
  - `datetime`

No external libraries are required.

## 🚀 How to Run

1. Clone the repository or download the script.
2. Open your terminal or command prompt.
3. Navigate to the directory containing the script.
4. Run the script:

```bash
python script_name.py
