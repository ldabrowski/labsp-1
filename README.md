#muj pierszy readme z zadaniami :))
* Rozwiazania przykladowych zadan
## Laboratorium drógie

1. Wyswietl na ekran 4 ostatnie wiersze pliku *program.c*:


````sh
tail -n 4 program.c

````

2. Zadanie 9: zlicz ilosc znakow z 3 pierwszych lini pliku /etc/passwd


```sh
cat /etc/passwd/ | head -n 3 | wc -m
```

3. Zadanie 8: Zlicz pliki w /etc i pod katalogach

```sh
find etc -type f -follow | wc -l
```




