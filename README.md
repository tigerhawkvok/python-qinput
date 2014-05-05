python-qinput
=============

Easy Python 2 and 3 input/getch wrapper

## Why
Because I got tired of writing try/catch every single time I wanted to get a bit of user input!

## Usage

```python
import qinput
string = qinput.input("Question here")
# The response is stored in string
truthval = qinput.yn("Yes no question here")
# [Y/N] is appended to the user prompt, and the boolean value is stored truthval
```
