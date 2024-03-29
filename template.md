# Chase The Pair Challenge by HackEPS2019

## Descripció
Codi realitzat amb Python 2.7 utilitzant el mínim de caràcters possibles sense utilitzar funcions. S'utilitzen 242 caràcters, menys del límit actual de 280 caràcters d'un tweet.

No hi ha cap tipus d'optimització, per exemple, si s'ha trobat chase, no cal buscar més. En aquest codi es recorren tots els valors. El fitxer no es tanca per estalviar caràcters. Es requereix d'un fitxer "logs.txt" proporiconat pel generador de sets.

El cost del codi seria "n" quan es calculen les distàncies a chase, i "n" per trobar el mínim. Realment es podria guardar el mínim a la vegada que es calculen distàncies, però incrementaria el nombre de caràcters. Per tant, el cost és O(2n).

Per executar:
  python chaseThePair.py \<chase number\>

Exemple:
  python chaseThePair.py 10

Altres idees:
El codi s'havia realitzat originalment de forma ordenada utilitzant Python.
Per tal d'accelerar el codi, es pot utilitzar C i la llibreria MPI (o OpenMP) per paralelitzar el codi. Primerament calculant en paralel cada llista de números, i per cada llista, que cada fil/procés busqui la seva millor solució i que el fil principal sel·leccioni els resultats finals.

## Informació
- Group name: LoneWolves
- Cost: O(2n)
- Time expend: ~4 segons sense tenir en compte la lectura (i7-8550U 1.80GHz-2.00 GHz utilitzant Ubuntu on Windows 10)
- Sets size: 10M
