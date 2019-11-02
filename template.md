# Chase The Pair Challenge by HackEPS2019

## Descripció
Codi realitzat amb Python 2.7 utilitzant el mínim de caràcters possibles sense utilitzar funcions. S'utilitzen 242 caràcters.

No hi ha cap tipus d'optimització, per exemple, si s'ha trobat chase, no cal buscar més. En aquest codi es recorren tots els valors.

El cost del codi seria "n" quan es calculen les distàncies a chase, i "n" per trobar el mínim. Realment es podria guardar el mínim a la vegada que es calculen distàncies, però incrementaria el nombre de caràcters. Per tant, el cost és O(2n).

Per executar:
  python chaseThePair.py \<chase number\>

Exemple:
  python chaseThePair.py 10

## Informació
- Group name: LoneWolves
- Cost: O(2n)
- Time expend: ~4 segons sense tenir en compte la lectura (i7-8550U 1.80GHz-2.00 GHz utilitzant Ubuntu on Windows 10)
- Sets size: 10M
