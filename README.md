# Python Turtle for Shape drawing
> Program :
```python
import turtle

t = turtle.Turtle()
t.getscreen().bgcolor("black")
t.pendown
t.color("yellow")


def shape(pen, size, j):
    if size <= j:
        return
    else:
        for i in range(j):
            pen.forward(size)
            # shape(turtle, size/j,j)
            pen.left(360 / j)


if __name__ == "__main__":
    for i in range(3, 19, 1):
        shape(t, 120, i)
    turtle.done()
```
> Output :

![](output.png)
## Use mobile to run it without error. (install pydroid)
# [►](https://play.google.com/store/apps/details?id=ru.iiec.pydroid3)
