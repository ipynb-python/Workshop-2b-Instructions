
# Python Exercises: Lists & Loops

These exercises are designed to help you practice working with lists and loops in Python.

---

## TASKS


### Part 1: Accessing Elements

Create a new code file called `workshop2b_part1.py`

Start the file with the following lines of code:

```python
print("Part 1:")
letters = ['a', 'b', 'c', 'D', 'x', 'f', 'g', 'y' ]
```

**i.** Use `print(letters)` to display the full list.

**ii.** Access and print the first element of the list. 

**iii.** Access and print the third element of the list.

**iv.** Access and print the last element of the list using negative indexing.



Run the file and check the code output, it should be:

```
Part 1:
['a', 'b', 'c', 'D', 'x', 'f', 'g', 'y']
a
c
y
```


***

### Part 2: Modifying, Adding & Removing Elements

Create a new code file called `workshop2b_part2.py`

Start the file with the following lines of code:

```python
print("Part 2:")
letters = ['a', 'b', 'c', 'D', 'x', 'f', 'g', 'y' ]
```

Now add code lines to do the following. 

**i.** Change the letter `'D'` at index `3` to a lowercase `'d'`. Print the list to see the change.

**ii.** Insert the letter `'z'` at the beginning of the list (index `0`). Print the list.

**iii.** Use the `pop()` method to remove the last letter from the list. Print the popped letter.

**iv.** Print the modified list after the pop operation.

**v.** Add the letter `'h'` to the very end of the list. Print the list.

**vi.** Use the `.index()` method to locate the element `'x'` and store its index in a variable `idx`. Print the value of `idx`.

**vii.** Use the `del` statement and the `idx` variable to remove `'x'`. Print the modified list.

**viii.** Use the `remove()` method to find and remove the letter `'z'`. Print the final list.

Run the file and check the code output, it should be:

```
Part 2:
['a', 'b', 'c', 'd', 'x', 'f', 'g', 'y']
['z', 'a', 'b', 'c', 'd', 'x', 'f', 'g', 'y']
y
['z', 'a', 'b', 'c', 'd', 'x', 'f', 'g']
['z', 'a', 'b', 'c', 'd', 'x', 'f', 'g', 'h']
5
['z', 'a', 'b', 'c', 'd', 'f', 'g', 'h']
['a', 'b', 'c', 'd', 'f', 'g', 'h']
```

***

### Part 3: Organizing a List

Create a new code file called `workshop2b_part3.py`

Start the file with the following lines of code:

```python
print("Part 3:")
letters = ['f', 'g', 'd', 'c', 'e', 'a', 'b']
```

**i.** Print the total number of items (the length) in the `letters` list.

**ii.** Use the `reverse()` method to permanently reverse the list. Print the list to confirm the new order.

**iii.** Use the `sorted()` function to print the list in alphabetical order *without* changing the original list.

**iv.** Print the `letters` list again to show it was not changed.

**v.** Use the `sort()` method with `reverse=True` to permanently sort the list in reverse-alphabetical order. Print the list.

Run the file and check the code output, it should be:

```
Part 3:
7
['b', 'a', 'e', 'c', 'd', 'g', 'f']
['a', 'b', 'c', 'd', 'e', 'f', 'g']
['b', 'a', 'e', 'c', 'd', 'g', 'f']
['g', 'f', 'e', 'd', 'c', 'b', 'a']
```

***

### Part 4: Slicing

Create a new code file called `workshop2b_part4.py`

Start the file with the following lines of code:

```python
print("Part 4:")
letters = ['a', 'b', 'c', 'd', 'e', 'f', 'g']
```
**i.** Create a slice that contains the first four letters of the list (`['a', 'b', 'c', 'd']`). Print it.

**ii.** Create a slice that contains the letters `'d'`, `'e'`, and `'f'`. Print it.

**iii.** Make a copy of the entire `letters` list using a slice. Print the copy.

Run the file and check the code output, it should be:

```
Part 4:
['a', 'b', 'c', 'd']
['d', 'e', 'f']
['a', 'b', 'c', 'd', 'e', 'f', 'g']
```

***

### Part 5: Looping

*This section uses some code to run loops you may not have seen before (e.g. the `enumerate` function).*

*Check the cheat sheet to see an example on how to use it.*

Create a new code file called `workshop2b_part5.py`

Start the file with the following line of code:

```python
print("Part 5:")
```

**i.** Create a list called `list_one` containing `['h', 'i', 'j', 'k', 'l']`. 

Use a `for` loop and `range()` to loop over and print the first four items from `list_one`.

**ii.** Create a list called `list_two` containing `['m', 'n', 'o']`. 

Use a `for` loop with the `in` keyword to loop over and print all the items in `list_two`.

**iii.** Create a list called `list_three` containing `['p', 'q', 'r', 's']`. 

Use `enumerate()` in a `for` loop to print the index and the letter in this format: `0: p`.

Run the file and check the code output, it should be:

```
Part 5:
h
i
j
k
m
n
o
0: p
1: q
2: r
3: s
```

    
