# Exp.No:17  
## EXCEPTION HANDLING

---

### AIM  
To create python program to Place result="You can't divide with 0" to the right place so that program avoids ZeroDivisionError.

---

### ALGORITHM

1.Prompt the user to enter the numerator.

2.Prompt the user to enter the denominator.

3.If the denominator is 0:

4.Set result = "You can't divide with 0"

Else:

5.Perform the division: result = numerator / denominator

Display or return the result.



### PROGRAM

a=int(input())

b=int(input())

try:

    c=a/b
    
    print(c)
    
except:

    print("You can't divide with 0")
    
### OUTPUT


![image](https://github.com/user-attachments/assets/c59b99a4-f8dc-4594-abe2-6d04c4599280)


### RESULT
Thus the python program to Place result="You can't divide with 0" to the right place so that program avoids ZeroDivisionError was created and executed successfully.


