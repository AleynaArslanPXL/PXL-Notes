# Chapter 3: Protocols and Models

*Deze protocollen zijn nodig om communicatie via een of meer netwerken mogelijk te maken:*

- **Network Communications Protocols**: Stelt twee of meer apparaten in staat om via een of meer netwerken te communiceren. *Voorbeeld: TCP, IP, HTTP*.
- **Network Security Protocols**: Beveiligd gegevens om authenticatie, gegevensintegriteit en gegevenscodering te bieden. *Voorbeeld: SSH, SSL en TLS*.
- **Routing Protocols**: Stelt routers in staat route informatie uit te wisselen, padinformatie te vergelijken en vervolgens het beste pad naar het bestemmingsnetwerk te selecteren. *Voorbeeld: OSPF en BGP*.
- **Service Discovery Protocols**: Wordt gebruikt voor de automatische detectie van apparaten of diensten. *Voorbeeld: DHCP en DNS*.<br><br>

*Computers en netwerkapparaten gebruiken afgesproken protocollen om te communiceren:*

- **Addressing**: Identificeert de afzender en de ontvanger van het bericht met behulp van gedefinieerd addressingsschema. Voorbeeld: IPv4 en IPv6.
- **Reliability**: Biedt gegarandeerde leveringsmechanismen in het geval dat berichten tijdens het transport verloren gaan of beschadigd raken. Voorbeeld: TCP.
- **Flow Control**: Zorgt ervoor dat gegevens met een efficiënte snelheid tussen twee communicerende apparaten stromen. 
- **Sequencing:** Labelt elk verzonden gegevenssegment op unieke wijze. Voorbeeld: TCP.
- **Error Detection**: Wordt gebruikt om te bepalen of gegevens beschadigd zijn geraakt tijdens de verzending. Voorbeeld: TCP, Ethernet, IPv4 en IPv6.
- **Application Interface:** Bevat informatie die wordt gebruikt voor proces-naar-proces-communicatie tussen netwerktoepassingen. 
- **HTTP:** Definieert de inhoud en opmaak van verzoeken en antwoorden die worden uitgewisseld tussen de client en de server.
- **TCP:** Verantwoordelijk voor het garanderen van de betrouwbare levering van de informatie en het beheren van de flow control tussen de end devices.
- **IP:** Verantwoordelijk voor het afleveren van berichten van de afzender naar de ontvanger. 
- **Ethernet:** Verantwoordelijk voor de levering van berichten van een NIC naar een andere NIC op dezelfde LAN.<br><br>


## TCP/IP Layer

4. ### **Application Layer** 
*Name System:*
- **DNS** **(Domain Name System):** Vertaalt domeinnamen zoals cisco.com naar IP-adressen.

*Host Configuration:*
- **DHCPv4** **(Dynamic Host Config Porotocol voor IPv4):** Wijst bij het opstarten dynamisch IPv4-adresinformatie toe aan DHCPv4-clients.
- **DHCPv6** **(Dynamic Host Config Protocol voor IPv6):** Wijst bij het opstarten dynamisch IPv6-adresinformatie toe aan DHCPv6-clients.
- **SLAAC (Stateless Address Autoconfiguration):** Methode waarmee een apparaat zijn IPv6-adresgegevens kan verkrijgen zonder een DHCPv6-server te gebruiken.

*E-mail:*
- **SMTP (Simple Mail Transfer Protocol):** Stelt clients in staat om mails naar een mailserver te sturen en stelt servers in staat om mails naar andere servers te sturen.
- **POP3 (Post Office Protocol version 3):** Stelt klanten in staat om mails op te halen van een mailserver en de mails te downloaden naar de lokale mailtoepassing van de klant.
- **IMAP (Internet Message Access Protocol):** Biedt clients toegang tot mails die is opgeslagen op een mailserver en kan mails op de server onderhouden.

*File Transfer:*
- **FTP (File Transfer Protocol):** Stelt regels in waarmee een gebruiker op de ene host bestanden kan openen en overbrengen van en naar een andere host via een netwerk.
- **SFTP (SSH File Transfer Protocol):** Wordt gebruikt om beveiligde bestandsoverdrachtsessie tot stand te brengen waarin de bestandsoverdracht wordt versleuteld.
- **TFTP (Trivial File Transfer Protocol):** Eenvoudig, verbindingloos protocol voor bestandsoverdracht met niet erkende bestandslevering.

*Web and Web Services:*
- **HTTP (Hypertext Transfer Protocol):** Set van regels voor het uitwisselen van tekst, grafische afbeeldigen, geluiden etc. op het World Wide Web.
- **HTTPS (Hypertext Transfer Protocol Secure):** Een veilige vorm van HTTP die de gegevens versleutelt die via het WWW worden uitgewisseld.
- **REST (Representational State Transfer):** Webservice die API's en HTTPS-verzoeken gebruikt om webapps te maken.<br><br>

3. ### **Transport Layer**

*Connection-Oriented:*
- **TCP (Transmission Control Protocol):** Maakt betrouwbare communicatie mogelijk tussen processen die op afzondelijke hosts worden uitgevoerd.

*Connectionless:*
- **UDP (User Datagram Protocol):** Hiermee kan een proces dat op de ene host wordt uitgevoerd, pakketten verzenden naar een proces dat op een andere host wordt uitgevoerd.<br><br>

2. ### **Internet Layer**

*Internet Protocol:*
- **IPv4:** Ontvangt berichtsegmenten van de transportlaag, verpakt berichten in pakketten en adresseert pakketen voor end to end levering via een netwerk. = 32 bits.
- **IPv6:** Vergelijkbaar met IPv4. = 128 bits.
- **NAT:** Vertaalt IPv4 adressen van een particulier netwerk naar wereldwijd unieke openbare IPv4 adressen.

*Messaging:*
- **ICMPv4 (Internet Control Message Protocol voor IPv4):** Geeft feedback van een bestemmingshost naar een bronhost over fouten in pakketbezorging.
- **ICMPv6:** ICMP voor IPv6. 
- **ICMPv6 ND (Internet Control Message Protocol Neighbour Discovery):** Bevat vier protocolberichten die worden gebruikt voor adresresolutie en detectie van dubbele adressen.

*Routing Protocols:*
- **OSPF (Open Shortest Path First):** Routeringsprotocol met linkstatus dat een hiërarchisch ontwerp gebruikt op basis van gebieden.
- **EIGRP (Enhanced Interior Gateway Routing Protocol):** Routeringsprotocol dat gebruik maakt van een samengestelde metries op basis van bandbreedte, vertraging, belasting en betrouwbaarheid.
- **BGP (Border Gateway Protocol):** Routeringsprotocol dat wordt gebruikt tussen internet service providers om routeringsinformatie uit te wisselen.<br><br>

1. ### **Network Layer**

*Address Resolution:*
- **ARP (Address Resolution Protocol):** Biedt dynamische adrestoewijziging tussen een IPv4-adres en een hardwareadres.

*Data Link Protocols:*
- **Ethernet:** Definieert de regels voor bedradings- en signaleringsstandaarden van de netwerktoegangslaag.
- **WLAN (Wireless Local Area Network):** Definieert de regels voor draadloze signalering over radiofrequenties.<br><br>

## OSI Model Layer

**A**ll **P**eople **S**eem **T**o **N**eed **D**ata **P**rotection

7. **Application:** Bevat protocollen die worden gebruikt voor proces-naar-procescommunicatie.

6. **Presentation:** Zorgt voor een gemeenschappelijke weergave van de gegevens die worden overgedragen tussen Application Layer-services.

5. **Session:** Levert diensten aan de Presentation Layer om de dialoog te organiseren en de gegevensuitwisseling te beheren.

4. **Transport:** Definieert services om de gegevens te segmenteren, over te dragen en opnieuw samen te stellen voor individuele communicatie tussen end devices.

3. **Network:** Levert diensten om afzonderlijke stukjes data over het netwerk uit te wisselen tussen geïdentificeerde end devices.

2. **Data Link:** Beschrijft methoden voor het uitwisselen van dataframes tussen apparaten via een gemeenschappelijk medium.

1. **Physical:** Beschrijft de mechanisme, elektrische en functionele middelen om fysieke verbindingen te activeren, onderhouden en deactiveren voor een bittransitie van en naar netwerkapparaten.<br><br>

## Segmenting Messages

Segmentatie is het proces waarbij een gegevensstroom wordt opgedeeld in kleinere eenheden voor verzending via het netwerk. Segmentatie is noodzakelijk omdat datanetwerken de TCP/IP-protocolsuite gebruiken om gegevens in individuele IP-pakketten te verzenden.

*Segmenteren van berichten hebben 2 belangrijke voordelen:*

- Verhoogt de snelheid
- Verhoogt de efficiëntie

TCP is verantwoordelijk voor het rangschikken van de afzonderlijke segmenten.

- **Data:** Algemene term voor de PDU die wordt gebruikt door de Application Layer
- **Segment:** PDU Transport Layer
- **Packet:** PDU Network Layer
- **Frame:** PDU Data Link Layer
- **Bits:** Physical Layer PDU die wordt gebruikt bij het fysiek verzenden van gegevens via het medium.

Als de Transport-header TCP is, is het een segment, wanneer de header UDP is, is het een datagram.<br><br>

## Addressing

De Network en Data Link Layer zijn verantwoordelijk voor het leveren van data van het bronapparaat naar het doelapparaat. 

**Network Layer source and destination addresses:** Verantwoordelijk voor het afleveren van het IP-pakket van de source naar de destination, die zich op hetzelfde of een extern netwerk kan bevinden.
**Data Link Layer source and destination addresses:** Verantwoordelijk voor het leveren van het Data Link-frame van de ene NIC naar een andere NIC op hetzelfde netwerk.

*Een IP-adres bestaat uit twee delen:*

-  **Network portion (IPv4) of Prefix (IPv6)**: Het meest linkse deel van het adres dat het netwerk aangeeft waarvan het IP-adres lid is. Alle apparaten op hetzelfde netwerk hebben hetzelfde netwerkgedeelte van het adres.
-  **Host portion (IPv4) of interface-ID (IPv6)**: Het resterende deel van het adres dat een specifiek apparaat op het netwerk identificeert. Dit gedeelte is uniek voor elk apparaat of elke interface op het netwerk.

*MAC-adressen zijn fysiek ingebed in de Ethernet NIC:*

- **Source MAC address**: Dit is het datalinkadres, of het Ethernet MAC-adres, van het apparaat dat het datalinkframe met het ingekapselde IP-pakket verzendt.
- **Destination MACaddress**: Als het ontvangende apparaat zich op hetzelfde netwerk bevindt als het verzendende apparaat, is dit het datalinkadres van het ontvangende apparaat.