What is your pyhton project
The title of my python project is = Biyakugan Blue Color
and its loop the shape again and then it will form as a biyakugan 

how to run your project
press the run python to run your python
import turtle as t 
import colorsys
t.bgcolor("black")
t.tracer(100)
t.pensize(1)
h=0.5
for i in range (250):
	c=colorsys.hsv_to_rgb(h,1,1)
	h=0.0008
	t.fillcolor(c)
	t.begin_fill()
	t.fd(i)
	t.lt(100)
	t.circle(30)
	for j in range(2):
		t.fd(i*j)
		t.rt(109)
	t.end_fill()
