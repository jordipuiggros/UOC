## Com ha influït la renda a les eleccions al Parlament de Catalunya?

El passat 14/02/2021 es van celebrar eleccions al Parlament de Catalunya. Les dades d'aquests resultats han servit per omplir múltiples articles periodístics i tertútiles de radio/televisió, sovint d'una manera subjectiva. Aquest article preten ser una nova visió d'aquests resultats, sempre intentant mantenir una perspectiva del rigor que ens dona la dada.

Per posar-ho en context, les dades electorals que analitzarem provenen del web oficial de dades electorals de la
[Generalitat de Catalunya](https://gencat.cat/eleccions/resultatsparlament2021/resultados/resumen/AUCI)

A continuació adjuntem, a mode introductori, una visualització interactiva de bloc que ens permetrà veure com es composen els resultats per circumscripció electoral:

<div class="flourish-embed flourish-election" data-src="visualisation/8237234"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

L'objectiu d'aquest estudi és demostrar com la renda de les persones condiciona a l'hora d'emetre el vot en unes eleccions, i com les persones perceben els discursos dels diferents partits en funció de la seva renda bruta. 

### Resultats electorals per secció censal

Al web de la [Generalitat de Catalunya](https://gencat.cat/eleccions/resultatsparlament2021/resultados/resumen/AUCI) trobem els resultats electorals en diferents nivells de granularitat: a nivell de circumscripció, de comarca, vegueria, municipi, districte, barri o secció censal. Donat que el vot és secret, i per tant no tenim el vot emès per a cada ciutadà, per poder dur a terme aquet estudi farem servir el nivell de detall màxim en que podem conèixer el comportament electoral de la ciutadania, que és a nivell de mesa electoral, per entendre'ns, a nivell d'urna comptabilitzada (el que l'administració anomena secció censal).

A continuació presentem una visualització que ens permetrà explorar territorialment els resultats electorals obtinguts per partit i secció censal de tot Catalunya. Segons la cartografia usada del [Institut Cartogràfic de la Generalitat de Catalunya](https://www.icgc.cat/Descarregues/Cartografia-vectorial/Seccions-censals), Catalunya està formada per 5.084 seccions censals:

<div class="flourish-embed flourish-map" data-src="visualisation/8246354"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
 
* Existeixen algunes seccions censals sense informació electoral per part de la GenCat, com podreu comprobar a la visualització (unes 30 aprox).

### Renda Bruta i índex Gini

Abans d'analitzar com la renda influeix a l'hora d'exercir el dret a vot, primer visualitzarem com es comporta la renda en funció del territori. Igual que en el cas dels sufragis, no tenim la renda percebuda a nivell de persona, donat que la renda es publica d'una forma agregada i no individual, així doncs, per salvar aquest obstacle, analitzarem la renda bruta de les persones usant el nivell de granularitat màxim que [l'Instituto Nacional de Estadística](https://www.ine.es/dynt3/inebase/es/index.htm?padre=7132) ens permet, que són els municipis, els districtes i les seccions censals. 

Abans de veure la següent visualització, ens agradaria introduïr una ràtio anomenada [índex de Gini](https://ca.wikipedia.org/wiki/Coeficient_de_Gini), que ens permet analitzar les desigualtats en els ingressos d'una mateixa unitat geogràfica i que el mateix INE ens facilita. 

En la següent visualització podem interactuar per analitzar les seccions censals en funció de la Renda Bruta, però també en funció del índex Gini de desigualtats en els ingressos que hem comentat:

<div class="flourish-embed flourish-map" data-src="visualisation/8246723"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

* Existeixen algunes ( unes 65 aprox) seccions censals de les quals el INE no en disposa de la Renda Bruta.

### Renda Bruta i Resultats Electorals

Ara sí, en aquest apartat ens diposem a fer ja l'anàlisis del comportament electoral en funció del vot emès. Disposem de les dades electorals a nivell de secció censal i també de la Renda Bruta en el mateix nivell de granularitat, de manera que podem suposar ("imaginar") que cada una de les 5.084 seccions censals són "objectes" de les quals en volem analitzar-ne el seu comportament. A és a més, cada una d'aquestes 5.084 "unitats", en podem saber si es comporten d'una manera molt o poc desigual a nivell de renda percebuda, gracies al índex de Gini.

Farem el nostre anàlisis usant blocs de dos partits, que a priori (suposició subjectiva), es dirigeixen a un mateix públic objectiu (econòmicament parlant), malgrat que ho facin des de perspectives diferents (visió catalanista vs visió unionista):

ERC  i PSC. En aquest primer bloc analitzarem el comportament del dos partits més votats i que persegueixen un públic similar des d'una perspectiva de la socialdemocràcia, econòmicament parlant: 

<div class="flourish-embed flourish-scatter" data-src="visualisation/8247441" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
<div class="flourish-embed flourish-scatter" data-src="visualisation/8247395" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

JXCAT i CS. En aquest segon bloc contrastarem dos partits que fins fa poc compartien espai en el parlament europeu, dins del bloc liberal:

<div class="flourish-embed flourish-scatter" data-src="visualisation/8247464" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
<div class="flourish-embed flourish-scatter" data-src="visualisation/8247488" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

CUP i ECP. En aquest tercer bloc, compararem els dos partits que s'autodefineixen més d'esquerres:

<div class="flourish-embed flourish-scatter" data-src="visualisation/8247508" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
<div class="flourish-embed flourish-scatter" data-src="visualisation/8247529" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

PDCAT i PP. En aquest quart bloc, compararem dos partits que han tingut discursos similars durant la campanya en els seus plantejaments econòmics: 

<div class="flourish-embed flourish-scatter" data-src="visualisation/8246909" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
<div class="flourish-embed flourish-scatter" data-src="visualisation/8247352" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

En Blanc i VOX. Finalment, incorporarem un últim bloc on compararem un partit populista de nova creació, amb els vots en blanc emesos:

<div class="flourish-embed flourish-scatter" data-src="visualisation/8247579" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>
<div class="flourish-embed flourish-scatter" data-src="visualisation/8247563" style="width:48%; display: inline-block; vertical-align: top;"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

### Conclusions



