# Assignment 1 – IT3040 ITPM Transliteration Accuracy Testing (Option 1)

## Student Details

Name: Lakmali M.A.D.M
Student ID: IT23679344

---

## Project Description

This project contains automated test cases for evaluating the accuracy of the Singlish-to-Sinhala transliteration feature on:
https://www.pixelssuite.com/chat-translator

The testing is performed using Playwright automation with Excel-based test cases.

---

## Project Structure

```
IT23679344/
├── IT23679344_test_automation.py
├── IT23679344_Assignment 1 - Test cases.xlsx
├── IT23679344_repo_link.txt
└── README.md
```

---

## Setup Instructions

### 1. Install Python 3.13

Download from https://www.python.org
Make sure to enable "Add Python to PATH" during installation.

---

### 2. Install Dependencies

```
pip install -U pip
pip install playwright openpyxl
```

---

### 3. Install Playwright Browsers

```
playwright install
```

---

### 4. Project Setup

Place the following files in the same folder:

* IT23679344_test_automation.py
* IT23679344_Assignment 1 - Test cases.xlsx

---

### 5. Navigate to Project Folder

```
cd C:\Users\ASUS\Desktop\ITPMASSGMNT\IT23679344
```

---

### 6. Run the Script

```
python IT23679344_test_automation.py --excel "IT23679344_Assignment 1 - Test cases.xlsx" --header-row 1 --input-col "Input" --expected-col "Expected output" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
```

---

## Notes

* File names must match exactly
* Do not move the Excel file while the script is running
* Keep both files in the same directory
* Press CTRL + C to stop execution
* Do not interact with the browser during automation

---

## Test Coverage

Total Test Cases: 50
Type: Negative test cases
Input Types Covered: 24 Singlish input categories
Website Tested: pixelssuite.com/chat-translator

---

## Output

Actual Output and Status are automatically saved in the Excel file after execution.

---

## Summary

This project demonstrates automated testing of a transliteration system using Python, Playwright, and Excel integration, focusing on identifying failures through negative test cases.
