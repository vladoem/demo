# Kompletný Markdown Príručka

## Základné formátovanie textu

**Tučné písmo** alebo __takto__

*Kurzíva* alebo _takto_

***Tučná kurzíva***

~~Preškrtnutý text~~

## Nadpisy

# Nadpis 1
## Nadpis 2
### Nadpis 3
#### Nadpis 4
##### Nadpis 5
###### Nadpis 6

## Zoznamy

### Nečíslovaný zoznam
- Položka 1
- Položka 2
  - Podpoložka 2.1
  - Podpoložka 2.2
* Alternatívna položka
+ Ďalšia možnosť

### Číslovaný zoznam
1. Prvá položka
2. Druhá položka
   1. Podpoložka 2.1
   2. Podpoložka 2.2

### Kontrolný zoznam
- [x] Hotová úloha
- [ ] Nehotová úloha

## Odkazy

[Text odkazu](https://www.example.com)

[Odkaz s titulkom](https://www.example.com "Titulok odkazu")

Automatický odkaz: <https://www.example.com>

## Obrázky

![Alternatívny text](https://example.com/image.jpg)

![Alternatívny text](https://example.com/image.jpg "Titulok obrázku")

## Citácie

> Toto je citácia
> 
> Viacriadková citácia
>> Vnorená citácia

## Kód

Inline `kód`

```python
def funkcia():
    print("Blok kódu so zvýraznením syntaxe")
```

    Odsadený blok kódu
    bez zvýraznenia syntaxe

## Horizontálna čiara

---
alebo
***
alebo
___

## Tabuľky

| Stĺpec 1 | Stĺpec 2 | Stĺpec 3 |
|----------|:--------:|---------:|
| Predvolené | Stred | Vpravo |
| Dáta | Dáta | Dáta |

## Poznámky pod čiarou

Text s poznámkou[^1]

[^1]: Toto je poznámka pod čiarou.

## Definičný zoznam

Term
: Definition

## Escape znaky

\*Toto nie je kurzíva\*

## HTML v Markdown

<div style="color: red;">
  HTML je podporovaný v niektorých implementáciách
</div>

## Rozšírenia (podpora závisí od implementácie)

### Matematické vzorce (LaTeX)

$$E = mc^2$$

### Diagramy (Mermaid)

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

Potrebujete ďalšie informácie alebo ukážky?
