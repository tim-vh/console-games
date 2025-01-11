# Raad een getal

| 1 | 2 | 3 | 4 | 5 | 6 |
| --- | --- | --- | --- | --- | --- |
 ✅| ✅ | ✅ | ✅ | 🟦 | ⬜ |


## 5. Laat de speler meerdere keren raden

Maak een variabele om bij te houden of de speler het getal geraden heeft of niet:

```python
isGetalGeraden = False
```

Gebruik een `while` loop het raden van een getal te herhalen:

```csharp
while(isGetalGeraden == False):
    print("Welk getal denk je dat het is?: ")
    geradenGetal = input("Raad het getal: ")

    if(geradenGetal == teRadenGetal):
        print("Goed geraden")
    else:
        print("Dat was niet het goede getal")
```

Zet de variable `isGetalGeraden` op `true` wanneer het getal goed is geraden:

```python
    if(geradenGetal == teRadenGetal):
        isGetalGeraden = True
        print("Goed geraden")
```

<details>
<summary>Toon volledige code</summary>

```python
import random

print("Welkom bij het spel 'Raad een Getal'!")
print("Ik heb een getal tussen 1 en 10 gekozen. Kun jij het raden?")

teRadenGetal = random.randint(1, 10)
isGetalGeraden = False

while(isGetalGeraden == False):
    print("Welk getal denk je dat het is?: ")
    invoer = input("Raad het getal: ")
    geradenGetal = int(invoer)

    if(geradenGetal == teRadenGetal):
        isGetalGeraden = True
        print("Goed geraden")
    else:
        print("Dat was niet het goede getal")
```
</details>

---

[Vorige stap](stap_4.md) | [Volgende stap](stap_6.md)