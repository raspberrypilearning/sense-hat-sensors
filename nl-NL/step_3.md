## Testen van de Sense HAT

1. Open Python 3 en voer de volgende opdrachten rechtstreeks in de shell in:
    
    (sla de haakjes bij het invoeren over `>>>`)
    
    ```python
>>> from sense_hat import SenseHat>>> sense = SenseHat ()>>> sense.show_message ("Hallo wereld")
```

Druk op `Enter` na elke regel en na de derde regel verschijnt het bericht op het scherm van de Sense HAT.

2. Probeer nu de sensorwaarden op te halen:
    
    ```python
>>> sense.temperature>>> sense.humidity>>> sense.pressure
```

Wanneer je op `Enter`drukt, ziet u de waarde van de sensor.