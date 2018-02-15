## Gesichter

1. Öffne ein neues Fenster und tippe:
    
    ```python
from sense_hat import SenseHat
from time import sleep

sensoren = SenseHat()

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

sensoren.set_pixels(icon)
```

2. Erstelle nun dein eigenes Icon mit den Farben (`r` ist rot, `g` ist grün, `b` ist blau usw.). Dein Symbol muss wie das Beispiel 8x8 sein.

3. Führe den Code mit `F5` aus und du solltest dein Symbol auf dem Sense HAT-Display sehen.