
### Fáze první: základy Linuxu a terminálu (trvá 1 - 3 týdny)

cíl: naučit se pracovat s Linuxovým systémem, základy práce v terminálu, správa souborů a síťových nástrojů.

##### Úkoly:
-  nainstalujte si distribuci jako Ubuntu, Kali Linux (pro pokročilé), nebo Parrot OS
- naučte se příkazy:
	- práce s terminálem: `cd`, `ls`, `cat`, `grep`, `nano`, `chmod`, `chown`, `sudo`
	- správa služeb: `systemctl`, `service`
	- síťové příkazy: `ping`, `ifconfig / ip`, `netstat`, `ss`, `traceroute`, `nslookup`, `dig`

##### Doporučené zdroje:
- LinuxCommand.org - https://linuxcommand.org/
- TryHackMe: Linux Fundamentals https://tryhackme.com/module/linux-fundamentals
- OverTheWire: Bandit https://overthewire.org/wargames/bandit/


### Fáze druhá: úvod do síťování a protokolů (trvá 2-3 týdny)

cíl: porozumět síťovým modelům (OSI, TCP/IP), běžným protokolům a komunikaci mezi zařízeními

##### Úkoly:
- nastudujte si vrstvy OSI a TCP/IP
- naučte se, co dělají protokoly: TCP, UDP, IP, HTTP, HTTPS, DNS, DHCP, ICMP
- pracujte s příkazem `tcpdump`, čtěte pakety, analyzuj hlavičky

##### Doporučené zdroje:
- NetworkChuck (YouTube) - https://www.youtube.com/@NetworkChuck/featured
- Cisco Packet Tracer (simulátor síti) - https://prelogin-authoring.netacad.com/courses/packet-tracer
- TryHackMe: Intro to Networking - https://tryhackme.com/room/introtonetworking

### Fáze třetí: monitorování síťového provozu (trvá 3 - 4 týdny)

cíl: naučit se zachytávat a analyzovat síťový provoz

##### Nástroje:
- Wireshark - GUI pro analýzu paketů - https://www.wireshark.org/download.html
- tcpdump - CLI varianta
- NetFlow - ntopng - sledování síťového provozu v reálném čase

##### Úkoly:
- naučte se číst TCP handshake, DNS dotazy, HTTP požadavky
- filtrace provozu (porty, IP adresy, protokoly)
- vytvářejte si jednoduché reporty ze zachycených dat


### Fáze čtvrtá: skenování portů podle služeb (trvá 2 - 3 týdny)

cíl: naučit se detekovat otevřené porty, aktivní služby a operační systémy

##### Nástroje:
- Nmap - základní skener portů - https://nmap.org/
- Zenmap  grafická verze Nmapu - https://nmap.org/zenmap/
- Masscan - rychlý skener
- netcat - pro jednoduché spojení a testování portů

##### Úkoly:
- skenování jednotlivých IP, rozsahů
- detekce OS (`-0`), služeb (`-sV`)
- scanování z pohledu útočníka i obránce


### Fáze pátá: detekce bezpečnostních rizik (trvá 3 - 4 týdny)

cíl: identifikace zranitelností a rizik na základě síťové aktivity a služeb.

##### Nástroje:
- OpenVAS / Greenbone - https://www.openvas.org/
- Nessus - https://www.tenable.com/products/nessus
- Nikto - skenování webserverů (open source)
- Nmap NSE sktripty - pro pokročilé skenování

##### Úkoly:
- spusťte audit na testovacím zařízení (např. metasploitable VM)
- získejte výstupy a naučte se je interpretovat
- vyhodnoťte rizika (CVSS skóre)


### Fáze šestá: simulace útoku a obrana (red vs blue) (trvá 4 - 6 týdnů)

cíl: Porozumění, jak útočník přemýšlí a jak se bránít. Praktické využití znalostí

##### Nástroje a prostředí:
- Metasploit, Armitage - testovací exploity
- Kali Linux - ofenzivní nástroje (Hydra, SQLmap, atd.)
- Snort, Suricata, Zeek - IDS/IPS systémy
- Security Onion - kompletní monitoring a detekce

##### Úkoly:
- nastavte si testovací síť ve VirtualBoxu nebo Proxmoxu
- simulujte útoky typu: brute force, port scanning, DNS spoofing
- monitorujte útoky v nástrojích jako Snort/Zeek
- tvořte zákadní pravidla pro detekci


### Fáze sedmá: reálné scénáře a certifikace (průběžný proces který trvá 1 - 2 měsíce)

cíl: získání přehledu o profesionálních rámcích, best practices a případně certifikaci

##### Doporučené certifikace:
- CompTIA Security+
- CompTIA Network+
- CEH (Certified Ethical Hacker)
- eJPT (Junior Penetration Tester) od INE

##### Doporučené platformy pro trénink:
- TryHackMe - https://tryhackme.com/
- Hack The Box - https://www.hackthebox.com/
- Blue Team Labs Online - https://blueteamlabs.online/
- RangeForce - https://www.rangeforce.com/