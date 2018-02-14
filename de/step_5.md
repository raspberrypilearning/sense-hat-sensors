## Heiß machen

1. Ersetzen Sie die letzte Zeile durch:
    
    ```python
start_temperature = sense.temperature während True: print (sense.temperature) wenn sense.temperature > start_temperature + 2: sense.set_pixels (Symbol) else: sense.clear () sleep (1)
```

2. Führen Sie den Code erneut aus. Drücken Sie nun Ihren Finger gegen den Temperatursensor des Sense HAT und sehen Sie, ob Sie Ihr Symbol erscheinen lassen können!