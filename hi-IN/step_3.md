## चेहरे

\--- task \---

एक नई विंडो को खोले और टाइप करे:

```python
from sense_hat import SenseHat
from time import sleep

sense = SenseHat()

r = (255, 0, 0)
g = (0, 255, 0)
b = (0, 0, 255)
y = (255, 255, 0)
p = (255, 0, 255)
c = (0, 255, 255)
w = (255, 255, 255)
e = (0, 0, 0)

icon = [
    e, e, e, e, e, e, e, e,
    e, e, e, e, e, e, e, e,
    e, e, b, e, e, b, e, e,
    e, e, e, e, e, e, e, e,
    e, e, e, e, e, e, e, e,
    e, b, e, e, e, e, b, e,
    e, b, b, b, b, b, b, e,
    e, e, e, e, e, e, e, e,
]

sense.set_pixels(icon)
```

\--- /task \---

\--- task \---

अब रंगों का उपयोग करके अपना खुद का आइकन बनाएं (`r` लाल, `g` हरा, `b` नीला और आदि)। उदाहरण के प्रकार आपका आइकन 8x8 होना चाहिए।

\--- /task \---

\--- task \---

`F5` दबाकर कोड चलाएं और आपको Sense HAT डिस्प्ले पर अपना आइकन दिखाई देना चाहिए।

\--- /task \---