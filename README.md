# Geographisch aufgelöstes Modell für den Mikroplastik-Abrieb durch Besen und Kehrmaschinen
In diesem Repository befindet sich die vollständige Dokumentation der Modellierung des Mikroplastik-Abriebs durch Besen und Kehrmaschinen, die im Rahmen des Projektes *mMEU - Mobilitätsbedingte Mikroplastikemissionen in der Umwelt* durchgefüht wurde, inklusive der verwendeten Eingangsdaten und der Modellergebnisse. Das Projekt wurde vom Bundesministerium für Digitales und Verkehr als Teil der Innovationsinitiative mFUND gefördert. Link zur Projektwebsite: https://projekt-mmeu.de/

Zur Modellierung der Mikroplastik-Emissionen, die durch Besen und Kehrmaschinen im Berliner Stadtgebiet anfallen, werden georeferenzierte Daten der Berliner Stadtreinigung bzgl. der Reinigungshäufigkeit mit Literaturwerten zur Abriebsmenge verknüpft. Ergebnis der Modellierung ist ein georefenzierter Datensatz, der die spezifischen Mikroplastik-Abriebsmengen durch Besen und Kehrmaschinen auf Berliner Straßen abbildet. Dieser wird als Shapefile (.shp) zur Verfügung gestellt und durch eine Dokumentation im PDF-Format erläutert.

## Inhalte des Repositories
* `Ergebnisse/Mikroplastik_Emissionen_Straßenreinigung.zip`
Ausgangsdaten des Modells als zip-komprimiertes Shapefile
* `Ergebnisse/Dokumentation_Mikroplastik_Emissionen_Straßenreinigung.pdf`
Dokumentation des Datensatzes, Erklärung der Merkmale.
* `Eingangsdaten/Reinigungsklassen.zip`
Eingangsdaten von Berliner Stadtreinigung (BSR) (2012) als zip-komprimiertes Shapefile
* `Besen_Kehrmaschinen.ipynb`
Jupyter-Notebook, in dem das Modell in Textzellen hergeleitet und beschrieben wird, sowie in Python-Codezellen direkt ausgeführt werden kann.
* `README.md`
Beschreibung des Repositories (diese Datei)
* `requirements.txt`
Spezifikation der verwendeten Python-Pakete und deren Versionen. Insbesondere benötigt für die Erstellung einer im Browser ausführbaren Ansicht mit [binder](https://mybinder.org/).

## Datenquellen
Alle verwendeten Datenquellen sind unter der Creative Commmons Namensnennung 3.0 Deutschland (CC BY 3.0 DE) Lizenz öffentlich verfügbar.

* GEO-Daten für die Straßenverzeichnisse und Reinigungsklassen in Berlin
Berliner Stadtreinigung (BSR) (2012). BSR Straßenreinigung - Verzeichnisse und Reinigungsklassen. Berlin Open Data. https://daten.berlin.de/datensaetze/bsr-stra%C3%9Fenreinigung-verzeichnisse-und-reinigungsklassen 
* Mikroplastik-Abrieb durch Besen und Kehrmaschinen in Deutschland pro Kopf und Jahr   
Bertling, Jürgen; Bertling, Ralf; Hamann, Leandra (2018): Kunststoffe in der Umwelt: Mikro- und Makroplastik. Ursachen, Mengen, Umweltschicksale, Wirkungen, Lösungsansätze, Empfehlungen. Kurzfassung der Konsortialstudie, Fraunhofer-Instititut für Umwelt-, Sicherheits- und Energietechnik UMSICHT (Hrsg.), Oberhausen.
https://www.umsicht.fraunhofer.de/content/dam/umsicht/de/dokumente/publikationen/2018/kunststoffe-id-umwelt-konsortialstudie-mikroplastik.pdf
* Bevölkerungszahl Berlin   
Amt für Statistik Berlin-Brandenburg (o.J): Bevölkerungsstand.  
https://www.statistik-berlin-brandenburg.de/bevoelkerung/demografie/bevoelkerungsstand

## Binder
Das Modell kann ohne vorherige Installation über folgenden Link als interaktives Jupyter-Notebook im Browser aufgerufen werden:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/projekt-mmeu/mp-strassenreinigung/main?labpath=Besen_Kehrmaschinen.ipynb)

Beim ersten Aufruf wird das Notebook und eine virtuelle Umgebung initialisiert. Dieser Vorgang kann einige Minuten in Anspruch nehmen.

## Urheber
János Sebestyén, Jonathan Kirchhoff (beide Wuppertal Institut für Klima, Umwelt, Energie gGmbH)

## Lizenz
Sämtliche Inhalte des Repositories stehen unter der Creative Commmons Namensnennung 3.0 Deutschland (CC BY 3.0 DE) Lizenz. Sie können geteilt und weiterverarbeitet werden, wenn dabei auf die Urheber und die Lizenz verwiesen wird und eventuelle Änderungen kenntlich gemacht werden. Die vollständige Lizenz kann unter folgendem Link eingesehen werden:
https://creativecommons.org/licenses/by/3.0/de/

Jahr der Veröffentlichung: 2022
