Mi dirección de github de este repositorio es el siguiente: https://github.com/AlejandroIlgesias/Estrella.git

He creado un código que crea una estrella mediante el módulo de phyton "Turtle"

///from turtle import*
color("red","yellow")

begin_fill()
while True:
    forward(300)
    left(170)
    if abs(pos())<1:
        break
end_fill()
done()///
