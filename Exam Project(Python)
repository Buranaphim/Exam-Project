# Exam-Project
import turtle
def sier(side, depth):
    if depth == 1:
        for i in range(3):
            turtle.fd(side)
            turtle.left(120)
    else:
        sier(side/2, depth-1)
        turtle.fd(side/2)
        sier(side/2, depth-1)
        turtle.bk(side/2)
        turtle.left(60)
        turtle.fd(side/2)
        turtle.right(60)
        sier(side/2, depth-1)
        turtle.left(60)
        turtle.bk(side/2)
        turtle.right(60)
turtle.speed(0)
sier(300,6)

import turtle 
def branch(size, depth): 
    turtle.fd(size)
    if size>5:
        turtle.lt(depth/2)
        branch(size*0.75, depth) 
        turtle.rt(depth)
        branch(size*0.75, depth)
        turtle.lt(depth/2)
    turtle.bk(size)
size=124 
depth=24 
turtle.tracer(32,0) 
turtle.setheading(90) 
turtle.bk(size)
branch(size, depth) 
