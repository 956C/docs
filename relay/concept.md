# Allgemein

Nostr Relays sind ein wesentlicher Teil des Pareto-Backends (neben dem Multimedia-Storage).
Auf ihnen werden essentielle Informationen verwaltet, daher ist der Betrieb eigener Relays für die Pareto-Lösung unverzichtbar.

## sicher

- short notes
- long form content
- direct messages
- public chat
- reactions / reposts
- Autoren-Profile (nprofile)
- lists generell und follow lists
- highlights
- calender
- relay based groups
- nostr connect / wallet connect
- lightning zaps und zap goals

## eventuell

- Wiki
- live activities
- video events

# Zugriff

Der Zugriff soll für verschiedene Nutzergruppen mit entsprechenden Rollen und Berechtigungen möglich sein.

## Leser

- nur lesend / kostenfrei / via URL mittels Browser / kein Nostr-Client (Account) erforderlich

## interaktiver User

- kostenfrei / via Nostr-Client (like, vote, repost, comment, highlight, zap, ???)

## Autor 

- content production / kostenpflichtig (pauschal oder nutzungsbasiert) / via Pareto-Client / Pareto-Account (Nostr-Domäne, Lightning-Adresse)

# Relay Eigenschaften

- Relays nach aktuellem Stand der Technik (max. Anzahl supporteter NIPS)
- paid Relays (um flooding und spamming zu verhindern)
- Relay-Pool (für Skalierung) mit load balancing (geht das?), auto-sync, auto-backup, etc.
- Relays auf verschiedene Data Center verteilt (Länder, Jurisdiktionen, Anbieter) für Hochverfügbarkeit (Verhinderung von Ausfällen und Sperren)
- möglichst caching, indexing, search, categorizing (für thematische Filter und Antispam-Option) → siehe Primal Services
- Monitoring, KPI und Alerts (Admin-Dashboard)

# Auswahl-Prozess

- Anbieter
- VPS-Typ
- Relay-Software
- Admin-Tools