### N o T e S 

---

Day 1

Python data structures

* Python lists : things =[]


```py
import os
directories = os.listdir('Users/ckc')
directories.index('abcd')
directories[16]
directories('non') --> Value Error
```

### Dictionaries : 

* Keys and values 

Example : 

```py
contacts = {"name" : "chaitanya", "last name" : "chauhan"}
contacts will be printed.
# If we try to acces a key which doesn't exist, we get a key error.

We can use functions like keys() and get() to list the keys of dictionary or add any particular key to the dictionary.
If we use values(), we get the values of the key.

To add a new key, we can write
contacts["phone"]="239349238"
```

### Tuples

Tuples are like arrays enclosed inside circular () brackets.
We cannot append a new element to a tuple once it is created. It gives a Attribute error.

We can also make a set or a list using curly brackets {}. 
It shows the different values inside it once printed just like a normal set.





