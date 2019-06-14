## Mach es heiß

\--- task \---

Ersetze die letzte Zeile durch:

```python
start_temperatur = sensoren.temperature

while True:
    print(sensoren.temperature)
    if sensoren.temperature > start_temperatur + 2:
        sensoren.set_pixels(bild)
    else:
        sensoren.clear()
    sleep(1)
```

\--- /task \---

\--- task \---

Führe den Code erneut aus. Drücke nun deinen Finger gegen den Temperatursensor des Sense HAT und schau, ob du dein Bild erscheinen lassen kannst!

\--- /task \---