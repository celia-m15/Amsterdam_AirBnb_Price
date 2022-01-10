# Pràctica Kaggle APC UAB 2021 - 2022
### Nom: Cèlia Martínez
### DATASET: Amsterdam - Airbnb
### URL: https://www.kaggle.com/adityadeshpande23/amsterdam-airbnb

### Resum 
El dataset utilitza dades sobre vaires característiques d'un pis / apartament que per poder-lo llogar / comprar. Aquest està format per 14.966 files i 17 atributs. D'aquests 17 atribts 8 son enters, 4 son double i 5 son binaris.

### Objectius del dataset
L'objectiu principal és predir el preu del immoble a partir de les seves característiques.

### Experiments
Durant aquesta pràctica s'han realitzat diferents models per amb l'objectiu de trobar el més adient per les nostres dades

### Preprocessat
Primer de tot hem descartat algunes columnes que eren redundants i per tant no ens eren útils. Després hem comprovat si hi havia gaires valors NULL o NaN. I finalment hem basat aquest estudi en si hi ha una diferencia rellevant entre normalitzar les dades o no fer-ho, així que també les hem normalitzat.

### Conclusions
Hem vist que en general tots els models son molt dolents ja que les dades gaire bé no estna correlacionades. Tanmateix ens hem trobat amb una possible sortida degut a que el model de Random Forest amb dades normalitzades dona un molt bon resultat amb les dades d'entrenament pero força dolent amb les dades de test cosa que ens indica la possibilitat d'overfitting.

### Idees per treballa en un futur
La millor opció és provar de treure l'overfitting trobat al Random Forest, per veure si de veritat el model funciona bé o no. D'altra banda vista la poca correlació que tenen les dades sobre el preu, també seria interessant treballar en la predicció dels primers atributs del DataSet ja que, tot i no ser tant interessants com el preu, tenen una gran dependencia i correlació entre ells que ens pot facilitar la predicció.
