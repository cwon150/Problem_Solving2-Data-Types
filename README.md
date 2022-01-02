# PythonCoding_Problem_Solving2-Data-Types

Write a program that adds the digits in a 2 digit number. e.g. if the input was 35, then the output should be 3 + 5 = 8

two_digit_number = input("Type a two digit number: ")

# 🚨 Don't change the code above 👆

#Write your code below this line 👇

# Firstly, we find out the what type of the data output. By typing - print(type(two_digit_number))
# And so the result is <class 'str'> shows in console, which means the data sets will be strings output. 

digit1 = int(two_digit_number[0])

digit2 = int(two_digit_number[1])

print(digit1 + digit2)

# Alternatively we can write the following codes:

two_digit_number = input("Type a two digit number: ")

# Find out the type of output first - print(type(two_digit_number)

result = int(two_digit_number[0]) + int(two_digit_number[1])

print(result)
