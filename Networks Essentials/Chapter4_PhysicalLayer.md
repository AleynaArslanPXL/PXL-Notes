# Chapter 4: Physical Layer

*Doel van de Physical Layer:*

- De Physical OSI Layer biedt de middelen om de bits die deel uitmaken van een Data Link Layer-frame over de netwerkmedia te transporteren. 
- Deze laag accepteert een compleet frame van de datalinklaag en codeert het als een reeks signalen die naar de lokale media worden verzonden. 
- De gecodeerde bits die een frame vormen, worden ontvangen door een eindapparaat of een tussenapparaat.<br><br>

**Physical Components**<br>

*De Physical Layer-standaarden hebben betrekking op drie functionele gebieden:*

1. Fysieke componenten:
	- Zijn de elektronische hardwareapparaten, media en andere connectoren die de signalen verzenden die de bits vertegenwoordigen. Voorbeeld: NIC, interfaces en connectoren.
2. Codering:
	- Een methode of patroon dat wordt gebruikt om digitale informatie weer te geven.
3. Signalering:
	- Signalen die gegenereerd worden die de "1" en "0" op de media vertegenwoordigen. Een lange puls kan bijvoorbeeld 1 vertegenwoordigen terwijl een korte puls een 0 kan vertegenwoordigen.<br><br>

**Bandwidth**<br>

Gegevensoverdracht wordt meestal besproken in termen van bandbreedte. Digitale bandbreedte meet de hoeveelheid gegevens die in een bepaalde tijd van de ene plaats naar de andere kan stromen.

*Een combinatie van factoren bepaalt de praktische bandbreedte van een netwerk:*

- De eigenschappen van de fysieke media
- De gekozen technologieën voor het signaleren en detecteren van netwerksignalen<br><br>

**Bandwidth Terminology**

1. Latency
	- Verwijst naar de hoeveelheid tijd, inclusief vertragingen, voor gegevens om van het ene punt naar het andere te reizen.
2. Throughput
	- De maat voor de overdracht van bits over de media gedurende een bepaalde tijdsperiode. Throughput is meestal lager dan de bandwidth maar volgende factoren beïnvloeden de throughput:
		1. Hoeveelheid verkeer
		2. Type verkeer
		3. Latency die wordt gecreëerd door het aantal netwerkapparaten dat wordt aangetroffen tussen bron en bestemming.
3. Goodput
	- De maat voor bruikbare gegevens die over een bepaalde periode worden overgedragen.<br><br>

**Copper Cabling**

*Waarom wordt koper bekabeling nog gebruikt?*<br>
- Goedkoop<br>
- Eenvoudig te installeren
- Lage weerstand tegen elektrische stroom<br><br>

*Er zijn drie verschillende soorten koperen bekabeling die elk in specifieke situaties worden gebruikt:*
1. Unshielded Twisted-Pair (UTP) Cable
	- Wordt gebruikt voor het onderling verbinden van netwerkhosts met intermediaire netwerkapparaten zoals switches en routers.
		- Buitenmantel beschermt de koperdraden tegen fysieke schade.
		- Twisted-pairs beschermen het signaal tegen interferentie.
		- Kleurgecodeerde kunststof isolatie isoleert draden elektrisch van elkaar en identificeert elk paar.
<br><br>
2. Shielded Twisted-Pait (STP) Cable
	- Biedt betere bescherming tegen ruis. Aanzienlijk duurder en moeilijker te installeren. Als de kabel niet goed is geaard, kan de afscherming als antenne werken en ongewenste signalen opvangen.
		- Outer jacket
		- Gevlochten of folieschild
		- Folieschilden
		- Twisted pairs
<br><br>
3. Coaxial Cable
	- Wordt gebruikt om de elektronische signalen door te geven. Coax bevestigt antennes aan draadloze apparaten. De coaxkabel draagt RF (radiofrequentie) energie tussen de antennes en de radioapparatuur.
	- Biedt internetconnectiviteit door delen van de coaxkabel te vervangen en versterkingselementen te ondersteunen door glasvezel.<br><br>

**UTP Cabling**<br>

Bij gebruik als netwerkmedium bestaat UTP-bekabeling uit vier paar kleurgecodeerde koperdraden die in elkaar zijn gedraaid en vervolgens zijn ingepakt in een flexibele plastic omhulling.<br>

**Fiber-Optic Cabling**<br>
- Verzendt gegevens over langere afstanden met hogere bandbreedtes
- Volledig imuun voor EMI en RFI
- Flexibel en super dunne, transparante kabel van zeer zuiver glas

**Soorten glasvezelmedia**
1. Single-mode glasvezel (SMF)
2. Multimode glasvezel (MMF)




