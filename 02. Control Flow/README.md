# **🚦 Control Flow 🔄**

The control flow in Python determines the order in which statements are executed based on specific conditions. It allow us to make decisions and control the flow of your program. Let's explore the control flow constructs, starting from the basics and progressing to more advanced concepts! 🐍🔍

## **If-Else Statements 🌐❓**

The if-else statement is a fundamental control flow construct. It enable us to execute different blocks of code based on a condition. If the condition is true, the code inside the if block is executed. Otherwise, the code inside the else block is executed. Use it when we have binary conditions to handle. ✅❌

```
age = 20

if age >= 18:
    print("You are an adult.")
else:
    print("You are not an adult.")
```

## **Loops 🔄🔁**

Loops are used to repeatedly execute a block of code until a condition is met. Python provides two main types of loops: 

* **the for loop** and 
* **the while loop**.

The **for loop** is useful when we want to iterate over a sequence, such as a list, tuple, or string. It executes the block of code for each item in the sequence.

```
fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(fruit)
```

The **while loop** executes a block of code as long as a specified condition is true. It is useful when the number of iterations is not known in advance.

```
count = 0

while count < 5:
    print("Count:", count)
    count += 1
```

## **Conditional Loops and Control Statements 🔄🛑**

Python also provides conditional loops and control statements, such as break, continue, and pass. These statements enhance the control flow of our program.

The **break** statement allow us to exit a loop prematurely, even if the loop condition is still true.

```
fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    if fruit == "banana":
        break
    print(fruit)
```

The **continue** statement allows you to skip the rest of the current iteration and proceed to the next iteration of the loop.

```
fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    if fruit == "banana":
        continue
    print(fruit)
```

The **pass** statement is used as a placeholder when you want an empty block of code.

```
if True:
    pass
```

## **Nested Control Flow 🔄🔢**

We can nest control flow constructs within each other to create complex decision-making scenarios.

```
num = 10

if num > 0:
    if num % 2 == 0:
        print("Number is positive and even.")
    else:
        print("Number is positive and odd.")
elif num < 0:
    print("Number is negative.")
else:
    print("Number is zero.")
```

These are the basics of control flow in Python. Understanding and mastering these concepts will enable you to create more powerful and efficient programs. Happy coding! 💻🎉