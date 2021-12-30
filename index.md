## Com ha influït la renda percebuda a les últimes eleccions al Parlament de Catalunya?

El passat 14 de febrer del 2021, 2.884.845 persones (un 51,29% dels cens electoral) van exercir el seu dret a vot en les eleccions al Parlament de Catalunya. Les dades d'aquests resultats han servit per omplir múltiples articles periodístics i tertútiles de radio/televisió, sovint extraient-ne conclusions basades en sensacions i percepcions subjectives. Aquest document preten ser una nova visió d'aquests resultats, intentant sempre mantenir la perspectiva que ens donen les dades.

Per posar-ho en context, les dades electorals que analitzarem provenen del web oficial de dades electorals de la
[Generalitat de Catalunya](https://gencat.cat/eleccions/resultatsparlament2021/resultados/resumen/AUCI).

A continuació adjuntem, a mode introductori, una visualització interactiva de bloc que ens permetrà veure com es composen els resultats per cada circumscripció electoral:

<div class="flourish-embed flourish-election" data-src="visualisation/8237234"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

L'objectiu d'aquest estudi és demostrar com la renda de les persones influeïx a l'hora d'emetre el vot en unes eleccions, i com les persones perceben els discursos dels diferents partits i n'extrauen conclusions en forma de vot en funció de la seva renda bruta percebuda. 

### Resultats electorals per secció censal

Al web de la [Generalitat de Catalunya](https://gencat.cat/eleccions/resultatsparlament2021/resultados/resumen/AUCI) trobem els resultats electorals en diferents nivells de granularitat: a nivell de circumscripció, de comarca, vegueria, municipi, districte, barri o secció censal. Donat que el vot és secret, i per tant no tenim el vot emès per a cada ciutadà, per poder dur a terme aquest estudi farem servir el nivell de detall màxim en que podem conèixer el comportament electoral de la ciutadania, que és a nivell de mesa electoral, el que l'administració anomena secció censal.

A continuació presentem una visualització que ens permetrà explorar territorialment els resultats electorals obtinguts per partit i secció censal de tot Catalunya. Segons la cartografia usada del [Institut Cartogràfic de la Generalitat de Catalunya](https://www.icgc.cat/Descarregues/Cartografia-vectorial/Seccions-censals), Catalunya està formada per 5.084 seccions censals:

<div class="flourish-embed flourish-map" data-src="visualisation/8246354"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
 
* Existeixen algunes seccions censals sense informació electoral, com podreu veure en la visualització (unes 30 aprox).

### Renda Bruta i índex de Gini

Abans d'analitzar com la renda influeix a l'hora d'exercir el dret a vot, primer visualitzarem com es comporta la renda bruta en funció del territori. Igual que en el cas dels sufragis, no tenim la renda percebuda a nivell de persona, donat que la renda es publica d'una forma agregada i no individual, així doncs, per salvar aquest obstacle, analitzarem la renda bruta de les persones usant el nivell de granularitat màxim que [l'Instituto Nacional de Estadística](https://www.ine.es/dynt3/inebase/es/index.htm?padre=7132) ens permet, que són els municipis, els districtes i les seccions censals. 

Abans de veure la següent visualització, ens agradaria introduïr una ràtio anomenada [índex de Gini](https://ca.wikipedia.org/wiki/Coeficient_de_Gini), que ens permet analitzar com de desiguals són els ingressos en una mateixa unitat geogràfica i que el mateix INE ens facilita. Això permetrà al usuari comparar unitats geogràfiques amb rendes similars, però que tenen un comportament diferent en vots emesos.

Hem escollit la Renda Bruta, perquè a diferència de la Renda per Unitat de Consum o la Renda Neta (dades també disponibles en el dataset del INE), és un concepte que tothom entén i és molt senzill de comparar.

En la següent visualització podem interactuar per analitzar les seccions censals en funció de la Renda Bruta, però també en funció del índex Gini de desigualtats en els ingressos que hem comentat anteriorment:

<div class="flourish-embed flourish-map" data-src="visualisation/8246723"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

* Existeixen algunes seccions censals de les quals el INE no en disposa de la Renda Bruta (unes 65 aprox).

### Renda Bruta i Resultats Electorals

Ara sí, en aquest apartat ens diposem a fer ja l'anàlisis del comportament electoral en funció del vot emès. Disposem de les dades electorals a nivell de secció censal i també de la Renda Bruta en el mateix nivell de granularitat, de manera que podem suposar que cada una de les 5.084 seccions censals són "objectes" de les quals en volem analitzar el seu comportament. A més a més, cada una d'aquestes 5.084 "unitats", en podem saber si es comporten d'una manera molt o poc desigual a nivell de renda percebuda, gracies al índex de Gini.

En les següents visualitzacions, mitjançant scatter plots, compararem com es comporta el percentatge de vot emès a cada partit en una deteminada illa censal en funció del nivell de renda bruta d'aquella illa censal.

Farem el nostre anàlisis usant blocs de dos partits, que a priori, es dirigeixen a un mateix tipus de votant (econòmicament parlant), malgrat que ho facin des de perspectives diferents (visió catalanista vs visió unionista):

ERC i PSC. En aquest primer bloc analitzarem el comportament del dos partits més votats i que persegueixen un públic similar des d'una perspectiva de la socialdemocràcia: 

<div class="flourish-embed flourish-scatter" data-src="visualisation/8247441" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
<div class="flourish-embed flourish-scatter" data-src="visualisation/8247395" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

JXCAT i CS. En aquest segon bloc contrastarem dos partits que fins fa poc compartien espai en el Parlament Europeu, dins del bloc liberal:

<div class="flourish-embed flourish-scatter" data-src="visualisation/8247464" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
<div class="flourish-embed flourish-scatter" data-src="visualisation/8247488" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

CUP i ECP. En aquest tercer bloc, compararem els dos partits que s'autodefineixen com a més ancorats a l'esquerra:

<div class="flourish-embed flourish-scatter" data-src="visualisation/8247508" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
<div class="flourish-embed flourish-scatter" data-src="visualisation/8247529" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

PDCAT i PP. En aquest quart bloc, compararem dos partits que han tingut discursos similars durant la campanya en els seus plantejaments econòmics: 

<div class="flourish-embed flourish-scatter" data-src="visualisation/8246909" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
<div class="flourish-embed flourish-scatter" data-src="visualisation/8247352" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

En Blanc i VOX. Finalment, incorporarem un últim bloc on compararem un partit populista de nova creació, amb els vots en blanc emesos:

<div class="flourish-embed flourish-scatter" data-src="visualisation/8247579" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
<div class="flourish-embed flourish-scatter" data-src="visualisation/8247563" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Conclusions

Després d'analitzar en l'últim apartat el comportament de les seccions censals en funció de la renda bruta i el percentatge de vot, observem que:

* D'entrada, podem afirmar que existeix una relació entre percentatge de vot emès a un partit i augment del valor de la renda bruta. En són exemples molt clars el cas del PP, JXCAT i el PDCAT. A més renda bruta més augmenta el percentatge de vot. En el cas del PP veiem una anomàlia a la circumscripció de Girona, que s'explicaria per altres variables no econòmiques.

* Observem també l'efecte contrari, partits com PSC o ECP dismunueixen el seu percentatge de vot a mesura que augmenta la renda bruta. 

* Observem anomalies que s'haurien d'explicar amb altres variables. És el cas de la CUP, en que veiem com augmenta el vot en funció de la renda bruta malgrat fer un discurs ancorat a l'esquerra. Aquí probablement afegint la variable de nivell cultural/d'estudis ens permetria extraure més conclucions per explicar-ne el comportament.

* Finalment observem com el comportament del vot en blanc i el d'un partit populista es comporta d'una forma molt similar, cosa que ens pot fer pensar que això respon en certa a manera a un objectiu similar "vot de descontentament o de càstig".

Segurament el lector sigui capaç d'extraure moltes més conclusions i més més acurades que les meves, i probablement usant l'Índex de Gini es podria afinar molt més el comportament de les seccions censals. Deixem per més endavant l'ampliació d'aquest estudi introductori en que la gran dificultat tècnica ha estat unificar dades de tres fonts diferents i recodificar els índexs de les seccions censals codificades per l'ICGC i les seccions censals codificades segons l'INE, ja que malgrat que la granularitat és la mateixa, la codificació requereix d'una série de transformacions que deixem recollides en el nostra repositori de GitHub.


