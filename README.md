# [b3_java_diplome_dates](https://spoonless.github.io/epsi-b3-java/les_dates.html#id2)

## Diplôme et examens (suite) 
 
## Date des examens

### Reprenez l’implémentation du système de gestion des diplômes des chapitres précédents.

* Un Examen doit avoir une date. Attention, pour être valide, la date de l’examen doit être comprise entre le 1er octobre et le 30 juin. 
* De plus, une date d’examen ne peut pas être un samedi ou un dimanche.

* Surchargez la méthode toString de manière à ce qu’un Examen (et toutes les classes qui en héritent) génère une chaîne de caractères de la forme :

- 12,00/20 à l’examen du 07 janvier 2018

* Affichez la note sur 20 et la date pour chaque examen d’un diplôme.

## Note
Pour la création de la chaîne de caractères, pensez à afficher correctement les notes avec des virgules en tronquant à deux décimales après la virgule.
Il serait plus lisible d’aligner les notes en ajoutant des espaces à gauche. 
Vous pouvez vous reporter à la méthode String.format et aux motifs de formatage décrit dans la classe Formatter pour produire cette chaîne de caractères.
