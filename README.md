# Projekt: Bulls & Cows

## Popis projektu

Tento projekt je jednoduchá implementace klasické logické hry **Bulls & Cows** napsaná v jazyce **Python**.  
Program vygeneruje náhodné čtyřmístné číslo a úkolem hráče je toto číslo uhodnout.

Po každém pokusu program vrátí informaci ve formě počtu **bulls** a **cows**:

- **Bull** – číslice je správná a zároveň je na správné pozici.
- **Cow** – číslice se v hledaném čísle nachází, ale je na jiné pozici.

Hra končí ve chvíli, kdy hráč uhodne všechny čtyři číslice na správných pozicích.

---

## Pravidla hry

- Počítač vygeneruje náhodné čtyřmístné číslo.
- Všechny číslice jsou **unikátní** (žádná se neopakuje).
- **První číslice není nikdy 0.**
- Hráč zadává své tipy, dokud číslo neuhodne.

---

## Příklad
```
Hi there!
--------------------------------------------
I´ve generated a random 4 digit number for you.
Let´s play a bulls and cows game.
--------------------------------------------
Enter a number:
--------------------------------------------
>>>>: 1234
bull: 1, cows: 2
--------------------------------------------
>>>>: 1842
Correct, you´ve guessed the right number in: 2 guesses!
--------------------------------------------
That´s amazing!
