# parlons-velo-analyzer
Analyse des réponses du questionnaire de la FUB

```
# Generate Markdown files
python top_streets.py

# Test markdown content
docker run --rm -v $(pwd):/root/docs:ro -p 80:80 -t -i fstab/grip grip /root/docs/README.md 0.0.0.0:80
```

Les résultats sont dans le repertoire topstreets

### Contributeurs
* [Bruno Adelé](https://twitter.com/jesuislibre) - [#JeSuisUnDesDeux](https://twitter.com/search?q=%23JeSuisUnDesDeux)
### Résultats par département

Sur l'ensemble du téritoire, il y a eu 81447 réponses dont 52091 réponses avec une rue citée (63%)

| Departement | Nb réponses | Nb réponses avec rue | Nb points noirs |
|-------------|-------------|----------------------|-----------------|
|<a href='topstreets/01-AIN/README.md'>01-AIN</a>|393|240(61%)|<img src="img/bar_14.gif" />&nbsp;103|
|<a href='topstreets/02-AISNE/README.md'>02-AISNE</a>|176|72(40%)|<img src="img/bar_5.gif" />&nbsp;40|
|<a href='topstreets/03-ALLIER/README.md'>03-ALLIER</a>|127|44(34%)|<img src="img/bar_4.gif" />&nbsp;33|
|<a href='topstreets/04-ALPES HAUTE PROVENCE/README.md'>04-ALPES HAUTE PROVENCE</a>|201|89(44%)|<img src="img/bar_5.gif" />&nbsp;36|
|<a href='topstreets/05-HAUTES ALPES/README.md'>05-HAUTES ALPES</a>|368|138(37%)|<img src="img/bar_8.gif" />&nbsp;59|
|<a href='topstreets/06-ALPES MARITIMES/README.md'>06-ALPES MARITIMES</a>|1072|506(47%)|<img src="img/bar_26.gif" />&nbsp;187|
|<a href='topstreets/07-ARDECHE/README.md'>07-ARDECHE</a>|229|97(42%)|<img src="img/bar_6.gif" />&nbsp;48|
|<a href='topstreets/08-ARDENNES/README.md'>08-ARDENNES</a>|123|104(84%)|<img src="img/bar_5.gif" />&nbsp;36|
|<a href='topstreets/09-ARIEGE/README.md'>09-ARIEGE</a>|76|33(43%)|<img src="img/bar_2.gif" />&nbsp;18|
|<a href='topstreets/10-AUBE/README.md'>10-AUBE</a>|277|106(38%)|<img src="img/bar_7.gif" />&nbsp;54|
|<a href='topstreets/11-AUDE/README.md'>11-AUDE</a>|241|71(29%)|<img src="img/bar_5.gif" />&nbsp;41|
|<a href='topstreets/12-AVEYRON/README.md'>12-AVEYRON</a>|194|92(47%)|<img src="img/bar_4.gif" />&nbsp;35|
|<a href='topstreets/13-BOUCHES RHONE/README.md'>13-BOUCHES RHONE</a>|3547|2332(65%)|<img src="img/bar_64.gif" />&nbsp;454|
|<a href='topstreets/14-CALVADOS/README.md'>14-CALVADOS</a>|1002|471(47%)|<img src="img/bar_23.gif" />&nbsp;167|
|<a href='topstreets/15-CANTAL/README.md'>15-CANTAL</a>|131|102(77%)|<img src="img/bar_4.gif" />&nbsp;29|
|<a href='topstreets/16-CHARENTE/README.md'>16-CHARENTE</a>|194|71(36%)|<img src="img/bar_4.gif" />&nbsp;34|
|<a href='topstreets/17-CHARENTE MARITIME/README.md'>17-CHARENTE MARITIME</a>|1108|601(54%)|<img src="img/bar_27.gif" />&nbsp;194|
|<a href='topstreets/18-CHER/README.md'>18-CHER</a>|456|262(57%)|<img src="img/bar_12.gif" />&nbsp;92|
|<a href='topstreets/19-CORREZE/README.md'>19-CORREZE</a>|124|38(30%)|<img src="img/bar_3.gif" />&nbsp;26|
|<a href='topstreets/21-COTE OR/README.md'>21-COTE OR</a>|1053|641(60%)|<img src="img/bar_24.gif" />&nbsp;177|
|<a href='topstreets/22-COTES ARMOR/README.md'>22-COTES ARMOR</a>|268|128(47%)|<img src="img/bar_11.gif" />&nbsp;83|
|<a href='topstreets/23-CREUSE/README.md'>23-CREUSE</a>|2|0(0%)|<img src="img/bar_0.gif" />&nbsp;0|
|<a href='topstreets/24-DORDOGNE/README.md'>24-DORDOGNE</a>|60|26(43%)|<img src="img/bar_2.gif" />&nbsp;19|
|<a href='topstreets/25-DOUBS/README.md'>25-DOUBS</a>|696|392(56%)|<img src="img/bar_16.gif" />&nbsp;118|
|<a href='topstreets/26-DROME/README.md'>26-DROME</a>|1029|502(48%)|<img src="img/bar_23.gif" />&nbsp;167|
|<a href='topstreets/27-EURE/README.md'>27-EURE</a>|110|33(30%)|<img src="img/bar_3.gif" />&nbsp;25|
|<a href='topstreets/28-EURE ET LOIR/README.md'>28-EURE ET LOIR</a>|69|40(57%)|<img src="img/bar_3.gif" />&nbsp;26|
|<a href='topstreets/29-FINISTERE/README.md'>29-FINISTERE</a>|1284|797(62%)|<img src="img/bar_44.gif" />&nbsp;315|
|<a href='topstreets/2A-CORSE SUD/README.md'>2A-CORSE SUD</a>|222|56(25%)|<img src="img/bar_3.gif" />&nbsp;23|
|<a href='topstreets/2B-HAUTE CORSE/README.md'>2B-HAUTE CORSE</a>|33|5(15%)|<img src="img/bar_0.gif" />&nbsp;5|
|<a href='topstreets/30-GARD/README.md'>30-GARD</a>|462|195(42%)|<img src="img/bar_9.gif" />&nbsp;68|
|<a href='topstreets/31-HAUTE GARONNE/README.md'>31-HAUTE GARONNE</a>|4526|2934(64%)|<img src="img/bar_96.gif" />&nbsp;685|
|<a href='topstreets/32-GERS/README.md'>32-GERS</a>|70|66(94%)|<img src="img/bar_4.gif" />&nbsp;32|
|<a href='topstreets/33-GIRONDE/README.md'>33-GIRONDE</a>|2184|1001(45%)|<img src="img/bar_51.gif" />&nbsp;364|
|<a href='topstreets/34-HERAULT/README.md'>34-HERAULT</a>|2262|961(42%)|<img src="img/bar_41.gif" />&nbsp;297|
|<a href='topstreets/35-ILLE ET VILAINE/README.md'>35-ILLE ET VILAINE</a>|2130|1614(75%)|<img src="img/bar_50.gif" />&nbsp;355|
|<a href='topstreets/36-INDRE/README.md'>36-INDRE</a>|224|97(43%)|<img src="img/bar_5.gif" />&nbsp;41|
|<a href='topstreets/37-INDRE ET LOIRE/README.md'>37-INDRE ET LOIRE</a>|1206|857(71%)|<img src="img/bar_30.gif" />&nbsp;218|
|<a href='topstreets/38-ISERE/README.md'>38-ISERE</a>|3533|1965(55%)|<img src="img/bar_70.gif" />&nbsp;500|
|<a href='topstreets/39-JURA/README.md'>39-JURA</a>|280|139(49%)|<img src="img/bar_7.gif" />&nbsp;56|
|<a href='topstreets/40-LANDES/README.md'>40-LANDES</a>|103|29(28%)|<img src="img/bar_3.gif" />&nbsp;22|
|<a href='topstreets/41-LOIR ET CHER/README.md'>41-LOIR ET CHER</a>|115|59(51%)|<img src="img/bar_4.gif" />&nbsp;33|
|<a href='topstreets/42-LOIRE/README.md'>42-LOIRE</a>|960|522(54%)|<img src="img/bar_20.gif" />&nbsp;143|
|<a href='topstreets/43-HAUTE LOIRE/README.md'>43-HAUTE LOIRE</a>|212|21(9%)|<img src="img/bar_1.gif" />&nbsp;13|
|<a href='topstreets/44-LOIRE ATLANTIQUE/README.md'>44-LOIRE ATLANTIQUE</a>|3223|1803(55%)|<img src="img/bar_83.gif" />&nbsp;589|
|<a href='topstreets/45-LOIRET/README.md'>45-LOIRET</a>|1026|452(44%)|<img src="img/bar_20.gif" />&nbsp;144|
|<a href='topstreets/46-LOT/README.md'>46-LOT</a>|24|3(12%)|<img src="img/bar_0.gif" />&nbsp;3|
|<a href='topstreets/47-LOT ET GARONNE/README.md'>47-LOT ET GARONNE</a>|130|26(20%)|<img src="img/bar_2.gif" />&nbsp;17|
|<a href='topstreets/48-LOZERE/README.md'>48-LOZERE</a>|5|0(0%)|<img src="img/bar_0.gif" />&nbsp;0|
|<a href='topstreets/49-MAINE ET LOIRE/README.md'>49-MAINE ET LOIRE</a>|1497|835(55%)|<img src="img/bar_32.gif" />&nbsp;230|
|<a href='topstreets/50-MANCHE/README.md'>50-MANCHE</a>|369|191(51%)|<img src="img/bar_11.gif" />&nbsp;78|
|<a href='topstreets/51-MARNE/README.md'>51-MARNE</a>|709|580(81%)|<img src="img/bar_17.gif" />&nbsp;123|
|<a href='topstreets/52-HAUTE MARNE/README.md'>52-HAUTE MARNE</a>|149|82(55%)|<img src="img/bar_4.gif" />&nbsp;31|
|<a href='topstreets/53-MAYENNE/README.md'>53-MAYENNE</a>|353|182(51%)|<img src="img/bar_10.gif" />&nbsp;72|
|<a href='topstreets/54-MEURTHE ET MOSELLE/README.md'>54-MEURTHE ET MOSELLE</a>|837|598(71%)|<img src="img/bar_24.gif" />&nbsp;173|
|<a href='topstreets/55-MEUSE/README.md'>55-MEUSE</a>|10|4(40%)|<img src="img/bar_0.gif" />&nbsp;3|
|<a href='topstreets/56-MORBIHAN/README.md'>56-MORBIHAN</a>|725|336(46%)|<img src="img/bar_24.gif" />&nbsp;173|
|<a href='topstreets/57-MOSELLE/README.md'>57-MOSELLE</a>|447|274(61%)|<img src="img/bar_16.gif" />&nbsp;120|
|<a href='topstreets/58-NIEVRE/README.md'>58-NIEVRE</a>|249|130(52%)|<img src="img/bar_7.gif" />&nbsp;51|
|<a href='topstreets/59-NORD/README.md'>59-NORD</a>|3204|1837(57%)|<img src="img/bar_77.gif" />&nbsp;549|
|<a href='topstreets/60-OISE/README.md'>60-OISE</a>|387|170(43%)|<img src="img/bar_15.gif" />&nbsp;109|
|<a href='topstreets/61-ORNE/README.md'>61-ORNE</a>|168|41(24%)|<img src="img/bar_3.gif" />&nbsp;28|
|<a href='topstreets/62-PAS CALAIS/README.md'>62-PAS CALAIS</a>|530|162(30%)|<img src="img/bar_13.gif" />&nbsp;94|
|<a href='topstreets/63-PUY DOME/README.md'>63-PUY DOME</a>|1213|794(65%)|<img src="img/bar_24.gif" />&nbsp;175|
|<a href='topstreets/64-PYRENEES ATLANTIQUES/README.md'>64-PYRENEES ATLANTIQUES</a>|679|278(40%)|<img src="img/bar_16.gif" />&nbsp;114|
|<a href='topstreets/65-HAUTES PYRENEES/README.md'>65-HAUTES PYRENEES</a>|130|37(28%)|<img src="img/bar_3.gif" />&nbsp;24|
|<a href='topstreets/66-PYRENEES ORIENTALES/README.md'>66-PYRENEES ORIENTALES</a>|339|83(24%)|<img src="img/bar_6.gif" />&nbsp;49|
|<a href='topstreets/67-BAS RHIN/README.md'>67-BAS RHIN</a>|2702|2957(109%)|<img src="img/bar_60.gif" />&nbsp;428|
|<a href='topstreets/68-HAUT RHIN/README.md'>68-HAUT RHIN</a>|498|386(77%)|<img src="img/bar_20.gif" />&nbsp;145|
|<a href='topstreets/69-RHONE/README.md'>69-RHONE</a>|5486|4538(82%)|<img src="img/bar_98.gif" />&nbsp;696|
|<a href='topstreets/70-HAUTE SAONE/README.md'>70-HAUTE SAONE</a>|16|4(25%)|<img src="img/bar_0.gif" />&nbsp;4|
|<a href='topstreets/71-SAONE ET LOIRE/README.md'>71-SAONE ET LOIRE</a>|418|172(41%)|<img src="img/bar_11.gif" />&nbsp;85|
|<a href='topstreets/72-SARTHE/README.md'>72-SARTHE</a>|802|522(65%)|<img src="img/bar_21.gif" />&nbsp;152|
|<a href='topstreets/73-SAVOIE/README.md'>73-SAVOIE</a>|775|372(48%)|<img src="img/bar_17.gif" />&nbsp;123|
|<a href='topstreets/74-HAUTE SAVOIE/README.md'>74-HAUTE SAVOIE</a>|1180|620(52%)|<img src="img/bar_27.gif" />&nbsp;198|
|<a href='topstreets/75-PARIS/README.md'>75-PARIS</a>|6224|7225(116%)|<img src="img/bar_100.gif" />&nbsp;709|
|<a href='topstreets/76-SEINE MARITIME/README.md'>76-SEINE MARITIME</a>|1223|678(55%)|<img src="img/bar_31.gif" />&nbsp;222|
|<a href='topstreets/77-SEINE ET MARNE/README.md'>77-SEINE ET MARNE</a>|644|383(59%)|<img src="img/bar_23.gif" />&nbsp;165|
|<a href='topstreets/78-YVELINES/README.md'>78-YVELINES</a>|1990|1106(55%)|<img src="img/bar_58.gif" />&nbsp;414|
|<a href='topstreets/79-DEUX SEVRES/README.md'>79-DEUX SEVRES</a>|282|201(71%)|<img src="img/bar_8.gif" />&nbsp;62|
|<a href='topstreets/80-SOMME/README.md'>80-SOMME</a>|765|514(67%)|<img src="img/bar_16.gif" />&nbsp;120|
|<a href='topstreets/81-TARN/README.md'>81-TARN</a>|173|80(46%)|<img src="img/bar_7.gif" />&nbsp;52|
|<a href='topstreets/82-TARN ET GARONNE/README.md'>82-TARN ET GARONNE</a>|48|17(35%)|<img src="img/bar_2.gif" />&nbsp;15|
|<a href='topstreets/83-VAR/README.md'>83-VAR</a>|512|262(51%)|<img src="img/bar_11.gif" />&nbsp;83|
|<a href='topstreets/84-VAUCLUSE/README.md'>84-VAUCLUSE</a>|403|173(42%)|<img src="img/bar_8.gif" />&nbsp;61|
|<a href='topstreets/85-VENDEE/README.md'>85-VENDEE</a>|294|148(50%)|<img src="img/bar_11.gif" />&nbsp;79|
|<a href='topstreets/86-VIENNE/README.md'>86-VIENNE</a>|328|140(42%)|<img src="img/bar_9.gif" />&nbsp;65|
|<a href='topstreets/87-HAUTE VIENNE/README.md'>87-HAUTE VIENNE</a>|241|140(58%)|<img src="img/bar_11.gif" />&nbsp;79|
|<a href='topstreets/88-VOSGES/README.md'>88-VOSGES</a>|79|59(74%)|<img src="img/bar_5.gif" />&nbsp;39|
|<a href='topstreets/89-YONNE/README.md'>89-YONNE</a>|91|33(36%)|<img src="img/bar_3.gif" />&nbsp;26|
|<a href='topstreets/90-TERRITOIRE BELFORT/README.md'>90-TERRITOIRE BELFORT</a>|173|111(64%)|<img src="img/bar_6.gif" />&nbsp;48|
|<a href='topstreets/91-ESSONNE/README.md'>91-ESSONNE</a>|717|380(52%)|<img src="img/bar_29.gif" />&nbsp;208|
|<a href='topstreets/92-HAUTS SEINE/README.md'>92-HAUTS SEINE</a>|2767|1675(60%)|<img src="img/bar_79.gif" />&nbsp;562|
|<a href='topstreets/93-SEINE SAINT DENIS/README.md'>93-SEINE SAINT DENIS</a>|1061|690(65%)|<img src="img/bar_30.gif" />&nbsp;217|
|<a href='topstreets/94-VAL MARNE/README.md'>94-VAL MARNE</a>|1302|761(58%)|<img src="img/bar_43.gif" />&nbsp;310|
|<a href='topstreets/95-VAL OISE/README.md'>95-VAL OISE</a>|368|170(46%)|<img src="img/bar_13.gif" />&nbsp;93|
|<a href='topstreets/974-REUNION/README.md'>974-REUNION</a>|350|127(36%)|<img src="img/bar_7.gif" />&nbsp;55|
| **Total** |81447|52091(63%)|13935|
