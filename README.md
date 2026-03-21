# Python_Calculator_project
AUTHOR - AMIT

def add(num1,num2):
    return num1 + num2

def sub(num1,num2):
    return num1 - num2

def multiply(num1,num2):
    return num1 * num2

def divide(num1,num2):
    return num1 / num2

def average(num1,num2):
    return(num1+num2)/2


print("please select a operation:\n" \
      "1. addition\n" \
      "2. subtract\n" \
      "3. mulitply\n" \
      "4. divide\n" \
      "5. average\n")

select = int(input("Enter a operation from 1,2,3,4,5:"))

number1 = int(input("Enter a first number: "))
number2 = int(input("Enter a second number: "))


if select == 1:
    print(number1, "+", number2, "= ", \
          add(number1,number2))
    
elif select == 2:
    print(number1, "-", number2, "= ", \
          sub(number1,number2))
    
elif select == 3:
    print(number1, "*", number2, "= ", \
          multiply(number1,number2))
    
elif select == 4:
    print(number1, "/", number2, "= ", \
          divide(number1,number2))
    
elif select == 5:
    print("(",number1, "+", number2, "/", "2", ")", "= ", \
          average(number1,number2))
    
else:
    print("Invalid number!")
