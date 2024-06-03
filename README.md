# TASK_1_SIMPLE_CALCULATOR
# TASK_1_SIMPLE_CALCULATOR
## AIM
To develop a simple calculator program in Python that can perform basic arithmetic operations such as addition, subtraction, multiplication, and division.
## ALGORITHM
STEP 1:Define the Functions for Arithmetic OperationsCreate functions to perform addition, subtraction, multiplication, and division.
STEP 2:Display Options to the UserProvide a menu to the user to select the desired arithmetic operation.
STEP 3:Take User Input Prompt the user to input their choice of operation and the numbers they wish to perform the operation on.
STEP 4:Perform the Calculation Based on the user’s choice, call the appropriate function to perform the calculation.
STEP 5:Display the ResultOutput the result of the calculation to the user.
STEP 6:Error Handling Handle possible errors such as division by zero and invalid input.
STEP 7:Loop the Program Allow the user to perform multiple calculations without restarting the program.
## PROGRAM 
```python
print("1 - add")
print("2 - subtract")
print("3 - multiply")
print("4 - divide")
operation =  int(input("enter the option:"))

if(operation in [1,2,3,4]):
    number1 = int(input("Enter the first number:"))
    number2 = int(input("Enter the second number:"))

    if(operation == 1):
       result = number1 + number2
    elif(operation == 2):
       result = number1 - number2
    elif(operation == 3):
       result = number1 * number2
    elif(operation == 4):
       result = number1 // number2

else:
    print("Invalid operation entered")

print("The result of the operation is {}".format(result))
```
## OUTPUT
![](./WhatsApp%20Image%202024-06-02%20at%2022.45.54_9318ba89.jpg)
## RESULT
program is executed successfullY
