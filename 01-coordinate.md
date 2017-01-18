# Coordinate

La terra è un _geoide_. La forma geometrica che meglio l'approssima è un _ellissoide_ leggermente schiacciato ai poli, comunque è possibile approssimarla tramite una sfera.

**Asse di rotazione** (o _asse polare_)**:** passa da polo a polo attraversando il centro della Terra. È inclinato di 23°27' rispetto al "piano del'orbita".

**Equatore:** circonferenza massima alla quale si rapportano le latitudini. Determinato dal piano ortogonale all'asse polare e passante per il centro della Terra. Divide la Terra in emisfero Nord (_boreale_) e Sud (_australe_).

**Paralleli:** infinite circonferenze minori, parallele all'Equatore. {% em type="red" %}Luogo geometrico dei punti aventi uguale latitudine{% endem %}. Convenzionalmente ne contiamo 180 (90 a Nord, 90 a Sud)

**Meridiani:** infinite semi-circonferenze passanti per i poli. La parte opposta è detta **antimeridiano**. {% em type="red" %}Luogo geometrico dei punti aventi uguale longitudine{% endem %}. Il meridiano di Greenwich ha longitudine 0° ed è detto _fondamentale_.

**Latitudine &phi;:** Arco di meridiano compreso tra l'Equatore e un punto P. Vale 0° sull'Equatore, +90° al polo Nord, -90° al polo Sud.

**Longitudine &lambda;:** Arco di Equatore (o, equivalentemente, parallelo) compreso tra il Meridiano di Greenwich e un punto P. Vale 0° sul Meridiano di Greenwich, cresce verso Est fino a un massimo di 180°, decresce verso Ovest fino a un minimo di -180°.

> #### danger::
>
> **Grado di latitudine:** distanza angolare dall'uno all'altro dei 180 paralleli.
>
> **Grado di longitudine:** distanza angolare da uno all'altro dei 360 meridiani.

---

> #### default::
> 
> ## Differenza di latitudine tra due punti (&Delta;&phi;)
> 
> &Delta;&phi; = &phi;B - &phi;A
> 
> Misura angolare dell'arco di meridiano compreso tra i paralleli passanti per due punti.
> 
> È compresa tra 0° e 180°. 180° corrisponde alla differenza di latitudine tra i due poli.
>
> Ricorda: le latitudini sono positive al Nord e negative al Sud.
>
> ### Regola per calcolare &Delta;&phi;
> 
> * Se le due latitudini hanno lo stesso nome (entrambe N o S): si **sottraggono** e si attribuisce il segno del polo verso cui si dirive la nave (a prescindere dell'emisfero in cui si trova).
> * Se le due latitudini hanno nome contrario (una N, l'altra S): si **sommano** e si assegna uil nome della latitudine di destinazione.

---

> #### default::
>
> ## Differenza di longitudine tra due punti (&Delta;&lambda;)
>
> &Delta;&lambda; = &lambda;B - &lambda;A
>
> Arco di Equatore compreso tra i meridiani passanti per i due punti.
> 
> È compresa da 0° a 180°.
> 
> ### Regola per calcolare &Delta;&phi;
> 
> * Se le due longitudini hanno lo stesso segno (entrambe E o W): si **sottraggono** e si attribuisce il segno del punto cardinale verso cui si muove la nave.
> * Se le due longitudini hanno segno contrario (una E, l'altra W): si **sommano** e si attribuisce il segno del punto cardinale verso cui si muove la nave.
> * Se il risultato della somma o sottrazione è maggiore (in valore assoluto) di 180°, si sottrae tale valore a 360° (_esplemento_) e si inverte il segno.

---

> #### default::
>
> ## Esempio: 
> 
> Dati:
>
> * Partenza: &lambda;A = 120° E 
> * Destinazione: &lambda;B = 130° W
>
> Applico la regola:
> 
> 1. &lambda;A e &lambda;B hanno segno opposto: vanno sommati
> 2. &Delta;&phi; = 120° E + 130° W
>    * La destinazione è W, quindi assegniamo direzione W al risultato.
> 3. &rArr; 120 + 130 = 250 W
>    * Il risultato (in valore assoluto) è maggiore di 180°, quindi effettuiamo l'espletamento e invertiamo la direzione.
> 4. &rArr; 360 - 250 E = 110 E