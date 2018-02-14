## Test the Sense HAT

1. Open Python 3 and enter the following commands directly into the shell:
    
    (do not type the chevrons `>>>`)
    
    ```python
>>> from sense_hat import SenseHat
>>> sense = SenseHat()
>>> sense.show_message("Hello world")
```

Press `Enter` after each line, and after the third line, the message should appear on the Sense HAT's display.

2. Now try retrieving the sensor values:
    
    ```python
>>> sense.temperature
>>> sense.humidity
>>> sense.pressure
```

When you press `Enter`, you will see the sensor's value.