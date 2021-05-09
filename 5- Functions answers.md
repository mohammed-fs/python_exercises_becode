# Exercises
**1. Say Hello**</br>
Write a function called greetings(name) that returns a string of characters. This function will take as argument a variable name. This function will return a string `Hello name`.</br>
```
def greetings(name):
    print("Hello " + name)
greetings('Linus')
```
</br>

**2. Count employees**</br>
Create a function `sum_of_employees()` that calculates and returns the number of students in a list. The function will have to return an integer.</br>
```
## method 1
list1 = ['student1', 'student2', 'student3']
def sum_of_employees(list):
    count = 0
    for element in list:
        count += 1
    return count
print('The number of the student is ', sum_of_employees(list1))

## method 2
def sum_of_employees():
    return len(list1)
print(sum_of_employees())

## method 3
def sum_of_employees():
    print(len(list1))
sum_of_employees()
## Not sure if this answer the question.
```
</br>

**3. Is divisible ?**</br>
Create a function is_divisible(n, x, y) that checks if a number n is divisible by two numbers x AND y. All inputs are positive, non-zero digits.</br>

Example:</br>
```
is_divisible(3,1,3)--> True because 3 is divisible by 1 and 3
is_divisible(12,2,6)--> True because 12 is divisible by 2 and 6
is_divisible(100,5,3)--> False because 100 is not divisible by 3
is_divisible(12,7,5)--> False because 12 is neither divisible by 7 nor 5
```
