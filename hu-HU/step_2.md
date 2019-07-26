## Teszteld a Sense HAT-et

\--- task \---

Nyisd meg a Python 3-at és add meg a következő parancsot közvetlenül a shell-be:

(ne írd be a `>>>` jeleket)

```python
>>> from sense_hat import SenseHat
>>> sense = SenseHat()
>>> sense.show_message("Helló világ")
```

Üss `Enter`-t minden sor után és a harmadik sor után a szövegnek meg kellene jelennie a Sense HAT kijelzőjén.

\--- /task \---

\--- task \---

Most próbáld meg lekérdezni az érzékelő értékeit:

```python
>>> sense.temperature
>>> sense.humidity
>>> sense.pressure
```

Miután megnyomod az `Enter`-t, láthatod az érzékelő értékeit.

\--- /task \---