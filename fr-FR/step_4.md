## Réchauffe-le

\--- task \---

Remplace la dernière ligne par:

```python
temperature_au_debut = sense.temperature

while True:
    print(sense.temperature)
    if sense.temperature > temperature_au_debut + 2:
        sense.set_pixels(icone)
    else:
        sense.clear()
    sleep(1)
```

\--- /task \---

\--- task \---

Exécute le code à nouveau. Maintenant, met ton doigt sur le capteur de température du Sense HAT et vois si tu peux faire apparaître ton icône!

\--- /task \---