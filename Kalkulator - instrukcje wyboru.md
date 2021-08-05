
##### Table of Contents  
[Head ers](#headers)  
[Emphasis](#emphasis)  
...snip...    
<a name="headers"/>
## Headers

# Kalkulator - instrukcje wyboru
## Spis treści
* [Instrukcja if-else](#Instrukcja_if-else)
* [Instrukcja switch](#Instrukcja_switch)
* [Obsługa błędów](#Obsługa_błędów)
* [Zadania](#Zadania)
* [Link do kursu](#Link_do_kursu)
<a name="Instrukcja_if-else"/>
## Instrukcja if-else
Instrukcja if-else - określa, która instrukcja ma być uruchamiana, na podstawie wartości wyrażenia logicznego.

```ruby  
bool condition= true;

if (condition)
{
    Console.WriteLine("Zmienna przechowuje wartość "true" czyli z logiki prawdę.");
}
else
{
    Console.WriteLine("Zmienna przechowuje wartość "false", czyli z logiki fałsz.");
}
```
[Dokumentacja Microsoft - instrukcja if-else](https://docs.microsoft.com/pl-pl/dotnet/csharp/language-reference/keywords/if-else)

<a name="Instrukcja_switch"/>
## Instrukcja switch
Instrukcja switch - na podstawie przypadku - `expression`, wybiera jeden z wielu bloków kodu i wykonuje daną instrukcję.

```ruby  
Int expression= x

switch(expression) 
{
  case x:
    // code block
    break;
  case y:
    // code block
    break;
  default:
    // code block
    break;
}
```
[Dokumentacja w3schools - instrukcja switch](https://www.w3schools.com/cs/cs_switch.php)
[Dokumentacja Microsoft - instrukcja switch](https://docs.microsoft.com/pl-pl/dotnet/csharp/language-reference/keywords/switch)

## Obsługa błędów

## Zadania
Pobierz od użytkownika znak działania, wykorzystaj intrukcję if, w instrukcji umieść właściwe działanie matematyczne i wyświetl wynik.

## Link do kursu
[Poklikajmy - podstawy C#](https://youtu.be/daIjsicyZBk)
