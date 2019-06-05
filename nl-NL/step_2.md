## Test de Sense HAT

\--- task \---

Open Python 3 en voer de volgende opdrachten rechtstreeks in de shell in:

(typ niet de chevrons `>>>` in)

```python
>>> from sense_hat import SenseHat
>>> sense = SenseHat()
>>> sense.show_message("Hallo wereld")
```

Druk op `Enter` na elke regel en na de derde regel verschijnt het bericht op het scherm van de Sense HAT.

\--- /task \---

\--- task \---

Probeer nu de sensorwaarden op te halen:

```python
>>> sense.temperature>>> sense.humidity>>> sense.pressure
```

Wanneer u op `Enter` drukt, ziet u de waarde van de sensor.

\--- /task \---