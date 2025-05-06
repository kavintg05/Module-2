# Exp.No:2c
## BUILT-IN FUNCTIONS AND LAMBDA FUNCTIONS - RELATING TWO NUMBERS

---

### AIM  
To write a Python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function.

---

### ALGORITHM

1. Begin the program.  
2. Use `eval()` to get two numbers (`num1` and `num2`) from the user.  
3. Define a lambda function `max` that takes two arguments `x` and `y`.  
4. The lambda function compares the numbers and prints:
   - If `x > y`, then it prints: "`num2` is smaller than `num1`".
   - Otherwise, it prints: "`num1` is smaller than `num2`".
5. Call the lambda function by passing `num1` and `num2` as arguments.  
6. Terminate the program.

---

### PROGRAM

```
# Reg.No-212223060119
# Name-Kavindra T G
num1 = eval(input("Enter the first number: "))
num2 = eval(input("Enter the second number: "))

relation = lambda x, y: print(f"{y} is smaller than {x}" if x > y else f"{x} is smaller than {y}" if x < y else "Both numbers are equal")

relation(num1, num2)

```

### OUTPUT

![image](https://github.com/user-attachments/assets/d0d22424-bdd4-4446-931d-fb7f1607bdd4)




### RESULT
Thus, the python program to check the relation between two numbers — whether one number is greater than, equal to, or lesser than another — using a lambda function has been executed and verified successfully.



