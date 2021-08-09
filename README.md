# lab03starter
Starter Code for Lab03

#Step 1.1

#def draw_picture(the_turtle):
  #This will make the turtle draw the bottom of the box and turn North
  #the_turtle.forward(100)
  #the_turtle.left(90)
  #This will make the turtle draw the right side of the box and turn West
  #the_turtle.forward(100)
  #the_turtle.left(90)
  #This will make the turtle draw the top of the box and turn South
  #the_turtle.forward(100)
  #the_turtle.left(90)
  #This will make the turtle draw the left side of the box, closing it
  #the_turtle.forward(100)
  #the_turtle.left(90)    
#my_turtle = turtle.Turtle() 
#draw_picture(my_turtle)     

#Role of numbers: (left or right) a number of degrees, which changes direction
#Role of numbers: (forward or backward) a number of units moved
#The unit used is pixels

#The turtle, the one that drew the square, still drew the square
#Turtle 1 drew a diagonal to (-50, -50) then moved forward 100 units
#Turtle 2 drew a diagnol to (200, 100), turned left 90 degrees, and went up 100 units


#Step 1.2 Zoe
#def draw_z(the_turtle):
  #I want to make the turtle to make 1/2 the diagnol of my Z then the top horizontal line
  #the_turtle.left(45)
  #the_turtle.forward(100)
  #the_turtle.left(135)
  #the_turtle.forward(100)
  #I want the turtle to go back to the middle, without drawing to then draw the middle line of the Z
  #the_turtle.penup()
  #the_turtle.goto(0,0)
  #the_turtle.pendown()
  #the_turtle.forward(45)
  #the_turtle.backward(90)
  #Going back to the middle one last time I want the turtle to finish the second half of the Z diagnol and horizontal line
  #the_turtle.penup()
  #the_turtle.goto(0,0)
  #the_turtle.pendown()
  #the_turtle.left(45)
  #the_turtle.forward(100)
  #the_turtle.left(135)
  #the_turtle.forward(100)
#my_turtle = turtle.Turtle() 
#draw_z(my_turtle)

#Step 1.2 Rena
#import turtle 
  #imports the turtle function
#my_turtle = turtle.Turtle()
  #turtle named my_turtle is created
#def draw_picture(my_turtle):
   #I created a function so that we I call on it, it will draw out the letter R
  #my_turtle.right(90)
   #I started by turning right 90 degrees so that the turetl points down, getting ready to draw a vertical line
  #my_turtle.forward(100)
  #my_turtle.right(180)
  #my_turtle.forward (100)
  #my_turtle.right(90)
  #my_turtle.forward(50)
  #my_turtle.right(90)
  #my_turtle.forward(50)
  #my_turtle.right(90)
  #my_turtle.forward(50)
  #my_turtle.left(130)
   #I wanted to draw a diagonal line so the angle would have to be greater than 90 degrees
  #my_turtle.forward(70)
#draw_picture(my_turtle)

#Step 2.0
#1. The anonymous turtle is when there is only one turtle. So you don't need to specify if it's turtle_1, turtle_2, or turtle_3, you know it's THE turtle.
#2. Turtle with capitalized T means that it's an object, and in this case a function. Lower case turtle is a variable.
#3. my_turtle.left(90)
   #my_turtle.forward(100)
   #or do
   #my_turtle.setpos(0, 100)

#Step 2.1
import turtle
def draw_z(the_turtle, size):
  #I want to make the turtle to make 1/2 the diagnol of my Z then the top horizontal line
  the_turtle.left(45)
  the_turtle.forward(100 * size)
  the_turtle.left(135)
  the_turtle.forward(100 * size)
  #I want the turtle to go back to the middle, without drawing to then draw the middle line of the Z
  the_turtle.penup()
  the_turtle.goto(0,0)
  the_turtle.pendown()
  the_turtle.forward(45 * size)
  the_turtle.backward(90 * size)
  #Going back to the middle one last time I want the turtle to finish the seconed half of the Z diagnol and horizontal line
  the_turtle.penup()
  the_turtle.goto(0,0)
  the_turtle.pendown()
  the_turtle.left(45)
  the_turtle.forward(100 * size)
  the_turtle.left(135)
  the_turtle.forward(100 * size)
my_turtle = turtle.Turtle() 
#draw_z(my_turtle, 10)
#By multiplying it by size when moving forward and backwards we were able to adjust the size of the letter Z!
draw_z(my_turtle, 0.3)

#Rena is awesome and big brain
