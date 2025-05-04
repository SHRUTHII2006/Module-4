# Exp.No:20  
## SEB - ARITHMETIC CALCULATION USING CLASS

---

### AIM  
To write a Python program to perform addition and division operations using a class. The class should be named `Saveetha`, and the function names should be `setvalues` (to set `a` and `b` values), `add`and `sub`. The program should handle the following cases:  
- `choice 1` → Perform addition  
- `choice 2` → Perform subtraction  
- `choice 0` → Exit  
- For other choices, print 'Invalid choice'

---

### ALGORITHM

1. Begin the program.  
2. Create a class `Saveetha`.  
3. Define the following methods inside the `Saveetha` class:  
   - `__init__(self)`: Initializes `a` and `b` to zero.  
   - `setvalues(self, a, b)`: Sets the values of `a` and `b`.  
   - `add(self)`: Performs the addition operation.   
4. Create a `main()` function.  
5. Take input from the user for the values of `a` and `b` using `setvalues(a, b)` method.  
6. Use a `while True` loop to repeatedly ask the user for a choice:  
   - If the choice is 1, call the `add()` method and print the result.  
   - If the choice is 2, call the `sub()` method and print the result. 
   - If the choice is 0, print "Exiting!" and exit the loop.  
   - If the choice is not 1, 2, or 0, print "Invalid choice".  
7. Terminate the program.

---

### PROGRAM

```

class calculate:

def setvalues(self,a,b):

self.a=a

        self.b=b

    def add(self):

        print(f"Result:  {self.a+self.b}")

    def sub(self):

        print(f"Result:  {self.a-self.b}")

calc=calculate()

a=int(input())

b=int(input())

calc.setvalues(a,b)

while True:

    choice=int(input())

    if choice==1:

        calc.add()

    elif choice==2:

        calc.sub()

    elif choice==0:

        print("Exiting!")

        break

    else:

        print("Invalid input")
    

```

### OUTPUT

![image](https://github.com/user-attachments/assets/64ba1119-482e-4e60-a4d7-f63c754c1158)




### RESULT


Thus the Python program to perform addition and division operations using a class. The class should be named `Saveetha`, and the function names should be `setvalues` (to set `a` and `b` values), `add`and `sub`. The program should handle the following cases:  
- `choice 1` → Perform addition  
- `choice 2` → Perform subtraction  
- `choice 0` → Exit  
- For other choices, print 'Invalid choice' was successfully executed.
