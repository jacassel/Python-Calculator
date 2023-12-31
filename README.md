print("This is my Calculator App and demonstrates a basic understanding of Python.")
print("Enter '+' for addition")
print("Enter '-' for subtraction")
print("Enter '*' for multiplication")
print("Enter '/' for division")
print("Enter 'off' Close the Calculator App")
user_num1 = ''
user_num2 = ''
result = 0
while True:
    operator_choice = input("Which operator would you like to use: ")
    if operator_choice == '+':
        print("addition")
        user_num1 = input("your first number is: ")
        user_num2 = input("your second number is: ")
        result = round(int(user_num1) + int(user_num2))
        print(f'the result is: {result}')
    elif operator_choice == '-':
        print("subtraction")
        user_num1 = input("your first number is: ")
        user_num2 = input("your second number is: ")
        result = round(int(user_num1) - int(user_num2))
        print(f'the result is: {result}')
    elif operator_choice == '*':
        print("multiplication")
        user_num1 = input("your first number is: ")
        user_num2 = input("your second number is: ")
        result = round(int(user_num1) * int(user_num2))
        print(f'the result is: {result}')
    elif operator_choice == '/':
        print("division")
        user_num1 = input("your first number is: ")
        user_num2 = input("your second number is: ")
        result = round(int(user_num1) / int(user_num2))
        print(f'the result is: {result}')
    elif operator_choice == 'off':
        break
    else:
        print("please choose a valid operator")
