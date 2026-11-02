# Istria Real Estate Market Analysis
# Exploring Property Market Opportunities for German Buyers

# Projektbeschreibung

Im Rahmen dieses Data-Analytics-Projekts wird der Immobilienmarkt in Istrien (Kroatien)
analysiert. Ziel ist es, die Entwicklung des Immobilienmarktes zu untersuchen
und Standorte zu identifizieren, die interessante Marktmerkmale für potenzielle
deutsche Immobilienkäufer aufweisen.

Hierfür werden offizielle Daten zu Preisen und Transaktionen von Wohnungen, Apartments und Familienhäusern
auf Ebene der istrischen Städte und Gemeinden mit Tourismusdaten kombiniert.

# Szenario

Istrien gehört zu den bedeutenden Tourismus- und Immobilienregionen Kroatiens.
Gleichzeitig stellt Deutschland einen wichtigen Herkunftsmarkt für den Tourismus
in Istrien dar.

Für potenzielle Immobilienkäufer unterscheiden sich die einzelnen Standorte
innerhalb Istriens hinsichtlich Preisniveau, Marktentwicklung, Anzahl der
Immobilientransaktionen und touristischer Nachfrage.

Das Projekt untersucht diese Unterschiede datenbasiert. Hintergrund ist eine
mögliche zukünftige Geschäftsidee, deutsche Immobilieninteressenten mit dem
kroatischen Immobilienmarkt in Istrien zu verbinden.

# Business Question

Welche Standorte in Istrien weisen attraktive Immobilienmarkt-Merkmale für
potenzielle deutsche Immobilienkäufer auf?

# Analysefragen

1. Wie haben sich die medianen Preise für Wohnungen und Apartments in Istrien zwischen 2012 und 2025 entwickelt?

2. Welche istrischen Städte und Gemeinden weisen 2025 die höchsten bzw.
   niedrigsten medianen Preise für Wohnungen, Apartments und Familienhäuser pro m² auf?

3. Wie hat sich die Anzahl der veröffentlichten Immobilientransaktionen zwischen
   2012 und 2025 entwickelt und welche Standorte weisen 2025 die höchste
   Marktaktivität auf?

4. Besteht 2025 ein Zusammenhang zwischen dem Preisniveau und der Anzahl
   der veröffentlichten Immobilientransaktionen?

5. Wie hat sich die touristische Nachfrage aus Deutschland in Istrien zwischen
   2019 und 2025 entwickelt?

6. Welche istrischen Standorte verbinden Immobilienmarktaktivität mit einer
   hohen touristischen Nachfrage?


## Verwendete Technologien

- **Python und pandas:** Datenbereinigung, Datenaufbereitung und explorative Datenanalyse
- **Matplotlib und Seaborn:** Statistische Visualisierungen während der Analyse
- **Jupyter Notebook:** Durchführung und Dokumentation der Analyseschritte
- **Power BI:** Interaktive Visualisierung und Präsentation der Analyseergebnisse

## Power BI Dashboard

Die Ergebnisse der Immobilienmarktanalyse wurden abschließend in einem Power-BI-Bericht aufbereitet.

Der Bericht umfasst vier Seiten:

1. **Projektübersicht** – Einführung in die Analyse
2. **Immobilienmarkt** – Entwicklung und Analyse des Immobilienmarktes
3. **Standortvergleiche** – Vergleich ausgewählter Standorte in Istrien
4. **Marktpotenzial** – Zusammenführung relevanter Kennzahlen zur Bewertung von Marktmerkmalen

Das Dashboard ergänzt die Python-Analyse und ermöglicht eine übersichtliche Darstellung der wichtigsten Erkenntnisse.

## Zentrale Analyseergebnisse

### 1. Entwicklung der Immobilienpreise (2012–2025)

Die Analyse der verfügbaren Standortdaten zeigt einen deutlichen Anstieg der medianen Quadratmeterpreise für Wohnungen und Apartments in Istrien.

- **2012:** ca. 1.185 €/m²
- **2025:** ca. 2.456 €/m²

Insbesondere in den letzten Jahren des Untersuchungszeitraums ist ein deutlicher Preisanstieg erkennbar.

Die Werte basieren auf den verfügbaren Standortdaten. Da nicht für alle Städte und Gemeinden in jedem Jahr Preisangaben vorliegen, ist die Vergleichbarkeit eingeschränkt.

### 2. Regionale Preisunterschiede

Die Immobilienpreise unterscheiden sich deutlich zwischen den istrischen Städten und Gemeinden.

Zu den Standorten mit den höchsten ausgewiesenen Quadratmeterpreisen für Wohnungen und Apartments im Jahr 2025 gehören:

- **Umag:** ca. 3.551 €/m²
- **Rovinj:** ca. 3.355 €/m²

Die regionalen Preisunterschiede verdeutlichen, warum eine standortbezogene Betrachtung für potenzielle Immobilienkäufer wichtig ist.

### 3. Marktaktivität und Immobilientransaktionen

Auch die Anzahl der veröffentlichten Wohnungstransaktionen unterscheidet sich zwischen den Standorten.

Im Jahr 2025 weisen insbesondere folgende Städte eine hohe Marktaktivität auf:

- **Pula:** 388 Transaktionen
- **Umag:** 255 Transaktionen
- **Poreč:** 212 Transaktionen

Die Transaktionszahlen liefern zusätzliche Informationen zur Marktaktivität und ergänzen die Betrachtung der Immobilienpreise.

### 4. Zusammenhang zwischen Preisniveau und Marktaktivität

Die Korrelationsanalyse für 2025 zeigt einen positiven, aber begrenzten Zusammenhang zwischen dem Preisniveau und der Anzahl der veröffentlichten Immobilientransaktionen.

- **Korrelationskoeffizient:** r ≈ 0,36
- **Untersuchte Standorte:** 14

Ein höheres Preisniveau geht somit nicht zwangsläufig mit einer höheren Marktaktivität einher. Aus der Korrelation lässt sich außerdem kein ursächlicher Zusammenhang ableiten.

### 5. Touristische Nachfrage aus Deutschland

Die Auswertung der Tourismusdaten zeigt einen Anstieg der Gästeankünfte aus Deutschland in Istrien:

- **2019:** ca. 1,05 Millionen Gästeankünfte
- **2025:** ca. 1,23 Millionen Gästeankünfte

Die touristische Nachfrage stellt einen ergänzenden Faktor bei der Betrachtung regionaler Marktmerkmale dar. Sie erlaubt jedoch allein keine Aussage über die Rentabilität einer Immobilieninvestition.

### 6. Fazit und geschäftliche Einordnung

Die Analyse zeigt, dass sich istrische Standorte hinsichtlich Immobilienpreisen, Marktaktivität und touristischer Nachfrage deutlich unterscheiden.

Für potenzielle deutsche Immobilienkäufer kann deshalb eine Kombination mehrerer Kennzahlen hilfreicher sein als die ausschließliche Betrachtung des Quadratmeterpreises.

Das Projekt verdeutlicht, wie öffentlich verfügbare Daten mithilfe von Python analysiert und anschließend in Power BI für eine verständliche, datenbasierte Entscheidungsunterstützung aufbereitet werden können.

**Hinweis:** Die Ergebnisse basieren auf den verfügbaren veröffentlichten Daten. Fehlende Preisangaben, unterschiedliche Datenverfügbarkeit und begrenzte Fallzahlen sind bei der Interpretation zu berücksichtigen.
