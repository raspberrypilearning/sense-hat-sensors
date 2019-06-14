## Gesichter

\--- task \---

Öffne ein neues Fenster und tippe folgendes ein:

```python
from sense_hat import SenseHat
from time import sleep

sensoren = SenseHat()

r = (255, 0, 0)
g = (0, 255, 0)
b = (0, 0, 255)
ge = (255, 255, 0)
vio = (255, 0, 255)
cy = (0, 255, 255)
w = (255, 255, 255)
s = (0, 0, 0)

bild = [
    s, s, s, s, s, s, s, s,
    s, s, s, s, s, s, s, s,
    s, s, b, s, s, b, s, s,
    s, s, s, s, s, s, s, s,
    s, s, s, s, s, s, s, s,
    s, b, s, s, s, s, b, s,
    s, b, b, b, b, b, b, s,
    s, s, s, s, s, s, s, s,
]

sensoren.set_pixels(bild)
```

\--- /task \---

\--- task \---

Zeichne nun dein eigenes Bild mit diesen Farben (`r` ist rot, `g` ist grün, `b` ist blau, ge ist gelb, vio ist violett, s ist schwarz usw.). Dein Bild muss wie im Beispiel 8x8 groß sein.

\--- /task \---

\--- task \---

Führe den Code mit `F5` aus und du solltest dein Bild auf dem Sense HAT-Display sehen.

\--- /task \---