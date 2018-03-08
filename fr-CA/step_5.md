## Faites le chauffer

1. Remplacez la dernière ligne par:
    
    ```python
temperature_depart = sense.temperature

while True:
    print(sense.temperature)
    if sense.temperature > temperature_depart + 2:
        sense.set_pixels(icone)
    else:
        sense.clear()
    sleep(1)
```

2. Exécutez le code à nouveau. Maintenant, appuyez votre doigt contre le capteur de température sur le Sense HAT et voyez si vous pouvez faire apparaître votre icône!