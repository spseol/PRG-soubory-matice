# PRG -- soubory; matice

[![Join the chat at www:gitter.im/spseol/Python](https://badges.gitter.im/spseol/PRG-No.svg)](https://gitter.im/spseol/Python?utm_source=share-link&utm_medium=link&utm_campaign=share-link)

1. Vytvořte program, který do zadaného souboru ([matice.txt](matice.txt))
   vygeneruje matici čísel. Výsledek pak může vypadat například takto:


        99 75 63 41 67 74 41 25 56 89 93 75 54 93 75 37
        43 45 41 42 5 81 88 39 12 31 57 60 75 26 51 69
        25 57 42 68 73 63 12 61 3 3 54 87 88 69 0 38
        7 100 60 32 2 95 59 54 79 38 78 37 93 84 67 37
        79 97 73 69 47 59 98 42 37 33 60 58 75 53 62 41
        46 60 22 25 25 20 58 42 26 28 21 82 7 50 42 61
        67 25 92 84 23 66 17 14 94 31 67 2 75 39 89 45
        90 41 99 78 49 48 8 56 60 53 98 20 62 2 59 99
        53 60 98 42 57 4 50 39 22 62 6 3 21 37 44 35
        59 41 95 46 59 80 54 9 3 8 77 99 90 42 58 98
        91 17 45 80 24 62 100 5 16 18 7 11 33 35 0 69
        0 5 95 69 67 43 37 71 86 31 8 54 52 43 39 55

2. Vytvořte program, který přečte soubor ([matice.txt](matice.txt)) a vypíše
   aritmetický průměr všech hodnot v něm uložených.

3. Vytvořte program, který bude hodnoty uložené v souboru
   ([matice.txt](matice.txt)) vizualizovat. Pro vizualizaci můžete použít
   knihovnu [MatPlotLib](http://matplotlib.org) a její funkci
   [`imshow`](https://matplotlib.org/api/_as_gen/matplotlib.pyplot.imshow.html?highlight=imshow#matplotlib.pyplot.imshow).
   Můžete se podívat na 
   [spseol/PRG-jednoduche_obrazky](https://github.com/spseol/PRG-jednoduche_obrazky).
   ... a při převodu čísel z řetězců na nějaký číselný datový typ se vám bude
   hodit funkce 
   [`map`](https://duckduckgo.com/?q=python3+map+function).

```python

from pylab import imshow, show

data = [[1, 2, 3],
        [3, 4, 3],
        [5, 6, 7]]
imshow(data)
show()
```
![ukázka](ukazka.png)

:seedling:

`cmap='gnuplot'`    
![matice.txt](matice.png)

https://matplotlib.org/users/colormaps.html    
https://matplotlib.org/examples/color/colormaps_reference.html

