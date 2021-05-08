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
