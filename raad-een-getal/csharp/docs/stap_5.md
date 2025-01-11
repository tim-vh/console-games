# Raad een getal

| 1 | 2 | 3 | 4 | 5 | 6 |
| --- | --- | --- | --- | --- | --- |
 ✅| ✅ | ✅ | ✅ | 🟦 | ⬜ |


## 5. Laat de speler meerdere keren raden

Maak een variabele om bij te houden of de speler het getal geraden heeft of niet:

```csharp
bool isGetalGeraden = false;
```

Gebruik een `while` loop het raden van een getal te herhalen:

```csharp
while(isGetalGeraden == false)
{
    Console.Write("Welk getal denk je dat het is?: ");
    string invoer = Console.ReadLine();

    int geradenGetal = int.Parse(invoer);

    if(geradenGetal == teRadenGetal)
    {
        Console.WriteLine("Goed geraden");
    }
    else
    {
        Console.WriteLine("Dat was niet het goede getal");
    }
}
```

Zet de variable `isGetalGeraden` op `true` wanneer het getal goed is geraden:

```csharp
    if(geradenGetal == teRadenGetal)
    {
        isGetalGeraden = true;
        Console.WriteLine("Goed geraden");
    }
```

<details>
<summary>Toon volledige code</summary>

```csharp
Console.WriteLine("Welkom bij het spel 'Raad een Getal'!");
Console.WriteLine("Ik heb een getal tussen 1 en 10 gekozen. Kun jij het raden?");

Random random = new Random();
int teRadenGetal = random.Next(1, 10);
bool isGetalGeraden = false;

while(isGetalGeraden == false)
{
    Console.Write("Welk getal denk je dat het is?: ");
    string invoer = Console.ReadLine();

    int geradenGetal = int.Parse(invoer);

    if(geradenGetal == teRadenGetal)
    {
        isGetalGeraden = true;
        Console.WriteLine("Goed geraden");
    }
    else
    {
        Console.WriteLine("Dat was niet het goede getal");
    }
}

Console.ReadKey();
```
</details>

---

[Vorige stap](stap_4.md) | [Volgende stap](stap_6.md)