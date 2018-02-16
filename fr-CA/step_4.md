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

2. Créez maintenant votre propre icône en utilisant les couleurs (`r` est rouge, `g` est vert, `b` est bleu et ainsi de suite). Votre icône doit être 8x8 comme l'exemple.

3. Exécutez le code avec `F5` et vous devriez voir votre icône sur l'écran Sense HAT.