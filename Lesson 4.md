# Build a Christmas Tree!
We are going to take everything we taught Tina in the last three lessons and use what we learned to draw a Christmas Tree!!

## Start with the tree trunk
We are also going to have Tina start down and to the left a little.
```python
import turtle

tina = turtle.Turtle()
tina.shape("turtle")

tina.penup()
tina.goto(-20,-100)
tina.pensize(8)
tina.color("brown")
tina.begin_fill()
tina.fillcolor("brown")

tina.pendown()
tina.forward(40)

tina.right(90)
tina.forward(50)

tina.right(90)
tina.forward(40)

tina.right(90)
tina.forward(50)
tina.end_fill()
```
## Adding Some Foliage
We need to move Tina to the left and draw a large green equilateral triangle.
```python
import turtle

tina = turtle.Turtle()
tina.shape("turtle")

tina.penup()
tina.goto(-20,-150)
tina.color("brown")
tina.begin_fill()
tina.fillcolor("brown")

tina.pendown()
tina.forward(40)

tina.right(90)
tina.forward(50)

tina.right(90)
tina.forward(40)

tina.right(90)
tina.forward(50)
tina.end_fill()

tina.penup()
tina.goto(-50,-150)
tina.right(90)
tina.color("green")
tina.begin_fill()
tina.fillcolor("green")

tina.pendown()
tina.forward(200)
tina.left(120)
tina.forward(200)
tina.left(120)
tina.forward(200)
tina.end_fill()
```
## Time to add some decorations!
I am going to use a mix of blue and red ornaments to add to the tree.  To do this we will tell Tina to run around the tree and draw circles.
```python
import turtle

tina = turtle.Turtle()
tina.shape("turtle")

tina.penup()
tina.goto(-20,-150)
tina.color("brown")
tina.begin_fill()
tina.fillcolor("brown")

tina.pendown()
tina.forward(40)

tina.right(90)
tina.forward(50)

tina.right(90)
tina.forward(40)

tina.right(90)
tina.forward(50)
tina.end_fill()

tina.penup()
tina.goto(-100,-150)
tina.right(90)
tina.color("green")
tina.begin_fill()
tina.fillcolor("green")

tina.pendown()
tina.forward(200)
tina.left(120)
tina.forward(200)
tina.left(120)
tina.forward(200)
tina.end_fill()

tina.penup()
tina.right(190)
tina.forward(50)
tina.color("blue")
tina.begin_fill()
tina.fillcolor("blue")
tina.circle(10)
tina.end_fill()

tina.penup()
tina.forward(100)
tina.begin_fill()
tina.circle(15)
tina.end_fill()

tina.penup()
tina.right(120)
tina.forward(100)
tina.begin_fill()
tina.circle(10)
tina.end_fill()

tina.penup()
tina.right(110)
tina.forward(60)
tina.color("red")
tina.begin_fill()
tina.fillcolor("red")
tina.circle(10)
tina.end_fill()

tina.penup()
tina.right(110)
tina.forward(60)
tina.begin_fill()
tina.circle(10)
tina.end_fill()

tina.penup()
tina.right(110)
tina.forward(75)
tina.begin_fill()
tina.circle(20)
tina.end_fill()

tina.penup()
tina.right(180)
tina.forward(30)
tina.begin_fill()
tina.circle(10)
tina.end_fill()
```
## Let's finish it off with a greeting
Now let's send Tina to the top of the screen to wish everyone a Merry Christmas
```python
import turtle

tina = turtle.Turtle()
tina.shape("turtle")

tina.penup()
tina.goto(-20,-150)
tina.color("brown")
tina.begin_fill()
tina.fillcolor("brown")

tina.pendown()
tina.forward(40)

tina.right(90)
tina.forward(50)

tina.right(90)
tina.forward(40)

tina.right(90)
tina.forward(50)
tina.end_fill()

tina.penup()
tina.goto(-100,-150)
tina.right(90)
tina.color("green")
tina.begin_fill()
tina.fillcolor("green")

tina.pendown()
tina.forward(200)
tina.left(120)
tina.forward(200)
tina.left(120)
tina.forward(200)
tina.end_fill()

tina.penup()
tina.right(190)
tina.forward(50)
tina.color("blue")
tina.begin_fill()
tina.fillcolor("blue")
tina.circle(10)
tina.end_fill()

tina.penup()
tina.forward(100)
tina.begin_fill()
tina.circle(15)
tina.end_fill()

tina.penup()
tina.right(120)
tina.forward(100)
tina.begin_fill()
tina.circle(10)
tina.end_fill()

tina.penup()
tina.right(110)
tina.forward(60)
tina.color("red")
tina.begin_fill()
tina.fillcolor("red")
tina.circle(10)
tina.end_fill()

tina.penup()
tina.right(110)
tina.forward(60)
tina.begin_fill()
tina.circle(10)
tina.end_fill()

tina.penup()
tina.right(110)
tina.forward(75)
tina.begin_fill()
tina.circle(20)
tina.end_fill()

tina.penup()
tina.right(180)
tina.forward(30)
tina.begin_fill()
tina.circle(10)
tina.end_fill()

tina.penup()
tina.goto(0,100)
tina.color("black")
tina.write("Merry Christmas", align="center", font=("Arial", 30, "bold"))
tina.hideturtle()
```