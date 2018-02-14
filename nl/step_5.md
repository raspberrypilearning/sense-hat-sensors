## Maak het heet

1. Vervang de laatste regel door:
    
    ```python
start_temperature = sense.temperature while True: print (sense.temperature) if sense.temperature > start_temperature + 2: sense.set_pixels (icon) else: sense.clear () slaap (1)
```

2. Voer de code opnieuw uit. Druk nu met uw vinger tegen de temperatuursensor op de Sense HAT en kijk of u uw pictogram kunt laten verschijnen!