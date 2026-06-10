# 🌍 Freelancer Geo-Arbitrage & ETF Savings Calculator

Ein interaktiver Brutto-Netto-Rechner für deutsche Freiberufler (Selbstständige), die den Schritt ins Nicht-EU-Ausland (z. B. Thailand) wagen oder planen. Das Tool vergleicht die steuerlichen und abgabentechnischen Auswirkungen der gesetzlichen Krankenversicherung (GKV) in Deutschland mit den Kosten einer Auslands-Krankenversicherung inkl. GKV-Anwartschaft.

### 🔗 Live-Demo
Probiere den Rechner direkt im Browser aus:  
👉 **[https://fleischkuechle.github.io/Workation_earnings-calculator/](https://fleischkuechle.github.io/Workation_earnings-calculator/)**

---

## 🚀 Das Problem & Die Lösung

Wer als freiberuflicher Remote-Worker in Deutschland über der Beitragsbemessungsgrenze verdient, zahlt den **Höchstsatz in der GKV und Pflegeversicherung** (über 1.000 € im Monat). 

Verlegt man seinen Wohnsitz temporär oder dauerhaft in ein **Nicht-EU-Ausland**, entfällt die Pflichtmitgliedschaft. Stattdessen sichert man sich mit einer **Anwartschaftsversicherung** (gesetzlich fixiert) das Recht auf eine nahtlose Rückkehr in die deutsche GKV, während der reale Gesundheitsschutz extrem kostengünstig über eine **internationale Auslandskrankenversicherung** abgedeckt wird.

Dieses Tool berechnet exakt, wie viel Geld durch dieses Setup monatlich gespart wird und welchen **Hebel** diese Ersparnis über 5 Jahre am Aktienmarkt (ETF) entfaltet.

---

## 📊 Features & Berechnungsmodelle

Die App vergleicht **drei Lebensentwürfe** parallel und dynamisch:

1. **Modell 1: Deutschland**  
   Vollständige Abgabe von GKV + Pflegeversicherung (basierend auf der Beitragsbemessungsgrenze) sowie reguläre deutsche Einkommensteuer.
2. **Modell 2: Thailand (Pure Geo-Arbitrage)**  
   Wohnen im Ausland. Die GKV wird pausiert. Es fallen nur noch die **GKV-Anwartschaft (ca. 83,06 €)** sowie die **Auslands-KV (variabel, ca. 100–200 €)** an.
3. **Modell 3: Kombimodell (Thailand + Haus in DE)**  
   Für Digitale Nomaden, die ihre Zelte in Deutschland nicht komplett abbrechen wollen. Berechnet die Kosten im Ausland, während die laufenden Fixkosten für Immobilien/Wohnungen in Deutschland weitergetragen werden.

### Weitere Highlights:
* 📉 **Einkommensteuer-Schätzung:** Integrierte Steuerkurve basierend auf dem berechneten Netto-Einkommen.
* 📈 **5-Jahres-ETF-Effekt:** Automatische Simulation des Zinseszins-Effekts (Standard: 7% p.a.) für das gesparte Kapital plus vorhandenes Startkapital.
* 💾 **PDF-Export:** Ein optimiertes Stylesheet konvertiert die gesamte Übersicht per Knopfdruck in ein cleanes, druckbares PDF-Dokument ohne abgeschnittene Spalten.
* 🔄 **Local Storage:** Alle eingegebenen Stundensätze, Arbeitszeiten und individuellen Budgetkosten bleiben beim Neuladen des Browsers erhalten.

---

## 🛠️ Technologien

Das Projekt ist als **Single-Page-Application (SPA)** konzipiert, benötigt kein Backend und läuft direkt in jedem modernen Browser.

* **HTML5 / CSS3** (inkl. CSS Variables für Dark Mode & Print-Medien)
* **Vanilla JavaScript** (ES6+)
* **html2canvas** (v1.4.1) – Für das Rendern der UI in ein Bild
* **jsPDF** (v2.5.1) – Für die Generierung des PDF-Berichts

---

## 💻 Lokale Installation & Nutzung

Da es sich um eine reine Frontend-Anwendung handelt, kannst du das Tool entweder über die Live-Demo nutzen oder lokal ausführen:

1. Repository klonen:
```bash
   git clone [https://github.com/fleischkuechle/Workation_earnings-calculator.git](https://github.com/fleischkuechle/Workation_earnings-calculator.git)