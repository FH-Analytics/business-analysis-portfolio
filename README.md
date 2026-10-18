# business-analysis-portfolio
# Portfolio-Projekt: Digitaler Möbel-Konfigurator (HolzArt Manufaktur GmbH)
# Portfolio-Projekt: Business Analyse & Requirements Engineering (IREB)

Dieses Portfolio-Projekt entstand im Rahmen der Vorbereitung auf die IREB-Zertifizierung. Die Aufgabenstellung wird fortlaufend durch praktische Methoden des Requirements Engineerings gelöst, um eine vollständige Anforderungsspezifikation nach IREB-Standard zu erstellen.

---

## 1. Ausgangsszenario & Kundenauftrag

* **Kunde:** HolzArt Manufaktur GmbH (Mittelständischer Handwerksbetrieb für maßgefertigte Massivholzmöbel)
* **Ansprechpartner:** Thomas Weber (Geschäftsführer)

### Problemstellung
Die HolzArt Manufaktur wächst, jedoch stoßen die manuellen Prozesse in der Auftragsabwicklung an ihre Grenzen. Kundenanfragen und Bestellungen erfolgen derzeit über E-Mails, Anrufe oder Skizzen. Dies führt zu hohem Aufwand im Vertrieb, unvollständigen Werkstattzeichnungen, Nacharbeiten und teurem Verschnitt.

### Ziel des Projekts
Spezifikation und Entwicklung einer digitalen Lösung (**Online-Möbelkonfigurator mit integrierter ERP- und Werkstatt-Schnittstelle**). Kunden sollen Möbel online konfigurieren, bepreisen und bestellen können, während die Werkstatt automatisch aufbereite Fertigungsdaten erhält.

---

## 2. Systemkontext & Kontextdiagramm (IREB-Standard)

Zur eindeutigen Abgrenzung des zu entwickelnden Systems von seiner Umwelt (Systemgrenze) wurde das folgende Kontextdiagramm erstellt:

![Kontextdiagramm](./assets/Kontextdiagramm.png.png)
*[Editable Draw.io Source File](./assets/Kontextdiagramm.drawio)

### Methodische Erläuterung nach IREB
* **Systemgrenze:** Der Kreis in der Mitte umfasst das Gesamtsystem (Online-Konfigurator inkl. ERP-Anbindung).
* **Externe Akteure / Nachbarsysteme:** 
  * **Kunde:** Gibt Konfigurationsdaten ein und erhält Live-Preise sowie Auftragsbestätigungen.
  * **Werkstatt:** Empfängt die automatisiert generierten Fertigungsdaten zur Produktion.
* **Datenflüsse:** Die Pfeile repräsentieren ausschließlich reinen Informations- und Datenfluss 
