# Exp.No:2b  
## FUNCTIONS - PERFECT NUMBER

### AIM  
To write a Python program to check if a number is a Perfect number using the concept of functions.

---

### ALGORITHM
    
1. Begin the program.  
2. Read the number `n` from the user using `input()`.  
3. Convert the input to an integer.  
4. Define the function `perfectNumber(n)` with the following steps:  
    - Initialize a variable `factor_sum` to 0.  
    - Iterate through all numbers from 1 to `n//2` (as divisors of a number can't be greater than half of it).  
    - If a number `i` divides `n` perfectly (i.e., `n % i == 0`), add `i` to `factor_sum`.  
    - If `factor_sum` is equal to `n`, then print the number is a perfect number. Otherwise, print it's not a perfect number.  
5. Terminate the program.

---

### PROGRAM
```
#Reg.No:212223060119
#Name:Kavindra T G
#Add your Code Here
def perfectNumber(n):
    factor_sum = 0
    for i in range(1, n // 2 + 1):
        if n % i == 0:
            factor_sum += i
    if factor_sum == n:
        print(n, "is a Perfect Number")
    else:
        print(n, "is not a Perfect Number")

n = int(input("Enter a number: "))
perfectNumber(n)

```
### OUTPUT
![image](https://github.com/user-attachments/assets/d9efd5cf-4db3-4024-84d2-335d96a4a0af)

### RESULT
Thus, the python program to check if a number is a Perfect number using the concept of functions has been executed and verified successfully.
