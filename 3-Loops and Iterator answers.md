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
