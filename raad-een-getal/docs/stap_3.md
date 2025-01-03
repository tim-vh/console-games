# Raad een getal

| 1 | 2 | 3 | 4 | 5 | 6 |
| --- | --- | --- | --- | --- | --- |
 ✅| ✅ | 🟦 | ⬜ | ⬜ | ⬜ |


## 3. Vraag de speler om een getal

Voeg de volgende code toe om een bericht te tonen en om de invoer van de speler in een variabele te zetten:

```csharp
Console.Write("Welk getal denk je dat het is?: ");
string invoer = Console.ReadLine();
```

Vervolgens willen we deze invoer omzetten naar een getal (integer):


```csharp
int geradenGetal = int.Parse(invoer);
```

<details>
<summary>Toon volledige code</summary>

```csharp
Console.WriteLine("Welkom bij het spel 'Raad een Getal'!");
Console.WriteLine("Ik heb een getal tussen 1 en 10 gekozen. Kun jij het raden?");

Random random = new Random();
int teRadenGetal = random.Next(1, 10);

Console.Write("Welk getal denk je dat het is?: ");
string invoer = Console.ReadLine();

int geradenGetal = int.Parse(invoer);

Console.ReadKey();
```
</details>

---

[Vorige stap](stap_2.md) | [Volgende stap](stap_4.md)