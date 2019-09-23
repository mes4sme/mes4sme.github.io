Die dynamische Natur produktionsprozessbezogener Parameter erfordert den Einbezug von Unsicherheiten in die Fertigungsplanung. Bei der Produktionsplanung für Einzelfertiger besteht eine besondere Herausforderung, da diese Prozessparameter aufgrund der Individualität der einzelnen Kundenaufträge schwer abschätzbar sind.
Hier setzt das MES4SME Projekt an um mithilfe datengetriebener Optimierungsverfahren die effiziente Produktionsplanung im Kontext von Einzelfertigung zu erforschen.
Konkret hat MES4SME folgende Ziele:
* Integrationskomponente zur Sammlung, Aufbereitung und Bereitstellung aller erhobenen Produktionsdaten
* Process Mining Komponente zur datengetriebenen Identifikation der Produktionsprozesse für alle Produktvarianten
* Predictive Analysis Methoden zur Schätzung von Prozessvariablen, Materialfluss und Maschinenzustand
* Kognitives Dashboard für die nachvollziehbare Kommunikation der Predictive Analysis Ergebnisse für Experten
* Multikriterielle Optimierung der Produktionspläne

## Projektkonsortium

* FASTEC GmbH, Paderborn (Entwicklungspartner)
* pmOne Analytics GmbH, Paderborn (Entwicklungspartner)
* Deutsches Forschungszentrum für Künstliche Intelligenz GmbH (DFKI), Saarbrücken (Forschungspartner)
* Brabant & Lehnert GmbH, Wadern (Anwendungspartner)
* Verband Deutscher Maschinen- und Anlagenbau (VDMA), Frankfurt (Assoziierter Partner)
* Projektlaufzeit: 01.09.2018 - 31.08.2020

## Arbeitspakete

### Arbeitspakt 1: Anforderungsanalyse und -spezifikation

Um die aktuellen Engpässe, Bedürfnisse und Herausforderungen in der Optimierung der Produktionsplanung bei Einzelfertigern zu verstehen, ist es von entscheidender Bedeutung, zunächst sowohl die Produktions- als auch die Geschäftsprozesse bei dem Anwendungspartner zu erheben und deren Verknüpfung zu identifizieren. Zu diesem Zweck werden die Interviews mit den Experten von Brabant und Lehnert durchgeführt und zudem wird die Angemessenheit der Anwendung von den datengetriebenen Prozesserkennungsansätze untersucht. Sobald das Gesamtbild der Prozesse vorliegt, werden die Anwendungsszenarien erarbeitet und präzisiert. Diese Szenarien beinhalten als Vorarbeit zu AP5 auch Überlegungen zur Integration verschiedener analytischer Komponenten und Datenschichten, um die Produktionsplanung zu optimieren.

### Arbeitspakt 2: Prozessdatenakquisition, -integration und -aggregation

Im Fokus dieser Teilaufgabe steht die Anpassung und Inbetriebnahme von Maschinen-, Prozess- und Betriebsdaten-Modulen zur Erfassung und Bereitstellung der Betriebs- und Prozessdaten bei Brabant und Lehnert. Für die Erfassung der benötigten Daten aus der Produktion sind zunächst die notwendigen Schnittstellen zu den Maschinen und Prozessen zu schaffen. Diese Daten sollen unterschiedliche Dimensionen der Prozesse beschreiben, die erforderlich sind, um vorausschauende Schätzungen der wirtschaftlichen und technischen Parametern zu erstellen, um die Feinplanung bei Einzelfertigern durchzuführen. Dabei spielt die Einbindung von kundenindividuellen Bestellvorgaben in die produktionstechnischen Prozessdetails eine zentrale Rolle, die die zu implementierende ERP-Schnittstelle bereitstellen kann.

### Arbeitspakt 3: Datengetriebene Analyse der Produktionsprozessdaten

Die MES und ERP Systeme können die während der jeweiligen Prozessausführung generierten Aktivitäten protokollieren. Solche Prozessdaten dienen als wertvolle Quelle zur Durchführung von prädiktiven Analysen, die den Entscheidungsprozess durch Einblicke in das Prozessverhalten vorantreiben. In dieser Teilaufgabe wird erforscht, wie die Prozessinformationen in Prognosemodelle integriert werden können. In diesem Zusammenhang sollen fortschrittliche Process Mining Modelle hinsichtlich einer Erweiterung um Prognoseeigenschaften untersucht werden. Dabei werden verschiedene Algorithmen zur Identifikation der tatsächlichen Produktionsprozesse (Process Discovery), Clustering von Produktionsdaten anhand der Spezifikationen der Kundenaufträge und Prozessverbesserungen (Process Enhancement) angewendet. Ein effektives Design und die Implementierung solcher prädiktiven Ansätze sind entscheidend, um sicherzustellen, dass die Aktivitäten in der gewünschten Weise ablaufen, indem Fehler und Abweichungen von den geplanten Prozessstrukturen vorhergesagt bzw. vermieden werden.

### Arbeitspakt 4: Methoden zur Optimierung der Fertigungspläne

Der von der Predictive Analytics bereit zu stellende Arbeitsplan mit seinen möglichen Fertigungsvarianten muss unter Berücksichtigung multikriterieller Ziel- und Einflussgrößen auf die vorhandenen Ressourcen verplant werden. Optimierungsziele können einerseits materielle Ziele wie die Maximierung des Gesamtgewinns und der Maschinenkapazität oder die Minimierung der Gesamtkosten, der Produktionslaufzeit und der Lagerbestände sein. Andererseits können auch immaterielle Ziele wie die Maximierung der Kundenzufriedenheit (durch z.B. Liefertreue) angestrebt oder mehrere Ziele gleichzeitig optimiert werden. Die Ziele werden durch Interviews mit Fachexperten von Brabant und Lehnert definiert. Dabei spielen auch automatisches Berücksichtigen von Kapazitäten (ausreichend Personal, Material und sonstige Betriebsmittel vorhanden?), das Berücksichtigen alternativer Arbeitsgänge oder Arbeitspläne wie auch notwendiger Transport- und Liegezeiten, die Abhängigkeit mehrerer Ressourcen, die durchgängige Transparenz über die gesamte Planung usw. eine wichtige Rolle. In dieser Teilaufgabe wird erforscht, wie diese Informationen zur Konzeption der Optimierungsprobleme integriert werden können. 

### Arbeitspakt 5: Prototypische Systemintegration

Ziel dieser Aufgabe ist zunächst die Konzeption einer Gesamtarchitektur bestehend aus Einzelkomponenten der Partner. Für jede Komponenteninteraktion wird weiterhin eine Schnittstellenspezifikation erstellt. Auf Basis der Architektur erfolgt eine sukzessive Integration aller entwickelten Komponenten zu einer prototypischen Demonstrator-Realisierung.

### Arbeitspakt 6: Prototypischer Einsatz und Evaluation

In diesem Teilarbeitspaket wird der iterativ entwickelte Prototyp – dessen Modulbestandteile gemäß der in AP 5 definierten Gesamtarchitektur integriert werden bei Brabant und Lehnert in die Arbeitsvorbereitung eingeführt und im Praxistest erprobt. Die hier gesammelten Erfahrungen, werden unzweifelhaft zu Änderungen und Anpassungen führen, die gemeinsam von den IKT-Partnern umzusetzen sind. Diese werden auf Seiten von FASTEC zum einen die Datenlieferung aus der Produktion und auf Seiten von pmOne den Algorithmus der Analyse und Optimierung betreffen. 

### Arbeitspakt 7: Projektmanagement, Öffentlichkeitsarbeit und Breitenwirkung

Aufgaben des fachlichen Projektmanagements sind die Planung, Organisation, Steuerung und Kontrolle der einzelnen Teilaufgaben gemäß der festgelegten Arbeitsplanung. Insbesondere die Kommunikation unter allen Projektpartnern ist eine notwendige Voraussetzung für ein zielgerichtetes Handeln. Die einzelnen Aspekte werden zu Projektbeginn in einem Projektmanagementplan detailliert zusammengefasst. Zusätzlich beschäftigt sich dieses Arbeitspaket mit dem kontinuierlichen Risikomanagement der Projektdurchführung.

## Förderung

MES4SME ist eine Fördermaßnahme des Bundesministerium für Bildung und Forschung (BMBF, KMU-innovativ: IKT, Forschunkskennzeichen 01IS18021A, 01IS18021B, 01IS18021C). [Link zum Projektblatt](https://www.softwaresysteme.pt-dlr.de/media/content/Projektblatt_MES4SME.pdf)
