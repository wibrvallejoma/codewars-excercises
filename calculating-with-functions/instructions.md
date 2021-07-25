# Calculating with Functions

Excercises provided by [CodeWars](https://www.codewars.com/)

> First of all the instructions of the excercise.

## Instructions
This time we want to write calculations using functions and get the results. Let's have a look at some examples:

```python
seven(times(five())) # must return 35
four(plus(nine())) # must return 13
eight(minus(three())) # must return 5
six(divided_by(two())) # must return 3
```

**Requirements:**
- There must be a function for each number from 0 ("zero") to 9 ("nine")
- There must be a function for each of the following mathematical operations: plus, minus, times, dividedBy (`divided_by` in Ruby and Python)
- Each calculation consist of exactly one operation and two numbers
- The most outer function represents the left operand, the most inner function represents the right operand
- Division should be integer division. For example, this should return `2`, not `2.666666...`:

```python
eight(divided_by(three()))
```

## Test Cases
```python
test.describe('Basic Tests')
test.assert_equals(seven(times(five())), 35)
test.assert_equals(four(plus(nine())), 13)
test.assert_equals(eight(minus(three())), 5)
test.assert_equals(six(divided_by(two())), 3)
```

## Additional info
If you want to know how I solve this problem please open the `ideas.md` file.

Thank you
-W.
