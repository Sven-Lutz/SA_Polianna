# POLIANNA: Ein Datensatz zur Analyse von Klimapolitik-Design

## Überblick

Der POLIANNA-Datensatz wurde entwickelt, um die Analyse von Gestaltungselementen in Klimapolitiken zu unterstützen. Der Fokus liegt dabei auf der Automatisierung und Skalierbarkeit der Analyse, die traditionell manuell durchgeführt wurde. Der Datensatz adressiert zentrale Herausforderungen der Klimapolitikforschung, wie die Ambition und Wirksamkeit politischer Maßnahmen, und dient als Grundlage für die Entwicklung neuer textbasierter Analysewerkzeuge.

## Datensatzbeschreibung

Der POLIANNA-Datensatz umfasst eine umfassende Sammlung von Gestaltungselementen, die auf verschiedenen Abstraktionsebenen annotiert wurden. Die Annotationen basieren auf Textabschnitten aus EU-Klimapolitiken, darunter Richtlinien und Verordnungen, die sich auf die Minderung des Klimawandels und erneuerbare Energien beziehen.

### Besondere Merkmale
- **Granularität:** Die Texte wurden auf der Ebene einzelner Artikel annotiert, um maximale Flexibilität für Analysewerkzeuge zu gewährleisten.
- **Gestaltungselemente:** Der Datensatz erfasst:
  - Instrumententypen
  - Gestaltungseigenschaften
  - Technologie- und Anwendungsspezifität
- **Quellen:** Die Politiktexte stammen von [EUR-Lex](https://eur-lex.europa.eu/), der offiziellen Plattform der Europäischen Union für Rechtsdokumente.

## Ziele und Anwendungen

Der POLIANNA-Datensatz ermöglicht die Entwicklung und Evaluierung von Werkzeugen, die die Annotation und Analyse von Politikdesign automatisieren können. Zu den potenziellen Anwendungen zählen:
- Unterstützung bei der manuellen Annotation durch Vorschläge relevanter Textabschnitte.
- Vollständige Automatisierung der Textannotation in großem Maßstab.
- Forschung zur Entwicklung von evidenzbasierten Klimapolitiken.

## ClimateBERT

ClimateBERT ist ein spezialisierter Sprachmodellansatz, der auf Basis von BERT (Bidirectional Encoder Representations from Transformers) entwickelt wurde. Das Modell wurde speziell auf Domänentexte im Bereich Klimapolitik und Nachhaltigkeit trainiert, um eine höhere Präzision bei der Analyse relevanter Texte zu erreichen. Durch seine Anpassung an klimabezogene Dokumente bietet ClimateBERT eine bessere Leistung bei Aufgaben wie:
- Klassifikation politischer Texte
- Extraktion spezifischer Gestaltungselemente
- Identifikation von Trends in Politikdesigns

Im POLIANNA-Projekt wurde ClimateBERT für die Analyse von EU-Klimapolitiken eingesetzt. Das Modell ermöglicht es, komplexe Textstrukturen zu verstehen und die Annotationen effizienter zu gestalten.

## Outputs und Ergebnisse

Die Analyse des POLIANNA-Datensatzes liefert folgende Einblicke:
- **Verteilung der Gestaltungselemente:** Identifikation häufig genutzter Instrumententypen und Technologien in EU-Klimapolitiken.
- **Trends im Politikdesign:** Analyse von Veränderungen über die Zeit und zwischen unterschiedlichen Politikfeldern.
- **Leistung des Modells:** Hohe Genauigkeit und Übereinstimmung mit manuellen Annotationen, was die Validität der Ergebnisse stützt.
