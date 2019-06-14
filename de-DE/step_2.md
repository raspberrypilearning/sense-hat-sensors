## Teste das Sense-HAT

\--- task \---

Öffne Python 3 und gib die folgenden Befehle direkt in die Shell ein:

(Bitte die Größer-Zeichen `>>>` nicht eingeben)

```python
>>> from sense_hat import SenseHat
>>> sensoren = SenseHat()
>>> sensoren.show_message("Hallo Welt")
```

Drücke nach jeder Zeile `Enter` und nach der dritten Zeile sollte die Nachricht auf dem Display des Sense HAT erscheinen.

\--- /task \---

\--- task \---

Versuche nun, die Sensorwerte abzurufen:

```python
>>> sensoren.temperature
>>> sensoren.humidity
>>> sensoren.pressure
```

Wenn du `Enter` am Ende der Zeile drückst, siehst du den Wert des Sensors.

\--- /task \---