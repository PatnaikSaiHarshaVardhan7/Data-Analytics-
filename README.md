## Hi 👋😊 !  all my name is Harsha Patnaik , this my learning journey of Data Analytics .My Learning Approch : "Solving Problem Statements related to Data Analytics Path" 

# Data-Analytics

Data analytics is the process of examining raw data to uncover patterns, derive insights, and make informed decisions, ultimately converting data into actionable business intelligence.

# Roadmap for Data Analytics:

<img width="850" height="1300" alt="ChatGPT Image Oct 5, 2025, 01_21_41 PM" src="https://github.com/user-attachments/assets/28b8ca32-a19a-41d2-b091-1dbe59748ccf" />

# Python Programming Language:

⮞ Python Programming Language is both compiled and interpreted , object oriented high-level programming language with dynamic sematics.

⮞ Python Programming Language was developed by "Guido Van Rossum".

## Features of Python Programming Language:

⮞ Object Oriented 

⮞ Dynamically typed 

⮞ GUI programming support

⮞ Extensible

⮞ Large Standard Library

⮞ Free and open source

⮞ Cross Platform Language

⮞ Interpreted language

⮞ Expressive language 

⮞ Easy to learn & use 

## Applications of Python Programming Language:

⮞ Data Science

⮞ Web Development

⮞ Data Engineering

⮞ Machine Learning 

⮞ Artificial Intelligence 

⮞ Data Analytics  and so on...etc 

## Note: I used Python 3.13.7 & PyCharm.

## Variables:

Variables are place holders, which can store a value.

### Ex: 

Input: a = "Hello World"

           print(a)

Output: Hello World

## Rules of Variables

⮞ Case sensitive 

⮞ No spacing

⮞ Should not start with special characters (# , @ , | ...etc)

## Data Types 

⮞ Text type : String(str)

⮞ Numeric types : Integer(int) , floating poing(float) , Complex

⮞ Sequence types : list , tuple and range 

⮞ Mapping type : Dictionaries(dict)

⮞ Set type : set , frozenset

⮞ Boolean type : bool

⮞ Binary types : bytes , bytearray , memoryview  

## User - Input

### Syntax : 
    Ex : name = input("enter your name:")

### Note : Evaluete → eval


###
     Ex : expl = eval(input("enter any equation here : ")) 

## Type Casting 

Conversion of one data type to another is called as type casting 

They are of two types : Implicit typecasting  , Explicit typecasting 

### Note : "type" is a data type it tells about the type of the data 

    Ex: Input : name = "Harsha"
                print(type(name))
        Output : <class 'str'>
        
## Implicit typecasting : Automatically converting 

## Explicit typecasting : 

    Ex: Input: a = "123"
               a = float(a)
               print(a)
        Output: 123.0

### Problem Solving 1 (Go through it)

# Operators and Operands 

    Ex :  x + y = 0
          (x , y , 0) → Operands
          (+ , =) → Operators 

# Operators in Python

1. Arithmetic Operators (+,-,*,/,//,**,%)
2. Comparision Operators (<,>,<=,=>,==,!=)
3. Logical Operators (and , or , not)
4. Assignment Operators (=,+=,-=,*=)
5. Identity Operators (is,is not)
6. Membership Operators (in , not in)
7. Bitwise Operators (AND(&),OR(|),XOR(^),LEFT SHIFT(<<),RIGHT SHIFT(>>))

### Explaination:

    // → floor division (Quotient)
    ** → exponentiation
    % → modulus (Reminder)
    and → if both the operands are true , then the output is True
    or → if either of the operands are true , then the output is True  
    not → it gives complement , True → Flase , Flase → True 

### AND 

    0 & 0 → 0
    1 & 0 → 0
    0 & 1 → 0
    1 & 1 → 1

### 
    Note : print(bin(15)) 
           Output: 0b1111

### OR

    0 | 0 → 0
    1 | 0 → 1
    0 | 1 → 1
    1 | 1 → 1

### XOR 

    0 ^ 0 → 0
    1 ^ 0 → 1
    0 ^ 1 → 1
    1 ^ 1 → 0

# Conditional Statements

1. if statement
### Syntax:
        if Condition :
                print("Statement")
        
2. if-else statement
### Syntax:
        if Condition :
                print("Statement")
        else :
               print("Statement")

3. if-elif-else statement
 ### Syntax:
        if Condition :
                print("Statement")  
        elif Condition :
                print("Statement")
        else :
               print("Statement")

4. Nested if statement
### Syntax:
        if Condition :
                print("Statement")
                     if Condition :
                             print("Statement")
        else:
             print("Statement")
   
5. Short hand if statement
 ### Syntax:
        if Condition : print("Statement") 
   
6. Short hand if-else statement
### Syntax:
        print("Statement") if Condition print("Statement")

## Loops

1. for loop
2. while loop
3. while True
4. Nested loop

### for loop
   #### Syntax:
    for i(variable) in range(n,m)
               print("Statement")
    (or)
    for i in range(n,m,l)  #Note:l=Gap
           print("Statement")

### Q. Multiplication table using for loop
    n = int(input("enter a number:"))
    i = 0
    m = int(input("enter a number upto:"))
    print(n, "table")
    for i in range(0,m):
    print(n,"x",i,"=",n*i)
    
    # Output:
    # enter a number:5
    # enter a number upto:10
    # 5 table
    # 5 x 0 = 0
    # 5 x 1 = 5
    # 5 x 2 = 10
    # 5 x 3 = 15
    # 5 x 4 = 20
    # 5 x 5 = 25
    # 5 x 6 = 30
    # 5 x 7 = 35
    # 5 x 8 = 40
    # 5 x 9 = 45

### While loop
#### Syntax:
    while Condition :
          print ("Statement")
          increament / decreament

### Q. Multiplication table using while loop
    n = int(input("enter a number:"))
    i = 0
    m = int(input("enter a number upto:"))
    print(n, "table")
    while i in range(0,m):
          print(n,"x",i,"=",n*i)
          i+=1
            
    # Output:
    # enter a number:5
    # enter a number upto:11
    # 5 table
    # 5 x 0 = 0
    # 5 x 1 = 5
    # 5 x 2 = 10
    # 5 x 3 = 15
    # 5 x 4 = 20
    # 5 x 5 = 25
    # 5 x 6 = 30
    # 5 x 7 = 35
    # 5 x 8 = 40
    # 5 x 9 = 45
    # 5 x 10 = 50

### while True 
#### Syntax:
       while True :
             print("Statement")

### Nested loop
#### Syntax:
       for loop :
                for loop :
                          print("Statement")
       print("Statement")

### Q. Print 
1

1 2

1 2 3

1 2 3 4

1 2 3 4 5

             for i in range(1,6):
             for j in range(1,i+1):
             print(j,end=" ")
             print()
    
             # Output:
             # 1 
             # 1 2 
             # 1 2 3 
             # 1 2 3 4 
             # 1 2 3 4 5 

## for loop with conditional statement 
Q. for range 1 to 100,
   commen multiples of 8 and 12,
   both using for and while individually 
   ##### for

    for i in range(1,101):
    if i % 8 == 0 :
        print(i,"is a multiple of 8")
    elif i % 12 == 0 :
        print(i,"is a multiple of 12")
    else:
        print(i)

#### Output:
![WhatsApp Image 2025-10-06 at 12 48 19_1f14d6c7](https://github.com/user-attachments/assets/6fe7ba5e-73f6-4488-875d-ca8e3be4910e)
