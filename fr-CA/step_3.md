## Tester le Sense HAT

1. Ouvrez Python 3 et entrez les commandes suivantes directement dans le shell:
    
    (ne pas taper les chevrons `>>>`)
    
    ```python
>>> à partir de sense_hat import SenseHat>>> sens = SenseHat ()>>> sense.show_message ("Bonjour tout le monde")
```

Appuyez sur `Entrez` après chaque ligne, et après la troisième ligne, le message devrait apparaître sur l'écran de Sense HAT.

2. Essayez maintenant de récupérer les valeurs du capteur:
    
    ```python
>>> sense.temperature>>> sens.humidité>>> sens.pression
```

Lorsque vous appuyez sur `Enter`, vous voyez la valeur du capteur.