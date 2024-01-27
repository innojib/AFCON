# AFCON
Compétition qui existe depuis 1957, la Coupe d'afrique des nations a pour objectif de rassembler tout le continent africain autour d'une passioncommune : le foot-ball. 
[Mon texte ici] 
...
<div style="min-height:699px"><script type="text/javascript" defer src="https://datawrapper.dwcdn.net/P1cH2/embed.js?v=3" charset="utf-8"></script><noscript><img src="https://datawrapper.dwcdn.net/P1cH2/full.png" alt="Cette carte indique le nombre de participation au tournoi de la Coupe d'Afrique des nations" /></noscript></div>

>


 


## Sommaire : 
1. [Collecte des données](#données)
2. [Titre 2.](#localisationCarte)
3. [Titre 3](#Commentaire)
4. [Titre 4](#commentaire)
5. [Titre 5](#commentaire)


## 1. Collecte des données <a name="données"></a>

Les données utilisées pour cette analyse du football africain sont issues de sources diverses dont Wikipédia, les archives de l'Urssf, la chaine l'équipe.
>Remarque : les informations issues de Wikipédia ont été croisées d'utres sources d'informations pour s'assurer de leur fiabilité.  

``` sparql
#Mon code sparql
SELECT DISTINCT ?pays ?paysLabel
WHERE {
  ?pays wdt:P31 wd:Q9430. #océans
  SERVICE wikibase:label {bd:serviceParam wikibase:language "fr" }
}
```

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
