What is nested list?

A nested list is a list that contains another list. It is also referred to as a multi-diminsional array. For example, a 2 dimensional array is used below:
```python
nested_list = [['blue', 'green'], ['red', 'black'], ['blue', 'white']]
print len(nested_list)
# prints 3
print nested_list[1]
# prints ['red', 'black']
print nested_list[1][0]
# prints red
```
To go through every element in this list, use a nested for loop.
```python
>>> nested_list = [['blue', 'green'], ['red', 'black'], ['blue', 'white']]
>>> for inner in nested_list:
...     for value in inner:
...         print value
... 
blue
green
red
black
blue
white
```
[problem](https://www.hackerrank.com/challenges/nested-list/problem)
[benim cozumum](https://github.com/doganaktarr/My-HackerRank-Solutions/blob/master/Python/Basic%20Data%20Types/Nested%20Lists.py)

