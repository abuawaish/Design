# Design
New design thorough python programming with the help of turtle module
import turtle
ls=["red","yellow","green","cyan","blue","white"]
t=turtle.Turtle()
sc=turtle.Screen()
sc.bgcolor('black')
t.speed(30)
for i in range(150):
	t.color(ls[i%6])
	t.forward(i*4)
	t.left(150)
	t.width(2)
	
