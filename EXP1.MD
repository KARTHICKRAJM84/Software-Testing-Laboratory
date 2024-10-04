# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                       
### REGISTER NUMBER : 212221040126

### AIM:  
To write python programs for do…while, while, for, switch and if…else and test with possible test 
Cases 

### Algorithm:
1. Start the program.
2. Create separate files for each given program.
3. Write simple program for each construct.
4.  the program with possible test cases.
5. Stop the program.
### Program:

```
##do…while
def display():
    start = input("Enter a positive value for START: ")
    end = input("Enter a positive value for END: ")
    
    if start.isnumeric() and end.isnumeric():
        start = int(start)
        end = int(end)
        
        if start < end :  
            while start <= end:    
                print(start, end=' ')
                start += 1
    else:
        print("Enter a valid positive number.")

display()
```
```
 ##while
start=input("Enter a positive value for START: ")
end=input("Entera positive value for END: ")
if start.isnumeric() and end.isnumeric():
    start =int(start)
    end = int(end)
    
    while start < end:
        print(start)
        start+=1
else:
    print("Enter a valid positive number.")
```
```

###switch\
def switch():
    switcher = {
        0: "even",
        1: "odd"
    }

    n = input('Enter a value for N: ')
    try:
        n = int(n)
        print(switcher[n % 2])
    except ValueError:
        print("Enter a valid number.")

switch()
```
```

##ifelse
def compare():
    a = input("Enter a value for A: ")
    b = input("Enter a value for B: ")
    
    try:
        a = int(a)
        b = int(b)
        
        if a > b:
            print("A is greater than B")
        elif a < b:
            print("B is greater than A")
        else:
            print("A is equal to B")
    
    except ValueError:
        print("Enter a valid number.")


compare()
```
```

##for
def iterate():
    string = input("Enter a string: ")
    for i in string:
        print(ord(i), end=" ")

iterate()
```















### Output:

![Screenshot 2024-08-23 105409](https://github.com/user-attachments/assets/62b431f6-331b-40fe-b380-a35d262d1f70)

![Screenshot 2024-08-23 105421](https://github.com/user-attachments/assets/ded320c9-830f-46fd-a8a1-20735f971320)
![Screenshot 2024-08-23 112030](https://github.com/user-attachments/assets/b4a23cd6-d69a-4858-b3e2-c30a5a6d5555)
![Screenshot 2024-08-23 112048](https://github.com/user-attachments/assets/1901e89b-5ef2-439f-92e1-2de79ea90e5e)

![Screenshot 2024-09-20 103151](https://github.com/user-attachments/assets/700bd3bc-b9f6-4cc5-86e8-7f0ba7683d67)
![Screenshot 2024-09-20 103708](https://github.com/user-attachments/assets/5b48bb1b-2fa8-46e7-8618-b7cd43890c56)
![Screenshot 2024-09-20 104217](https://github.com/user-attachments/assets/cc1a8e4f-2311-41db-b947-74cd3fed5a00)

![Screenshot 2024-09-20 104302](https://github.com/user-attachments/assets/84916d83-b4e6-4e32-8f35-fbfa01417880)



### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.
