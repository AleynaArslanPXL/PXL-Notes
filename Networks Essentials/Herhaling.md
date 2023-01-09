# Herhaling

## OSI Layer

**Layer 1: Physical Layer**: bits
- Protocol: Ethernet
- Adressering: bekabeling

**Layer 2: Data Link Layer**: frames
- Protocol: Ethernet, ARP
- Addressering: MAC adressen

**Layer 3: Network Layer**: packets
- Protocol: IP, ICMP
- Adressering: IP-adressen

**Layer 4: Transport Layer**: segments
- Protocol: TCP, UDP
- Adressering: port numbers

**Layer 5: Application Layer**: data
- Protocol: HTTP, HTTPS, SMTP, POP, IMAP, DHCP, DNS

## Application Layer:
### DNS (Domain Name System)

1. Functie: omzetten van naam naar IP adres
2. Poort: 53
3. Transport Layer: gebruikt UDP, TCP

### DHCP (Dynamic Host Configuration Protocol)

1. Functie: automatisch toekennen van netwerk gegevens zoals:

- IP
- Subnet
- Default Gateway
- DNS

2. Poort: client 68 en server 67
3. Transport Layer: UDP

### HTTP (Hypertext Transfer Protocol)

1. Functie: niet geëncrypteerd opvragen webpagina's
2. Poort: 80
3. Transport Layer: TCP


### HTTPS (Hypertext Transfer Protocol Secure)

1. Functie: geëncrypteerd opvragen webpagina's
2. Poort: 443
3. Transport Layer: TCP

### FTP (File Transfer Protocol)

1. Functie: overbrengen data
2. Poort: 20 en 21
3. Transport Layer: TCP

### POP (legacy)
1. Functie: ontvangen van mailsb
2. Poort: 110
3. Transport Layer: TCP

### IMAP
1. Functie: ontvangen mails
2. Poort: 143
3. Transport Layer: TCP

### SMTP
1. Functie: verzenden mails<br>
2. Poort: 25 en 587<br>
3. Transport Layer: TCP

## TCP/IP Layer

**Layer 1: Application:**
- Protocol: HTTP, DNS, DHCP, FTP

**Layer 2: Transport:** 
- Protocol: TCP, UDP

**Layer 3: Internet:** 
- Protocol: IPv4 & 6, ICMPv4 & 6

**Layer 4: Network Access:**
- Protocol: Ethernet, ARP, WLAN

