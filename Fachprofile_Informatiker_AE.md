# Fachprofile Informatiker/in EFZ Applikationsentwicklung für den Lerncoach

Gilt für: Informatiker/in EFZ, Fachrichtung Applikationsentwicklung (Bildungsverordnung 2021), Schweiz.
Rangfolge: Unterrichtsmaterial > Angaben des Nutzers > dieses Profil > allgemeines Wissen.
Ein Thema aus diesem Profil wird erst zum Lernziel, wenn der Nutzer es als Lernziel nennt.
Hinweis: Modultitel und üK-Liste mit dem Modulplan der eigenen Schule bzw. modulbaukasten.ch abgleichen.

## Allgemeine Stufen-Logik
- Stufe 1: Wissen. Begriff, Regel, Definition oder Fakt wiedergeben.
- Stufe 2: Verstehen. Eine Standardaufgabe lösen, wie sie im Unterricht vorgemacht wurde.
- Stufe 3: Anwenden. Mehrere Schritte oder bekannte Methoden kombinieren.
- Stufe 4: Analysieren. Unbekannter, aber realistischer Kontext (z. B. Fallbeispiel aus dem Betrieb, fremder Code, Anforderung eines Kunden).
- Stufe 5: Beurteilen und Transfer. Prüfungsniveau: mehrere Themen kombinieren, begründen, bewerten oder etwas Eigenes entwerfen.

---

## E0 Niveau und Struktur
- 4 Jahre, Bildungsverordnung 2021. Berufsfachschule: 24 Module (960 Lektionen). Überbetriebliche Kurse (üK): 7 Module. Dazu ABU, Sport, Englisch, ggf. BMS.
- Jedes Modul hat Handlungsziele und eine Leistungsbeurteilung gemäss ICT-Modulbaukasten (modulbaukasten.ch). Die Lernziele dort sind massgebend.
- Die Modulnummern sind fix. Reihenfolge und Zuordnung zu den Semestern hängen von der Schule ab. Halte dich an den Modulplan im Material.
- Niveau: praxisnah und handlungsorientiert. Prüfungen sind oft am PC (Code schreiben, SQL ausführen, Diagramm erstellen) und teils Open Book, plus Theorie. Stufe 4–5 bedeutet: ein Problem aus dem Betriebsalltag lösen.
- Beispiele immer aus dem Berufsalltag: Webshop, Kundendatenbank, Ticketsystem, Login, Logfiles, API, Lager-App.
- Sprachen und Tools sind je nach Schule unterschiedlich (C#, Java, Python, JavaScript/TypeScript, SQL, PowerShell oder Bash). Übernimm die Sprache aus dem Material und frag nach, wenn sie unklar ist.
- Mathe-Grundlagen (Zahlensysteme, Bit/Byte, Logik, Prozent) stecken vor allem in Modul 114 und in der BMS.
- Code-Aufgaben: Ausgabe vorhersagen, Fehler finden, ergänzen oder selbst schreiben. Zahlensysteme immer mit Index kennzeichnen (z. B. 1011₂, 2F₁₆, 47₁₀).

## E1 Module Berufsfachschule

### 114 Codierungs-, Kompressions- und Verschlüsselungsverfahren einsetzen
- Themen: Zahlensysteme (binär, oktal, dezimal, hexadezimal), Zweierkomplement, Bit/Byte, Präfixe (kB vs. KiB), Zeichencodierung (ASCII, Unicode, UTF-8), Bildcodierung (RGB, Farbtiefe), verlustfreie und verlustbehaftete Kompression (RLE, Huffman, LZW, JPEG), Prüfsummen und Fehlererkennung (Parität, Hash), symmetrische und asymmetrische Verschlüsselung, Caesar und Vigenère, Signaturen, Zertifikate.
- Hilfsmittel: Umrechnungen meist ohne Taschenrechner.
- Stufe 5: Speicherbedarf eines Bildes vor und nach der Kompression berechnen, oder ein Verschlüsselungsverfahren für einen Anwendungsfall begründet wählen.

### 117 Informatik- und Netzinfrastruktur für ein kleines Unternehmen realisieren
- Themen: OSI- und TCP/IP-Modell, IPv4-Adressen, Subnetting (CIDR), Gateway, DNS, DHCP, Switch und Router, Verkabelung, Freigaben und Berechtigungen, Netzwerkplan.
- Stufe 5: Netzplan für ein KMU mit Subnetzen und Adressierung erstellen.

### 122 Abläufe mit einer Scriptsprache automatisieren
- Themen: Scripting (PowerShell, Bash oder Python), Variablen, Schleifen, Bedingungen, Parameter, Dateien und Logs verarbeiten, Fehlerbehandlung, Zeitplanung (Task Scheduler, cron).
- Stufe 5: Skript, das Logfiles auswertet und einen Report erstellt.

### 162 Daten analysieren und modellieren
- Themen: Datenarten und Datenformate (CSV, JSON, XML), Datenqualität, Entitäten, Attribute, Beziehungen, ERM bzw. ERD (Kardinalitäten 1:1, 1:n, n:m), Normalisierung (1. bis 3. Normalform), konzeptionelles und logisches Modell.
- Stufe 5: Aus einer Textbeschreibung ein normalisiertes ERD erstellen.

### 164 Datenbanken erstellen und Daten einfügen
- Themen: relationales Modell, DDL (CREATE, ALTER, DROP), Datentypen, Primär- und Fremdschlüssel, Constraints, DML (INSERT, UPDATE, DELETE), Datenimport, referentielle Integrität.
- Stufe 5: Aus einem ERD ein vollständiges SQL-Skript mit Constraints und Testdaten schreiben.

### 165 NoSQL-Datenbanken einsetzen
- Themen: Typen (Dokument-, Key-Value-, Graph- und Spaltendatenbanken), CAP-Theorem, MongoDB-Abfragen, Datenmodellierung (Embedding vs. Referencing).
- Stufe 5: Relationales Modell in ein Dokumentenmodell überführen und die Wahl begründen.

### 183 Applikationssicherheit implementieren
- Themen: OWASP Top 10, SQL-Injection, XSS, CSRF, Authentifizierung und Autorisierung, Passwort-Hashing (Salt), Sessions und Tokens (JWT), Input-Validierung, Logging.
- Stufe 5: Verwundbaren Code finden, Angriff erklären und eine Korrektur schreiben.

### 231 Datenschutz und Datensicherheit anwenden
- Themen: revDSG (Schweiz) und DSGVO, Personendaten und besonders schützenswerte Daten, Schutzziele (Vertraulichkeit, Integrität, Verfügbarkeit), Backup-Strategien (3-2-1), Passwortmanagement, Verschlüsselung, Phishing.
- Stufe 5: Datenschutzproblem in einem Fallbeispiel erkennen und Massnahmen vorschlagen.

### 241 Innovative ICT-Lösungen initialisieren / 245 Innovative ICT-Lösungen umsetzen
- Themen: Innovationsmethoden (Design Thinking), Business Case, Machbarkeit, Prototyp, Umsetzung und Präsentation.
- Eher Coaching und Methodenfragen als Rechenaufgaben.

### 254 Geschäftsprozesse im eigenen Berufsumfeld beschreiben
- Themen: Prozessbegriff, BPMN (Ereignisse, Aktivitäten, Gateways, Pools/Lanes), Ist- und Sollprozesse, Prozessoptimierung.
- Stufe 5: Prozess aus einer Beschreibung als BPMN modellieren und eine Schwachstelle verbessern.

### 293 Webauftritt erstellen und veröffentlichen
- Themen: HTML5-Struktur und Semantik, CSS (Selektoren, Box Model, Flexbox, Grid, Responsive, Media Queries), Barrierefreiheit, Formulare, Hosting, Domain, FTP bzw. Deployment.
- Stufe 5: Responsives Layout nach Vorgabe mit semantischem HTML umsetzen.

### 306 Kleinprojekte im eigenen Berufsumfeld abwickeln
- Themen: Projektauftrag, Ziele (SMART), Phasenmodell (z. B. IPERKA, HERMES), Zeitplan und Gantt, Risiken, Ressourcen, Controlling, Abschlussbericht.
- Stufe 5: Kleines Projekt vollständig planen, inkl. Risikoanalyse.

### 319 Applikationen entwerfen und implementieren
- Themen: Grundlagen der Programmierung: Variablen, Datentypen, Operatoren, Verzweigungen, Schleifen, Methoden bzw. Funktionen, Arrays und Listen, Ein- und Ausgabe, Struktogramm bzw. Aktivitätsdiagramm, Debugging, Coding Conventions.
- Aufgabentypen: Code-Ausgabe vorhersagen, Fehler finden, Algorithmus als Struktogramm, kleines Programm schreiben, Trace-Tabelle.
- Stufe 5: Konsolenapplikation aus einer Anforderung entwerfen, z. B. ein Notenrechner mit Validierung.

### 320 Objektorientiert programmieren
- Themen: Klasse und Objekt, Attribute, Methoden, Konstruktor, Kapselung (Zugriffsmodifizierer), Vererbung, Polymorphie, Interfaces und abstrakte Klassen, UML-Klassendiagramm, Komposition und Aggregation, Collections.
- Stufe 5: Aus einer Fachbeschreibung ein Klassendiagramm entwerfen und implementieren.

### 321 Verteilte Systeme programmieren
- Themen: Client-Server, Kommunikationsmuster, REST, Messaging, Nebenläufigkeit, Konsistenz, Fehlertoleranz.
- Stufe 5: Architektur für ein verteiltes Szenario skizzieren und Fehlerfälle behandeln.

### 322 Benutzerschnittstellen entwerfen und implementieren
- Themen: Usability-Prinzipien (Normen, Gestaltgesetze), Personas, Wireframes und Mockups, Prototyping, UI-Implementation, Usability-Tests.
- Stufe 5: Bestehende UI analysieren, Mängel benennen, verbesserten Entwurf begründen.

### 323 Funktional programmieren
- Themen: Pure Functions, Immutability, Higher-Order Functions (map, filter, reduce), Lambdas, Rekursion, Funktionskomposition.
- Stufe 5: Imperativen Code in funktionalen Stil umschreiben.

### 324 DevOps-Prozesse mit Tools unterstützen
- Themen: Git (Branches, Merge, Merge Requests), CI/CD-Pipelines, automatisierte Tests in der Pipeline, Deployment, Monitoring.
- Stufe 5: Pipeline für ein Projekt entwerfen und Fehler in einer Pipeline-Konfiguration finden.

### 346 Cloud-Lösungen konzipieren und realisieren
- Themen: IaaS, PaaS, SaaS, Public, Private und Hybrid Cloud, Kostenmodelle, Skalierung, Verfügbarkeit, Datenstandort und Datenschutz (Schweiz).
- Stufe 5: Cloud-Architektur für einen Anwendungsfall wählen und die Kosten abschätzen.

### 347 Dienst mit Container anwenden
- Themen: Container vs. VM, Docker (Image, Container, Dockerfile, Volumes, Netzwerke), docker compose, Registry, Grundbegriffe der Orchestrierung.
- Stufe 5: Dockerfile und Compose-Datei für eine App mit Datenbank schreiben.

### 426 Software mit agilen Methoden entwickeln
- Themen: Agiles Manifest, Scrum (Rollen, Events, Artefakte), User Stories mit Akzeptanzkriterien, Story Points, Kanban, Burndown.
- Stufe 5: Sprint für ein Szenario planen, oder eine Scrum-Fehlsituation beurteilen.

### 431 Aufträge im eigenen Berufsumfeld selbstständig durchführen
- Themen: Auftragsabwicklung (z. B. IPERKA), Lernjournal und Arbeitsjournal, Dokumentation, Zeitmanagement, Reflexion.
- Eher Coaching, wenig Rechnen.

### 450 Applikationen testen
- Themen: Testarten (Unit-, Integrations-, System- und Abnahmetest), Testpyramide, Black- vs. White-Box, Äquivalenzklassen, Grenzwertanalyse, Testfälle und Testprotokoll, Testautomatisierung, Code Coverage, TDD.
- Stufe 5: Für eine Funktion vollständige Testfälle mit Äquivalenzklassen und Grenzwerten herleiten und als Unit-Tests schreiben.

## E2 Überbetriebliche Kurse (üK)
Typisch für Applikationsentwicklung, im Modulplan prüfen:
- 187 ICT-Arbeitsplatz mit Betriebssystem in Betrieb nehmen
- 106 Datenbanken abfragen, bearbeiten und warten (SELECT, JOIN, GROUP BY, Subqueries, Views, Rechte, Backup)
- 294 Frontend einer interaktiven Webapplikation realisieren
- 295 Backend für Applikationen realisieren (REST-API, CRUD)
- 210 Public Cloud für Anwendungen nutzen
- 223 Multi-User-Applikationen objektorientiert realisieren (Transaktionen, Concurrency)
- 335 Mobile-Applikation realisieren
Die üK sind sehr praktisch und enden mit einem Kompetenznachweis. Üben mit Code- und Umsetzungsaufgaben.

## E3 Allgemeinbildung und weitere Fächer
- ABU: Sprache und Kommunikation sowie Gesellschaft (Recht: Lehrvertrag, Miete, Kauf, Versicherungen; Politik: Schweizer Staatssystem, Abstimmungen; Wirtschaft: Budget, Steuern, Konsum; Ethik, Ökologie). Zur Schlussprüfung gehört eine Vertiefungsarbeit. Fallbeispiele aus dem Leben von Lernenden.
- Englisch: Fachenglisch IT (Dokumentation lesen, Fehlermeldungen, E-Mails, Präsentationen). Niveau ca. B1–B2.
- BMS (falls besucht): Mathematik (Algebra, Funktionen, Geometrie, Trigonometrie, Statistik; technische Richtung zusätzlich Analysis und Vektoren), Deutsch, Französisch, Englisch, Geschichte und Politik, Wirtschaft und Recht, Naturwissenschaften. Niveau ähnlich wie im Gymi, aber anwendungsorientierter.

## E4 Qualifikationsverfahren (QV)
- IPA (Individuelle Praktische Arbeit) im Betrieb, Erfahrungsnoten aus den Modulen, ABU-Prüfung.
- Bei der IPA hilft der Coach nur mit Methodik und Fragen, keine fertigen Texte oder Code.
