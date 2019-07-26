## Maak het heet

1. Vervang de laatste regel door:
    
    ```python
start_temperature = sense.temperature while True: print (sense.temperature) if sense.temperature > start_temperature + 2: sense.set_pixels (icon) else: sense.clear () sleep (1)
```

2. Voer het programma opnieuw uit. Druk nu met je vinger tegen de temperatuursensor op de Sense HAT en kijk of je jouw pictogram kunt laten verschijnen!