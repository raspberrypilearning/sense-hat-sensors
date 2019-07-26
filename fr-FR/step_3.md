## Visages

\--- task \---

Ouvre une nouvelle fenêtre et tape:

```python
from sense_hat import SenseHat
from time import sleep

sense = SenseHat()

rg = (255, 0, 0)
vt = (0, 255, 0)
bl = (0, 0, 255)
jn = (255, 255, 0)
mg = (255, 0, 255)
cy = (0, 255, 255)
bc = (255, 255, 255)
e = (0, 0, 0)

icone = [
    e, e, e, e, e, e, e, e,
    e, e, e, e, e, e, e, e,
    e, e, bl, e, e, bl, e, e,
    e, e, e, e, e, e, e, e,
    e, e, e, e, e, e, e, e,
    e, bl, e, e, e, e, bl, e,
    e, bl, bl, bl, bl, bl, bl, e,
    e, e, e, e, e, e, e, e,
]

sense.set_pixels(icone)
```

\--- /task \---

\--- task \---

Crée maintenant ta propre icône en utilisant les couleurs (`rg` est rouge, `vt` est vert, `bl` est bleu et ainsi de suite). Ton icône devra avoir une taille de 8x8 comme dans l'exemple.

\--- /task \---

\--- task \---

Exécute le code avec `F5` et tu devrais voir ton icone s'afficher sur le Sense HAT.

\--- /task \---