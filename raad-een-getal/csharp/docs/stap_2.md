# Raad een getal

| 1 | 2 | 3 | 4 | 5 | 6 |
| --- | --- | --- | --- | --- | --- |
 ✅| 🟦 | ⬜ | ⬜ | ⬜ | ⬜ |


## 2. Genereer een random getal

Maak een instantie van de Random klasse om een willekeurig getal te genereren:

```csharp
Random random = new Random();
```

Genereer een willekeurig getal tussen 1 en 10:

```csharp
int teRadenGetal = random.Next(1, 10);
```

<details>
<summary>Toon volledige code</summary>

```csharp
Console.WriteLine("Welkom bij het spel 'Raad een Getal'!");
Console.WriteLine("Ik heb een getal tussen 1 en 10 gekozen. Kun jij het raden?");

Random random = new Random();
int teRadenGetal = random.Next(1, 10);

Console.ReadKey();
```
</details>

---

[Vorige stap](stap_1.md) | [Volgende stap](stap_3.md)
