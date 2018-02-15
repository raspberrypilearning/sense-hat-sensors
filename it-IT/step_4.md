## Le espressioni facciali

1. Apri una nuova finestra e digita:
    
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

2. Ora crea la tua icona usando i colori (`r` è rosso, `g` è verde, `b` è blu e così via). L'icona deve essere 8x8 come nell'esempio.

3. Esegui il programma con `F5`, dovresti vedere apparire la tua icona sul display del Sense HAT.