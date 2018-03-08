## それを熱くする

1. 最後の行を次のように置き換えます。
    
    ```python
start_temperature = sense.temperature while True：print（sense.temperature）if sense.temperature > start_temperature + 2：sense.set_pixels（アイコン）else：sense.clear（）sleep（1）
```

2. コードをもう一度実行します。 Sense HATの温度センサーに指を押して、あなたのアイコンを表示させることができるかどうかを確認してください！