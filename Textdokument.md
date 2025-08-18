# Webhosting Überblick

## Hosting-Arten im Vergleich

| Typ                       | Erklärung                                                                 | Vorteile                                                   | Nachteile                                                                 | Beste Eignung               | Beispiel Anbieter       |
|---------------------------|---------------------------------------------------------------------------|------------------------------------------------------------|---------------------------------------------------------------------------|-----------------------------|-------------------------|
| **Shared Hosting**        | Mehrere Webseiten teilen sich die Bandbreite des gleichen Servers         | günstig                                                    | Sicherheit und Performancebeschränkung                                   | Für privaten Gebrauch       | Ionos                   |
| **Dedicated Server**      | Auf gleichem Server, aber Accounts sind getrennt                          | Mehr Konfigurationsmöglichkeiten, sicherer als Shared      | –                                                                         | –                           | Hetzner                 |
| **VPS (Virtual Private Server)** | Komplett getrennte Speicherung von Kundendaten und Unternehmensdaten | Volle Rechte und Kontrolle, volle Bandbreite               | –                                                                         | –                           | Contabo                 |
| **Managed Hosting**       | Daten werden auf einem eigenen Server verwaltet                           | IT-Kosten werden übernommen                                | Keine volle Kontrolle über Hardware, eingeschränkte Konfigurationsmöglichkeiten | Serverüberwachung           | Kinsta                  |
| **Cloud Hosting**         | Webseiten befinden sich auf verbundenen Servern                           | Erhebliche bessere Performance                             | Datensicherheit                                                           | –                           | Amazon Web Services     |

---

## Weitere Möglichkeit: Serverhousing / Colocation

Ein Unternehmen bietet dir einen Hosting-Standort an.  
Das Unternehmen hat jedoch komplette Administratorrechte und kann die Konfiguration frei anpassen.

---

## Typische Services von Webhostern

- Bereitstellung von Speicherplatz  
- Backup-Services  
- Technischer Support  
- Auswertungen  

---

## Beispiel: Green Hosting

### Domain
- Sichere `.ch` Domain durch DNSSEC  
- Weitere Domains oder Endungen separat bestellbar  
- Einrichtung von Domain und E-Mail-Weiterleitung inklusive  

### Hosting
- 100 GB schneller Speicher (100% SSD)  
- 1 GB RAM  
- 25 Datenbanken  
- Unlimitierte Domains aufschaltbar  
- 750 Subdomains  
- Datenschutzkonform mit ADV  

### Sicherheit
- Let's Encrypt SSL-Zertifikat  
- Automatisiertes Backup alle 6 Stunden  
- Kostenlose, einfache Datenwiederherstellung  
- Daten im zertifizierten Schweizer Datacenter gesichert (inkl. gratis DNSSEC)  
- Firewall gegen Cyberangriffe  
- SPAM-Schutz mit Black-/Whitelist  

---

## Anbieter: NOVATREND Services GmbH

- **Adresse**: Bahnhofstrasse 18, CH-6340 Baar  
- **Tel.**: +41 44 500 40 70  
- **Mail**: info@novatrend.ch  
- **Preis**: 13.95 CHF  

---

## Wichtige Grundlagen

- **Hosts-Datei**: Lokale Textdatei zur Domainauflösung.  
- **DNS-Server**: Übersetzt Domainnamen (z. B. `google.com`) in IP-Adressen.  
- **DHCP**: Verteilt automatisch IP-Adressen und Netzwerkeinstellungen im Netzwerk.  
- **Root-Nameserver**: Kennt die zuständigen Nameserver für jede Top-Level-Domain.  
- **DNS-Request Ablauf**:  
  1. Rechner fragt zuerst Hosts-Datei.  
  2. Dann DNS-Server.  
  3. Dieser ermittelt die richtige IP-Adresse über die Hierarchie bis zum Root-Nameserver.  
