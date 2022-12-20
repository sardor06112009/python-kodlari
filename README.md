from turtle import *

def fleur():
    for i in range(200):
        speed(20)
        circle(190-i,90)
        left(90)
        circle(190-i,90)
        left(18)
fleur()
mainloop()

#2
from turtle import *
color('green')
bgcolor('black')
speed(11)
hideturtle()
b = 0
while b < 200:
    right(b)
    forward(b * 3)
    b=b + 1   
    
#3
from turtle import *

def fleur():
    for i in range(200):
        speed(20)
        circle(190-i,90)
        left(90)
        circle(190-i,90)
        left(18)
fleur()
mainloop()
