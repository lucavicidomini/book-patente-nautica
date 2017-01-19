# Esercizi svolti sulla differenza di coordinate

> #### default::
> Questi esercizi sono necessari solo per la patente senza limiti.

---

A = ( &phi; = 40° 30' N, &lambda; = 120° 50' E )
<br>
B = ( &phi; = 20° 15' N, &lambda; = 80° 30' W )

&Delta;&phi; = &phi;B - &phi;A

Entrambe le latitudini sono N (ovvero positive), quindi si effettua la sottrazione:

&Delta;&phi; = 20° 15' N - 40° 30' N

Siccome il minuendo (&phi;B = 20° 15' N) è più piccolo del sottraendo (&phi;A = 40° 30' N), si *invertono*
i termini della sottrazione e si invertirà anche il segno del risultato.

|              |     | Gradi | Minuti |    | Note |
| ------------ | --: | ----: | -----: | -- | ---- |
| &phi;A       |     | 40    | 30     | N  |      |
| &phi;B       | -   | 20    | 15     | N  |      |
| &Delta;&phi; |     | 20    | 15     | S  | È stato invertito il segno |

&Delta;&lambda; = &lambda;B - &lambda;A 

In questo caso le longitudini hanno segno opposto: &lambda;A è positiva (E), &lambda;B è negativa (W).

&Delta;&lambda; = 80° 30' W - 120° 50' E

Sommiamo le longitudini e assegnamo il segno della coordinata di destinazione, dopodiché controlliamo se è 
necessario calcolare l'espletamento.

|                 |    | Gradi | Minuti |    | Note |
| --------------- | --: | ----: | -----: | -- | ---- |
| &phi;A          |     | 80    | 30     | W  |      |
| &phi;B          | +   | 120   | 50     | E  |      |
|                 |     | 200   | 80     | W  | Normalizziamo i minuti |
|                 |     | 201   | 20     | W  | Il risultato è >180: calcoliamo l'espletamento |
| &nbsp;          |     |       |        |    |      |
|                 |     | 360   | 00     |    |      |
|                 | -   | 201   | 20     | W  | Per effettuare la sottrazione, denormalizziamo i minuti |
| &nbsp;          |     |       |        |    |      |
|                 |     | 359   | 60     |    |      |
|                 | -   | 201   | 20     | W  |      |
|                 |     | 158   | 40     | E  | È stato invertito il segno |
 
---