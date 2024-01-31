Compétition qui existe depuis 1957, la Coupe d'afrique des nations a pour objectif de rassembler tout le continent africain autour d'une passion commune : le foot-ball. Créée par une initiative commune de l'Afrique du Sud, l'Egypte, Le soudan et l'Ethiopie, la première édition ne se jouera qu'avec 03 équipes, L'Afrique du Sud étant encore sous Apartheid écartée pour cause de racisme, ne voulant inclure des joueurs noirs dans l'équipe nationale.
Cependant, les années suivantes, la CAN est devenue de plus en plus inclusive et le tournoi accueil dorénavant 24 équipes qualifiées tous les 2 ans à la compétition continentale et permet de découvrir la diversité du continent.


## Sommaire : 
1. [Collecte des données](#données)
2. [Présentation des pays du continent africain](#paysSurnom)
3. [Les Buts marqués entre l'édition 1992 et l'édition 2021](#Goalscorers)
4. [Titre 4](#commentaire)
5. [Titre 5](#commentaire)


## 1. Collecte des données <a name="données"></a>

Les données utilisées pour cette analyse du football africain sont issues de sources diverses dont Wikipédia, les archives de la RSSf(source:African Nations Cup 1992 (rsssf.org)) , la chaine l'Equipe, entres autres.
J'ai fait le choix de recueillir les données sur les sélections qualifiées à partir de l'année 1992, correspondant à la première édition organisée par le Sénégal.

>Remarque : les informations issues de Wikipédia ont été croisées d'autres sources d'informations pour s'assurer de leur fiabilité. Elles ont été recueillies et formatées manuellement au format csv.
>Le traitement sur l'outil Open Refine est une étape de vérification et de validation du jeu de données créé.
>Le jeu de donnée se présente comme suit
*   

``` sparql
#defaultView:ImageGrid
SELECT DISTINCT ?paysLabel ?drapeau
WHERE {
  ?country wdt:P31/wdt:P279* wd:Q6256;  # Instance de pays 
           wdt:P30 wd:Q15;               # Localisation Afrique
           rdfs:label ?paysLabel;
           wdt:P298 ?isoCode.            # ISO code pour ne pas avoir de doublons

  OPTIONAL { ?country wdt:P41 ?drapeau. }   # Drapeau

  FILTER(LANG(?paysLabel) = "fr")     # Filter by French labels
  FILTER(?isoCode != "null")             
}
ORDER BY ?paysLabel
```
>
## 2.Les pays du continent africain <a name="pays africains"></a>
<div class="flourish-embed flourish-cards" data-src="visualisation/16598308"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


>

>
## 3.Les Buts marqués Par pays Entre l'édition 1992 et l'édition 2021 <a name="buts marqué de 1992 à 2021"></a>
[Mon texte ici]

> Story
https://public.flourish.studio/story/2162474/


...
<div style="min-height:699px"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/P1cH2/embed.js?v=3" charset="utf-8"></script><noscript><img src="https://datawrapper.dwcdn.net/P1cH2/full.png" alt="Cette carte indique le nombre de participation au tournoi de la Coupe d'Afrique des nations" /></noscript></div>

>

