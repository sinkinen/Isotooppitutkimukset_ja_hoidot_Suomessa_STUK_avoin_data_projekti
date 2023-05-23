# Isotooppitutkimukset ja hoidot Suomessa STUK avoimen datan analyysi :fire: :fire: :fire: 

## Yleistä
Tämä repo sisältää jupyter notebookin (python) (data_analyysi_STUK_aineisto.ipynb), jolla STUK:n avointa data-aineistoa voi tarkastella.
Notebook on ohjelmoitu CSC:n tarjoamassa [CSC notebooks pilviympäristössä](https://notebooks.rahtiapp.fi/welcome).

STUK:n data on saavatilla osoitteesta:
https://www.stuk.fi/avoin-data/isotooppitutkimukset-ja-hoidot-suomessa

## Käyttö
1. Lataa tämä repository koneelle
2. Kirjaudu [CSC notebook palveluun](https://notebooks.rahtiapp.fi/welcome) (vaatii Haka- tai csc-tunnuksen)
3. Kirjautumisen jälkeen valitse Jupyter Machine Learning ympäristö
4. Siirrä reposta lataamasi tiedostot juureen (drag and drop)
6. Lataa [STUK avoin excel aineisto](https://www.stuk.fi/avoin-data/isotooppitutkimukset-ja-hoidot-suomessa) ja siirrä juureen
7. Lataa vielä avoin [geodata sairaanhoitopiireistä:  'healthDistrictsEPSG4326.geojson'](https://github.com/VuokkoH/koronavirus-avoindata) ja siirrä juureen
8. Avaa notebook `data_analyysi_STUK_aineisto.ipynb` ja pääset tarkastelemaan aineistoa

## Muuta 
Suosittelen käyttämään CSC-notebook ympäristö datan tarkasteluun, mutta jos lokaalisti notebookkia haluaa tarkastella  niin alla on määritelty tärkeimmät kirjastot, jotka on vaadittu että kirjaston saa toimimaan: 
`pandas, numpy, geopandas, matplotlib, geojson, plotly, openpyxl`

_Requirements.txt_ tiedostossa on kaikki CSC Jupyter Machine Learning ympäristöön asennetut paketit.

Jos käytät notebookkia suoraan CSC:n notebooks ympäristössä, niin alkuun pitää asentaa seuraavat ohjelmistot erikseen:
```
%pip install openpyxl
%pip install plotly
%pip install chart_studio
%pip install geojson
%pip install geopandas
%pip install moviepy
%pip install -U kaleido
```

## Yhteystiedot
19.5.2023 Satu Inkinen, etunimi.sukunimi [@]hus.fi
