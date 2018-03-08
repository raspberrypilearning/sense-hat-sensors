## Fallo scaldare

1. Sostituisci l'ultima riga con:
    
    ```python
start_temperature = sense.temperature

while True:
    print(sense.temperature)
    if sense.temperature > start_temperature + 2:
        sense.set_pixels(icon)
    else:
        sense.clear()
    sleep(1)
```

2. Esegui nuovamente il programma. Ora premi un dito sopra il sensore di temperatura del Sense HAT e vedi se riesci a far apparire l'icona!