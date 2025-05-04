# Exp.No:16  
## DICTIONARY - DICTIONARY KEYS ARE INTEGERS AND VALUES ARE THE FACTORIAL OF THE KEYS.


### AIM  

To Write a python program that asks the user to enter an integer n and return a dictionary whose keys are integers 1, 2, 3, ... n and whose values ​​are 1! , 2! , 3! , … , n!


### ALGORITHM

1.Prompt the user to enter an integer n.

2.Validate the input to ensure it is a positive integer (optional but recommended).

3.Initialize an empty dictionary called factorial_dict.

4.Initialize a variable factorial with value 1.

5.Loop from i = 1 to n (inclusive):

6.Multiply factorial by i to get i!.

7.Add an entry to factorial_dict with key i and value factorial.

8.After the loop ends, return or display factorial_dict.




### PROGRAM

def factorial(n):

    if n == 0 or n == 1:
    
        return 1
        
    return n * factorial(n - 1)

def generate_factorial_dict(n):

    return {i: factorial(i) for i in range(1, n)}
    
try:
    n = int(input())
    
    if n < 1:
    
        print("Please enter a positive integer.")
        
    else:
    
        result = generate_factorial_dict(n)
        
        print("The obtained dictionary is d = ", result)
        
except ValueError:

    print("Invalid input! Please enter an integer.")
    

### OUTPUT

![image](https://github.com/user-attachments/assets/17d53664-0549-4978-bd37-3c333b807e34)


### RESULT

Thus the python program that asks the user to enter an integer n and return a dictionary whose keys are integers 1, 2, 3, ... n and whose values ​​are 1! , 2! , 3! , … , n! was written and executed successfully.
