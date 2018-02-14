## 顔

1. 新しいウィンドウを開き、次のように入力します。
    
    ```python
from sense_hat import SenseHat from time import睡眠センス= SenseHat（）r =（255,0,0）g =（0,255,0）b =（0、0、255）y =（255,255,0）p =（255,0,255）c =（0,255,255）w =（255,255,255）e =（0,0,0）アイコン= [e、e、e、e、e、e、 e、e、e、e、e、e、e、e、e、e、e、e、e、e、 b、b、b、b、e、e、e、e、e、e、e、e、e、e、 e、e、e、e、e、e、e、e、e、] sense.set_pixels（アイコン）
```

2. `r`が赤、`g`が緑色、`b`が青色など）の色を使用して独自のアイコンを作成します。 あなたのアイコンは例のように8x8でなければなりません。

3. コードを`F5`で実行します。 Sense HATディスプレイにアイコンが表示されます。