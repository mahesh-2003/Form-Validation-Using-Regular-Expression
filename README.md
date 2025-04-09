# Form-Validation-Using-Regular-Expression
# User Input Validator

This is a Python script that collects and validates user information including:

- Name
- Date of Birth
- Email ID (Gmail only)
- Mobile Number

Each input is validated using regular expressions and proper formatting. The script ensures that the user provides inputs in the correct format before proceeding.

---

## 🧰 Requirements

- Python 3.6 or higher

No external libraries are needed — only built-in modules (`re` and `datetime`) are used.

---

## ▶️ How to Run

1. Clone this repository or download the script file:

git clone https://github.com/yourusername/user-input-validator.git

css
Copy
Edit

2. Navigate to the project directory:

cd user-input-validator

markdown
Copy
Edit

3. Run the script:

python user_input_validator.py

yaml
Copy
Edit

---

## 📥 Input Format

| Field         | Format                          | Example               |
|---------------|----------------------------------|-----------------------|
| Name          | Alphabets and spaces only       | John Doe              |
| Date of Birth | dd-mm-yyyy                      | 15-08-1990            |
| Email         | Gmail only, lowercase preferred | johndoe123@gmail.com  |
| Mobile Number | xxx-xxx-xxxx                    | 123-456-7890          |

---

## ✅ Output

If all inputs are valid, the script will display the collected information:

--- User Information --- Name : John Doe Date of Birth: 15 August 1990 Mail ID : johndoe123@gmail.com Mobile : 1234567890

yaml
Copy
Edit

---

## 📌 Notes

- The script performs basic validation and formatting.
- Date validation includes checking for real calendar dates (e.g., no 31-02-2020).
- Email validation is restricted to Gmail accounts only.



