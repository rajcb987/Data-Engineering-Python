## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

Answer: It is called high level programming languaue as it is easier to understand and the typed codes can be understood by human easily,  it is then converted to low level languaue using interpreter or compiler so that machine can undertand it.


Q2. Why is Python called a dynamically typed language?

Answer: It is called dynamically typed languaues we do not need to define the data type of the variable, it is decided at the runtime.


Q3. List some pros and cons of Python programming language?

Answer:
Pros of Python Languaue:

It has large libraries
It is easy to learn and understand
It is Highly scallable
It is hihgly in demand

Cons of Python Languaue:

It is slower in compilation in comparison with java and C++
It uses more memory


Q4. In what all domains can we use Python?

Python can be used in many domains such as game development, IOT, Machine Learning, Artificial Intelligance, Data Analytics etc.


Q5. What are variable and how can we declare them?

Answer: Variables can be called as identifiers, it is a name given to a specific memory location.
Ex of declaration of variable:

int_var = 5
str_var = "This is Raj's pen"
float_var = 2.5
bool_var = True


Q6. How can we take an input from the user in Python?

Answer: Using input() function


Q7. What is the default datatype of the value that has been taken as an input using input() function?

Answer:  string

Q8. What is type casting?

Answer: Externally changing the datatype of any variable is called as type casting.


Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

Answer: We can but with the help of another function "split()".
Ex:	a,b = input("Enter two no.s: ").split()

Q10. What are keywords?

Answer: Keywords are the predefined words in any programming languaue, also it can not be used as a variable.
Ex: if,elif,else, True, False, None

Q11. Can we use keywords as a variable? Support your answer with reason.

Answer: No, we can't. As it is already defined in the system to do some specific task.

Q12. What is indentation? What's the use of indentation in Python?

Answer: Indentation are the spaces in python. Indentation is used to denote the block of code in python.

Q13. How can we throw some output in Python?

Answer: Using print() function.

Q14. What are operators in Python?

Answer:
Operators are used to perform operations on variables and values.
Types:

Arithmetic operators
Assignment operators
Comparison operators
Logical operators

Q15. What is difference between / and // operators?

Answer:

Using '/' for division will give float value as an output and using '//' for division will give you integer value.

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```

Answer: 

Str_var = 'iNeuron'
print(Str_var*3)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

Answer:

a = input("Enter a no: ")

if (int(a) % 2) == 0:
    print(a, "is an even number")
else:
    print(a, "is an Odd number")


Q18. What are boolean operator?

Answer: These are the logical operators in python returning either True or False. Ex: and, or and not

Q19. What will the output of the following?
```
1 or 0

0 and 0

True and False and True

1 or 0 or 0
```

Answer:

1 or 0 : 1

0 and 0 : 0

True and False and True : False

1 or 0 or 0 : 1

Q20. What are conditional statements in Python?

Answer:if, elif, else, nested if- else

Q21. What is use of 'if', 'elif' and 'else' keywords?

if is used to apply the condition, elif can be used for nested if-else, and else can be used to concluded the condition.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

Answer:
age = input("Enter your age: ")

if int(age) >= 18:
    print("I can vote")
else:
    print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Answer:

numbers = [12, 75, 150, 180, 145, 525, 50]

even_sum = 0
for x in numbers:
    if (x % 2) == 0:
        even_sum += x
print(even_sum)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

Answer:
a,b,c = input('Enter 3 no.s: ').split()
x = 0
if a > b:
    x = a
else:
    x = b
if x > c:
    print('Greatest no is: ', x)
else:
    print('Greatest no is: ', c)

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

Answer:

numbers = [12, 75, 150, 180, 145, 525, 50]

for i in numbers:

    if i > 500:
        break
    elif i < 150 and (i%5) == 0:

        print(i)