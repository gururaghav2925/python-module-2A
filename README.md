#  Python Program: Compute the Factorial of a Given Number

##  Aim
To write a Python program that computes the factorial of a given number.

##  Procedure
1. Start the program and prompt the user to enter a non-negative integer.
2. Check if the number is zero or one — the factorial is 1 in both cases.
3. If the number is greater than 1, use a loop (or recursion) to calculate the factorial:
   - Initialize a variable (e.g., `fact`) to 1.
   - Multiply `fact` by each number from 1 to the input number.
4. Print the final result.
5. End the program.
## Program 

```python
a=int(input())
fact=1
if a<0:
    print("Factorial does not exist for negative number")
elif a==0:
    print("the factorial of 0 is 1")
else:
    for i in range(1,a+1):
      fact=fact*i
    print("Factorial of the given number",a,"is",fact)

```
## Output

![image](https://github.com/user-attachments/assets/09e9d414-24db-4542-9943-c948bf1b65b0)


##  Result
The program successfully calculates the factorial of a given number and displays the result.
