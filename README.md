# fun2
Python code for loop


import turtle
col = ('red','cyan','green','pink','yellow','white')
fig = turtle.Turtle()
screen = turtle.Screen()
screen.bgcolor('black')
fig.speed(25)


for i in range(150):
    fig.circle(70)
    fig.color(col[i%6])
    fig.forward(i*1.5)
    fig.left(59)
    fig.width(2)
