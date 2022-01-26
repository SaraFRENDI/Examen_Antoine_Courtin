# Sujet : Les principaux établissements d'enseignement supérieur en france 

<iframe style="width: 90vw; height: 80vh; border: none;" src="https://query.wikidata.org/embed.html#%23Etablissements%20sup%C3%A9rieurs%0A%23defaultView%3AImageGrid%0A%23defaultView%3AMap%0ASELECT%20%3Fitem%20%3FitemLabel%20%3Fimage%20%3Fdatecreation%20%3Fcoord%20WHERE%0A%7B%0A%20%20%3Fitem%20wdt%3AP31%20wd%3AQ3918.%0A%3Fitem%20wdt%3AP17%20wd%3AQ142.%0AOPTIONAL%20%7B%0A%3Fitem%20wdt%3AP18%20%3Fimage.%20%23affichier%20les%20images%20%0A%3Fitem%20wdt%3AP571%20%3Fdatecreation.%0A%3Fitem%20wdt%3AP18%20%3Fimage%20.%0A%3Fitem%20wdt%3AP625%20%3Fcoord%20.%0A%0A%7D%0A%0A%20%20SERVICE%20wikibase%3Alabel%20%7Bbd%3AserviceParam%20wikibase%3Alanguage%20%22fr%2Cen%22%7D%0A%7D" referrerpolicy="origin" sandbox="allow-scripts allow-same-origin allow-popups" ></iframe>



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

<iframe style="width: 30vw; height: 100vh; border: none;" src="https://query.wikidata.org/embed.html#SELECT%20%3Fitem%20%3FitemLabel%20%3Fdatecreation%20%3Fimage%20%3Fcoord%20WHERE%20%7B%0A%3Fitem%20wdt%3AP31%20wd%3AQ3918.%0A%3Fitem%20wdt%3AP17%20wd%3AQ142.%0AOPTIONAL%20%7B%0A%3Fitem%20wdt%3AP571%20%3Fdatecreation.%0A%3Fitem%20wdt%3AP18%20%3Fimage%20.%0A%3Fitem%20wdt%3AP625%20%3Fcoord%20.%0A%0A%7D%0A%0A%0A%0ASERVICE%20wikibase%3Alabel%20%7B%20bd%3AserviceParam%20wikibase%3Alanguage%20%22fr%22.%20%7D%0A%7D" referrerpolicy="origin" sandbox="allow-scripts allow-same-origin allow-popups" ></iframe> 

## 2) Les établissements français Publics et privés 

