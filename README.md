# luve
import turtle

# Configurações da tela
screen = turtle.Screen()
screen.bgcolor("white")

# Configurações da tartaruga
t = turtle.Turtle()
t.shape("turtle")
t.color("red")
t.fillcolor("pink")
t.pensize(3)
t.speed(2)

# Desenhar o coração
t.begin_fill()
t.left(140)
t.forward(180)
t.circle(-90, 200)
t.setheading(60)
t.circle(-90, 200)
t.forward(180)
t.end_fill()

# Esconder a tartaruga
t.hideturtle()

# Finalizar
turtle.done()
