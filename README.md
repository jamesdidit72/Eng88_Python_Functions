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