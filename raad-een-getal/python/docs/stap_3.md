# Raad een getal

| 1 | 2 | 3 | 4 | 5 | 6 |
| --- | --- | --- | --- | --- | --- |
 ✅| ✅ | 🟦 | ⬜ | ⬜ | ⬜ |


## 3. Vraag de speler om een getal

Voeg de volgende code toe om een bericht te tonen en om de invoer van de speler in een variabele te zetten:

```python
print("Welk getal denk je dat het is?: ")
geradenGetal = input("Raad het getal: ")
```

Vervolgens willen we deze invoer omzetten naar een getal (integer):


```python
int geradenGetal = int.Parse(invoer);
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
```
</details>

---

[Vorige stap](stap_2.md) | [Volgende stap](stap_4.md)