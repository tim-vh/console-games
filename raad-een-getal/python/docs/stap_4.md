# Raad een getal

| 1 | 2 | 3 | 4 | 5 | 6 |
| --- | --- | --- | --- | --- | --- |
 ✅| ✅ | ✅ | 🟦 | ⬜ | ⬜ |


## 4. Kijk of het getal goed is geraden

Kijk met `if` of het geraden getal gelijk is aan het te raden getal. 

```python
if(geradenGetal == teRadenGetal):
    print("Goed geraden")
else:
    print("Dat was niet het goede getal")

```
<details>
<summary>Toon volledige code</summary>

```python
import random

print("Welkom bij het spel 'Raad een Getal'!")
print("Ik heb een getal tussen 1 en 10 gekozen. Kun jij het raden?")

teRadenGetal = random.randint(1, 10)

print("Welk getal denk je dat het is?: ")
invoer = input("Raad het getal: ")
geradenGetal = int(invoer)

if(geradenGetal == teRadenGetal):
    print("Goed geraden")
else:
    print("Dat was niet het goede getal")
```
</details>

---

[Vorige stap](stap_3.md) | [Volgende stap](stap_5.md)