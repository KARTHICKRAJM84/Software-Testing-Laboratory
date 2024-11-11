# Ex.No: 6 To check whether the string is Palindrome and generate test cases.

### DATE:                                                                            
### REGISTER NUMBER : 212221040073
### AIM: 
Write a Python program to check whether the string is Palindrome and generate test cases. 
### Algorithm:
1. Start
2. Get an input from the user by prompting 
3. Run a loop form 0 to len/2.
4. Check if the characters are the same both from the start and the end till len/2. 
5. If it is, return the result that it is a palindrome. 
6. Else, return that it is not a palindrome. 
7. Stop the program.
### Program:
```
def is_palindrome(s):
    if not isinstance(s, str):
        return f"Invalid input: {s} is not a string."
    s = s.lower().replace(" ", "").replace(",", "").replace(".", "")
    return f"{s} is a palindrome." if s == s[::-1] else f"{s} is not a palindrome."

print(is_palindrome("madam"))            
print(is_palindrome("racecar"))          
print(is_palindrome("hello"))            
print(is_palindrome("A man a plan a canal Panama")) 
print(is_palindrome("12321"))            
print(is_palindrome("12345"))            
print(is_palindrome("Was it a car or a cat I saw")) 
print(is_palindrome("No lemon, no melon"))           
print(is_palindrome(12321))              
print(is_palindrome(["madam"]))          
```











### Output:

![image](https://github.com/user-attachments/assets/a34883da-216a-45f0-a722-0ae81cfe18a1)




### Result:
Thus, a program to check palindrome has been written and test cases have been written and verified successfully.
