>Compétition qui existe depuis 1957, la Coupe d'afrique des nations a pour objectif de rassembler tout le continent africain autour d'une passion commune : le foot-ball. Créée à l'intiative de l'Afrique du Sud, l'Egypte, X et Y, la première édition...

## Sommaire : 
1. [Collecte des données](#données)
2. [Les pays du continent africain](#paysSurnom)
3. [Titre 3](#Commentaire)
4. [Titre 4](#commentaire)
5. [Titre 5](#commentaire)


## 1. Collecte des données <a name="données"></a>

Les données utilisées pour cette analyse du football africain sont issues de sources diverses dont Wikipédia, les archives de la RSSf, la chaine l'Equipe, entres autres.
J'ai fait le choix de recueillir les données sur les sélections qualifiées à partir de l'année 1992, correspondant à la première édition organisée par le Sénégal.

>Remarque : les informations issues de Wikipédia ont été croisées d'utres sources d'informations pour s'assurer de leur fiabilité dont .  

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
<iframe src='https://flo.uri.sh/visualisation/16598308/embed' title='Interactive or visual content' class='flourish-embed-iframe' frameborder='0' scrolling='no' style='width:100%;height:600px;' sandbox='allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/16598308/?utm_source=embed&utm_campaign=visualisation/16598308' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>


>

>
## 3.Les Buts marqués Par pays Entre l'édition 1992 et l'édition 2021 <a name="buts marqué de 1992 à 2021"></a>
[Mon texte ici]

<div class="flourish-embed" data-src="story/2162474"><script src="https://public.flourish.studio/resources/embed.js"></script></div>




...
<div style="min-height:699px"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/P1cH2/embed.js?v=3" charset="utf-8"></script><noscript><img src="https://datawrapper.dwcdn.net/P1cH2/full.png" alt="Cette carte indique le nombre de participation au tournoi de la Coupe d'Afrique des nations" /></noscript></div>

>




[Mon texte ici]

```sparql

#Titre
SELECT DISTINCT  ?o ?oLabel ?a?image
{
  ?o wdt:P wd:Q. #COMMENTAIRE
  ?o wdt:P ?a. #MON COMMENTAIRE
  OPTIONAL { .} 
  SERVICE wikibase:label {bd:serviceParam wikibase:language "fr" }
}
```
[Mon texte ici]

|     colonne1     | colonne  (en km²)|
|:----------------:|:----------------:|
|  Objet           |      14 056 000  |
|  Objet           |      76 174 000  |
|   Objet          |      20 327 000  |
|  Objet           |     106 460 000  |
|    Objet         |     161 760 000  |
|    Objet         |     361 260 000  |

> *[Mon texte ici]
>
>> [Mon texte ici]


[Mon texte ici]

## Titre <a name="Titrage"></a>
[Mon texte ici]

## 3.Titre <a name="titre2"></a>

[Mon texte ici]

## 4. Titre <a name="titre"></a>

![lambda](https://upload.wikimedia.org/wikipediap.jpg "Image de l’observation au microscope de microplastiques")
[Mon texte ici]


[Mon texte ici]

-----------------------------------------------------------------------------
[Mon texte ici]

## 5. Titre: objet de ma partie<a name="objet"></a>

<div class="flourish-embed flourish-cards" data-src="visualisation/12790"><script src="https://public.flourish.cvbnstudio/resources/embed.js"></script></div>

[Mon texte ici]

## 6. Titre
 


> [Mon texte ici]
>
>>[Mon texte ici]

## Conclusion : <a name="conclusion"></a>

[Mon texte ici
- anaphainetai o helios
- dura lex sed lex
- ]
