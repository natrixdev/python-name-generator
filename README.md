# Python names generator.

# Summary

- [Install the module names](https://github.com/natrixdev/python-name-generator#1)
- [Create random names with python](https://github.com/natrixdev/python-name-generator#2)
- [Create random male names](https://github.com/natrixdev/python-name-generator#3)
- [Create random female names](https://github.com/natrixdev/python-name-generator#4)
- [Create random male first names](https://github.com/natrixdev/python-name-generator#5)
- [Create random female first names](https://github.com/natrixdev/python-name-generator#6)
- [Create random last names](https://github.com/natrixdev/python-name-generator#7)

# 1
### Requires module "names"
`pip install names`

### Supported By Names Module :

| Male Names                               | Female Names                             |
| ---------------------------------------- | ---------------------------------------- |
| Create random male names                 | Create random female names               |
|Create random male first names            | Create random female first names         |


| Neutral Names | 
|---------------|
|Create random last names|
|Create random names|

# Usages:

# 2

## Create random names with python
Then to create random names just do:

```py
import names

for i in range(10):
    print(names.get_full_name())
```

## Create random male names

# 3

```py
for i in range(10):
    rand_name = names.get_full_name(gender='male')
    print(rand_name)
 ```
    
## Create random female names

# 4

```py
for i in range(10):
    rand_name = names.get_full_name(gender='female')
    print(rand_name)
```

## Create random male first names

# 5

```py
for i in range(10):
        rand_name = names.get_first_name(gender='male')
        print(rand_name)
```

## Create random female first names

# 6

```py
for i in range(10):
    rand_name = names.get_first_name(gender='female')
    print(rand_name)
```

# 7

## Create random last names

```py 
for i in range(10):
    rand_name = names.get_last_name()
    print(rand_name)
 ```


# Made by [natrix](https://github.com/natrixdev)

### Support Us Please

| Star                                     | Fork                                     |
| ---------------------------------------- | ---------------------------------------- |
| ![Star](https://i.imgur.com/41nhvJ1.png) | ![Fork](https://i.imgur.com/MOtHDPV.png) |
