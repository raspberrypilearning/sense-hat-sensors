## Testez le Sense HAT

1. Ouvrez Python 3 et entrez les commandes suivantes directement dans le shell:
    
    (ne pas taper les chevrons `>>>`)
    
    ```python
>>> à partir de sense_hat importer SenseHat>>> sens = SenseHat ()>>> sense.afficher_message ("Bonjour tout le monde")
```

Appuyez sur `Entrée` après chaque ligne, et après la troisième ligne, le message devrait apparaître sur l'écran de Sense HAT.

2. Essayez maintenant de récupérer les valeurs du capteur:
    
    ```python
>>> sense.temperature>>> sens.humidité>>> sens.pression
```

Lorsque vous appuyez sur `Entrée`, vous voyez la valeur du capteur.