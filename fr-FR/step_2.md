## Tester le Sense HAT

\--- task \---

Ouvre Python 3 et entre les commandes suivantes directement dans l'interpréteur de commande:

(ne tape pas les chevrons `>>>`)

```python
>>> from sense_hat import SenseHat
>>> sense = SenseHat()
>>> sense.show_message("Bonjour tout le monde")
```

Appuie sur `Entrée` après chaque ligne, et après la troisième ligne, le message devrait apparaître sur l'écran du Sense HAT.

\--- /task \---

\--- task \---

Maintenant essaie de récupérer les valeurs des capteurs:

```python
>>> sense.temperature
>>> sense.humidity
>>> sense.pressure
```

Lorsque tu appuies sur `Entrer`, tu vas voir la valeur du capteur.

\--- /task \---