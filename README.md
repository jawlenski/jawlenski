- 👋 Hi, I’m @jawlenski
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
jawlenski/jawlenski is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
def swap_if_less(num1, num2):
    if num1 < num2:
        # Swap the values
        num1, num2 = num2, num1
    return num1, num2

# Taking user input for the numbers
number1 = float(input("Enter the first number: "))
number2 = float(input("Enter the second number: "))

# Call the function to swap if necessary
result1, result2 = swap_if_less(number1, number2)

# Display the result
print(f"After checking and possibly swapping, the numbers are: {result1}, {result2}")

