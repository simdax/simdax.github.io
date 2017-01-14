Al contrepoint.
===

1. Le contrepoint énonce les règles qui régissent un ensemble de
*plusieurs* mélodies. Sa forme la plus basique est celle qui régit
l'ensemble de _deux_ mélodies. Au-dessus de six mélodies simultanées,
on considère que l'exercice n'a pas plus de sens

1. Elle étudie les distances entre les sons, et leurs propriétés.

1. Elle est à la musique ce que l'arithmétique, l'étude des nombres
   "ronds", est aux mathématiques. Comme tous les *nombres*
   entretiennent un rapport entre eux, chaque note d'une musique
   polyphonique, du XIVème siècle à Kendji Girac, est, à sa manière,
   contrapuntique. Elle est une écriture "élémentaire".
   

1. C'est un niveau élémentaire quasi-complet, en ce que les seuls
   règles du contrepoint peuvent seules régir les autres paramètres
   musicaux: rythme, mélodie et harmonie. Le seul paramètre musical
   qui lui échappe est le *timbre*.
   
   * Corrollaire: en ce que le *timbre* est l'élément le plus saillant
     de l'écoute quotidienne, le *contrepoint* est l'élément le plus
     absent des conversations sur la musique, que cela soit au
     quotidien ou sur france culture; ainsi que sur les émotions qui
     lui sont accollées naturellement par l'animal à grandes oreilles
     qu'est l'homme.
     
1. En ce qu'elle régit l'ensemble des autres éléments de la
   composition, elle est l'âme de ce qu'on appelle le classicisme
   musical, au sens large. On peut "coller" aux règles du contrepoint,
   ou en "dévier".
   
   * on en dévie d'un point de vue formel, c'est-à-dire en _ajoutant_
     des *axiomes* (des principes premiers) à ceux du
     contrepoint. Pour être plus exact, on peut les _modifier_, mais
     pas les _éliminer_, de même qu'on ne peut pas "enlever le 7" des
     entiers naturels ou la "multiplication" des additions basiques de
     l'arithmétique. On pourrait décider que 2+2=5, ou à la limite
     décider de ne pas y penser, mais il n'empêche qu'en tant que pur
     concept, l'addition et le nombre 2 existent dans le monde des
     Idées, en train de se baigner avec ses amis 28 et Pi au carré
     fois i.
   * En cela, l'étude du contrepoint est aussi l'étude de toutes les
     musiques dites, un peu abusivement, "non-contrapuntiques".


Mathématique modulaire
==

1. Avant l'étude du contrepoint, rappellons les pièces disponibles à
   disposer sur l'échiquier:

    * Une gamme comporte sept notes.
    * un ensemble de sept notes forment une octave: chaque octave
      possède les mêmes notes.
    * une distance pouvant être négative ou positive, il n'y a que
      trois distances (conceptuelles) (plus la distance nulle,
      triviale): 1, 2 ou 3.
    * une mélodie est un ensemble d'intervalles compris entre 1 et 3,
      doublés d'un signe '+' ou '-' précisant la nature précise de
      l'intervalle (et plus concrètement la direction
      mélodique). C'est donc une direction et une suite d'intensités.

    Exemples concrets: une mélodie commence par une note qu'on va
    appeler 'do' en soi (sans hauteur ni timbre). Il peut être suivi
    par trois distances, qui, positives, aboutiraient respectivement à
    'ré', 'mi', ou 'fa', et qui, négatives, aboutiraient
    respectivement à 'si', 'la', 'sol'. Il n'existe, dans l'étude
    abstraite du contrepoint, pas d'autres notes (pas de dièse ou de
    bémol, pas de note doublée à l'octave, et pas de répétition). 
    
    * l'ensemble 'ré et si', par rapport à do, possède une caractéristique
      commune, celle d'être à une distance de 1. 'mi et la' sont à une
      distance de 2 et l'ensemble sol et fa sont à une distance de 3.

Mathématiquement, l'étude du contrepoint est équivalent à l'étude de
l'ensemble modulo 7.

N'importe quelle mélodie, considérée comme un ensemble aléatoire des
mots suivants: "do ré mi fa sol la si" peut être transformé par
l'ensemble de 0 à 6.

Tout mélodie considérée comme un trait parcourant l'ensemble audible,
par exemple une portée possédant n'importe quelle clef est 

La première abstraction contrapuntique consistera à enrouler ce trait
autour d'un seul bloc de taille 7.


| "do" | "ré" | "mi" | "fa" | "sol" | "la" | "si" | "do" | "ré" | "mi" | "fa" | "sol" | "la" | "si" | "do" |
|------+------+------+------+-------+------+------+------+------+------+------+-------+------+------+------|
|    0 |    1 |    2 |    3 |     4 |    5 |    6 |    7 |    8 |    9 |   10 |    11 |   12 |   13 |   14 |
|    0 |    1 |    2 |    3 |     4 |    5 |    6 |    0 |    1 |    2 |    3 |     4 |    5 |    6 |    0 |
|    0 |   -6 |   -5 |   -4 |    -3 |   -2 |   -1 |    0 |   -6 |   -5 |   -4 |    -3 |   -2 |   -1 |    0 |


Cette vision modulaire a l'avantage de remplacer une mélodie comme
ensemble de notes, de points, par un ensemble d'intervalles, de
relations.

Mouvements
=====

1. L'axiome basique du contrepoint est le suivant:

    * chaque mélodie possède deux jumelles oscillant en parallèle à
      une distance de tierce autour d'elle.

Urmelodie
===

Dans un souci de pédantisme inexcusable, nous userons d'un vocabulaire
inutilement superfétatoire.

Une mélodie considérée comme un atome, est entouré de deux électrons
qui vibrent à même vitesse autour de lui. 

L'exemple le plus basique et triviale prend comme noyau une melodie
absurde, c'est-à-dire statique, constituée d'une seule note.

Ses électrons sont situés chacun à la distance moyenne de 2. Il
oscille dans le temps entre la distance 2 et -2.

Premier constat : tout noyau est l'électron d'une autre mélodie,
considéré comme noyau.

Imaginons une "urmelodie" dont le dessin mélodique serait -2 2 -2 2.

Son premier électron "+2 -2" est constant sur 0. Son second électron
ferait par ailleurs le dessin mélodique de "-4 4", qu'on peut traduire
par "fa sol".


Mouvements mélodique
===

Considérons maintenant uniquement le mouvement intervallique de ces
électrons. Ce qui nous intéresse effectivement en contrepoint, c'est
de trouver une mélodie dont le mouvement intervallique est *opposée* à
la mélodie originelle. Autrement dit, de trouver une mélodie qui monte
quand la première descend, et vice-versa.

Libérons nos électrons à travers l'octave. Comme, selon notre premier
principe, chaque note trouve son équivalent dans les octaves
inférieures et supérieurs, il est possible de transposer les notes
suivantes afin d'atteindre une mélodie unidirectionnelle:

-2 2. 2 devient -5. Puis -2, pour ne pas être situé au-dessus du -5,
descendra à -9. Puis le -5 à -12 etc.

Les intervalles font -3 -4.

Pour monter on inverse les intervalles : 4 3.

L'électron 2 est l'inverse de l'électron 1. C'est-à-dire qu'il descend
au rythme de -4 -3 (au lieu de -3 -4), et monte au rythme de 3 4 (au
lieu de 4 3).

La dernière étape est donc de calculer ces 2x2=4 mélodies jumelles
pour n'importe quelle urmelodie.

Un contrechant choisira entre l'électron 1 et 2 dans une quantité
différente, qui constituera sa signature.

Algorithme
===

On peut considérer toute mélodie comme une variation autour de
l'urmelodie statique, "000000..."

Les quatres melodies jumelles étant successivement

| DO |  0 |  0 |  0 |  0 |  0 |  0 |
|----+----+----+----+----+----+----|
| MI |  3 | -3 |  3 | -3 |  3 | -3 |
|    | -4 |  4 | -4 |  4 | -4 |  4 |
| LA | -3 |  3 | -3 |  3 | -3 |  3 |
|    |  4 | -4 |  4 | -4 |  4 | -4 |


Comme on peut le voir, il est simple de programmer 


```

//Prendre les intervalles d'une mélodie
mel=UrMel.differentiate.drop(1);
accs=[3,-3,4,-4];
electrons=[[2],[2],[-2],[-2]] + UrMel.first;

// générer les quatre électrons l'entourant
for i in mel.size 
    accs=accs.neg;
    for j in accs.size 
        electrons[j].put(i+1,note+acc[j])

// retrouver la melodie
electrons.do(_.integrate)

```




Conclusion
===


Voilà pour l'exposé sommaire du premier type de contrepoint.

Un certain nombre de compositeurs ont passé leur vie à explorer les
possibilités de ce jeu. De même qu'un certain nombre de savants des
plus respectables ont passé leur vie à explorer le système ptoléméien
de l'univers, tentant de placer la terre au centre de l'univers.


Le prochain chapitre aborde la question du contrepoint élargi,
incluant : la possibilité de mouvements parallèle, ainsi que la
possibilité de consonnance de distance 3.







mouvement contraire
