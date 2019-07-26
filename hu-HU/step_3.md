## Arcok

\--- task \---

Nyiss meg egy új ablakot és írd be:

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

ikon = [
    e, e, e, e, e, e, e, e,
    e, e, e, e, e, e, e, e,
    e, e, b, e, e, b, e, e,
    e, e, e, e, e, e, e, e,
    e, e, e, e, e, e, e, e,
    e, b, e, e, e, e, b, e,
    e, b, b, b, b, b, b, e,
    e, e, e, e, e, e, e, e,
]

sense.set_pixels(ikon)
```

\--- /task \---

\--- task \---

Most készítsd el a saját ikonodat a színek segítségvel (az `r` a piros, a `g` a zöld, a `b` a kék és így tovább). Az ikonodnak 8x8 nagyságúnak kell lennie, mint a példában.

\--- /task \---

\--- task \---

Futtasd a kódot az `F5`-tel és látnod kellene az ikonodat megjelenni a Sense HAT kijelzőjén.

\--- /task \---