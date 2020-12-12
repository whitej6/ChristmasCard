# Let's Have Tina Draw Some Shapes!

Let start by seeing if we can get Tina to draw a line.  We first need to tell Tina to use her pen with the `pendown` function, then we can have her move with the pend down to draw a line.
```python
import turtle

tina = turtle.Turtle()
tina.shape("turtle")

tina.pendown()
tina.forward(100)
```
Now that we have a simple line let's add some color to the line and make the line a little thicker.
```python
import turtle

tina = turtle.Turtle()
tina.shape("turtle")

tina.pensize(8)
tina.color("green")

tina.pendown()
tina.forward(100)
```
Cool! Tina is now green and is drawing a thicker line.  Next we can tell Tina to turn right 90 degrees and continue walking forward.
```python
import turtle

tina = turtle.Turtle()
tina.shape("turtle")

tina.pensize(8)
tina.color("green")

tina.pendown()
tina.forward(100)

tina.right(90)
tina.forward(100)
```
Perfect!! Let have Tina make two more right turns and complete the square.
```python
import turtle

tina = turtle.Turtle()
tina.shape("turtle")

tina.pensize(8)
tina.color("green")

tina.pendown()
tina.forward(100)

tina.right(90)
tina.forward(100)

tina.right(90)
tina.forward(100)

tina.right(90)
tina.forward(100)
```
Tina! Great job on drawing a square, now let's fill in the square with green. To this we will need to tell Tina to `being_fill` the `fillcolor` and when to `end_fill`.
```python
import turtle

tina = turtle.Turtle()
tina.shape("turtle")

tina.pensize(8)
tina.color("green")
tina.begin_fill()
tina.fillcolor("green")

tina.pendown()
tina.forward(100)

tina.right(90)
tina.forward(100)

tina.right(90)
tina.forward(100)

tina.right(90)
tina.forward(100)
tina.end_fill()
```
Now that Tina has created a squared let's draw some ribbon on the square to make sure it does not come unwrapped. We will change Tina's color and we want to make sure Tina isn't scribbling with the new color so we will teach her a new command `penup`
```python
import turtle

tina = turtle.Turtle()
tina.shape("turtle")

tina.pensize(8)
tina.color("green")
tina.begin_fill()
tina.fillcolor("green")

tina.pendown()
tina.forward(100)

tina.right(90)
tina.forward(100)

tina.right(90)
tina.forward(100)

tina.right(90)
tina.forward(100)
tina.end_fill()

tina.penup()
tina.right(90)
tina.forward(50)
tina.right(90)
tina.color("red")

tina.pendown()
tina.forward(100)
tina.penup()

tina.right(90)
tina.forward(50)
tina.right(90)
tina.forward(50)
tina.right(90)

tina.pendown()
tina.forward(100)
tina.penup()
```
Let's have Tina start more to the left so we have more room to work with and let's add a blue equilateral triangle to the drawing.
```python
import turtle

tina = turtle.Turtle()
tina.shape("turtle")
tina.speed(100)

# Here is where we tell Tina to move to the left
tina.penup()
tina.goto(-180, 0)

tina.pensize(8)
tina.color("green")
tina.begin_fill()
tina.fillcolor("green")

tina.pendown()
tina.forward(100)

tina.right(90)
tina.forward(100)

tina.right(90)
tina.forward(100)

tina.right(90)
tina.forward(100)
tina.end_fill()

tina.penup()
tina.right(90)
tina.forward(50)
tina.right(90)
tina.color("red")

tina.pendown()
tina.forward(100)
tina.penup()

tina.right(90)
tina.forward(50)
tina.right(90)
tina.forward(50)
tina.right(90)

tina.pendown()
tina.forward(100)
tina.penup()

tina.forward(30)
tina.color("blue")
tina.fillcolor("blue")

tina.begin_fill()
tina.pendown()
tina.forward(100)
tina.left(120)
tina.forward(100)
tina.left(120)
tina.forward(100)
tina.end_fill()
```
Lastly let's teach Tina to draw a circle, luckily she knows the `circle` command.
```python
import turtle

tina = turtle.Turtle()
tina.shape("turtle")
tina.speed(100)

# Here is where we tell Tina to move to the left
tina.penup()
tina.goto(-180, 0)

tina.pensize(8)
tina.color("green")
tina.begin_fill()
tina.fillcolor("green")

tina.pendown()
tina.forward(100)

tina.right(90)
tina.forward(100)

tina.right(90)
tina.forward(100)

tina.right(90)
tina.forward(100)
tina.end_fill()

tina.penup()
tina.right(90)
tina.forward(50)
tina.right(90)
tina.color("red")

tina.pendown()
tina.forward(100)
tina.penup()

tina.right(90)
tina.forward(50)
tina.right(90)
tina.forward(50)
tina.right(90)

tina.pendown()
tina.forward(100)
tina.penup()

tina.forward(30)
tina.right(90)
tina.forward(50)
tina.left(90)
tina.color("blue")
tina.fillcolor("blue")

tina.begin_fill()
tina.pendown()
tina.forward(100)
tina.left(120)
tina.forward(100)
tina.left(120)
tina.forward(100)
tina.end_fill()

tina.penup()
tina.left(120)
tina.forward(180)
tina.color("orange")
tina.fillcolor("orange")

tina.begin_fill()
tina.pendown()
tina.circle(50)
tina.end_fill()
```

