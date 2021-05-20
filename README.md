# Functions
## (DRY) the aim of functions is to "dont repeat yourself"

### First iteration
```python
def greeting(name):
    print(f'Hello {name}')
    print('Welcome to Cyber Security')


user = input('What is your name? ')
greeting(user)
```
### math functions

```python
def add(value_1, value_2):
    return value_1 + value_2


print(add(5, 5))


def subtract(value_1, value_2):
    return value_1 - value_2


print(subtract(5, 5))

def multiply(value_1, value_2):
    return value_1 * value_2


print(multiply(5, 5))


def divide(value_1, value_2):
    return value_1 / value_2


print(divide(5, 5))

```