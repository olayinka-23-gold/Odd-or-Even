## 🔢 Odd or Even Checker

This is a simple Python script that checks whether a user-inputted number is **odd** or **even**. It includes basic input validation and user-friendly prompts to ensure a smooth experience.

### 🔧 Features:
- Validates that the number is greater than zero
- Determines if a number is even or odd
- Keeps prompting until a valid number is entered

### 💻 Code

```python
while True:
    number = int(input("Enter a number to check if it is odd or even: "))
    
    # Make sure the number is greater than zero
    if number > 0:
        break  # Exit the loop if valid input
    print("Number must be greater than zero. Try again.")

# Check if the number is even or odd
if number % 2 == 0:
    print(f"{number} is an even number.")
else:
    print(f"{number} is an odd number.")
```

---

### 💡 Notes:
- This script ensures that 0 or negative numbers are not accepted.
- You can add enhancements like `try/except` to handle non-numeric input in the future.

