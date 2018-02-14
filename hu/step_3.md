## Tesztelje a Sense HAT-ot

1. Nyissa meg a Python 3 parancsot, és adja meg a következő parancsokat közvetlenül a shell-ba:
    
    (ne írja be a chevrons `>>>`)
    
    ```python
>>> sense_hat import SenseHat>>> sense = SenseHat ()>>> sense.show_message ("Hello world")
```

Nyomja meg a 123_6_0_321 | Enter</code> gombot minden sor után és a harmadik sor után az üzenet megjelenik a Sense HAT kijelzőjén.

2. Most próbálja meg lekérni az érzékelő értékeit:
    
    ```python
>>> sense.temperature>>> sense.humidity>>> sense.pressure
```

Ha megnyomja a `Enter`gombot, megjelenik az érzékelő értéke.