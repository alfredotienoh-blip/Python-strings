# Python-strings
## Strings are arrays. Python doesn't have character data types. A single character is simply a string with a length of 1.
## Square brackets can be used to access elements of the string.
## Get the character at position 1 (remember that the first character has the position 0):
a = "Hello, World!"
print(a[1])

# Looping through a string
## Since strings are arrays, we can loop through the characters in a string, with a for loop.
for x in "banana":
    print(x)

# Length of a string
## To get the length of a string, use the len() function.
a = "Hello, World!"
print(len(a))

# Check string
## To check if a certain phrase or character is present in a string, we can use the keyword in.
txt = "The best things in life are free!"
if "free" in txt:
    print("Yes, 'free' is present.")

## Use check string in an if statement
txt = "The best things in life are free!"
if "expensive" not in txt:
    print("No, 'expensive' is NOT present.")

# Slicing strings
## You can return a range of characters by using the slice syntax.
## Specify the start index and the end index, separated by a colon, to return a part of the string.
b = "Hello, World!"
print(b[2:5])

# Slice from the start
## By leaving out the start index, the range will start at the first character:
b = "Hello, World!"
print(b[:5])

# Slice to the end
## By leaving out the end index, the range will go to the end of the string:
b = "Hello, World!"
print(b[2:])

# Negative indexing
## Use negative indexes to start the slice from the end of the string:
b = "Hello, World!"
print(b[-5:-2])

# Modify strings
## Python has a set of built-in methods that you can use on strings.
## Upper case
a = "Hello, World!"
print(a.upper())

## Lower case
a = "Hello, World!"
print(a.lower())

## Lower case
a = "Hello, World!"
print(a.lower())

## Replacing a string
## The replace() method replaces a string with another string.
a = "Hello, World!"
print(a.replace("H", "J"))

