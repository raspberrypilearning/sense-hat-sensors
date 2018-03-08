## Fais-le chaud

1. Remplacer la dernière ligne par:
    
    ```python
start_temperature = sense.temperature alors que True: print (sense.temperature) si sense.temperature > start_temperature + 2: sense.set_pixels (icône) else: sens.clear () sleep (1)
```

2. Exécutez le code à nouveau. Maintenant, mettez votre doigt sur le capteur de température sur le Sense HAT et voyez si vous pouvez faire apparaître votre icône!