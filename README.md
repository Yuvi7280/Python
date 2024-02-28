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
b) Print your name by using for loop

c) check the user name is palindrome or not

a) star_pattern = [
"***** ",
"*    *",
"*    *",
"*    *",
"***** "
]

for pattern in star pattern:
print (pattern)

b) name = 'Yuvika'
print("\nPrinting each letter of the name:")
for letter in name:
print (letter)

c) is_palindrome = name.lower() == name [::-1].lower()
print('\nName is a palindrome' if is_palindrome else 'Name is not a palindrome')
