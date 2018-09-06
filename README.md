
## Here's a simple list:


```python
cats = ['Maine Coon', 'Tabby', 'Siamese', 'Garfield', 'Sylvester']
```


```python
cats
```




    ['Maine Coon', 'Tabby', 'Siamese', 'Garfield', 'Sylvester']



## Iterate through the list and print each cat.


```python
# Your code here
```

## Create a new list cat_jrs by appending ‘Jr.’ to each of the cats names.


```python
# Your code here
```

## Sort the list in alphabetical order.


```python
# Your code here
```

# Sort the list in reverse alphabetical order


```python
# Your code here
```

## Look up a new string or list method and explain how it works.


```python
# Your code here
```

# Extension: Sort the list by the 3rd letter of each name.
Hint: look at the docstring's optional parameter, `key=`.   
You can then define a special function called a *lambda function* on the fly like this:  
`lambda thing: thing*-1` or `lambda x: operation(x)`

Like a for loop you can create any variable name after calling `lambda`.  
After calling lambda and a variable name, you then always use a colon `:`.  
To the right of the colon is whatever you want your function to do with your variable.

More completely:


```python
numbers = [5,3,7,82, 17]
numbers.sort()
numbers
```




    [3, 5, 7, 17, 82]




```python
numbers.sort(key=lambda x: x*-1) #Effectively sorts in descending order by taking the inverse
numbers
```




    [82, 17, 7, 5, 3]




```python
numbers.sort(key=lambda num: abs(11-num)) #Try to explain what this does.
numbers
```




    [7, 17, 5, 3, 82]




```python
# Your code here
```
