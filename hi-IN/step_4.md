## इसे गर्म करे

\--- task \---

आखिरी लाइन को नीचे दिए गए लाइनों से बदलें:

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

\--- /task \---

\--- task \---

कोड फिर से चलाएं। अब Sense HAT पर तापमान सेंसर के खिलाफ अपनी उंगली दबाएं और देखें कि क्या आप अपना आइकन प्रदर्शित कर सकते हैं!

\--- /task \---