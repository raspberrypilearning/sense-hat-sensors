## センスHATをテストする

1. Python 3を開き、次のコマンドをシェルに直接入力します。
    
    （シェブロンを入力しないでください`>>>`）
    
    ```python
>>> sense_hatからのインポートSenseHat>>> sense = SenseHat（）>>> sense.show_message（ "Hello world"）
```

プレス`入力`各行の後、3行目の後に、Sense HATのディスプレイにメッセージが表示されます。

2. 次にセンサー値を取得してみましょう：
    
    ```python
>>> sense.temperature>>> sense.humidity>>>感圧
```

`Enter`を押すと、センサーの値が表示されます。