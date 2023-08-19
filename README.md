# Snake_game

#import packages
import turtle
import random 
import time

#creating screen 
screen =turtle.Screen()
screen.title("Snack Game")
screen.setup(width=700,height=700)
screen.tracer(0)
screen.bgcolor("#1d1d1d")

#creating border
turtle.speed(5)
turtle.pensize(4)
turtle.penup()
turtle.goto(-310,250)
turtle.pendown()
turtle.color("red")
turtle.forward(600)
turtle.right(98)
turtle.forward(500)
turtle.right(98)
turtle.forward(600)
turtle.right(98)
turtle.forward(500)
turtle.penup()
turtle.hideturtle()

#score
score=0;
delay=0.1

#snake
snake=turtle.Turtle()
snake.shape()
snake.shape("square")
snake.color("green")
snake.penup()
