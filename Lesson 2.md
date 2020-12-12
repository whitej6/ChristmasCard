# Let's Welcome Tina the Turtle!

## What is Turtle?
Turtle is a built in python library that you can use to draw things on the your screen.  For this fun hour we will be calling our turtle Tina and showing you some of the cool things Tina can do.

## How can I make Tina appear?
Let's first start by including the turtle library so we can summon Tina.
```python
import turtle
```
Okay now that we have included the code let's use it to summon Tina to our screens.  To do this we will need to use the `Turtle` class in the code we just included and let Tina know we want her to look like a turtle.
```python
import turtle

tina = turtle.Turtle()
tina.shape("turtle")
```
Now that Tina is here let's take what we learned in the first lesson and see if we can get Tina to say `Hello`.
```python
import turtle

tina = turtle.Turtle()
tina.shape("turtle")
print("Hello")
```
One thing we will notice is a small window has appeared below Tina's playground and in that window we see `Hello`.  Now let's try to see if we can get Tina to write out `Hello, my name is Tina!`.  To do this we need to give Tina some commands, her first command will be `write`.  We can think of the `write` command as similar to how we used `print` but it is going to be sent to Tina to execute.
```python
import turtle

tina = turtle.Turtle()
tina.shape("turtle")

tina.write("Hello, my name is Tina")
```
Uh oh!!! Tina is writing something so small I can't read it, let's tell Tina to use a bigger font!
```python
import turtle

tina = turtle.Turtle()
tina.shape("turtle")

tina.write("Hello, my name is Tina", font=("Arial", 10, "bold"))
```
Well I can now read what Tina wrote to me but she's standing on the first word, let's tell her to back up a little bit.
```python
import turtle

tina = turtle.Turtle()
tina.shape("turtle")

tina.write("Hello, my name is Tina", font=("Arial", 10, "bold"))
tina.back(20)
```
