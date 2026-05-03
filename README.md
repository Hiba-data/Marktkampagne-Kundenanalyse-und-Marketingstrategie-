 Marketing Data Analysis using Machine Learning
Marketing-Datenanalyse auf Basis von Machine Learning.
Ziel dieser Arbeit ist es, Kunden besser zu verstehen, sie in sinnvolle Segmente zu unterteilen und ihre Reaktion auf Marketingkampagnen vorherzusagen.

 Project Objectives

Die Analyse konzentriert sich auf drei zentrale Fragestellungen:

Wie können Kunden sinnvoll segmentiert werden?
Welche Faktoren beeinflussen das Einkommen der Kunden?
Wie reagieren unterschiedliche Kundengruppen auf Marketingkampagnen?
 Models Used

Im Projekt wurden drei Machine-Learning-Modelle eingesetzt:

Einkommensvorhersage (Regression)
→ Vorhersage des Einkommens basierend auf Kundendaten
Kundensegmentierung (Clustering – K-Means)
→ Identifikation von Kundengruppen mit ähnlichen Eigenschaften
Kampagnenklassifikation (Random Forest)
→ Vorhersage, ob ein Kunde auf eine Marketingkampagne reagiert 
-- Dataset Overview
Zeilen: 2.240
Spalten: 27

Die Features umfassen:

🧑 Kundeninformationen
💰 Ausgaben & Kaufverhalten
📢 Marketinginteraktionen
📅 Kundendaten & Beschwerden

Der Datensatz ist gut strukturiert und ermöglicht vielfältige Analysen.

⚙️ Workflow

Der Analyseprozess bestand aus folgenden Schritten:

Datenverständnis & Exploration
Datenbereinigung & Vorbereitung
Feature Engineering
Modelltraining
Evaluation & Optimierung
Interpretation der Ergebnisse
📈 Key Results
💰 Income Prediction
R² ≈ 0.75
Modell erklärt ~75 % der Einkommensvarianz
Kein Overfitting → stabile Generalisierung

👉 Anwendung:

Schätzung fehlender Einkommenswerte (Imputation)
👥 Customer Segmentation
Optimale Clusteranzahl: k = 3
Hauptunterscheidungsmerkmale:
Einkommen
Haushaltsgröße
Bildungsniveau

Cluster:

🏆 Premium Kunden
💻 Cyber Kunden
🏷️ Rabatt Kunden
🎯 Campaign Classification
Bestes Modell: Random Forest (optimiert mit GridSearchCV)
F1-Score: 0.82

Ergebnisse:

Hohe Precision (keine False Positives)
Guter Recall
Starke Gesamtleistung
🔍 Key Insights
Einkommen ist der wichtigste Einflussfaktor
Kunden unterscheiden sich stark in Kaufverhalten und Rabattnutzung
Online-Kaufverhalten variiert je nach Segment
Nicht alle Kampagnen funktionieren gleich gut für alle Kunden
💡 Business Recommendations
🎯 Zielgerichtete Kampagnen pro Kundensegment
💎 Fokus auf High-Value Kunden (Premium Segment)
🏷️ Rabattstrategien für preissensitive Kunden optimieren
🌐 Online-Marketing für digitale Kundengruppen verstärken
🚀 Conclusion

Diese Analyse zeigt, wie Machine Learning genutzt werden kann, um:

Kunden besser zu verstehen
Marketing effizienter zu gestalten
datengetriebene Entscheidungen zu treffen
