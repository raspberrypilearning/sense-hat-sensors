## Make it hot

1. Replace the last line with:

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

1. Run the code again. Now press your finger against the temperature sensor on the Sense HAT and see if you can make your icon appear!
