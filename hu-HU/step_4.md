## Melegítsd fel

\--- task \---

Cseréld le az utolsó sort erre:

```python
start_temperature = sense.temperature

while True:
    print(sense.temperature)
    if sense.temperature > start_temperature + 2:
        sense.set_pixels(ikon)
    else:
        sense.clear()
    sleep(1)
```

\--- /task \---

\--- task \---

Futtasd újra a kódot. Most tedd az ujjad a Sense HAT hőmérsékletérzékelőjére és nézd meg, hogy megjelenik-e az ikonod!

\--- /task \---