## Prova il Sense HAT

1. Apri Python 3 e inserisci i seguenti comandi direttamente nella shell:
    
    (non digitare i segni di *maggiore* `>>>`)
    
    ```python
>>> from sense_hat import SenseHat
>>> sense = SenseHat()
>>> sense.show_message("Hello world")
```

Premi `Invio` dopo ogni riga e dopo la terza riga, il messaggio dovrebbe apparire sul display del Sense HAT.

2. Ora prova a recuperare i valori del sensore:
    
    ```python
>>> sense.temperature
>>> sense.humidity
>>> sense.pressure
```

Quando premerai `Invio`, vedrai il valore dei sensori.