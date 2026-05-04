Assignment 1 – IT3040 ITPM
Transliteration Accuracy Testing (Option 1)
This project contains automated test cases for evaluating the accuracy of the Singlish-to-Sinhala transliteration feature on pixelssuite.com/chat-translator.
---
Project Structure
```
assignment1_repo/
├── test_automation/
│   ├── test_automation.py          # Playwright automation script
│   └── Assignment 1 - Test cases.xlsx  # Test cases with results
└── README.md
```
---
Setup Instructions
1. Install Python 3.13
Download and install from python.org
> ⚠️ During installation, make sure to check **"Add Python to PATH"**
---
2. Install Dependencies
Open Command Prompt and run:
```bash
pip install -U pip
pip install playwright openpyxl
```
---
3. Install Playwright Browsers
```bash
playwright install
```
---
4. Project Setup
Place the following files in the same folder:
`test_automation.py`
`Assignment 1 - Test cases.xlsx`
---
5. Navigate to the Project Folder
Open Command Prompt and navigate using `cd`:
```bash
cd C:\Users\Kaushini\Documents\test_automation
```
(Replace the path with the actual location of your files)
---
6. Run the Script
```bash
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --header-row 1 --input-col "Input" --expected-col "Expected output" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
```
---
Notes
Make sure the Excel file name matches exactly as shown above
Do not move the Excel file to another folder while the script is running
Keep both files (`test_automation.py` and the Excel file) in the same directory
Press CTRL + C to stop the script after execution is complete
A browser window will open automatically — do not click or interact with it during the test run
Results (Actual Output and Status) will be saved automatically to the Excel file
---
Test Coverage
Total Test Cases: 50
Type: Negative test cases (system failure cases)
Input Types Covered: 24 Singlish input categories
Website Tested: pixelssuite.com/chat-translator – Chat Sinhala mode
