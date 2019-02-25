1. Which of the following are operators, and wich are values?
```python
*           # operator
'hello'     # value
-88.8       # value
-           # operator
/           # operator
+           # operator
5           # value
```
2. Which of the following is a variable, and which is a string?
```python
spam        # variable
'spam'      # string
```
3. Name three data types.
```python
# int
# string
# float
```

4. What is an expression made up of? What do all expressions do?

5. This chapter introduced assignment statements, like `spam = 10`. What is the difference between an expression and a statement?

6. What does the variable `bacon` contain after the following code runs?
```python
bacon = 20
bacon + 1

# bacon still holds the value 20
```
7. What should the following two expressions evaluate to?
```python
'spam' + 'spamspam'     # 'spamspamspam'
'spam' * 3              # 'spamspamspam'

# both return 'spamspamspam'
```
8. Why is `eggs` a valid variable name while `100` is invalid?
```python
# because the variables can't start with a number
```

9. What three functions can be used to get the integer, floating-point number, or string version of a value?
```python
# for integer:
int()

# for floating-point number:
float()

# for string:
str()
```

10. Why does this expression cause an error? How can you fix it?
```python
'I have eaten ' + 99 + ' burritos.'
# because 99 is an int and can't concatenate str with int
```

```python
# the fix is:
'I have eaten ' + str(99) + ' burritos.'
```
