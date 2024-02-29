# POO_Reto_1

## 1. A basic, simple calculator.
Something you learn how to do as a kid (if you are lucky). Give it numbers, the operator, and it'll give you the answer.

```
def basic_operation(num1, num2, operation):
    if operation == "+":
        return num1 + num2
    elif operation == "-":
        return num1 - num2
    elif operation == "*":
        return num1 * num2
    elif operation == "/":
        if num2 != 0:
            return num1 / num2
        else:
            return "Don't divide by zero!"
    else:
        return "Operation is not allowed. Please use +, -, *, or /."   
```
As you may see, the code takes two numers and one operator, and makes the correspondent operation.

## 2. Do you even know what a palindrome is? Find out here.
A palindrome is a word, phrase, etc, that will be the same whether you read it forward or backward - a real intelectual exercise, if you want to create them. This code helps you estimate if it really is a palindrome. Type the word, phrase, whatever, and it should tell you if it's exactly the same.

```
def is_palindrome(string):
    string = string.replace(" ", "").lower()
    counter = 0
    for char in range(len(string)):
        if string[char] == string[len(string) - char -1]:
                counter += 1
        else: pass
    if counter == len(string):
        return True
    else: return False
```
It takes the string, makes it understandable and then evaluates each character with its couterpart. Easier said than done.

## 3. Memorizing all the prime numbers is hard.
But they are exigent numbers which makes them easier to find. Apart from 2 and 3, any other prime number can be written with the formula "6n + 1" or "6n – 1". But don't worry, this code can save you doing such a complicate computation.

```
```

## 4. You could need this operation someday, or not.
Code that sums any consecutive pair in the array, and determines which sum is the biggest one.

```
```

## 5. I ran out of ideas, but my teacher has not.
This is about finding cousin words. Somehow.

```
```
