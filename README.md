# Exam

## Whirlwind, Lists, Loops, Cond. Stmts., Functions, Modules, Dicts
### What is the difference between a list and a dictionary?
A `list` is an ordered sequence of elements. The elements can have any type, and the elements don't have to be of the same type.  
A `dictionary` is an unordered set of key-value pairs. The keys can have any hashable type, while the values don't have any type restrictions.  
The elements of a list can be accessed by their index, whereas the values of a dictionary is accessed by their key.
### How do you write a module in Python?
Python modules are `.py` files that consist of Python code. Any Python file can be referenced as a module.  
Some modules are available through the [Python Standard Library](https://docs.python.org/3/library/), while others can be installed with Python's package manager `pip`.  
You can write your own module by creating a `.py` file. In this file you can write Python code like you would do in any Python script. To use this module in another Python script, you simply just `import` it and you will be able to use the variables, funtions, and classes you have made in the module with the `.` notation.

```python
# hello.py
# Define a function
def world():
    print("Hello, World!")

# Define a variable
shark = "Sammy"

# Define a class
class Octopus:
    def __init__(self, name, color):
        self.color = color
        self.name = name

    def tell_me_about_the_octopus(self):
        print("This octopus is " + self.color + ".")
        print(self.name + " is the octopus's name.")
```

```python
# main_program.py
# Import hello module
import hello

# Call function
hello.world()

# Print variable
print(hello.shark)

# Call class
jesse = hello.Octopus("Jesse", "orange")
jesse.tell_me_about_the_octopus()
```
If you modue contains code that should only run when it is run as the main, you should encapsulate it:
```python
if __name__ == '__main__':
    #run code
```
If not it will run the code when imported.

## Files, CLI, OO, Exceptions

- How do you open a file in Python?
- How do you throw an exception in Python?

## Intro to Plotting

- How do you plot a line chart in Matplotlib?
- What is an axis in a Matplotlib plot?

## Intro to Numpy and Plotting Cntd.,

- What does it mean that an array has a shape?
- How do you plot multiple lines in Matplotlib?

## Intro to Pandas

- What is a `DataFrame`?
- How do you access a row in a `DataFrame`?

## Multiprocessing, generators and intro to Requests

- What is the difference between an iterator and a generator?
- How do you parallelise programs in Python?

## Graphs & PageRank

- What is a graph?
- Why does the PageRank algorithm exist?

## Webscraping Basics, Regular Expr. & Selenium

- What is a regular expression?
- What is Selenium?

## Feature spaces

- What is a feature?
- What is a feature vector?

## Neural Networks

- What is a neuron?
- What is an activation function?

## Image Proc. (OpenCV)

- How do you represent an image in a Numpy array?
- What is a colour space?

## Movement Detection

- What is an ‘object’?
- How does movement detection work?