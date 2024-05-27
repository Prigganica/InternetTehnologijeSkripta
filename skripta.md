VI domaći
1. Da li TCP podržava streaming?
- DA
2. Pridružite aplikacijama transportne protokole koje koriste:
- WEB - TCP
- TELNET – TCP
- FTP - TCP
- eMail - TCP
- Video konferencije - UDP
- VoIP - UDP
- SNMP - UDP

3. Pridružite transportnim protokolima iz TCP/IP seta atribut pouzdanopsti (pouzdan-
nepouzdan):

- TCP - pouzdan
- UDP - nepouzdan
- RTSP - nepouzdan
- RTP - nepouzdan
4. Izaberite moguće situacije:
- Jedan servis sa istim servisom na različitim hostovima
- Više istih klijenata i više različitih servera na istom hostu
- Više različitih servera na istom hostu
5. Koje transportne portove koristi WEB server kada prima zahtjev za HTML stranicom?
- tcp 80
6. Koje transportne portove koristi vaš browser (bilo koji) kada šalje zahtjev za HTML stranicom?
- tcp više od 1023
7. Koje transportne portove koristi MS SQL server?
- tcp od 256 do 1023
8. Koji transportni protokol koristi koncept “kliznog prozor“?
- TCP
9. Da li UDP provjerava stanje veze prije slanja podataka?
- NE
10. Izaberite validne socket-e:
- 10.10.10.1 : tcp : 1028
- 10.10.10.254 : udp : 10028
- 190.1.108.19 : udp : 28

7

VII domaći
11. Koje vrste DNS servera postoje?
- lokalni serveri
- root
- TLD serveri
- autorizovani
12. Koji port koristi DNS?
- TCP 53
- UDP 53
13. Koji DNS server komunicira sa klijentom?
- lokalni serveri
14. Koliko maksimalno može imati znakova FQDN?
- 255
15. Koja organizacija je zadužena za dodjelu TLD domena?
- ICANN
16. Koliko maksimalno nivoa (podnivoa) može imati TLD?
- 127
17. TLD se dijele:
- gTLD
- ccTLD
18. Koje vrste DNS servera zona postoje?
- primarni
- sekundarni
- glavni
- keš
19. Koje vrste DNS servera zahtjeva postoje?
- iterativni
- rekurzivni
20. Kako se zove DNS server koji razriješi upit?
- Autorizovani
21. U koliko IP adresa se može preslikavati domensko ime marko.ac.me?
- u jednu Ip adresu
- u više IP adresa
22. U koliko IP adresa se može preslikavati domensko ime etf.ac.me?
- u jednu IP (v4 ili v6) adresu
- u više IP (v4 ii v6) adresa
23. Koliko maksimalno može imati karaktera labela u domenskom imenu?
- 63
24. Kojim redosljedom teče proces razrešavanja DNS imena sa strane klijenta?
1) Da li sam to ja?
2) Provjera lokalnog fajla hosts
3) Upit za DNS server
4) Broadcast za LAN
5) „Host not found“
25. Koje vrste VPN-a postoje?
- VPN na nivou aplikacije
- VPN na data-link nivou
- VPN na mreznom nivou

8

26. Kojim redosljedom teče proces razrešavanja DNS imena sa strane servera?
1) Traženje u lokalnom kešu ili fajl hosts
2) Zahtjev lokalnom DNS serveru
3) Zahtjev root DNS serveru
4) Zahtjev TLD DNS servisu
5) Zahtjev autoritativnom DNS servisu
6) Pronalaženje zapisa
7) Odgovor klijentu
27. Kojoj vrsti VPN-a priprada MPLS VPN?
- VPN na data-link nivou
28. Da li VPN na mrežmom sloju može da mijenja IP adresu u IP datagramu?
- NE
29. Koja osobina IP protokola je osnov VPN-a?
- enkapsulacija
30. Koje od ponuđenih protokola koristi VPN?
- PPTP
- L2FP
- L2TP
- Ipsec
31. Koja, od ponuđenih, je najveća korist VPN-a?
- Niska cijena
32. Koja, od ponuđenih, je najveća mana VPN-a?
- Nezaštićenost podataka
33. Da li postoji mogućnost da računar kojiima privatnu IP adresu koristi neki internet servis, tj.
da pristupa servisima sa globalne mreže?
- DA
34. Koji od ponuđenih vrsta VPN-a ima najmanji nivo bezbjednosti?
- VPN na nivou aplikacije
35. Kako se puni NAT tabela?
- ručno
- pomoću dolazećih domenskih imena
- pomoću odlazećih datagrama
36. Koje verzije IP-a podržava NAT i NAPT?
- IPv4
- IPv6
37. NAT protokol vrši:
- zamjenu Ip adresa u IP paketima i mapiranje izvršene zamjene
38. Koristeći PAT (NAPT) protokol, koliko vam je namanje potrbno javnih IP adresa da bi omogućili
stalno korišćenje interneta u LAN mreži koja ima 20 računara?
- 1

9

VIII domaći
39. IP adresa vašeg računara je 89.188.43.22/24. Na koji način možete saznati MAC adresu
računara 89.188.43.222/24?
- nb/stat -A 89.188.43.222
- ping 89.188.43.222, arp-a
40. IP adresa vašeg računara je 89.188.43.22/24. Na koji način možete saznati MAC adresu
računara 89.188.44.222/24?
- To nije moguće odraditi.
41. Da li možete pristupiti internetu ako IP adresa DNS servera nije ispravno konfigurisana?
- Da, ako u URL polje kucamo IP adresu
42. U hosts fajlu vašeg računara postoji sljedeći zapis: 195.66.164.240 proba. Nakon kucanja
http://proba u URL polje browser-a, otvoriće se sjedeći sajt:
- www.telekom.me
43. Kojim komandama možete provjeriti možete li stupiti u konekciju sa računarom 89.188.43.22?
- ping 89.188.43.22
- tracert 89.188.43.22 5
44. IP adresa računara je 89.188.43.22 , a MAC adresa istog je aa-11-22-23-41-44. Da li možete
pingovati gornji računar, ako ste prethodno izvršili komandu: arp-d 89.188.43.22?
- Da, ako nije konfigurisana firewall zaštita na putanje do traženog računara.
45. IP adresa računara je 89.188.43.22 , a MAC adresa istog je aa-11-22-23-41-44. Da li možete
pingovati gornji računar, ako ste prethodno izvršili komandu: arp-s 89.188.43.22 bb-11-22-23-
41-44?
- NE
46. Kojom naredbom ćete dobiti informacije o tekućim TCP/IP konekcijama?
- netstat -anbo
47. Kako ćete provjeriti IP adresu računara čije je ime LN1-01?
- nbtstat - a LN1-01
48. Kako ćete provjeriti kako vaš default-ni DNS razrešava adresu www.os.ac.me?
- nslookup www.os.ac.me
49. Kojom komandom možete provjeriti MAC adresu vašeg računara?
- ipconfig/all
50. Pomoću koje komande možete saznati ime vašeg računara?
- nbstat -n
- ipconfig/all
51. Kojom komandom ćete provjeriti sadržaj ARP tabele?
- arp -a
52. Kako cete iza arp tabele izbrisati par 89.188.33.61 00-11-cd-ff-gg-hh?
- arp -d 89.188.33.61
53. Kojim komandama možete provjeriti da li je TCP/IP konfiguracija vašeg računara ispravna?
- ping 127.0.0.1
- ping localhost
54. Kojom naredbom ćete provjeriti stanje portova na vašem računaru i PID-ove procesa koji ih
koriste?
- netstat -ao

10

IX domaći
55. Koja je funkcija SNMP protokola?
- upravljanje internetom
56. Koji je od ponuđenih protokola zadužen za prenos WEB sadržaja preko interneta?
- HTTP
- HTTPS
57. Koliko transportnih portova koristi FTP servis?
- 2 tcp
58. Koliko transportnih portova koristi TFTP servis?
- 1 udp
59. Koji od ponuđenih programa može obavljati funkciju WEB servera?
- Apache
- MS IIS
- Nginx
60. Koji od ponuđenih programa su WEB klijenti?
- Google Chrome
- Mozila Firefox
- MS IE
61. Pomoću kojih od ponuđenih programa se može kreirati WEB stranica?
- Dreamweaver
- Notepad
- Front Page
- Microsoft World
62. Odrediti kojoj WEB tehnologiji pripadaju poznati web sajtovi:
- www.os.ac.me - WEB 1.0
- www.facebook.com - WEB 2.0
- Wikipedia - WEB 2.0
63. Od čega se sastoji URI?
- URL
- URN
64. Koji od ponuđenih servisa koristi NVT?
- Telntet
- FTP
65. Da li email adresa zavisi od ISP kod kojeg ste kupili pristup internetu?
- NE
66. Koji je od ponuđenih protokola zadužen za primanje eMail poruka?
- POP3
- IMAP
67. Koji je od ponuđenih protokola zadužen za slanje eMail poruka?
- SMTP
68. Koji od ponuđenih servisa koristi spooling?
- eMAIL
69. U koje svrhe se koristi metod POP before (prije) SMTP-a?
- Metod sprečavanja slanja meila prije autorizacije
70. Ako je na hostu 11.11.11.11, čije je domensko ime m.spr.com, podignut email server, a
korisničko ime klijenta koji je otvorio nalog na istom je markom. Koja je validna email adresa
ovog klijenta?
- markom@m.spr.com
- markom@11.11.11.11

11

71. Na kojoj vrsti prenosa podataka je baziran HTTP protokol?
- unicast
72. Koji od ponuđenih protokola koristi MIB promjenjive?
- SNPM
73. Koji od ponuđenih programa može obavljati funkciju eMail servera?
- postfix
- sendmail
- MS Exchange
74. Korisnik st1, sa šifrom 123, želi da, pomoću browsera, sa WEB servera os.ac.me(koristi port
80) učita spisak.htm. Šta korisnik treva da otkusa u URL polje?
- http://st1:123@os.ac.me/spisak.htm
- http://st1:123@os.ac.me:80/spisak.htm
75. Korisnik st1, sa šifrom 123, želi da, pomoću browsera, sa WEB servera os.ac.me(koristi port
167) učita stranicu spisak.htm. Šta korisnik treva da otkusa u URL polje?
- http://st1:123@os.ac.me/spisak.htm
- http://st1:123@os.ac.me:167/spisak.htm
76. Korisnik st1, sa šifrom 123, želi da, pomoću browsera, sa FTP servera os.ac.me(koristi port 21)
učita stranicu spisak.htm. Šta korisnik treva da otkusa u URL polje?
- ftp://st1:123@os.ac.me/spisak.htm
- ftp://st1:123@os.ac.me:21/spisak.htm
77. Korisnik st1, sa šifrom 123, želi da, pomoću browsera, sa FTP servera os.ac.me(koristi port
167) učita stranicu spisak.htm. Šta korisnik treva da otkusa u URL polje?
- ftp://st1:123@os.ac.me/spisak.htm
- ftp://st1:123@os.ac.me:167/spisak.htm
78. Koja verzija IP-a NE podržava NAT i NAPT?
- ni jedna od ponuđenih
79. Koja od navedenih zapisa može biti dio PAT(NAPT) tabele?
- 192.1.1.2:2331; 89.188.23.1: 31200
- 10.10.10.1:21; 199.99.99.2:12345
80. Koja od navedenih zapisa može biti dio NAT tabela?
- 192.1.1.2; 89.188.23.1
- 10.10.1.2; 10.11.1.2
- 10.10.10.1; 199,.99.99.2

12

X domaći
81. Šta se podrazumijeva pod socijalnim inženjeringom?
- tehnike ugrožavanja IS preko zaposlenih
82. Koji od navedenih subjekata (njihov IS) je najčešći cilj napada preko Interneta?
- Velike kompanije
83. Računarska mreža je zaštićena posebnim firewall-om. Gdje je najbolje postaviti host sa bazom
podataka?
- u DMZ zonu
84. Gdje se koristi pojam DMZ (demilitarizovana zona)?
- kod zaštite servera pomoću firewall-a
85. Koja je funkcija VoIP gateway-a?
- povezivanje telefonske mreže sa IP mrezom
86. Koji se od navedenih protokola koristi kod QoS?
- RSVP
87. Koji su najveći tehnički problemi IP telefonije?
- Gubitak paketa
- Kašnjenje
- Eho
- Džiter
88. Firewall može biti realizovan kao?
- Softver
- Poseban mrežni uređaj
- Dodatna funkcija na ruteru
89. Sa kojim od ponuđenih uređaja može da komunicira IP telefon koji koristi IP telefoniju?
- sa IP telefonom
- sa mobilnim telefonom povezanim na 3G mrežu
- sa mobilnim telefonom povezanim na GSM mrežu
- sa fiksnim telefonom povezanim na PSTN
- sa računarom povezanim na Internet
90. Da li IP telefon ima IP adresu?
- DA
91. Koji od ponuđenih standarda daje preporuke za povećanje bezbjednosti IS-a?
- ISO 27002
92. Koje komponente čine bezbjednost IS povezanog na Internet?
- zaposleni
- tehnologija
- poslovni procesi- procedure
93. Koji od ponuđenih uređaja može izvršiti konverziju govora u IP paket?
- SMART telefon
- PC računar
- IP telefon

13

Dodatna pitanja
1. Kada DHCP server dodjeljuje parametre nekom hostu koji transportni protokol koristi?
- UDP
2. Navedite primjer jednog zapisa u ARP kešu i napišite naredbu kojom se briše ARP keš sa
računara (Windows)?
- arp-a
- IP_MAC 125.0.5.63_ FA.3A.45.18.BC.87
3. Na koji način možete provjeriti za koliko ICMP poruke stižu do hosta 20.12.12.21?
- ping 20.12.12.21
4. Navedite bar četri Internet servisa koji koriste nepouzdani TCP/IP transportni protokol:
- DNS, RIP, NFS, SNMP, video i audio konferencije, video streaming, internet
telefoniranje, internet igre
5. Navesti primjer jednog socket-a:
- 147.55.68.77:TCP:80
6. Kako ćete saznati IP adresu hosta čije je domensko ime mo.cg.ac.yu, a koristite računar
povezan na Internet i ima WXP OS?
- ping mo.cg.ac.yu
7. Kada kao adresu unesete www.krstarica.com vaš browser će sledećim redosledom razrešavati
tu adresu:
- provjera svog imena, provjera fajla host, upit ka NS serveru, broadcast na fizičku
mrežu, host not found

8. Nabrojte 6 Internet servisa i pripadajućih aplikativnih protokola TCP/IP sloja
- IRC FTP TELNET HTTP SMTP POP3
- IRC FTP TELNET WEB Email Email
9. Može li se ARP tabela iskoristiti za realizaciju VPN-a?
- Da, ali je to nezaštićen VPN
10. Ako korisnik stud1 želi da, pomoću browsera, sa WEB servera ispit.cg.yu pročita fajl
spisak.html iz direktorijuma doc kako izgleda URL, odnosno šta će unijeti u polje predviđeno
za web adresu:
- http://stud1:@ispit.cg.yu/doc/spisak.html
11. Koji od navedenih standarda zahtijeva autorizaciju korisnika pri preuzimanju mail-a?
- POP3, IMAP4
12. Navesti tri Email servera i tri Email klijenta?
- Posfix, SendMail, qmail
- Microsoft Outlook, Outlook Express, Eudora
13. Koji protokol se koristi za rad na udaljenom računaru ili terminalski rad?
- TELNET port 23
14. Kojom naredbom se ostvaruje loopback ili provjerava instaliranje TCP/IP-a na hostu?
- ping 127.0.0.1
15. Koji transportni protokol TCP/IP steak se koristi pri razrješavanju MAC adrese hosta iz njegove
IPadrese?
- ARP
16. Da li se može saznati MAC adresa hosta 195.66.123.1 koji nije u vašoj fizičkoj mreži i kako?
- Ne
17. Na koji način možete provjeriti kojom putanjom i koliko usmjerivača će proći vaš IP datagram
do hosta 200.12.12.211?
- tracert 200.12.12.211
18. Navedite bar 4 Internet servisa koji koriste pouzdani TCP/IP transportni protokol:
- Telnet, HTTP, FTP, SMTP

14
19. Kojom naredbom ćete ustanoviti da li i koji procesi na vašem računaru koriste određene
portove:
- nestat -a(-n)
20. Šta je osim.cg.yu?
- Ne može se zaključiti iz naziva
21. Koji je najjeftiniji način kreiranja korporacijske WAN mreže ili povezivanja dvije LAN mreže
(imaju mogućnost pristupa Internetu)?
- VPN
22. Na hostu sa IP adresom 10.66.16.21 je podignut web server. Da li se ovom serveru može
pristupiti sa Interneta ako je fizička mreža u kojoj se nalazi povezana sa Internetom?
- Da, ako se na gateway-u koristi dinamički NAT
23. Navesti tri WEB servera i tri WEB browser-a?
- Apache, Microsoft, Google
- Internet Explorer, Mozzila Firefox, Opera
24. Ako želite da pomoću browsera, sa WEB servera ispit.cg.yu koji osluškuje na TCP portu 899
pročitajte fajl spisak.html kako izgleda URL, odnosno šta ćete unijeti u polje predviđeno za
web adresu:
- http://@ispit.cg.yu:899/spisak.html
25. Koji od navedenih standarda definiše format multimedijalnih mail poruka?
- MIME
26. Kada koristite WEB Smail koju klijentski aplikaciju koristite za čitanje maila, a koji protokol, na
aplikativnom nivou TCP/IP steaka, ona koristi?
- Outlook Express POP3
27. Koji protokol se koristi za prenos fajlova preko Interneta? Koji su djelovi tog protokola i koje
portove koristite?
- FTP Protocol interpreter (21), Data Transfer Protocol (20)
28. Nabrojte nivoe zaštite privatnosti korporacijske mreže i podataka od napada na Internetu:
- Firewall, zaštita servera, zaštita radnih stanica
