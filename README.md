# Sujet : Les principaux établissements d'enseignement supérieur en france 

<iframe frameborder="0" width="800" height="600" src="https://data.opendatasoft.com/map/embed/etablissements_sup_fr_sara/?&static=false&scrollWheelZoom=false"></iframe>



## 1) Requette sur les différents établissements supérieurs françcais, leur date de création ainsi que les images corespondantes

```sparql
#Etablissements supérieurs
#defaultView:ImageGrid
#defaultView:Map
SELECT ?item ?itemLabel ?image ?datecreation ?coord WHERE
{
  ?item wdt:P31 wd:Q3918.
?item wdt:P17 wd:Q142.
OPTIONAL {
?item wdt:P18 ?image. #affichier les images 
?item wdt:P571 ?datecreation.
?item wdt:P18 ?image .
?item wdt:P625 ?coord .

}

  SERVICE wikibase:label {bd:serviceParam wikibase:language "fr,en"}
}

```

<iframe frameborder="0" width="800" height="600"src="https://query.wikidata.org/embed.html#SELECT%20%3Fitem%20%3FitemLabel%20%3Fdatecreation%20%3Fimage%20%3Fcoord%20WHERE%20%7B%0A%3Fitem%20wdt%3AP31%20wd%3AQ3918.%0A%3Fitem%20wdt%3AP17%20wd%3AQ142.%0AOPTIONAL%20%7B%0A%3Fitem%20wdt%3AP571%20%3Fdatecreation.%0A%3Fitem%20wdt%3AP18%20%3Fimage%20.%0A%3Fitem%20wdt%3AP625%20%3Fcoord%20.%0A%0A%7D%0A%0A%0A%0ASERVICE%20wikibase%3Alabel%20%7B%20bd%3AserviceParam%20wikibase%3Alanguage%20%22fr%22.%20%7D%0A%7D" </iframe> 

## 2) Les types d'établissements supérieurs

<iframe frameborder="0" width="800" height="600" src="https://data.opendatasoft.com/map/embed/type_etablissement_sara/?&static=false&scrollWheelZoom=false"></iframe>

