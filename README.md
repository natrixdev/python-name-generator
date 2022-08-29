# Python names generator.

# Summary

- [Install the module names](### Requires module "names")
- [Create random names with python](
- [Create random male names](
- [Create random female names](
- [Create random male first names](
- [Create random female first names](
- [Create random last names](


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

## Create random names with python
Then to create random names just do:

```py
import names

for i in range(10):
    print(names.get_full_name())
```

## Create random male names

```py
for i in range(10):
    rand_name = names.get_full_name(gender='male')
    print(rand_name)
 ```
    
## Create random female names

```py
for i in range(10):
    rand_name = names.get_full_name(gender='female')
    print(rand_name)
```

## Create random male first names

```py
for i in range(10):
        rand_name = names.get_first_name(gender='male')
        print(rand_name)
```

## Create random female first names

```py
for i in range(10):
    rand_name = names.get_first_name(gender='female')
    print(rand_name)
```

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
