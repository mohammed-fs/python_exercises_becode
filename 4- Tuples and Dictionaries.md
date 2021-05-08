# Exercises
**1. Choose 5 movies you like and create a dictionary that associates each of these movies with its director.**</br>
```
movies = {'Inception':'Christopher Nolan',
          'The Big Lebowski':'Joel Coen',
          'Fight Club':'David Fincher',
          'The Matrix':'Lana Wachowski',
          'Interstellar':'Christopher Nolan'}
```
</br>

**2. Add an entry to the dictionary of the previous question (a new movie and its director)**</br>
`movies['Parasite'] = 'Bong Joon Ho'`

</br>

**3. How would you cut the following string at each space and put it in a list:**</br>
```
sentence = "I am the best coder in Telenet !"
str_to_list = sentence.split()
print(str_to_list)
```
</br>

**4. Transform this string Why_am_I_Mister_pink_? by removing the underscores: Why am I Mister pink ?**</br>
```
str1 = "Why_am_I_Mister_pink_"
print(str1.replace('_', ' '))
```

</br>

**6. Display only keys of this dictionary.**</br>
```
movies = {"Memories of Murder" : "Bong Joon Ho",
          "Pulp Fiction" : "Quentin Tarantino",
          "The Usual Suspects" :"Bryan Singer"}
print(movies.values())
```
</br>

**7. Replace the value of Pulp Fiction by Quentin Tarantino.**
```
movies = {"Memories of Murder" : "Bong Joon Ho", "Pulp Fiction" : "That guy!", "The Usual Suspects" :"Bryan Singer"}
movies["Pulp Fiction"] = 'Quentin Tarantino'
```

</br>

**8. Create a dictionary to build the total time with the length of each movie corresponding to the following table:**</br>
```
Memories Of Murder // 132 minutes
Pulp Fiction // 154 minutes
The Usual Suspects // 106 minutes
Interstellar // 169 minutes
Take Shelter // 120 minutes
```
```
movies_time = {'Memories Of Murder': 132,
               'Pulp Fiction': 154,
               'The Usual Suspects': 106,
               'Interstellar': 169,
               'Take Shelter': 120}
```

**9. Calculate the number of hours it takes to watch all the movies**</br>
```
movies_hours = (sum(movies_time.values())) / 60
print(movies_hours)
```
</br>

**10. Remove one of the movies from the dictionary**</br>
`del movies_time['The Usual Suspects']`
