## Mach es heiß

1. Ersetze die letzte Zeile durch:
    
    ```python
start_temperatur = sensoren.temperature

while True:
    print(sensoren.temperature)
    if sensoren.temperature > start_temperatur + 2:
        sensoren.set_pixels(icon)
    else:
        sensoren.clear()
    sleep(1)
```

2. Führe den Code erneut aus. Drücke nun deinen Finger gegen den Temperatursensor des Sense HAT und schau, ob du dein Symbol erscheinen lassen kannst!