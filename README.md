# Python
Programming in Python
Write python program to print first letter of your name 
a) Example: Peter
               *      *
               *             *
               *              *
               *      *
               *
               *
               *

code:

name = "Ujjwal"
for i in range(7):
    if i == 0:
        print("*    *")
    elif i in [1, 2, 3]:
        print("*    *")
    elif i == 4:
        print(" *  * ")
else:
    print("  **  ")
b) Print your name by using for loop

code:
name = "Ujjwal"
for letter in name:
    print(letter)

c) check the user name is palindrome or not

code:
name = "Ujjwal"
if name.lower() == name[::-1].lower():
    print("The name is a palindrome")
else:
    print("The name is not a palindrome")





