# AI Chatbot

Only with 5 lines of code

## 1 . You need to install prsaw

You can do it importing the module:

```python
from prsaw import RandomStuff
```

## 2 . You define the code

```python
import the module
from prsaw import RandomStuffV2

# initiate the object
rs = RandomStuffV2() 

# get a response from an endpoint
response = rs.get_ai_response("What is your name?")
print(response)

# close the object once done (recommended)
rs.close()

# Output:
My name is RSA, if you forget my name for any reason :-)
# Other possible output:
I believe you asked that before. Anyway, call me RSA.
```

## 3 . Use the input function

```python
# import the module
from prsaw import RandomStuffV2

# initiate the object
rs = RandomStuffV2() 

# get a response from an endpoint
# My input : What is your father's name?
user_input = input("> ")
response = rs.get_ai_response(user_input)
print(response)

# close the object once done (recommended)
rs.close()
```

`Output:`

```tex
As a robot, I don't really have a father. Do you love your father?
```

## Additional information

### PRSAW

It is an acronym for `Python Random Stuff API Wrapper`, as the name implies is a wrapper for the Random Stuff API.

## Reference

[prsaw](https://pypi.org/project/prsaw/)
[How to make an AI Chat Bot](https://www.youtube.com/watch?v=xKfaobGpKlQ)
