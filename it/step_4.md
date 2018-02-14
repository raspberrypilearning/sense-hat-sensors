## Faces

1. Open a new window and type:
    
    ```python
from sense_hat import SenseHat
from time import sleep

sense = SenseHat()

r = (255, 0, 0)
g = (0, 255, 0)
b = (0, 0, 255)
y = (255, 255, 0)
p = (255, 0, 255)
c = (0, 255, 255)
w = (255, 255, 255)
e = (0, 0, 0)

icon = [
    e, e, e, e, e, e, e, e,
    e, e, e, e, e, e, e, e,
    e, e, b, e, e, b, e, e,
    e, e, e, e, e, e, e, e,
    e, e, e, e, e, e, e, e,
    e, b, e, e, e, e, b, e,
    e, b, b, b, b, b, b, e,
    e, e, e, e, e, e, e, e,
]

sense.set_pixels(icon)
```

2. Now make your own icon using the colours (`r` is red, `g` is green, `b` is blue and so on). Your icon must be 8x8 like the example.

3. Run the code with `F5` and you should see your icon on the Sense HAT display.