# Ex.No: 1 Write programs in Python Language to demonstrate the working of followingconstructs with possible test cases: a) do…while b) while…do c) if …else d) switch e) for 

### DATE:                                                                       
### REGISTER NUMBER : 212221040073

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
### do…while
```
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
### Output:
![STL 01A](https://github.com/user-attachments/assets/1cd97bdc-c6bd-4fed-9cc2-cb92601d2369)
 ### while
```
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
### Output:
![STL 01B](https://github.com/user-attachments/assets/4fe75f84-856e-491c-ae99-dc2225514e4b)
![STL 01 b](https://github.com/user-attachments/assets/cd745beb-1db8-4eab-a44c-8e36d78b9566)

### if else
```
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
### Output:
![STL 01D](https://github.com/user-attachments/assets/9125819e-35db-4250-89d9-336f4f04022b)
### switch
```
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
### Output:
![STL 01C](https://github.com/user-attachments/assets/4b2df571-633c-496e-a41b-3ecf0240bc3e)
### for
```
def iterate():
    string = input("Enter a string: ")
    for i in string:
        print(ord(i), end=" ")

iterate()
```
### Output:
![STL 01E](https://github.com/user-attachments/assets/6678bdad-8da4-49fb-a251-50f73b383b5a)
### Result:
Thus, the python program to demonstrate the working of given constructs is implemented and the output is verified successfully.
