---
title: "Know Your Boundaries, Turtle"
weight: 4
chapter: false
---

Currently with our turtle game you can move your player turtle off the screen which we don’t want to do so in this exercise we are going to draw a border and then set boundaries so your turtle can not move off the screen.

>**Step 1.** Use Save As to save your module as `kbgame3`

>**Step 2.** Move to the top of your code just under the \#Set up Screen section and the `wn.bgcolor('Navy')` line. Create a new turtle element called `#Draw border` by typing:

```python {title="python"}
wn.bgcolor('Navy')

# Draw border
mypen = turtle.Turtle()
mypen.penup()
mypen.setposition(-300,-300)
mypen.pendown()
mypen.pensize(3)
mypen.color('white')
for side in range(4):
    mypen.forward(600)
    mypen.left(90)
mypen.hideturtle()

# Create player turtle
```

`setposition` places the mypen turtle in the bottom left hand corner of your screen 

`pendown` gets your mypen turtle ready to draw, and the `for side in range (4):` tells your mypen turtle to draw four sides using a simple loop of draw forward for 600 points then turn left and repeat four times.

>**Step 3.** Save and Run your module.  

Notice how a turtle 'draws' the borders when the module loads? If you would like to get straight to the turtle-ly action try setting `mypen.speed(0)` after setting `mypen.color('...')`

{{% notice note %}}

While there is now a border your player turtle can still go off screen, this is because we have not set boundaries yet.

{{% /notice %}}

Now we have to do something called boundary checking, what this will do is check the location of our turtle and if the left is lower than -290 and on the right it is greater than +290 we have hit either the left or right borders \(x Axis\) and if the top is greater than +290 and bottom lower than -290 we have hit either the top or bottom borders \(y Axis\). We then simply choose what we want to happen when this occurs - for this game we are going to bounce off the border wall at 180 degrees.

>**Step 4.** As we need this to happen every time during the game we need the code to be written within the while True loop under the line `player.forward\(speed\)`:

```python {title="python"}
while True:
    player.forward(speed)

    # Boundary Player Checking x coordinate
    if player.xcor() > 290 or player.xcor() < -290:
        player.right(180)

    # Boundary Player Checking y coordinate
    if player.ycor() > 290 or player.ycor() < -290:
        player.right(180)
```

{{% notice note %}}

**Note:** We have set the boundary at 290 and -290 so that the turtle bounces when the front of the turtle hits the boundary and not the middle. Before moving on, check your indenting and make sure it looks like above, for the while loop to work all the code needs to be indented.

{{% /notice %}}

>**Step 5.** Save and then Run your module.

{{% notice style="info" title="Challenge!" icon="lightbulb" %}}

Again before moving to the next section you can edit your code to make changes such as changing the angle your turtle bounces at or making the border wall thicker or thinner or adding a colour.

{{% /notice %}}

Your code should now look like this:

```python {title="python"}
#Turtle Graphics Game
import turtle


#Set up screen
turtle.setup(650,650)
wn = turtle.Screen()
wn.bgcolor("Navy")

#Draw border
mypen = turtle.Turtle()
mypen.penup()
mypen.setposition(-300,-300)
mypen.pendown()
mypen.pensize(3)
for side in range(4):
    mypen.forward(600)
    mypen.left(90)
mypen.hideturtle()

#Create player turtle
player = turtle.Turtle()
player.color("darkorange")
player.shape("turtle")
player.penup()
player.speed(0) 

#Set speed variable
speed = 1

#Define  functions

def turn_left():
    player.left(30)

def turn_right():
    player.right(30)

def increase_speed():
    global speed
    speed += 1

#Set keyboard bindings
turtle.listen()
turtle.onkey(turn_left, "Left")
turtle.onkey(turn_right, "Right")
turtle.onkey(increase_speed, "Up") 


while True:
    
    player.forward(speed)

    #Boundary Checking x cordinate
    if player.xcor() > 290 or player.xcor() <-290:
        player.right(180)
    #Boundary Checking y cordinate
    if player.ycor() > 290 or player.ycor() <-290:
        player.right(180)

```

{{% notice style="tip" title="Time to celebrate" %}}

**Congratulations Module 3 Completed**

{{% /notice %}}
