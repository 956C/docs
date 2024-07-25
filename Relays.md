1. Allgemein

Nostr Relays sind ein wesentlicher Teil des Pareto-Backends (neben dem Multimedia-Storage).
Auf ihnen werden essentielle Informationen verwaltet, daher ist der Betrieb eigener Relays für die Pareto-Lösung unverzichtbar.

a. sicher
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

b. eventuell
- Wiki
- live activities
- video events

2. Zugriff

Der Zugriff soll für verschiedene Nutzergruppen mit entsprechenden Rollen und Berechtigungen möglich sein.

a. Leser
- nur lesend / kostenfrei / via URL mittels Browser / kein Nostr-Client (Account) erforderlich
b. interaktiver User
- kostenfrei / via Nostr-Client (like, vote, repost, comment, highlight, zap, ???)
c. Autor 
- content production / kostenpflichtig (pauschal oder nutzungsbasiert) / via Pareto-Client / Pareto-Account (Nostr-Domäne, Lightning-Adresse)

3. Relay Eigenschaften

- Relays nach aktuellem Stand der Technik (max. Anzahl supporteter NIPS)
- paid Relays (um flooding und spamming zu verhindern)
- Relay-Pool (für Skalierung) mit load balancing (geht das?), auto-sync, auto-backup, etc.
- Relays auf verschiedene Data Center verteilt (Länder, Jurisdiktionen, Anbieter) für Hochverfügbarkeit (Verhinderung von Ausfällen und Sperren)
- möglichst caching, indexing, search, categorizing (für thematische Filter und Antispam-Option) → siehe Primal Services
- Monitoring, KPI und Alerts (Admin-Dashboard)

4. Auswahl-Prozess

- Anbieter
- VPS-Typ
- Relay-Software
- Admin-Tools