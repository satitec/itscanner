# IT-Network DocuScanner

**Sat-iTec Systemhaus GmbH** · https://www.sat-itec.se

Proprietaeres Tool zur Netzwerk-Inventarisierung und IT-Dokumentation
nach BSI-Grundschutz.

## Features

- Active Directory Integration via natives LDAP/LDAPS
- Software- und Lizenz-Inventarisierung (CIM/WMI mit DCOM-Fallback)
- SMB- und NFS-Freigaben-Erfassung mit Berechtigungen
- BSI-Grundschutz-Checks (heuristisch aus Scan-Daten)
- Web-UI mit REST-API
- SQLite-Datenbank, embedded
- Plattform: Windows (Service) + Linux (systemd)

## Installation

Fertige Installer fuer Windows und Linux stehen in der
[Releases-Seite](https://github.com/satitec/itscanner/releases) zur Verfuegung.

| Plattform | Datei |
|---|---|
| Windows (NSIS Installer) | `ITScanner-Server-Setup-X.XX.XX.exe` |
| Debian / Ubuntu (apt) | `itscanner-server_X.XX.XX_amd64.deb` |
| Linux universell (systemd) | `itscanner-server-linux-X.XX.XX.tar.gz` |

Auto-Update prueft automatisch das jeweils neueste Release in
diesem Repository.

## Lizenz

Closed-Source proprietaere Software. Alle Rechte vorbehalten.
Sat-iTec Systemhaus GmbH.

Fuer Lizenz-Fragen, Support oder Sonderanfragen:
**support@sat-itec.se**
