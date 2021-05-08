# Exercises
**1. Display all employee in the employees list.**</br>
```
employees = ["Merouane", "Koen", "Jonas", "Hendrik", "Sophie", "Ferdi", "Ignace", "Axel", "Jeroen", "Adrien"]
for employee in employees:
    print(employee)
```
**2. Display only those whose first name begins with the letter J**
```
letter = 'J'
for x in employees:
    if x[0] == letter:
        print(x)
# for multiple letter using list
letter2 = ['M', 'S', 'A']
for x in employees:
    if x[0] in letter2:
        print(x)
```
**3. Display integers from 0 to 23 not included, using a for loop and the range() instruction.**
```
for a in range(23):
    print(a)
```
**4. Use the break instruction to interrupt a for loop to display integers from 1 to 10 included, when the loop variable is 7**
```
a = 1
for a in range(1,11):
    print(a)
    if a == 7:
        break
```

**6. Follow the instructions :**</br>
`list_of_num = [23, 18, 64, 35, 92]`
  * sort and display the list</br>
`print(sorted(list_of_num))`

  * add item 43 to the list and display the list</br>
```
list_of_num.append(43)
print(list_of_num)
```

* reverse and display the list</br>
```
list_of_num.reverse()
print(list_of_num)
```

* display the index of element 35</br>
`print(list_of_num.index(35))`</br>

* remove item 35 and display the list</br>
```
list_of_num.remove(35)
print(list_of_num)
```
* display the sub-list of the 2nd to 3rd element</br>
`print(list_of_num[1:3])`</br>

* display the sub-list from the beginning to the 2nd element</br>
`print(list_of_num[:2])`</br>

* display the sub-list of the 3rd element at the end of the list</br>
`print(list_of_num[-3])`</br>

* display the last element using a negative indication.</br>
`print(list_of_num[-1])`</br>

**7.a Write an algorithm that asks the user to enter a number.**</br>
Then make sure that your program displays all the numbers up to the number, for example, if the user enters the number 3, then your program will display something like this: 0,1,2,3</br>
```
num = int(input("Enter a number: "))
for x in range(num):
    print(x)
```
**7.b Now make sure that your program displays all the numbers down to 0**</br>
for the same example, your program will display something like this: 3,2,1,0</br>
```
num = int(input("Enter a number: "))
for x in reversed(range(10)):
    print(x)
```
**8.The price is right ! Create a variable that will contain the number to be found.**
Then create an algorithm that will ask the user to find this price. If the user enters a number that is too high, he will have the sentence: It’s less. If he enters a number that is too low, he will have the sentence: It’s more. If the user finds the right price he will have the sentence: Well done, you won.

```
num = 13
user_num = int(input('Enter a number: '))
if user_num < num:
    print("It's more")
elif user_num > num:
    print("It's less")
elif user_num == num:
    print("Well done, you won")
```
