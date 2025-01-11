# Raad een getal

| 1 | 2 | 3 | 4 | 5 | 6 |
| --- | --- | --- | --- | --- | --- |
 ✅| ✅ | ✅ | 🟦 | ⬜ | ⬜ |


## 4. Kijk of het getal goed is geraden

Kijk met `if` of het geraden getal gelijk is aan het te raden getal. 

```csharp
if(geradenGetal == teRadenGetal)
{
    Console.WriteLine("Goed geraden");
}
else
{
    Console.WriteLine("Dat was niet het goede getal");
}

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

if(geradenGetal == teRadenGetal)
{
    Console.WriteLine("Goed geraden");
}
else
{
    Console.WriteLine("Dat was niet het goede getal");
}

Console.ReadKey();
```
</details>

---

[Vorige stap](stap_3.md) | [Volgende stap](stap_5.md)