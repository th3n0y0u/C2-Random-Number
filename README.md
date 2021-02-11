## Random Number Generator

A function that lets the computer that picks a number within a range.

### Formula
```python
# Import the random libary

import random

# pick a number between a range

variable = random.radint(startNum, endNum)

```

startNum and endNum and inclusive, which means that the number are part of the options for the computer to chose from.

### Rule

In order to set a range, check how many options are needed, For example, a coin has 2 sides, so a coin flipper generator will have 2 options.

*Ex.*
```python

import.random

coin = random.radint(0, 1)

if(coin == 1):
  print("head")
else:
  print("tails")
```
 > heads *or* tails
