Bestaande werkafspraken en praktijk opnemen in het model
========================================================

De volgende voorstellen betreffen het opnemen van bestaande werkafspraken en
praktijk in het model.

Opnemen definitie ‘maaiveld’
----------------------------

**Gerelateerde issue(s)**
[\#156](https://github.com/Geonovum/IMGeo2018/issues/156)  

**Huidige situatie** In de BGT catalogus komt de term ‘maaiveld’ voor zonder
definitie of nadere toelichting.

**Nieuwe situatie** Het voorstel is om in de BGT catalogus in het hoofdstuk
Ontwerpprincipes de volgende definitie van ‘maaiveld’ op te nemen:

*“Het oppervlak van de vaste aarde, daar waar de aarde niet bedekt is met
water.*  
*Het maaiveld vormt de grens tussen de ondergrond en de bovengrond. (bron:
BRO).”*

**Onderbouwing** *Maaiveld komt regelmatig als term terug in de BGT, maar wordt
nergens uitgelegd. Op deze manier wordt expliciet gemaakt wat in BGT context
onder het maaiveld wordt verstaan.*

**Impact** De impact van deze wijziging is 'zeer laag':

-   *Verplicht/niet verplicht:* Dit betreft een wijziging in het verplichte deel
    van IMGeo.

-   *Software:* er is geen aanpassing van de software nodig.

-   *Dataconversie:* er is geen dataconversie nodig.

-   *Inwinning:* naar verwachting hoeven er geen gegevens door bronhouders
    ingewonnen te worden. Het betreft een verandering van topologische regels op
    bestaande gegevens.

-   *Samenhang basisregistraties:* er is geen impact voor andere
    basisregistraties voorzien; IMGeo past met dit voorstel aan op de definitie
    van de Basisregistratie Ondergrond (BRO).

**Implementatie-advies** n.v.t.

Opnemen regels voor indeling van particuliere terreinen
-------------------------------------------------------

**Gerelateerde
Github-issue(s)** [\#9](https://github.com/Geonovum/IMGeo2018/issues/9)

**Huidige situatie** In de BGT gegevenscatalogus paragraaf 2.4 Dekking staat het
volgende:

>   De BGT wordt landsdekkend beheerd voor het grondgebied van Nederland binnen
>   de gemeentegrenzen. Daartoe behoren ook industriële complexen, zoals
>   Schiphol, de Hoogovens en Europoort.

**Nieuwe situatie** Aan deze paragraaf wordt de volgende tekst toegevoegd:

>   “Dit geldt voor alle particuliere terreinen waar deze informatie voorziet in
>   een betere of zelfs noodzakelijke, wettelijk geregelde dienstverlening door
>   bronhouders en gebruikers. Denk daarbij bijv. aan de inzet van hulpdiensten
>   maar ook de dienstverlening door netbeheerders dat deels een wettelijke taak
>   is.”

**Onderbouwing** Met deze toevoeging is ook het mogelijk om particuliere en
bedrijventerreinen nader in te delen. Dit ten behoeve van de inzet van
hulpdiensten en de dienstverlening door netbeheerds.

**Impact** De impact van deze wijziging wordt ingeschat op relatief ‘*laag*’:

-   *Verplicht/niet verplicht:* Dit betreft een wijziging in het verplichte deel
    van IMGeo.

-   *Software:* er is geen aanpassing van de software nodig.

-   *Dataconversie:* er is geen dataconversie nodig.

-   *Inwinning:* naar verwachting hoeven er geen tot weinig extra gegevens door
    bronhouders ingewonnen te worden. Veelal zullen dergelijke gegevens van
    grotere particuliere en bedrijventerreinen, en grote industriële complexen
    al beschikbaar zijn.

-   *Samenhang basisregistraties:* er is geen impact voor andere
    basisregistraties voorzien.

**Implementatie-advies** Implementatie-afspraken/termijnen dienen nader te
worden bepaald t.a.v. wanneer bronhouders de gegevens voor dergelijk complexen
en terreinen kunnen hebben aangeleverd.

Opnemen regels voor objecten buiten Nederland
---------------------------------------------

**Gerelateerde
Github-issue(s)** [\#9](https://github.com/Geonovum/IMGeo2018/issues/9)

**Huidige situatie** In de BGT gegevenscatalogus paragraaf 2.4 Dekking staat het
volgende:

>   De BGT wordt landsdekkend beheerd voor het grondgebied van Nederland binnen
>   de gemeentegrenzen.

**Nieuwe situatie** Aan deze paragraaf wordt de volgende tekst toegevoegd:

>   Ten behoeve van beheer door bronhouders kunnen objecten die deels buiten de
>   landsgrens liggen in hun geheel worden opgenomen in de BGT. Wanneer
>   daarbuiten meer informatie benodigd is, het gehele object ligt dus buiten
>   Nederland, wordt deze informatie niet als BGT inhoud beschouwd.

**Onderbouwing** Met deze verduidelijking hoeven bronhouders niet actief op de
landgrens, en worden objecten die geheel buiten Nederland liggen (‘eilandjes’)
uitgesloten in de dekking van de BGT. Dit is vergelijkbaar met het principe van
bronhoudergrenzen: bronhouders knippen niet actief op de gemeentegrens, maar op
de grens waar objectkenmerken veranderen.

**Impact** De impact van deze wijziging wordt ingeschat op relatief ‘*laag*’:

-   *Verplicht/niet verplicht:* Dit betreft een wijziging in het verplichte deel
    van IMGeo.

-   *Software:* er is geen aanpassing van de software nodig.

-   *Dataconversie:* er is geen dataconversie nodig.

-   *Inwinning:* naar verwachting hoeven er geen extra gegevens door bronhouders
    ingewonnen te worden. Bronhouders dienen te controleren of er objecten
    geheel buiten Nederland zijn aangeleverd aan de LV-BGT.

-   *Samenhang basisregistraties:* er is geen impact voor andere
    basisregistraties voorzien.

**Implementatie-advies** Implementatie-afspraken/termijnen dienen nader te
worden bepaald t.a.v. wanneer bronhouders de gegevens hebben nagelopen.

Opnemen regels voor plaatsing en draaiing van labels
----------------------------------------------------

**Gerelateerde Github-issue(s)**
[\#3](https://github.com/Geonovum/IMGeo2018/issues/3)

**Huidige situatie** In hoofdstuk 5 van de BGT catalogus worden de volgende
eisen gesteld aan de plaatsing en draaiing van een Nummeraanduidingreeks bij een
Pand of tekst van een OpenbareRuimteLabel

>   De visualisatie van een openbare ruimtenaam vindt plaats door de coördinaten
>   van het midden (centrum) van de tekst vast te leggen, evenals de rotatie van
>   de tekst ten opzichte van de normale tekstrichting. De normale tekstrichting
>   is van links naar rechts oftewel, in een kaartbeeld met de noordrichting aan
>   de bovenzijde, van west naar oost. Voor namen van wegen, waterlopen en
>   spoorbanen dient de rotatiehoek te worden vastgelegd, zodat de naam met de
>   richting van de weg, waterloop of spoorbaan mee kan worden gevisualiseerd.
>   De naam wordt geautomatiseerd uit de BAG overgenomen.

>   De visualisatie van een nummeraanduidingreeks vindt plaats door de
>   coördinaten van het midden (centrum) van de tekst vast te leggen, alsmede de
>   rotatie van de tekst ten opzichte van de normale tekstrichting. Het
>   coördinatenpunt van de nummeraanduidingreeks wordt circa 4 meter vanaf de
>   voorgevel (‘straatzijde’) binnen het pand geplaatst.

**Nieuwe situatie** Het voorstel is om aan de regels voor het attribuut
rotatiehoek van huisnummers de volgende extra regels op te nemen:

>   De visualisatie van een nummeraanduidingreeks vindt plaats door de
>   coördinaten van het midden (centrum) van de tekst vast te leggen, alsmede de
>   rotatie van de tekst ten opzichte van de normale tekstrichting. **De normale
>   tekstrichting is van links naar rechts oftewel, in een kaartbeeld met de
>   noordrichting aan de bovenzijde, van west naar oost. Voor huisnummers dient
>   de rotatiehoek te worden vastgelegd, zodat het nummer haaks of eenwijdig aan
>   de voorgevel mee kan worden gevisualiseerd, waarbij de kleinste rotatie
>   wordt gekozen ten opzichte van de normale tekstrichting.** Het
>   coördinatenpunt van de nummeraanduidingreeks wordt circa 4 meter vanaf de
>   voorgevel (‘straatzijde’) binnen het pand geplaatst. **Elke
>   nummeraanduidingreeks van een Pand wordt eenmaal afgebeeld.**

Bij de regels voor het attribuut ‘rotatiehoek’ in hoofdstuk 8 Attributen wordt
het volgende toevoegd:

>   Voor de rotatiehoek van een label van een BGT\|IMGeo object gelden de
>   volgende eigenschappen en eisen:

>   Eenheid : booggraad; één booggraad is een 360ste deel van een cirkelomtrek

>   Oriëntering : met de klok mee (positief) t.o.v. normale tekstrichting
>   (horizontaal = 0 graden; voor een kaart die noord georiënteerd is.)

>   Decimale precisie : 1 (= 1 cijfer achter de komma, ofwel 1/10 booggraad)

>   Bereik (min/max) : [-90, +90], waarbij [270,360] niet gelijk is aan [-90,0].

**Onderbouwing** Met dit voorstel wordt duidelijkheid gegeven hoe huisnummers
gepresenteerd dienen te worden in de BGT. In de praktijk zullen huisnummers dus
een draaiing hebben tussen -45 en +45 graden.

**Impact** De impact van deze wijziging wordt ingeschat op relatief ‘*laag*’:

-   *Verplicht/niet verplicht:* Dit betreft een wijziging in het verplichte deel
    van IMGeo.

-   *Software:* er is geen aanpassing van de software nodig, immers bestaande
    werkafspraak.

-   *Dataconversie:* er is geen dataconversie nodig.

-   *Inwinning:* huisnummers moeten gecontroleerd worden op juiste plaatsing en
    draaiing. Dit kan grotendeels geautomatiseerd met software.

-   *Samenhang basisregistraties:* er is geen impact voor andere
    basisregistraties voorzien.

**Implementatie-advies** Implementatie-afspraken/termijnen dienen nader te
worden bepaald t.a.v. wanneer de gegevens zijn gecontroleerd. Juiste
rotatiehoeken zijn met software automatisch af te leiden uit de geometrie van
panden. Eventueel kwaliteitsdashboard inzetten om ‘te veel’ gedraaide
huisnummers te localiseren.

Opnemen regels voor panden boven water
--------------------------------------

**Gerelateerde
Github-issue(s):** [\#61](https://github.com/Geonovum/IMGeo2018/issues/61) 

**Huidige situatie** In de BGT wordt in principe waterdeel opgenomen met
relatieve hoogte 0. Voor panden wordt de maaiveldgeometrie opgenomen wat
impliceert dat een pand ook een relatieve hoogte 0 heeft. Onduidelijkheid
bestaat hoe een pand boven water moet worden afgebakend, en welke relatieve
hoogte deze moet krijgen.

**Nieuwe situatie** Het voorstel is om a*an* de afbakeningsregels voor Pand het
volgende toe te voegen:

*“Voor panden die in hun geheel boven water liggen, bijvoorbeeld een
brugwachtershuis dat aan een brug hangt, geldt dat dit pand in de BGT voorkomt
met een relatieve hoogte (rh) van één hoger dan het water waar het zich boven
bevindt.”*

**Onderbouwing** Met deze wijziging worden regels toegevoegd aan de afbakening
van panden boven water, waardoor afbakening door bronhouders gemakkelijker en
uniformer wordt.

**Impact** De impact van dit voorstel wordt ingeschat op ‘**laag**‘:

-   *Verplicht/niet verplicht:* dit betreft een wijziging in het verplichte deel
    van IMGeo.

-   *Software:* er is geen aanpassing van de software nodig.

-   *Dataconversie:* bestaande gegevens hoeven niet worden geconverteerd.

-   *Inwinning:* bronhouders dienen de huidige populatie van panden
    boven/naast/onder water na te lopen om vast te stellen of deze objecten aan
    de nieuwe afbakeningsregels voldoen.

-   *Samenhang basisregistraties:* er is geen impact voor andere
    basisregistraties voorzien; de eisen t.a.v. maaiveldniveau en topologie zijn
    BGT-eigen principes en raken als zodanig niet aan de BAG.

**Implementatie-advies** Implementatie-afspraken/termijnen dienen nader te
worden bepaald t.a.v. wanneer bronhouders hun bestaande gegevens hebben
gecontroleerd en aangepast conform de nieuwe afbakeningsregels.

Verduidelijken regels voor gemaal, sluisdeur en stuw
----------------------------------------------------

**Gerelateerde
Github-issue(s)** [\#37](https://github.com/Geonovum/IMGeo2018/issues/37), [\#72](https://github.com/Geonovum/IMGeo2018/issues/72) 

**Gerelateerde voorstellen** Uitbreiden van typen bij FunctioneelGebied en
Hernoemen ‘sluis’ naar ‘sluisdeur’.

**Huidige situatie** In de BGT catalogus worden de volgende afbakeningsregels
voor gemaal, sluis en stuw gegeven:

>   Tot deze typen kunstwerkdelen behoren die objecten die niet tot een ander
>   BGT-objecttype behoren. Dit betekent in de regel dat bij een gemaal de
>   bakken waar het water door wordt geleid tot dat object behoren. Een pand
>   waarin de pompen staan, vormt als pand inhoud van de BGT.

>   Bij een sluiscomplex behoren alleen de sluisdeuren tot BGT-inhoud en bij een
>   stuw uitsluitend de klep of schuif.  
>   Sluisdeuren worden in gesloten stand in het BGT-bestand opgenomen.

**Nieuwe situatie** Het voorstel is om de volgende afbakeningsregels voor
gemaal, sluis en stuw in de BGT gegevenscatalogus op te nemen:

>   Bij een gemaal worden de eventueel aanwezige bakken waar het water door
>   wordt geleid als gemaaldeel opgenomen in de BGT. 

>   De eventuele overige objecten zoals muren, kademuren, panden en
>   overbruggingen vormen als zodanig inhoud van de BGT. Over al deze relevante
>   BGT-objecten is het mogelijk om het, niet verplichte, IMGeo functioneel
>   gebied gemaalcomplex op te nemen.  
>   Nadere typeringen van gemaal wordt beschouwd als beheerinformatie en niet
>   opgenomen in de BGT.

>   Bij een sluis behoren alleen de sluisdeuren, in gesloten stand, tot
>   BGT-inhoud.

>   De eventuele overige objecten zoals muren, kademuren, panden en
>   overbruggingen vormen als zodanig inhoud van de BGT. Over al deze relevante
>   BGT-objecten is het mogelijk om het, niet verplichte, IMGeo functioneel
>   gebied sluiscomplex op te nemen.  
>   Nadere typeringen van sluis wordt beschouwd als beheerinformatie en niet
>   opgenomen in de BGT.

>   Bij een stuw behoort uitsluitend de klep of schuif waarover het water kan
>   stromen tot BGT-inhoud.  
>   De eventueel aanwezige bakken waar het water door wordt geleid, worden als
>   stuwdeel opgenomen in de BGT. Eventuele overige objecten zoals muren,
>   kademuren, panden en overbruggingen vormen als zodanig inhoud van de BGT.
>   Over al deze relevante BGT-objecten is het mogelijk om het, niet verplichte,
>   IMGeo functioneel gebied stuwcomplex op te nemen.  
>   Nadere typeringen van stuw wordt beschouwd als beheerinformatie en niet
>   opgenomen in de BGT.

**Onderbouwing** Met deze afbakeningsregels sluit de BGT beter aan op de
afbakeningsregels van de waterwereld (IMWA).

**Impact** De impact van dit voorstel wordt ingeschat op ‘laag tot zeer laag’:

-   *Verplicht/niet verplicht:* dit betreft een wijziging in het verplichte deel
    van IMGeo.

-   *Software:* er is geen aanpassing van de software nodig.

-   *Dataconversie:* bestaande gegevens hoeven niet worden geconverteerd.

-   *Inwinning:* bronhouders dienen de huidige populatie van objecten van het
    type gemaal , sluis(deur) en stuw na te lopen om vast te stellen of deze
    objecten aan de nieuwe afbakeningsregels voldoen.

-   *Samenhang basisregistraties:* er is geen impact voor andere
    basisregistraties voorzien.

**Implementatie-advies** Implementatie-afspraken/termijnen dienen nader te
worden bepaald t.a.v. wanneer bronhouders hun bestaande gegevens hebben
gecontroleerd en aangepast conform de nieuwe afbakeningsregels.

Opnemen afbakeningsregels voor tunneldeel en duiker
---------------------------------------------------

**Gerelateerde
Github-issue(s)** [\#62](https://github.com/Geonovum/IMGeo2018/issues/62)

**Huidige situatie** In het objectenhandboek wordt bij
[tunneldeel](http://imgeo.geostandaarden.nl/def/imgeo-object/tunneldeel/tunneldeel)
en
[duiker](http://imgeo.geostandaarden.nl/def/imgeo-object/kunstwerkdeel/duiker-niet-bgt)
toegelicht dat deze altijd onder maaiveld liggen en dus een relatieve hoogte
kleiner dan 0 hebben. In het informatiemodel wordt dit nergens expliciet
vastgelegd.

**Nieuwe situatie** In de afbakeningsregels voor tunneldeel en duiker wordt de
regel van ‘onder maaiveld’ toegevoegd.

In de BGT catalogus bij tunneldeel:

>   10.10.3 Relatieve hoogte

>   **Tunneldelen hebben altijd een relatieve hoogte lager dan 0.**

>   In tunneldelen ligt of liggen altijd één of meer wegdelen. Deze wegdelen
>   bezitten dezelfde aanduiding voor relatieve hoogte als het tunneldeel waarin
>   zij liggen.

In de IMGeo catalogus bij duiker:

>   9.9 Kunstwerkdeel

>   **Duikers hebben altijd een relatieve hoogte lager dan 0.**

>   IMGeo voegt enkele optionele kunstwerken toe. Dit zijn allemaal
>   vlakobjecten.

**Onderbouwing** Met deze afbakeningsregel sluit het informatiemodel aan bij het
objectenhandboek.

**Impact** De impact van dit voorstel wordt ingeschat op ‘**laag tot zeer
laag**’:

-   *Verplicht/niet verplicht:* dit betreft een wijziging in het verplichte deel
    van IMGeo.

-   *Software:* er is geen aanpassing van de software nodig. Software van
    bronhouder en LV-BGT kan technisch gezien alle relatieve hoogten aan bij
    tunneldeel en duiker.

-   *Dataconversie:* bestaande gegevens hoeven niet worden geconverteerd.

-   *Inwinning:* bronhouders dienen de huidige populatie van objecten tunneldeel
    en duiker na te lopen om vast te stellen of deze objecten aan deze
    afbakeningsregels voldoen.

-   *Samenhang basisregistraties:* er is geen impact voor andere
    basisregistraties voorzien.

**Implementatie-advies** n.v.t.

Schrappen minimale afmetingen voor afbakening BGT Scheiding
-----------------------------------------------------------

**Gerelateerde
Github-issue(s):** [\#28](https://github.com/Geonovum/IMGeo2018/issues/28) 

**Huidige situatie** In de BGT moet een object Scheiding worden opgenomen en in
IMGeo mag optioneel een OverigeScheiding worden opgenomen.

Veelal moet een object als Scheiding in de BGT worden opgenomen als deze aan
minimale afmetingen voldoet, bijvoorbeeld:

>   Scheidingen van het type hek die een minimale lengte van 10m en een minimale
>   hoogte van 1m hebben, worden vastgelegd.

of

>   Scheidingen van het type muur, met een minimale lengte van 1m en met een
>   minimale breedte van 30cm worden opgenomen.

In het optionele deel van IMGeo mogen ook objecten die kleiner zijn worden
opgenomen als OverigeScheiding:

>   In de BGT worden scheidingen alleen vastgelegd als ze bepaalde minimum
>   afmetingen hebben, die per type scheiding verschillen (zie deel I). In IMGeo
>   kunnen scheidingen, die kleiner dan het BGT minimum zijn, worden opgenomen
>   als objecttype ‘overige scheiding’. Deze kent dezelfde typen scheiding.

**Nieuwe situatie** Het voorstel is om de minimale afmetingen voor het opnemen
van een scheiding als BGT Scheiding te schrappen.

In hoofdstuk 10 van de BGT catalogus wordt bij de afbakeningsregels voor
Scheiding het volgende aangepast:

>   Scheidingen worden als lijnobject vastgelegd als de breedte kleiner is dan
>   30cm.

>   Bij scheidingen breder dan 30cm moet de buitenomtrek waar het object de
>   grond raakt worden ingewonnen en vastgelegd als vlakgeometrie.

>   Een scheiding wordt vastgelegd waar het object de ondergrond raakt. In de
>   scheidingen worden onderbrekingen van \<1m genegeerd. Doorgangen worden
>   gezien als integraal onderdeel van de scheiding.

>   **Scheidingen van het type hek die een minimale lengte van 10m en een
>   minimale hoogte van 1m hebben, worden vastgelegd.**

>   Scheidingen van de typen kademuur en walbescherming worden opgenomen aan de
>   bovenzijde aan de waterkant. Kademuren breder dan 30cm worden ingewonnen als
>   vlakobject; de omtrek van het object aan de bovenzijde wordt dan vastgelegd.

>   **Scheidingen van het type muur, met een minimale lengte van 1m en met een
>   minimale breedte van 30cm worden opgenomen.** Een muur smaller dan 30cm
>   wordt als lijnobject vastgelegd, een bredere muur als vlakobject. **Muren
>   met een minimale hoogte van 50cm worden vastgelegd.**

In terreinen met een fysiek voorkomen ‘erf’ worden alleen die scheidingen
opgenomen die direct aan de straatzijde zijn gelegen.

In hoofdstuk 9 van de IMGeo catalogus wordt bij de afbakeningsregels voor
OverigeScheiding het volgende aangepast:

>   IMGeo kent naast de BGT typen scheiding ook draadraster en faunaraster.
>   Bovendien zijn heggen/hagen in IMGeo vertegenwoordigd, zij het niet als
>   scheiding maar als vegetatieobject. Draadraster en faunaraster worden als
>   lijnobject opgenomen.

>   **In de BGT worden scheidingen alleen vastgelegd als ze bepaalde minimum
>   afmetingen hebben, die per type scheiding verschillen (zie deel I). In IMGeo
>   kunnen scheidingen, die kleiner dan het BGT minimum zijn, worden opgenomen
>   als objecttype ‘overige scheiding’. Deze kent dezelfde typen scheiding.** De
>   populatie van Overige Scheiding bestaat uit: **· Scheidingen die niet
>   voldoen aan de BGT minimummaat;** · scheidingen in terrein met fysiek
>   voorkomen ‘erf’ die niet aan de straatzijde gelegen zijn. IMGeo muren en
>   kademuren van breder dan 30 cm worden als vlakobject vastgelegd; smallere
>   worden als lijnobject vastgelegd.

De minimale afmetingen (breedte) voor het opnemen van een scheiding als lijn of
vlak wordt niet gewijzigd.

**Onderbouwing** Uit analyse blijkt dat in de BGT (peildatum: 13 januari 2018)
570.691 scheidingen van type hek van 371 verschillende bronhouders bestaan die
kleiner zijn dan 10 meter. 92 bronhouders hebben een OverigeScheiding van het
type hek opgevoerd die groter is dan 10 meter. 

Ofwel de afbakeningsregels in de BGT catalogus en IMGeo catalogus worden door
bronhouders niet opgevolgd.

Onderscheid tussen twee objecten Scheiding en OverigScheiding is wel nodig voor
bijvoorbeeld het opnemen van draadraster en faunaraster en scheidingen tussen
percelen.

**Impact** De impact van dit voorstel wordt ingeschat op relatief ‘*gemiddeld*’.

-   *Verplicht/niet verplicht:* Dit betreft een wijziging in het verplichte deel
    van IMGeo.

-   *Software:* er is geen aanpassing van de software nodig.

-   *Dataconversie:* bestaande gegevens dienen geconverteerd te worden, waarbij
    voor OverigScheiding nieuwe objecten Scheiding met nieuwe identificaties
    ontstaan.

-   *Inwinning:* naar verwachting hoeven er geen gegevens door bronhouders
    ingewonnen te worden.

-   *Samenhang basisregistraties:* er is geen impact op de samenhang met andere
    basisregistraties voorzien.

**Implementatie-advies** Het implementatieadvies is als volgt:

1.  Stel een werkafspraak op dat bronhouders scheidingen omzetten die nu als
    OverigeScheiding zijn opgenomen, maar met deze regel als Scheiding moeten
    worden opgenomen in de BGT.

2.  Onderzoek daarbij of deze conversie via een eenmalige centrale conversie in
    LV-BGT of BRAVO mogelijk is, anders via regulier mutatieproces door
    bronhouders. Gebruik om de voortgang te monitoren het kwalititeitsdashboard.

Schrappen inwinregel voor plantvakken kleiner dan 5m2
-----------------------------------------------------

**Gerelateerde
Github-issue(s):** [\#198](https://github.com/Geonovum/IMGeo2018/issues/198) 

**Huidige situatie** In de afbakeningsregels bij Wegdeel in de BGT catalogus
wordt gesteld dat

>   Uitsparingen in wegdelen, meestal van het type voetpad, voor stedelijk groen
>   worden niet afzonderlijk geregistreerd indien \<5 m2 . Het wegdeel wordt
>   daarbij geacht door te lopen.

In IMGeo wordt de mogelijkheid geboden om deze kleine plantvakken op te nemen:

>   In de BGT worden uitsparingen in wegdelen voor stedelijk groen niet apart
>   ingewonnen indien \< 5 m2. In IMGeo kunnen deze worden opgenomen als
>   ‘begroeid terreindeel groenvoorziening’.

**Nieuwe situatie** Het voorstel is om de inwinregel voor kleine plantvakken te
schrappen. Bovenstaande zinsnedes worden verwijderd uit het informatiemodel.

**Onderbouwing** Uit analyse blijkt dat in de BGT (peildatum: 22 maart 2018)
445.253 begroeid terreindelen met fysiek-voorkomen ‘groenvoorziening’ van 424
verschillende bronhouders bestaan die kleiner zijn dan 5 m2.

Bronhouders nemen nu dus massaal kleine plantvakken op in de BGT,
hoogstwaarschijnlijk voor groenbeheer. Het vasthouden aan deze inwinregel voor
kleine plantvakken lijkt dus niet zinvol.

**Impact** De impact van dit voorstel wordt ingeschat op ‘**laag tot zeer
laag**’:

-   *Verplicht/niet verplicht:* dit betreft een wijziging in het verplichte deel
    van IMGeo.

-   *Software:* er is geen aanpassing van de software nodig.

-   *Dataconversie:* bestaande gegevens hoeven niet worden geconverteerd.

-   *Inwinning:* bronhouders hoeven naar verwachting geen extra gegevens in te
    winnen.

-   *Samenhang basisregistraties:* er is geen impact voor andere
    basisregistraties voorzien.

**Implementatie-advies** n.v.t.

Aanpassen definities van rijbanen en fietspad bij Wegdeel
---------------------------------------------------------

**Gerelateerde issue(s)**
[\#11](https://github.com/Geonovum/IMGeo2018/issues/11)  

**Huidige situatie** In de BGT zijn de volgende classificaties en definities
voor Wegdelen opgenomen:

>   rijbaan autosnelweg: Wegdeel dat onderdeel is van een weg uitsluitend
>   bestemd voor snelverkeer en met gescheiden rijbanen en ongelijkvloerse
>   kruisingen, daartoe aangeduid met het betreffende verkeersbord. (bron: BGT)

>   rijbaan autoweg: Wegdeel dat onderdeel is van een weg uitsluitend bestemd
>   voor snelverkeer, daartoe aangeduid met het betreffende verkeersbord. (bron:
>   BGT) rijbaan regionale weg: Wegdeel dat onderdeel is van een weg die een
>   verbinding vormt tussen bewoonde oorden of tussen wijken binnen een dorp of
>   stad. (bron: BGT)

>   rijbaan regionale weg: Wegdeel dat onderdeel is van een weg die een
>   verbinding vormt tussen bewoonde oorden of tussen wijken binnen een dorp of
>   stad. (bron: BGT)

>   fietspad: Weg uitsluitend bestemd voor fietsers en/of bromfietsers en
>   daartoe aangeduid met een blauw bord met daarop een wit rijwiel, of een
>   blauw of zwart bord met daarop de tekst “FIETSPAD” of “RIJWIELPAD”. (bron:
>   CROW)

**Nieuwe situatie** Het voorstel is om de volgende definities van classificaties
van een Wegdeel aan te scherpen:

>   rijbaan autosnelweg: Wegdeel dat onderdeel is van een weg uitsluitend
>   bestemd voor snelverkeer en met gescheiden rijbanen en ongelijkvloerse
>   kruisingen, daartoe aangeduid met het betreffende verkeersbord **G01**.
>   (bron: BGT)

>   rijbaan autoweg: Wegdeel dat onderdeel is van een weg uitsluitend bestemd
>   voor snelverkeer, daartoe aangeduid met het betreffende verkeersbord
>   **G03**. (bron: BGT)

>   rijbaan regionale weg: Wegdeel dat onderdeel is van een weg die een
>   verbinding vormt tussen bewoonde oorden of tussen wijken binnen een dorp of
>   stad **waarbij er een, meestal fysieke, scheiding is tussen langzaam verkeer
>   en snelverkeer.** (bron: BGT+CROW)

>   fietspad: Weg **of strook van een weg** uitsluitend bestemd voor fietsers
>   en/of bromfietsers en daartoe aangeduid met een blauw bord met daarop een
>   wit rijwiel **(bord G11 of G12a)**, een blauw of zwart bord met daarop de
>   tekst “FIETSPAD” of “RIJWIELPAD” **(bord G13)**, **of een wit rijwielsymbool
>   op een strook oranjekleurige verharding.** (bron: CROW)

**Onderbouwing** Met deze wijziging sluiten de definities voor rijbaan in de BGT
beter aan op definities de verkeerskundige wereld, en de BRT. Met deze wijziging
kan een fietsstrook (oranjekleurige strook verharding met een fietssymbool) ook
als fietspad worden afgebakend. Fietssuggestiestroken (zonder fietssymbool)
vallen buiten de definitie; fietssuggestiestroken hebben geen wettelijke status.

**Impact** De impact van dit voorstel wordt ingeschat op relatief 'laag':

-   Verplicht/niet verplicht: Dit betreft een wijziging in het verplichte deel
    van IMGeo.

-   Software: er is geen aanpassing van de software nodig.

-   Dataconversie: bestaande gegevens hoeven niet worden geconverteerd.

-   Inwinning: bronhouders dienen de bestaande wegdelen na te lopen om vast te
    stellen of deze aan de nieuwe definities voldoen.

-   Samenhang basisregistraties: er is geen impact voor andere basisregistraties
    voorzien; IMGeo past met dit voorstel aan op de andere registraties en
    systematieken.

**Implementatie-advies** Implementatie-afspraken/termijnen dienen nader te
worden bepaald t.a.v. wanneer bronhouders hun bestaande gegevens hebben
gecontroleerd en aangepast conform de nieuwe definities.

Aanpassen definitie sluis(deur)
-------------------------------

**Gerelateerde
Github-issue(s)** [\#72](https://github.com/Geonovum/IMGeo2018/issues/72)

**Gerelateerde voorstel(len)** Afbakening sluiscomplexen en Hernoemen sluis naar
sluisdeur

**Huidige situatie** In IMGeo komt het bgt-type ‘sluis’ bij een Kunstwerdeel
voor met de volgende definitie:

>   sluis: Een kunstmatige, beweegbare waterkering die de verbinding tussen twee
>   wateren kan afsluiten of openstellen en daartoe van deuren of schuiven is
>   voorzien. (bron: BGT)

**Nieuwe situatie** Het voorstel is om met het hernoemen van ‘sluis’ naar
‘sluisdeur’ de definitie als volgt aan te passen:

>   sluis**deur** = Het beweegbare deel van een kunstmatige waterkering die de
>   verbinding tussen twee wateren kan afsluiten of openstellen en daartoe van
>   deuren of schuiven is voorzien. (bron: BGT)

**Onderbouwing** In de afbakeningsregels voor sluis staat het volgende in de BGT
gegevenscatalogus:

>   Bij een sluiscomplex behoren alleen de sluisdeuren tot BGT-inhoud...

Ofwel: in de huidige BGT wordt met sluis bedoelt sluisdeur en niet een
sluiscomplex.

**Impact** De impact van dit voorstel wordt ingeschat op relatief 'laag':

-   Verplicht/niet verplicht: Dit betreft een wijziging in het verplichte deel
    van IMGeo.

-   Software: er is geen aanpassing van de software nodig.

-   Dataconversie: bestaande gegevens hoeven niet worden geconverteerd.

-   Inwinning: bronhouders dienen de bestaande wegdelen na te lopen om vast te
    stellen of deze aan de nieuwe definities voldoen.

-   Samenhang basisregistraties: er is geen impact voor andere basisregistraties
    voorzien; IMGeo past met dit voorstel aan op de andere registraties en
    systematieken.

**Implementatie-advies**

Aanpassen definitie bunker
--------------------------

**Gerelateerde Github-issue(s)**
[\#183](https://github.com/Geonovum/IMGeo2018/issues/183)

**Huidige situatie** In IMGeo komt het plus-type ‘bunker’ bij een OverigBouwwerk
voor met de volgende definitie:

>   *bunker:* Een bunker is een militair verdedigingswerk dat een zekere mate
>   van bescherming biedt tegen beschietingen en bombardementen.

**Nieuwe situatie** Het voorstel is om de definitie van ‘bunker’ als volgt aan
te passen:

>   *bunker:* Een bunker is een **van oorsprong** militair verdedigingswerk dat
>   een zekere mate van bescherming biedt tegen beschietingen en bombardementen.

**Onderbouwing** Met de huidige definitie zou verwarring kunnen ontstaan dat
alleen de bunkers die in gebruik zijn als militair verdedingswerk mogen worden
opgenomen in IMGeo.

**Impact** De impact van dit voorstel wordt ingeschat op relatief 'laag':

-   Verplicht/niet verplicht: Dit betreft een wijziging in het optionele deel
    van IMGeo.

-   Software: er is geen aanpassing van de software nodig.

-   Dataconversie: bestaande gegevens hoeven niet worden geconverteerd.

-   Inwinning: bronhouders hoeven naar verwachting geen extra gegevens in te
    winnen.

-   Samenhang basisregistraties: er is geen impact voor andere basisregistraties
    voorzien.

**Implementatie-advies** n.v.t.

Aanpassen definitie nauwkeurigheid bij Plaatsbepalingspunt
----------------------------------------------------------

**Gerelateerde Github-issue(s)**
[\#114](https://github.com/Geonovum/IMGeo2018/issues/114)

**Huidige situatie** In de BGT catalogus wordt volgende definitie voor het
attribuut ‘nauwkeurigheid’ van een Plaatsbepalingspunt gegeven.

>   nauwkeurigheid: Gerealiseerde geometrische nauwkeurigheid van **de geometrie
>   van het object ten opzichte van de werkelijkheid**, uitgedrukt in
>   centimeters.

**Nieuwe situatie** Het voorstel is om de definitie van ‘nauwkeurigheid’ als
volgt aan te passen:

nauwkeurigheid: Gerealiseerde geometrische nauwkeurigheid van **het punt als het
resultaat van het inwinnings- en verwerkingsproces**, uitgedrukt in centimeters.

**Onderbouwing** De geometrische nauwkeurigheid van de plaatsbepalingspunten
moeten worden geregistreerd als de zogenaamde absolute nauwkeurigheid. Het is
niet juist om hiervoor relatieve precisie toe te passen.

**Impact** De impact van dit voorstel wordt ingeschat op relatief 'laag':

-   Verplicht/niet verplicht: Dit betreft een wijziging in het optionele deel
    van IMGeo.

-   Software: er is geen aanpassing van de software nodig.

-   Dataconversie: bestaande gegevens hoeven niet worden geconverteerd.

-   Inwinning: bronhouders hoeven naar verwachting geen extra gegevens in te
    winnen.

-   Samenhang basisregistraties: er is geen impact voor andere basisregistraties
    voorzien.

**Implementatie-advies** n.v.t.

Aanpassen definitie put(deksel) bij Put
---------------------------------------

**Gerelateerde Github-issue(s)**
[\#92](https://github.com/Geonovum/IMGeo2018/issues/92)

**Huidige situatie** In de IMGeo komen o.a. de volgende classificaties met
definities van Put voor.

brandkraan / -put: Op de drinkwaterleiding aangesloten kraan, of een put voor
het plaatsen van een brandkraan, op of nabij de openbare weg, voor
brandbestrijding.

drainageput: Put welke toegang geeft naar een poreuze of geperforeerde
buisleiding, aangebracht onder de grond om de afwatering van de grond te
verbeteren.

gasput: Put met afsluitkraan ten behoeve van het ondergrondse leidingenstelsel
voor gastransport.

inspectie- / rioolput: Put die toegang geeft tot een (riool)leiding.

kolk: Op het riool aangesloten voorziening voor de opvang van hemel- en
afvalwater afkomstig van erop aangesloten oppervlakken.

waterleidingput: Put met afsluitkraan ten behoeve van het ondergrondse
leidingenstelsel voor watertransport.

**Nieuwe situatie** Het voorstel is om in deze definities zodanig aan te passen
dat het de deksel van de put betreft:

>   brandkraan / -put: Op de drinkwaterleiding aangesloten kraan, of **deksel
>   van** een put voor het plaatsen van een brandkraan, op of nabij de openbare
>   weg, voor brandbestrijding. (bron: CROW)

>   drainageput: Put**deksel** welke toegang geeft naar een poreuze of
>   geperforeerde buisleiding, aangebracht onder de grond om de afwatering van
>   de grond te verbeteren.

>   gasput: **Deksel van** een put met afsluitkraan ten behoeve van het
>   ondergrondse leidingenstelsel voor gastransport.

>   inspectie- / rioolput: **Deksel van een constructie** die toegang geeft tot
>   een riool**stelsel**.

>   kolk: **Deksel van een ingegraven bak** voor de opvang **en afvoer van
>   neerslag** afkomstig van erop aangesloten oppervlakken. (bron: CROW)

>   waterleidingput: **Deksel van een put** met afsluitkraan ten behoeve van het
>   ondergrondse leidingenstelsel voor watertransport.

**Onderbouwing** De huidige definities van deze putten lijken betrekking te
hebben op de gehele put terwijl IMGeo in principe alleen het deksel opneemt,
niet het onderliggende object. Dit conflicteert met de regels/definities die
RIONED hanteert bij deze objecten. De nieuwe definities lossen dit conflict op.

**Impact** De impact van dit voorstel wordt ingeschat op relatief 'laag':

-   Verplicht/niet verplicht: Dit betreft een wijziging in het optionele deel
    van IMGeo.

-   Software: er is geen aanpassing van de software nodig.

-   Dataconversie: bestaande gegevens hoeven niet worden geconverteerd.

-   Inwinning: bronhouders hoeven naar verwachting geen extra gegevens in te
    winnen.

-   Samenhang basisregistraties: er is geen impact voor andere basisregistraties
    voorzien.

**Implementatie-advies** n.v.t.

Toelichten samenvallen coördinaten kruinlijn en objectbegrenzing
----------------------------------------------------------------

**Gerelateerde
Github-issue(s)** [\#36](https://github.com/Geonovum/IMGeo2018/issues/36), [\#175](https://github.com/Geonovum/IMGeo2018/issues/175)

**Huidige situatie** In hoofdstuk 10 van de BGT catalogus is bij de regels voor
opname van kruinlijnen bij een wegdeel (10.1.2), ondersteunend wegdeel (10.2.2)
en onbegroeid terreindeel (10.4.2) de volgende zinsnede opgenomen.

>   Eén van de zijden van het ondersteunend wegdeel valt altijd samen met de
>   kruinlijn, zijnde bovenkant talud.

**Nieuwe situatie** Het voorstel is om de zinsnede uit te breiden met de
volgende tekst:

>   Een van de zijden van het begroeid terreindeel valt altijd samen met de
>   kruinlijn, zijnde bovenkant talud. **De coördinaten van de kruinlijn zijn
>   identiek met die van de objectbegrenzing ter plaatse.**

Ook wordt de tekst over afbakening van kruinlijnen opgenomen bij
begroeidterreindeel (10.5).

**Onderbouwing** Voor bronhouders en softwareleveranciers was de term
‘samenvallen’ lange tijd onduidelijk of dit betekende dat coördinaten van een
zijde van het object en de kruinlijn identiek moesten zijn. Met toevoeging van
deze zin wordt dit expliciet vastgelegd. Software van bronhouders en BGT keten
werkt al op deze regel.

**Impact**

De impact van dit voorstel wordt ingeschat op ‘**laag tot zeer laag**’:

-   *Verplicht/niet verplicht:* dit betreft een wijziging in het verplichte deel
    van IMGeo.

-   *Software:* er is geen aanpassing van de software nodig.

-   *Dataconversie:* bestaande gegevens hoeven niet worden geconverteerd.

-   *Inwinning:* bronhouders dienen de huidige kruinlijnen na te lopen om vast
    te stellen of deze voldoen aan deze regel.

-   *Samenhang basisregistraties:* er is geen impact voor andere
    basisregistraties voorzien.

**Implementatie-advies** n.v.t.

Toelichten samenvallen functionele gebieden en objectgrenzen
------------------------------------------------------------

**Gerelateerde
Github-issue(s)** [\#119](https://github.com/Geonovum/IMGeo2018/issues/119)

**Huidige situatie** In hoofdstuk 2 van de BGT catalogus wordt beschreven dat
BGT objecten kunnen worden geclusterd in een macro-object (ofwel Functioneel
Gebied).

>   Macro-objecten zijn geen inhoud van de BGT; in het eigen beheersysteem kan
>   men indien gewenst macro-objecten definiëren, die een clustering van BGT
>   objecten bevatten. In het optionele deel van IMGeo kunnen deze worden
>   uitgewisseld als Functioneel Gebied.

**Nieuwe situatie**

Het voorstel is om in hoofdstuk 2 aan de tekst toe te voegen dat ook delen van
BGT objecten geclusterd kunnen worden in een Functioneel Gebied.

>   Macro-objecten zijn geen inhoud van de BGT; in het eigen beheersysteem kan
>   men indien gewenst macro-objecten definiëren, die een clustering van BGT
>   objecten **en/of delen van BGT-objecten** bevatten. In het optionele deel
>   van IMGeo kunnen deze worden uitgewisseld als Functioneel Gebied.

**Onderbouwing** Met de toevoeging van deze zinsnede wordt meer duidelijkheid
gegeven dat ook delen van BGT-objecten, en daarmee dat de objectgrens van een
Functioneel Gebied niet persé hoeft samen te vallen de grenzen van de
geclusterde object

**Impact** De impact van dit voorstel wordt ingeschat op ‘**zeer laag**’:

-   *Verplicht/niet verplicht:* dit betreft een wijziging in het optionele deel
    van IMGeo.

-   *Software:* er is geen aanpassing van de software nodig.

-   *Dataconversie:* bestaande gegevens hoeven niet worden geconverteerd.

-   *Inwinning:* bronhouders hoeven geen gegevens in te winnen.

-   *Samenhang basisregistraties:* er is geen impact voor andere
    basisregistraties voorzien.

**Implementatie-advies** n.v.t.

Toelichten geen plaatsbepalingspunten bij planinformatie, OngeclassificeerdObject en registratieve gebieden
-----------------------------------------------------------------------------------------------------------

**Gerelateerde
Github-issue(s)** [\#79](https://github.com/Geonovum/IMGeo2018/issues/79),
[\#124](https://github.com/Geonovum/IMGeo2018/issues/124)

**Huidige situatie** In de IMGeo catalogus in paragraaf 3.5 Meetgegevens is de
volgende zinsnede opgenomen:

>   Net als in de BGT worden bij optionele IMGeo objecten de
>   plaatsbepalingspunten opgenomen.

**Nieuwe situatie** Het voorstel is om de IMGeo catalogus de volgende tekst toe
voegen

>   Net als in de BGT worden bij optionele IMGeo objecten de
>   plaatsbepalingspunten opgenomen. **Uitgezonderd van deze regel zijn alle
>   registratieve gebieden en alle geplande objecten.**

Ook wordt aan de BGT catalogus in paragraaf 3.12.1 Plaatsbepalingspunt de
volgende tekst toegevoegd over plaatsbepalingspunten bij ongeclassificeerde
objecten:

>   Een ongeclassificeerd object bezit impliciet plaatsbepalingspunten, immers
>   het is ontstaan doordat er een vlak 'overblijft' na classificatie van
>   objecten in een gebied in de transitie naar de BGT. "Automatisch" bestaat de
>   begrenzing van het ongeclassificeerde object uit geclassificeerde objecten
>   met pbp's. Deze 'gemeenschappelijke' pbp's behoren ook tot het ingesloten
>   ongeclassificeerde object.

**Onderbouwing** Planinformatie en registratieve gebieden zijn niet in te meten
en hebben logischerwijs du sook geen plaatsbepalingspunten. Voor
ongeclassificeerde objecten is niet duidelijk of / hoe deze objecten
plaatsbepalingspunten hebben. Dit voorstel neemt deze onduidelijkheden weg. De
software in de BGT keten werkt al volgens deze regels.

**Impact** De impact van dit voorstel wordt ingeschat op ‘**zeer laag**’:

-   *Verplicht/niet verplicht:* dit betreft een wijziging in het optionele deel
    van IMGeo.

-   *Software:* er is geen aanpassing van de software nodig.

-   *Dataconversie:* bestaande gegevens hoeven niet worden geconverteerd.

-   *Inwinning:* bronhouders hoeven geen gegevens in te winnen.

-   *Samenhang basisregistraties:* er is geen impact voor andere
    basisregistraties voorzien.

**Implementatie-advies** n.v.t.

Toelichten Nederlandse tijdzone met zomer/wintertijd
----------------------------------------------------

**Gerelateerde
Github-issue(s)** [\#13](https://github.com/Geonovum/IMGeo2018/issues/13)

**Huidige situatie** In de BGT catalogus wordt in het 4.5.3 Tijdgeldigheid het
volgende beschreven:

>   Als tijdstip (datum en tijd) voor ontstaan, wijzigen en vervallen van
>   objecten geldt het uitgangspunt dat hierbij de tijdzone voor Nederland, de
>   Midden-Europese tijdzone, van kracht is.

**Nieuwe situatie** Het voorstel is om de tekst in 4.5.3 als volgt te
verduidelijken:

>   Als tijdstip (datum en tijd) voor ontstaan, wijzigen en vervallen van
>   objecten geldt dat hierbij de tijdzone voor Nederland van kracht is: **in de
>   winter wordt de wintertijd aangehouden oftewel Midden-Europese Tijd (MET) en
>   in de zomer wordt de zomertijd aangehouden oftewel Midden-Europese Zomertijd
>   (MEZT). Om dubbele tijdstippen in de historie van een object te voorkomen,
>   mag in de nacht van zomertijd naar wintertijd tussen 02.00 u MEZT en 0.20 u
>   MET geen mutaties aan de BGT worden doorgevoerd.**

**Onderbouwing** Met deze aanpassing wordt duidelijkheid gegeven over wat
‘Nederlandse tijd’ en hoe om wordt gegaan met zomer/wintertijd.

**Impact** De impact van dit voorstel wordt ingeschat op ‘**zeer laag**’:

-   *Verplicht/niet verplicht:* dit betreft een wijziging in het verplichte deel
    van IMGeo.

-   *Software:* er is geen aanpassing van de software nodig.

-   *Dataconversie:* bestaande gegevens hoeven niet worden geconverteerd.

-   *Inwinning:* bronhouders hoeven geen gegevens in te winnen.

-   *Samenhang basisregistraties:* er is geen impact voor andere
    basisregistraties voorzien, met deze wijziging past BGT zich aan op de tekst
    in de BAG.

**Implementatie-advies** n.v.t.

Tekstuele aanpassing relatieve i.p.v. interne precisie
------------------------------------------------------

**Gerelateerde
Github-issue(s)** [\#142](https://github.com/Geonovum/IMGeo2018/issues/142)

**Huidige situatie** In de BGT catalogus in paragraaf 4.2 wordt het volgende
beschreven:

De positionele nauwkeurigheid van een object wordt beschreven op het niveau van
het objecttype. Hiermee wordt aan elk object binnen dat objecttype een
nauwkeurigheidseis gesteld. De BGT hanteert voor het beschrijven van de
positionele nauwkeurigheid de **zogenaamde interne precisie, ook bekend onder de
naam relatieve precisie**.

**Nieuwe situatie** Het voorstel is om deze tekst als volgt aan te passen:

De positionele nauwkeurigheid van een object wordt beschreven op het niveau van
het objecttype. Hiermee wordt aan elk object binnen dat objecttype een
nauwkeurigheidseis gesteld. De BGT hanteert voor het beschrijven van de
positionele nauwkeurigheid **de relatieve precisie**.

**Onderbouwing** Met deze aanpassing wordt de tekst verkort en dus duidelijker.

**Impact** De impact van dit voorstel wordt ingeschat op ‘**zeer laag**’:

-   *Verplicht/niet verplicht:* dit betreft een wijziging in het verplichte deel
    van IMGeo.

-   *Software:* er is geen aanpassing van de software nodig.

-   *Dataconversie:* bestaande gegevens hoeven niet worden geconverteerd.

-   *Inwinning:* bronhouders hoeven geen gegevens in te winnen.

-   *Samenhang basisregistraties:* er is geen impact voor andere
    basisregistraties voorzien.

**Implementatie-advies** n.v.t.
