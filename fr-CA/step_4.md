## Visages

1. Ouvrez un nouveau fichier Python et tapez:
    
    ```python
from sense_hat import SenseHat
from time import sleep

sense = SenseHat()

r = (255, 0, 0)
v = (0, 255, 0)
b = (0, 0, 255)
j = (255, 255, 0)
vi = (255, 0, 255)
c = (0, 255, 255)
bc = (255, 255, 255)
n = (0, 0, 0)

icone = [
    n, n, n, n, n, n, n, n,
    n, n, n, n, n, n, n, n,
    n, n, b, n, n, b, n, n,
    n, n, n, n, n, n, n, n,
    n, n, n, n, n, n, n, n,
    n, b, n, n, n, n, b, n,
    n, b, b, b, b, b, b, n,
    n, n, n, n, n, n, n, n,
]

sense.set_pixels(icone)
```

2. Maintenant, faites votre propre icône en utilisant les couleurs (`r` est rouge, `v` est vert, `b` est bleu, et ainsi de suite). Votre icône doit avoir 8x8 pixels comme l'exemple.

3. Exécutez le code avec la touche `F5` et vous devriez voir votre icône sur l'affichage du Sense HAT.