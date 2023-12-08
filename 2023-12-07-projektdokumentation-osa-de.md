Projektdokumentation
====================

***Moodle-Plugin zur integrierten und nachhaltigen Umsetzung und Anwendung von Online Self Assessments an der Pädagogischen Hochschule Weingarten***

**Simon Schaudt** **Manuel Ecker**

**E-Mail: zendi\@ph-weingarten.de**



# <a name="laufzeitkonzeptionundprogrammierung"></a>Laufzeit der Konzeption und Programmierung

| Laufzeit                                           | Monate  |
| :------------------------------------------------- | :------ |
| **Konzeption des OSAs:**                           | **2**   |
| **Programmierung des OSA Plugins:**                | **6,5** |
| **Dokumentation und Veröffentlichung auf Github:** | **0,5** |
| Gesamtprojektlaufzeit PHokus:                      | **29**  |
| Gesamtprojektlaufzeit TEgoDi:                      | **36**  |

Übersicht über die Laufzeit der Konzeption und Programmierung

# <a name="hinweisesoftwarereleasestatus"></a>Hinweise zum Softwarereleasestatus

| Hinweise zum Softwarereleasestatus \[1\]                     | Datum          |
| :----------------------------------------------------------- | :------------- |
| Der Code des OSA Plugins befindet sich im **Alpha** Stadium. | **2023-12-08** |

Hinweise zum Softwarereleasestatus

# <a name="moodlepluginosa"></a>Entwicklungsprojektkontext

Online Self Assessments (OSAs) sind Selbst-Rating-Verfahren, die an Hochschulen sowohl zur Studienorientierung als auch zur Unterstützung des Lernverhaltens im Studium Anwendung finden, um den Studienerfolg zu erhöhen (Diercks et al., 2009; Petri et al., 2022; Schmidt-Atzert et al., 2019). Sie haben das Potenzial, Studierende bei der Selbstregulation ihres Lernverhaltens zu unterstützen. Eine strukturierte Reflexion von Lernerfahrungen oder dem aktuellen Wissensstand wird unterstützt und gibt so Orientierung für individuelle Lernziele (Baars et al. 2014; Boud & Brew, 1995; Schmidt-Atzert et al., 2019).

An der Pädagogischen Hochschule Weingarten werden Online Self Assessments in unterschiedlichen Kontexten eingesetzt. Insbesondere im Hinblick auf Maßnahmen zur Sicherung des Studienerfolgs prognostiziert das Prorektorat für Lehre und Studium eine wachsende Bedeutung dieser Werkzeuge. Die beiden zentralen OSAs entstanden in den Projekten TEgoDi und PHokus. Um die weitere Nutzung dieser Entwicklungen nachhaltig in die Servicestruktur der Hochschule einbinden zu können und eine Professionalisierung der Weiterentwicklung sicherzustellen, wurde die Entwicklung und Programmierung eines Moodle-Plugins im Zentrum für Digitalisierung (ZenDi) initiiert.

## <a name="projekttegodi"></a>Projekt TEgoDi

Im Rahmen der gemeinsamen „Qualitätsoffensive Lehrerbildung“\[2\] von Bund und Ländern wurde an der Pädagogischen Hochschule Weingarten das Projekt „Teacher Education goes Digital“\[3\] (01.03.2020 bis 31.12.2023) vom  Bundesministerium für Bildung und Forschung gefördert\[4\]. Ziel von TEgoDi war die wissenschaftlich fundierte und forschungsbasierte Vermittlung digitalisierungsbezogener Kompetenzen für Lehramtsstudierende, Lehrkräfte und Hochschullehrer. Im Mittelpunkt steht ein projektbasierter Ansatz mit zwei verpflichtenden Projekten (Lehr-Lern-Konzept und Medienentwicklungsprojekt), bei denen verschiedene medien(fach)didaktische Kompetenzen gestärkt werden sollen. Studierende müssen im Laufe ihres Lehramtsstudiums (Bachelor und Master) beide Medienprojekte abschließen. Innerhalb eines Teilprojekts wurde ein **Online Self Assessment** entwickelt, das Studierenden einen Überblick zu ihren medien(fach)didaktischen Kompetenzen gibt. Die sich anschließende Förderung dieser Kompetenzen basiert auf einem bildungstheoretisch fundierten, interdisziplinär ausgerichteten Konzept, Medienprojekte im Lehramtsstudium integrativ zu implementieren (Müller et al., 2021).

Dieses entwickelte OSA mit dem Namen „Kompass Digitaler Kompetenzen Lehramt“ (KomDiKoLa) basiert auf dem „Weingartener Kompetenzmodell“ und wurde in Anlehnung an das europäische „Digital Competence Framework for Educators“\[5\]-Modell (DigCompEdu) entwickelt. Hierbei können Studierende anhand von sechzehn Basiskompetenzen ihren aktuellen medien(fach)didaktischen Kompetenzstand einschätzen. Den Studierenden wird empfohlen, die eigenen medien(fach)didaktischen Kompetenzen mithilfe des KomDiKoLa vor und nach der Durchführung eines Medienprojekts zu reflektieren, um individuelle Entwicklungspotenziale zu erkennen.

## <a name="projektphokus"></a>Projekt PHokus

Das Projekt PHokus\[6\] der PH Weingarten wurde im Rahmen des Projekts „E2BS - Eignungsfeststellung, Beratung und Begleitung im Lehramtsstudium stärken“\[7\] (01.08.2019 bis 31.12.2021) entwickelt und vom Ministerium für Wissenschaft, Forschung und Kunst Baden-Württemberg finanziert. Ziel war es studienbegleitende Assessment-, Beratungs- und Coachingmaßnahmen zu implementieren, die, basierend auf systematischem Feedback und verstärkter Reflexion, individuelle Lernprozesse in relevanten Wissens- und Kompetenzbereichen im Studienverlauf der Lehramtsstudiengänge (BA-Phase) fördern.

Als wichtiges Element bietet das Self Assessment Lehramtsstudierenden der PH Weingarten die Gelegenheit sich mit ihren Erwartungen auseinander zu setzen, welche sie an das Studium aber auch an den Lehrerberuf haben. Zu drei Zeitpunkten im Bachelorstudium werden Interessen, Motivation und Umgang mit den Anforderungen auf dem Weg zur erfolgreichen Lehrperson reflektiert. Die Assessments sollen dabei unterstützen, auf Basis der Ergebnisse, persönliche Entwicklungsziele zu identifizieren und weitere Schritte auf dem Weg zu einer/einem erfolgreichen Lehrer/in zu planen. Das Self Assessment ist für die Studierenden der PH Weingarten verpflichtend und an Studienleistungen sowie die Zulassung zur Abschlussprüfung geknüpft.

## <a name="moodlepluginfuerosa"></a>Moodle-Plugin für OSA

Im Rahmen des Entwicklungsprozesses im Projekt TEgoDi wurden unterschiedliche Tools zur Umsetzung des KomDiKoLa recherchiert und untersucht. Dabei wurden verschiedene Onlinebefragungssysteme (Limesurvey, SoSci Survey, Evasys), LMS und CMS/Blogsysteme und  Eigenentwicklungen anderer Hochschulen, beispielsweise SelfAssessments (SAM) der RWTH Aachen\[8\], betrachtet. Das Projekt traf die Entscheidung für eine Umsetzung des OSA innerhalb von Moodle, dem Lernmanagement-System der PH Weingarten, unter Verwendung eines Befragungs-Werkzeugs. Hierbei waren vor allem Aspekte der Nachhaltigkeit ausschlaggebend. Moodle ist ein zentrales und etabliertes System an der PH und wird durch das ZenDi betrieben und supportet.

PHokus wählte eine Realisierung mit dem Online-Befragungstool SoSci Survey, wofür allerdings studentische Hilfskräfte mit Programmierfähigkeiten erforderlich waren. Notwendige Anpassungen und Optimierungen sind nur im begrenzten Umfang möglich und setzen PHP-Programmierfähigkeiten voraus. Ein nachhaltiger Betrieb und die Weiterentwicklung können nicht sichergestellt werden, da dies von keiner zentralen Service-Einrichtung übernommen werden kann.

In beiden Projekten konnte insgesamt keine passgenaue Lösung umgesetzt werden. Es stehen bisher nur technische Umsetzungen mit Einschränkungen in den Bereichen Darstellungsmöglichkeiten, Funktionalität, User Experience (UX), Auswertungsgrafiken und Berichte zur Verfügung. Um bessere Möglichkeiten zur technischen Realisierung von OSAs zu schaffen wurde deshalb im Projektverlauf von TEgoDi ein Softwareentwicklungsprojekt gemeinsam mit dem Zentrum für Digitalisierung (ZenDi) gestartet, das die Entwicklung eines entsprechenden Plugins für Moodle zum Ziel hatte. Dabei sollten die Anforderungen und bisherigen Erfahrungen aus den Bemühungen in den Projekten TEgoDi und PHokus die Basis der Funktionalitäten darstellen. Alle Ergebnisse der Begleitforschung und abgeleitete Verbesserungsmaßnahmen für KomDiKoLa wurden aufgegriffen und organisatorische und technische Voraussetzungen zur nachhaltigen Nutzung von Online Self Assessments an der Pädagogischen Hochschule Weingarten geschaffen.

# <a name="anforderungsanalyse"></a>Anforderungsanalyse

Die Anforderungen an das Online Self Assessment kommen aus Richtung von
zwei Projekten. Einmal dem Projekt TEgoDi (Teacher Education goes
Digital)/KomDiKoLa (Kompass digitaler Kompetenzen Lehramt) und dem
PHokus Projekt. Anforderungen, welche beiden Projekten zugrunde liegen,
werden als solche gemeinsam dargestellt.

Grundsätzlich geht es beim Online Self Assessment darum, dass durch die
Nutzer/innen des Self Assessments mithilfe eines Fragebogens
Selbsteinschätzungen getroffen werden, welche zu einer
kompetenzbasierten individuellen Rückmeldung inklusive Empfehlung für
die einzelnen Nutzer/innen führen. Schlussendlich soll dadurch eine
sukzessive Kompentenzentwicklung der Nutzer/innen angestoßen und
ermöglicht werden.

## <a name="anforderungentegodiphokus"></a>Anforderungen, welche beiden Projekten zugrunde liegen

  - Erstellen von Frage-Items folgender Fragetypologien:
      - Mehrere Items des Typs Likert
      - Mehrere Items des Typs Multiple Choice
      - Typ offene Fragen
      - Typ Antwortskala in Form eines Sliders
  - Ausfüllen des OSAs durch die Nutzer/innen
  - Speicherung der einzelnen Antworten in Bezug zum/zur ausfüllenden
    Anwender/in
  - Zusammenfassung der Werte mehrerer Items einer Skala
  - Berechnung des Mittelwerts der Items
  - Individuelles Feedback
  - Individueller Feedbackreport
  - Grafische Aufbereitung der Ergebnisse
  - Beschriftung der Ergebnisgrafiken
  - Ergebnisse des OSAs soll zeitlich im Vergleich zu bisherigen
    Durchführungen dargestellt werden
  - Überblick über die entsprechenden Ergebnisse vor detailliertem
    Feedbackbericht
  - Anonymisierter Download der Datensätze

## <a name="anforderungentegodi"></a>Anforderungen aus dem Projekt TEgoDi/KomDiKoLa

  - OSA soll zu verschiedenen Zeitpunkten des Studiums durchgeführt
    werden
  - Individuelle Benennung des Titels der Aktivität/des Materials
  - Bearbeitung der Ergebnisgrafiken (Darstellungsart und farbliche
    Gestaltung)
  - Interaktive Ergebnisgrafiken

## <a name="anforderungenphokus"></a>Anforderungen aus dem Projekt PHokus

  - Vergleich des Mittelwerts mit einem Vergleichs-/Normwert, der
    manuell eingegeben wurde
  - Ergebnis als Übertrag in ein Ampelsystem und Auswahl von
    Textbausteinen auf Basis der Ampel-Einstufung
  - Spezifisches Feedback aufgrund der Einordnung im Ampelsystem

## <a name="implikationenausdenanforderungen"></a>Implikationen aus den Anforderungen

### <a name="implikationenallgemein"></a>Allgemeine Implikationen

Es ergeben sich folgende allgemeinen Implikationen aus den
Anforderungen:

  - Nutzerdefinierte Benennung des OSAs
  - Textbaustein für die Einführung in das OSA zur Verfügung stellen
  - Einfügen von Grafiken/Maskottchen soll möglich sein
  - Einbindung von Audio und Video (Opencast)
  - Einfügen von Textabschnitten
  - Einfache Maske zum Einstellen der Inhalte
  - Visualisierungen und Feedback verweisen auf weiteres Material
  - Darstellung auf einer Ergebnis-/Übersichtsseite, welche Fragen wie
    beantwortet wurden
  - Verschiedene Antwortformate sollen einstellbar sein
  - Einfache Fragetypen (Single, Multiselect)
  - Bewertung in Stufen
  - Nutzerspezifische Empfehlungen zu weiteren Materialien
  - Eingabe von Standard/Normwerten
  - Export der Ergebnisse in eine PDF
  - OSA Dashboard auf oberster Ebene in Moodle auf Systemdashboardebene
    (ein extra Plugin würde dafür benötigt)
  - Funktion zum Senden von Nachrichten an Berater, falls weitergehende
    Beratung gewünscht wird
  - Rollenvergabe an nicht Lehrende zur Administration des Plugins
  - Backupfunktion: Bereinigung der Datenbank über die Zeit? Zu
    überlegen wäre, welche Werte dauerhaft gespeichert bleiben müssten,
    um Vergleichswerte zu besitzen und evtl. eine Langzeitauswertung zu
    ermöglichen.
  - (Automatische) Rückmeldung zum Kompetenzstand -\> Kompetenzen müssen
    vorher definiert werden und bestimmten Kategorien zugeordnet werden
    können
  - Erinnerungen, dass ein OSA ansteht

### <a name="implikationentechnisch"></a>Technische Implikationen

Es ergeben sich folgende technische Implikationen aus den Anforderungen:

  - Auswertung per Diagramme (D3.js). Aktuelle Durchführung und
    Vergleich zu vorherigen Versuchen
  - PDF PHP Library für die Erzeugung der Auswertung
  - Zeitgesteuerte Freigabe des OSAs
  - Plugin soll mobilgerätefreundlich sein
  - Plugin ist modular aufgebaut
  - Backupfunktion
  - Löschfristen: Automatische Löschung nach Zeit X
  - Export der Daten -\> anonymisiert
  - Rollenvergabe an nicht Lehrende zur Administration des
    Moduls/Plugins
  - Antwortverknüpfung mit Nutzeraccount zur späteren Vergleichbarkeit
    (nur für Nutzenden, nicht für Lehrende oder sonstige
    Forschungsabteilungen)
  - Selbsteinschätzung evtl. Fremdeinschätzung
  - Automatische E-Mailerinnerung, dass ein OSA ansteht, wenn bestimmte
    Bedingungen erfüllt sind unter Zuhilfenahme von cron
  - Bildung von Gruppen zum späteren Vergleich mit anderen Gruppen
    (beispielsweise andere Kohorte)

### <a name="implikationenvisuell"></a>Visuelle Implikationen

Es ergeben sich folgende visuelle Implikationen aus den Anforderungen:

  - Das Standardtheme von Moodle soll verwendet werden
  - Farbschema: Verwendung einer Ampel-Einstufung und Einsatz von Icons
  - Darstellung des Feedbacktexts und der Ergebnisgrafiken in der PDF

# <a name="kurzuebersicht"></a>Kurzübersicht über den Fortschritt der Entwicklung des OSA Plugins

Die Kurzüberischt über den Fortschritt der Entwicklung des OSA Plugins
soll zeigen welche Funktionen bereits voll funktionsfähig sind und an
welchen Stellen weitere Entwicklung sinnvoll ist. Zur Einordnung wird
der Grad der Umsetzung in folgender Tabelle beschrieben:

| Grad der Umsetzung | Bedeutung                                                                                       |
| :----------------- | :---------------------------------------------------------------------------------------------- |
| \+                 | Dies ist eine bei der Anforderungsanalyse mitkonzipierte und angedachte Funktionalität.         |
| \++                | Dies ist eine teilweise bereits programmierte Funktion. Es sind weitere Maßnahmen erforderlich. |
| \+++               | Dies ist eine bereits programmierte Funktion. Vereinzelte Bugs sind bekannt.                    |
| \++++              | Dies ist eine programmierte Funktion. Keine Bugs sind bekannt.                                  |

Grad der Umsetzung

## <a name="kurzuebersichtanforderungen"></a>Kurzübersicht Anforderungen

| Anforderungen, welche beiden Projekten zugrunde liegen                                         | Grad der Umsetzung | Kommentar                                                            |
| :--------------------------------------------------------------------------------------------- | :----------------- | :------------------------------------------------------------------- |
| Erstellen von Frage-Items der Fragetypologie des Typs Likert                                   | \++++              |                                                                      |
| Erstellen von Frage-Items der Fragetypologie des Typs Multiple Choice                          | \++++              |                                                                      |
| Erstellen von Frage-Items der Fragetypologie des Typs offene Frage                             | \++++              |                                                                      |
| Erstellen von Frage-Items der Fragetypologie des Typs Antwortskala in Form eines Sliders       | \++++              |                                                                      |
| Ausfüllen des OSAs durch die Nutzer/innen                                                      | \++++              |                                                                      |
| Speicherung der einzelnen Antworten in Bezug zum/zur ausfüllenden Anwender/in                  | \++++              |                                                                      |
| Zusammenfassung der Werte mehrerer Items einer Skala                                           | \++++              |                                                                      |
| Berechnung des Mittelwerts der Items                                                           | \++++              |                                                                      |
| Individuelles Feedback                                                                         | \++++              |                                                                      |
| Individueller Feedbackreport                                                                   | \++                | Der individuelle Feedbackreport muss noch mit Daten befüllt werden   |
| Grafische Aufbereitung der Ergebnisse                                                          | \++++              | Weitere visuelle Aufbereitungen können in Zukunft hinzugefügt werden |
| Beschriftung der Ergebnisgrafiken                                                              | \+                 |                                                                      |
| Ergebnisse des OSAs soll zeitlich im Vergleich zu bisherigen Durchführungen dargestellt werden | \+                 |                                                                      |
| Überblick über die entsprechenden Ergebnisse vor detailliertem Feedbackbericht                 | \++++              |                                                                      |
| Anonymisierter Download der Datensätze                                                         | \+                 |                                                                      |

Anforderungen, welche beiden Projekten zugrunde liegen

| Anforderungen aus dem Projekt TEgoDi/KomDiKoLa                              | Grad der Umsetzung | Kommentar                                                                      |
| :-------------------------------------------------------------------------- | :----------------- | :----------------------------------------------------------------------------- |
| OSA soll zu verschiedenen Zeitpunkten des Studiums durchgeführt werden      | \++++              |                                                                                |
| Individuelle Benennung des Titels der Aktivität/des Materials               | \++++              |                                                                                |
| Bearbeitung der Ergebnisgrafiken (Darstellungsart und farbliche Gestaltung) | \++++              | D3.js Code muss direkt bearbeitet und in das OSA Verzeichnis platziert werden. |
| Interaktive Ergebnisgrafiken                                                | \++++              |                                                                                |

Anforderungen aus dem Projekt TEgoDi/KomDiKoLa

| Anforderungen aus dem Projekt PHokus                                                                   | Grad der Umsetzung | Kommentar |
| :----------------------------------------------------------------------------------------------------- | :----------------: | :-------- |
| Vergleich des Mittelwerts mit einem Vergleichs-/Normwert, der manuell eingegeben wurde                 |       \++++        |           |
| Ergebnis als Übertrag in ein Ampelsystem und Auswahl von Textbausteinen auf Basis der Ampel-Einstufung |       \++++        |           |
| Spezifisches Feedback aufgrund der Einordnung im Ampelsystem                                           |       \++++        |           |

Anforderungen aus dem Projekt PHokus

## <a name="kurzuebersichtimplikationen"></a>Kurzübersicht Implikationen

| Technische Implikationen aus den Anforderungen                                                                           | Grad der Umsetzung | Kommentar                                                                         |
| :----------------------------------------------------------------------------------------------------------------------- | :----------------- | :-------------------------------------------------------------------------------- |
| Auswertung per Diagramme (D3.js) Aktuelle Durchführung                                                                   | \++++              |                                                                                   |
| Auswertung per Diagramme (D3.js) Aktuelle Durchführung mit Vergleich zu vorherigen Versuchen                             | \+                 | Daten müssen noch aus der Datenbank geholt werden                                 |
| PDF PHP Library für die Erzeugung der Auswertung                                                                         | \++                | Einbindung von Text und Grafiken muss noch erfolgen                               |
| Zeitgesteuerte Freigabe des OSAs                                                                                         | \+++               | Die Einstellungen im Abschnitt Attempts dürfen nicht beide den Wert 0 haben       |
| Plugin soll mobilgerätefreundlich sein                                                                                   | \++++              |                                                                                   |
| Plugin ist modular aufgebaut                                                                                             | \++++              |                                                                                   |
| Backupfunktion                                                                                                           | \+                 |                                                                                   |
| Löschfristen: Automatische Löschung nach Zeit X                                                                          | \+                 |                                                                                   |
| Export der Daten -\> anonymisiert                                                                                        | \+                 |                                                                                   |
| Rollenvergabe an nicht Lehrende zur Administration des Moduls/Plugins                                                    | \++++              |                                                                                   |
| Antwortverknüpfung mit eigenem Nutzeraccount zur späteren Vergleichbarkeit                                               | \++++              |                                                                                   |
| Selbsteinschätzung                                                                                                       | \++++              |                                                                                   |
| Fremdeinschätzung                                                                                                        | \+                 | Templates müssen angepasst und eine weitere Datenbanktabelle muss erstellt werden |
| Automatische E-Mailerinnerung, dass ein OSA ansteht, wenn bestimmte Bedingungen erfüllt sind unter Zuhilfenahme von cron | \+                 |                                                                                   |
| Bildung von Gruppen zum späteren Vergleich mit anderen Gruppen (beispielsweise andere Kohorte)                           | \+                 |                                                                                   |

Technische Implikationen aus den Anforderungen

| Visuelle/optische Implikationen aus den Anforderungen               | Grad der Umsetzung | Kommentar                                                                |
| :------------------------------------------------------------------ | :----------------- | :----------------------------------------------------------------------- |
| Das Standardtheme von Moodle soll verwendet werden                  | \++++              |                                                                          |
| Farbschema: Verwendung einer Ampel-Einstufung und Einsatz von Icons | \++++              |                                                                          |
| Darstellung des Feedbacktexts und der Ergebnisgrafiken in der PDF   | \++                | Übertragung der Ergebnisgrafiken und Feedbacktexte in die PDF fehlt noch |

Visuelle Implikationen aus den Anforderungen

# <a name="kernfunktionenosa"></a>Kernfunktionen des OSAs

Die Kernfunktionen des OSAs sollen folgende Aspekte umfassen:

  - [Admin-Einstellungen](#admineinstellungen)
  - [Erste Anlage des OSAs](#ersteanlageosa)
  - [Useransicht Selbst- und Fremdeinschätzung](#useransichtselbstundfremdeinschaetzung)
  - [Einstellungen zu den Fragetypologien](#einstellungenfragetypologien)
  - [Feedbackeinstellungen](#feedbackeinstellungen)

![Scribble Übersicht](/images/scribble-osa.svg "Scribble Übersicht")

## <a name="admineinstellungen"></a>Admin-Einstellungen

Die Admin-Einstellungen werden benötigt, um entsprechende externe
Libraries nachladen zu können (D3.js) und festzulegen welche Anzahl an
OSA Übersichten mithilfe des möglicherweise zukünftigen Zusatz-Plugins
(siehe Kapitel [Idee für Zusatz-Plugin](#ideezusatzplugin)) angezeigt
werden sollen. Es können einzelne Fragetypologien systemweit aktiviert
und deaktiviert werden. Für die zukünftige Entwicklung ist bereits eine
Funktion für das Teilen von OSA Vorlagen mit anderen Kurslehrenden
angedacht. In den Einstellungen kann die Option zum Teilen, zur
selbständigen Steuerung durch die lehrende Person, freigegeben werden,
sodass es jedem Kurslehrenden und jeder Kurslehrende frei gestellt ist
OSAs zu teilen.

### <a name="beschreibungadmineinstellungen"></a>Konfigurationsoptionen und Funktionen

  - Setze die Anzahl an angezeigten X (3) Assessments im Dashboard -\>
    Nur Admin kann diese Einstellung festlegen -\> Schreibe in/hole von
    DB
  - Setze Einstellung, ob die Freigabe der OSA Vorlage von Lehrenden für
    andere Lehrende erlaubt sein soll. -\> Standard=Nein -\> Nur Admin
    kann diese Einstellung ändern -\> Hole aus/schreibe in DB
  - Setze Einstellung welche Fragetypen erlaubt/aktiviert sein sollen
    -\> Nur Admin kann diese Einstellung festlegen -\> Schreibe in/hole
    aus DB
  - Setze Standardeinstellungen für die einzelnen Fragetypologien
      - Anzahl Checkboxenelemente -\> Standard=1 Min=1 Max=20 -\> Hole
        aus/schreibe in DB
      - Anzahl Stufen Likertskala -\> Standard=5 Min=2 Max=10 -\> Hole
        aus/schreibe in DB
      - Anzahl Stufen Slider -\> Standard=4 Min=2 Max=20 -\> Hole
        aus/schreibe in DB
  - Setze Standardeinstellungen für die Ergebniskategorien
      - Anzahl Ergebniskategorien -\> Standard=4 Min=2 Max=10 -\> Hole
        aus/schreibe in DB
  - Setze Standardeinstellungen für Struktur
      - Automatische Seitennummerierung -\> Standard=Ja -\> Durch
        Lehrende individuell änderbar -\> Hole aus/schreibe in DB

### <a name="beschreibungergebnisadmineinstellungen"></a>Realisierungsaspekte

  - Setze Standardeinstellungen (Durch Lehrende veränderbar/nicht veränderbar) für OSA Elemente (Frage/Struktur/Dashboard)

### <a name="scribbleadmineinstellungen"></a>Scribble Admin-Einstellungen

![Scribble Admin-Einstellungen](/images/scribble-adminsettings.svg
"Scribble Admin-Einstellungen")

## <a name="ersteanlageosa"></a>Initiale Erstellung einer OSA Aktivität

Bei der ersten Anlage des OSAs werden die Grundeinstellungen durch die
Lehrenden festgelegt. Neben dem Titel, der Beschreibung der OSA
Aktivität, Einstellungen zu den Kompetenzkategorien, kann auch die
Anzahl an erlaubten Versuchen, der Zeit zwischen den Versuchen der
Nutzer/innen, die zukünftige Option zum Teilen des OSA als Vorlage und
der Titel des Projekts eingestellt werden.

### <a name="beschreibungersteanlageosa"></a>Konfigurationsoptionen und Funktionen

  - Grundeinstellungsmöglichkeiten für die erste Anlage des OSAs:
      - Grundinformationen des OSA im Menüpunkt “Allgemeines”
          - Titel des OSAs -\> Hole von/schreibe in DB
          - Optionaler Text -\> Hole von/schreibe in DB
          - Optionale Grafik -\> Hole von/schreibe in DB
          - Text -\> Hole von/schreibe in DB
      - Grundinformationen des OSAs im Menüpunkt Fragen zu
        Identifizierung
          - Auswahl von 2 Identifizierungsmerkmalen mit je 3 Optionen:
          - Identifizierungsmerkmal: Letzte 3 Ziffern der
            Matrikelnummer, Vorname Mutter, Vorname Vater (jeweils die
            letzten 3 Ziffern, Buchstaben) -\> Hole von/schreibe in DB
      - Grundinformationen des OSAs im Menüpunkt Einschätzung
          - Erlaube Fremdeinschätzung -\> Hole von/schreibe in DB -\>
            Standardeinstellung=Nein
      - Grundinformationen des OSAs im Menüpunkt Einverständniserklärung
        für Forschungszwecke
          - Titel des Projekts/der Veranstaltung -\> Hole von/schreibe
            in DB
          - Abfrage aktivieren -\> Hole von/schreibe in DB -\>
            Standardeinstellung=Nein
          - Zugehöriger Text wird in den Admin-Einstellungen
            bereitgestellt
      - Wiederverwendung/Vorlagenmanagement:
          - Erlaube das Teilen des OSAs als Vorlage -\> Hole
            von/schreibe in DB -\> Standardeinstellung=Nein -\> In
            Adminsettings global ein-/ausschaltbar

### <a name="beschreibungergebnisersteanlageosa"></a>Realisierungsaspekte

  - Lege Grundstruktur des OSAs für weiteres Hinzufügen von
    Inhaltselementen (Frage-/Strukturelementen) an
  - Lege Kompetenzkategorien an
  - Erlaube die anonyme Identifizierung bei längeren Forschungsprojekten
  - Ermögliche die Fremdeinschätzung
  - Ermögliche die einfache Erstellung der Erklärungen für
    Forschungszwecke
  - Ermögliche das Teilen von OSAs als Vorlage

### <a name="scribbleersteanlageosa"></a>Scribble erste Anlage des OSAs

![Scribble Initiale Erstellung einer OSA
Aktivität](/images/scribble-erste-anlage-des-osa.svg
"Scribble Initiale Erstellung einer OSA Aktivität")

## <a name="useransichtselbstundfremdeinschaetzung"></a>Useransicht Selbst- und Fremdeinschätzung

Die Useransicht dient der Eingabe der Selbsteinschätzungen durch die
Nutzenden. Dabei stehen verschiedene Fragetypen zur Verfügung. Die
Fremdeinschätzung soll den Reflexionsprozess der teilnehmenden Person
unterstützen.

### <a name="beschreibunguseransichtselbstundfremdeinschaetzung"></a>Konfigurationsoptionen und Funktionen

  - Modi: Selbstbewertung, Fremdbewertung
      - Selbstbewertung
      - Fremdbewertung -\> Hole Namen der zu bewertenden Person aus der
        DB
  - Aktueller Fortschritt (Selbst- und Fremdbewertung):
      - Hole Überschriften aus der DB und erstelle einzelne Seiten
        daraus (außer, es ist für einzelne Überschriften in der DB
        deaktiviert)
      - Stelle eine Übersicht in Form eines Breadcrumbs zur Verfügung
      - Markiere aktuellen Breadcrumb farbig
  - Stelle Überschrift der Seite dar
      - Hole Überschrift aus der DB
  - Generische Fragetypologie
      - Frage -\> Hole aus DB
      - Optionaler Text -\> Hole aus DB
      - Grafik/Video/Text -\> Hole Typ und Daten aus DB/Opencast
  - Fragetypologie Likert
      - Likertskalenitems (bis 10 stufig) -\> Hole aus DB
      - Beschreibung -\> Hole aus DB
      - Grafik -\> Hole aus DB
      - Likertskalenitem gewählt/nicht gewählt -\> Schreibe in/hole aus
        DB
  - Fragetypologie Multiple Choice (Checkbox)
      - Checkboxmenge -\> Hole aus DB
      - Beschreibung -\> Hole aus DB
      - Grafik -\> Hole aus DB
      - Checkbox gewählt/nicht gewählt -\> Schreibe in/hole aus DB
  - Fragetypologie offene Frage (Texteingabe)
      - Text -\> Hole aus DB/schreibe in DB
  - Fragetypologie Antwortskala in Form eines Sliders
      - Sliderabschnitte -\> Hole aus DB und berechne Darstellung im
        Frontend
      - Sliderstatus -\> Schreibe in/hole aus DB
      - Grafik -\> Hole aus Datenbank
      - Text -\> Hole aus Datenbank
  - Navigation
      - Prüfe welche die nächste und welche die vorherige Seite ist und
        verlinke
  - Bearbeitungsstatus
      - Hole/schreibe aktuellen Bearbeitungsstatus
        (Seitenzahl/abgeschlossen bzw. nicht abgeschlossen) aus/in DB

### <a name="beschreibungergebnisuseransichtselbstundfremdeinschaetzung"></a>Realisierungsaspekte

  - Holen der Daten und Schreiben des aktuellen Fortschritts der Selbst-
    und Fremdbewertung in die DB

### <a name="scribbleselbstfremdeinschaetzungosa"></a>Scribble Useransicht Selbst- und Fremdeinschätzung

<a name="fig-scribble-tn-selbst-und-fremdeinschaetzung"></a>
![Scribble Useransicht Selbst- und
Fremdeinschätzung](/images/scribble-tn-selbst-und-fremdeinschaetzung.svg
"Scribble Useransicht Selbst- und Fremdeinschätzung")


## <a name="einstellungenfragetypologien"></a>Einstellungen zu den Fragetypologien

Die Fragetypologien ermöglichen später, je nach Einsatz, sowohl eine
quantitative als auch eine qualitative Auswertung der Antworten der
Nutzer/innen.

### <a name="fragetypologiemultiplechoice"></a>Typ Multiple Choice

#### <a name="beschreibungfragetypologiemultiplechoice"></a>Konfigurationsoptionen und Funktionen

  - Einstellungsmöglichkeit wie viele Checkboxen das Element haben soll.
      - Minimum=1 Maximum=20 -\> Schreibe Einstellung für Element in DB
      - Standardeinstellung=1 -\> Hole Standardeinstellung für Element
        aus DB -\> Standardeinstellung kann vom Admin gesetzt werden
      - Weitere Einstellungen werden dynamisch ergänzt auf Basis
        aktueller Stufenanzahl

#### <a name="beschreibungergebnisfragetypologiemultiplechoice"></a>Realisierungsaspekte

  - Darstellung der Checkboxen mit Beschreibung (Checkboxtext) für
    Teilnehmende des OSA (siehe [Scribble Useransicht Selbst- und
    Fremdeinschätzung](#fig-scribble-tn-selbst-und-fremdeinschaetzung))
  - Darstellung der Checkboxen zum Ankreuzen für TN des OSAs, welche
    andere TN bewerten
  - Darstellung der Checkboxen bei der Auswertung
  - Weiterverarbeitung durch D3.js

### <a name="fragetypologielikert"></a>Typ Likert

#### <a name="beschreibungfragetypologielikert"></a>Konfigurationsoptionen und Funktionen

  - Einstellungsmöglichkeit wie viele Stufen die Likertskala haben soll.
      - Minimum=2 Maximum=10 -\> Schreibe Einstellung für Element in DB
      - Standardeinstellung=5 -\> Hole Standardeinstellung für Element
        aus DB -\> Standardeinstellung kann vom Admin gesetzt werden
      - Weitere Einstellungen werden dynamisch ergänzt auf Basis
        aktueller Stufenanzahl
      - Auswählen des Bilds für jede Stufe (optional) -\> Schreibe/hole
        aus DB
      - Kurze Beschreibung der Stufe -\> Schreibe/hole aus DB

#### <a name="beschreibungergebnisfragetypologielikert"></a>Realisierungsaspekte

  - Darstellung der Likertskala zum Ankreuzen für Teilnehmende des OSAs
    (siehe [Scribble Useransicht Selbst- und
    Fremdeinschätzung](#fig-scribble-tn-selbst-und-fremdeinschaetzung))
  - Darstellung der Likertskala zum Ankreuzen für TN des OSAs, welche
    andere TN bewerten
  - Darstellung der Likertskala bei der Auswertung
  - Weiterverarbeitung durch D3.js

### <a name="fragetypologieoffenefragetextelement"></a>Typ offene Frage

#### <a name="beschreibungfragetypologieoffenefragetextelement"></a>Konfigurationsoptionen und Funktionen

  - Einstellungsmöglichkeit zur Beschreibung des Textelements, damit
    später in das erzeugte Textfeld Freitext eingetragen werden kann.
      - Beschreibung -\> Beschreibung für Element Schreibe in/hole aus
        DB (für Screenreader)
      - Textfeldinhalt Schreibe in/hole aus DB

#### <a name="beschreibungergebnisfragetypologieoffenefragetextelement"></a>Realisierungsaspekte

  - Darstellung des Textfelds für Teilnehmende des OSAs (siehe [Scribble
    Useransicht Selbst- und
    Fremdeinschätzung](#fig-scribble-tn-selbst-und-fremdeinschaetzung))
  - Fremdeinschätzung: Darstellung des Textfelds
  - Darstellung des Textfelds bei der Auswertung
  - Weiterverarbeitung durch D3.js?

### <a name="fragetypologieantwortskalaslider"></a>Typ Antwortskala in Form eines Sliders

#### <a name="beschreibungfragetypologieantwortskalaslider"></a>Konfigurationsoptionen und Funktionen

  - Einstellungsmöglichkeit des Sliders.
      - Festlegung der Stufen
      - Standardeinstellungen=4 -\> Hole Standardeinstellung aus DB -\>
        Standardeinstellung kann vom Admin gesetzt werden
      - Minimum=2; Maximum=10 -\> Schreibe Einstellungen für Element in
        DB
      - Benennung der einzelnen Stufen
      - Hinzufügen von Bildern für die Stufen -\> Speichere in/hole aus
        DB
      - Hinzufügen von Beschreibungen in Textform für die einzelnen
        Stufen -\> Speichere in/hole aus DB
      - Speichere Wert als Fließkommazahl

#### <a name="beschreibungergebnisfragetypologieantwortskalaslider"></a>Realisierungsaspekte

  - Darstellung des Sliders für Teilnehmende des OSAs (siehe
    [Useransicht Selbst- und Fremdeinschätzung]())
  - Fremdeinschätzung: Darstellung des Sliders
  - Darstellung des Sliders bei der Auswertung
  - Weiterverarbeitung durch D3.js

## <a name="feedbackeinstellungen"></a>Feedbackeinstellungen

### <a name="beschreibungfeedbackeinstellungen"></a>Konfigurationsoptionen und Funktionen

  - Auswertungseinstellungen:
      - Biete Möglichkeit zur Anpassung der Anzahl der
        Ergebniskategorien: Hole Standardwert von DB -\> In
        Adminsettings festlegbar; Min=2 Max=10 -\> Hole von/schreibe in
        DB
      - Lege jeweiligen Titel der Kategorien fest -\> Hole von/schreibe
        in DB
      - Lege Bedingungen für jeweilige Kategorie fest
          - Wähle Kategorie {Checkbox,Likertskala,Slider,Textfeld} -\>
            Hole von/schreibe in DB
          - Frage -\> Hole von/schreibe in DB
          - Operator -\> Hole von/schreibe in DB
          - Vergleichswert/Ergebnis -\> Hole von/schreibe in DB
          - Füge Verknüpfung hinzu -\> Hole von/schreibe in DB
          - Füge neue Bedingung hinzu -\> Hole von/schreibe in DB
      - Kategorieergebnis
          - Bild -\> Hole von/schreibe in DB
          - Text -\> Hole von/schreibe in DB
          - Links -\> Hole von/schreibe in DB

### <a name="beschreibungergebnisfeedbackeinstellungen"></a>Realisierungsaspekte

  - Biete Möglichkeit der Verknüpfung von Auswertungsbedingungen
  - Biete Möglichkeit kategorienhaftes Feedback/kategorienhafte
    Empfehlungen zu geben

### <a name="scribblefeedbackeinstellungen"></a>Scribble Feedbackeinstellungen

![Scribble Feedbackeinstellungen](/images/scribble-feedback.svg
"Scribble Feedbackeinstellungen")

# <a name="ideezusatzplugin"></a>Idee für Zusatz-Plugin

## <a name="zusatzosadashboard"></a>OSA Dashboard

Die Idee des OSA Dashboards ist, den Nutzer/innen direkt nach der
Anmeldung in Moodle eine Übersicht über die nächsten OSA Durchführungen
zu geben und den aktuellen Status der Durchführungen - Wird
durchgeführt, Erledigt - anzuzeigen. Des Weiteren sollen jeweils die
aktuellen Empfehlungen eines OSAs als Popup angezeigt werden können.

### <a name="beschreibungzusatzosadashboard"></a>Konfigurationsoptionen und Funktionen

  - Grundansicht des OSAs im Dashboard:
      - Zeige die letzten X (3) Assessments: Hole von DB -\> In
        Adminsettings festlegbar
          - Titel der X Assessments -\> Hole jeweils von DB
          - Status der jeweils X Assessments -\> Hole von DB
          - Ergebnisdiagramm -\> Hole von DB
          - Information -\> Hole von DB
      - Zeige die Empfehlungen zum jeweils X-ten Assessment
          - Hole entsprechende Empfehlung zur Leistungsstufe/Kategorie
            aus DB inklusive Links zu weiteren Materialien

### <a name="beschreibungergebniszusatzosadashboard"></a>Realisierungsaspekte

  - Stelle Übersicht über aktuelle, vergangene und zukünftige
    Assessments inklusive des Status (in Bearbeitung/Erledigt) dar
  - 2 Wochenübersicht zur Planung
  - Biete Möglichkeit sich direkt Empfehlungen und das zugehörige
    Diagramm anzeigen zu lassen

### <a name="scribblezusatzplugin"></a>Scribble Zusatz-Plugin OSA Dashboard

![Scribble Zusatz-Plugin OSA
Dashboard](/images/scribble-osa-dashboard.svg
"Scribble Zusatz-Plugin OSA Dashboard")

![Scribble Zusatz-Plugin OSA Dashboard
Detailansicht](/images/scribble-osa-dashboard-detail.svg
"Scribble Zusatz-Plugin OSA Dashboard Detailansicht")

# <a name="programmierung"></a>Programmierung

Die Programmierung des OSA Plugins beruht auf PHP, JS, Mustache,
verschiedenen Moodle APIs und D3.js. D3.js hat Ähnlichkeiten zu
Low-Level Grafikbibliotheken und setzt direkt am DOM (Document Object
Model) des Browsers an (Bostock et al., 2011). Vorteile bietet D3.js, da
es für interaktive Grafiken geeignet ist und durch die Verwendung von
SVG auflösungsunabhängig arbeitet. Auch Interaktivität ist mithilfe von
D3.js umsetzbar. Damit ist es zwar möglicherweise aufwändiger in der
Erstellung dafür aber vielseitigst und browserübergreifend für alle
Arten von Grafiken zur Datenvisualisierung geeignet.

## <a name="ordnerstrukturosa"></a>Ordnerstruktur OSA Plugin

Der Aufbau des OSA Plugins ist in folgender Ordnerstruktur abgebildet:

![Ordnerstruktur OSA Plugin](/images/ordnerstruktur-osa-plugin.svg
"Ordnerstruktur OSA Plugin")

### <a name="osaordner"></a>OSA Ordner

Der OSA Ordner enthält unter anderem Dateien zur Einstellung von
Admin-Einstellungen (settings.php), zur Darstellung der OSA Oberfläche
(view.php), zur Einstellung von Lehrendeneinstellungen (mod\_form.php),
weitere Einstellungen zu den Fragetypologien (wie beispielsweise
edit\_questiontype\_textelement.php), die lib.php mit allen Funktionen
welche benötigt werden, die Datei zur Speicherung der Eintragungen der
Nutzer/innen, eine Datei zur Darstellung der Ergebnisseite
(view\_results.php) und eine Datei zur Generierung des Ergebnisberichts
als PDF durch die Verwendung von TCPDF. Die zugehörigen Klassen befinden
sich in `/classes/form/`.

### <a name="classesordnerevent"></a>Classes Ordner mit Unterordner event

In diesem Ordner sind die Events gespeichert. Klassen werden automatisch
geladen.

### <a name="dbordner"></a>db Ordner

Der db Ordner enthält unter anderem bereits erstellte Event Handler für
das Plugin (events.php), die Berechtigungen für die einzelnen Rollen
(access.php) und die Beschreibung der Datenbank (install.xml). Die
Datenbank ist in mehrere Tabellen aufgeteilt:

  - **mdl\_osa:** Enthält alle Daten für die initiale Anlage der OSA
    Aktivität. Unter anderem sind dort die Optionen für die
    Kompetenzkategorien, die Anzahl der Durchführungsversuche und die
    Daten für die Zeit zwischen den Durchführungsversuchen gespeichert.
  - **mdl\_osa\_instance\_qtlikertscale:** Enthält alle Daten für die
    Anlage der Items des Typs Likert.
  - **mdl\_osa\_instance\_qtlikertscale\_a:** Enthält alle Antworten der
    Nutzer/innen des Plugins zu den Items des Typs Likert.
  - **mdl\_osa\_instance\_qtcheckbox:** Enthält alle Daten für die
    Anlage der Items des Typs Multiple Choice.
  - **mdl\_osa\_instance\_qtcheckbox\_a:** Enthält alle Antworten der
    Nutzer/innen des Plugins zu den Items des Typs Multiple Choice.
  - **mdl\_osa\_instance\_qttextelement:** Enthält alle Daten für die
    Anlage des Typs offene Frage.
  - **mdl\_osa\_instance\_qttextelement\_a:** Enthält alle Antworten der
    Nutzer/innen des Plugins zu den Items des Typs offene Frage.
  - **mdl\_osa\_instance\_qtslider:** Enthält alle Daten für die Anlage
    des Typs Antwortskala in Form eines Sliders.
  - **mdl\_osa\_instance\_qtslider\_a:** Enthält alle Antworten der
    Nutzer/innen des Plugins des Typs Antwortskala in Form eines
    Sliders.
  - **mdl\_osa\_qtype\_collection:** Enthält alle Daten für die
    Zuordnung von Fragetyp zu Kursmodulid und weitere Daten wie die
    beispielsweise die Sortierreihenfolge der Fragenanordnung und die
    zugehörige Auswertungskategorie.
  - **mdl\_osa\_cat\_std\_vals:** Enthält alle Daten für die Speicherung
    der Standardwerte pro Kategorie.
  - **mdl\_osa\_cat\_feedback\_settings:** Enthält alle Daten für die
    Speicherung von unteren und oberen Grenzwerten und je nach
    berechnetem Wert das entsprechende Feedback.

### <a name="langordner"></a>lang Ordner mit Unterordner en

Im lang Ordner mit Unterordner en werden die Sprachdateien für das
Plugin gespeichert. Weitere Übersetzungen können hier beispielsweise
unter `/lang/de/` in Zukunft hinzugefügt werden.

### <a name="pixordner"></a>pix Ordner

Im pix Ordner ist das Icon des Plugins abgelegt.

### <a name="templatesordner"></a>templates Ordner

Im templates Ordner werden alle Templates gespeichert. Dazu gehören
unter anderem je ein Template für die Darstellung der Fragetypologien
via view.php (viewqttypes.mustache), für die Darstellung der
verbleibenden Zeit bis zum nächsten Versuch
(viewinfonextattempt.mustache), für die beantworteten Fragen, für die
Buttons der Einstellungsdialoge (z.B. viewbuttonsettings.mustache) und
für die Definition der Ergebnisgrafiken anhand von D3.js. Um eine
einfache Anpassung der Ergebnisgrafiken zu garantieren werden die Werte
in der lib.php berechnet, an das Template viewresults.mustache übergeben
und JS Variablen zugeordnet. In diesem Template werden weitere Templates
geladen (z.B. boxplot.mustache). Diese erlauben, mit nur wenig
Änderungen an einer einzigen Datei, die grafische Anpassung (siehe
Kapitel [Exemplarische technische
Umsetzung](#exemplarischetechnischeumsetzung)).

## <a name="exemplarischeumsetzung"></a>Exemplarische grafische und technische Umsetzung an verschiedenen Stellen des OSA Plugins

### <a name="exemplarischegrafischeumsetzung"></a>Exemplarische grafische Umsetzung

Das Design des Plugins ist an das Standardtheme von Moodle 4.x angelehnt
und ist sowohl auf klassischen Desktopsystemen als auch auf mobilen
Endgeräten bequem verwendbar (siehe [Mobile Ansicht OSA Plugin: **Links
oben:** Lehrendenansicht mit Buttons zum Hinzufügen von
Fragetypologien](#fig-screenshot-mobile-ansicht-osa)).

<a name="fig-screenshot-mobile-ansicht-osa"></a>
![Mobile Ansicht OSA Plugin: **Links oben:** Lehrendenansicht mit
Buttons zum Hinzufügen von Fragetypologien **Rechts oben:**
Nutzendenansicht Typ Multiple Choice **Links unten:** Nutzendenansicht
des Typ Likert **Rechts unten:** Nutzendenansicht des Typ
Likert](/images/screenshot-mobile-ansicht-osa.svg
"Mobile Ansicht OSA Plugin: **Links oben:** Lehrendenansicht mit Buttons zum Hinzufügen von Fragetypologien **Rechts oben:** Nutzendenansicht Typ Multipe Choice **Links unten:** Nutzendenansicht des Typ Likert **Rechts unten:** Nutzendenansicht des Typ Likert")

Die Nutzeroberfläche ist so aufgebaut, dass per Klick auf die Buttons in
chronologischer Reihenfolge das OSA von der lehrenden Person
eingerichtet, Fragetypen hinzugefügt und Auswertungseinstellungen
festgelegt werden können (siehe [Ansicht OSA Plugin: Buttons
Fragetypologien und weitere Einstellungen Kategorien und
Auswertungseinstellungen](#fig-screenshot-screen-ansicht-hinzufuegen-von-fragetypologien-und-einstellungen)).

<a name="fig-screenshot-screen-ansicht-hinzufuegen-von-fragetypologien-und-einstellungen"></a>
![Ansicht OSA Plugin: Buttons Fragetypologien und weitere Einstellungen
Kategorien und
Auswertungseinstellungen](/images/screenshot-screen-ansicht-hinzufuegen-von-fragetypologien-und-einstellungen.svg
"Ansicht OSA Plugin: Buttons Fragetypologien und weitere Einstellungen Kategorien und Auswertungseinstellungen")


Um Items des Fragetyps Likert zu erstellen bietet die
[Einstellungsmaske](#fig-screenshot-standardansicht-osa-sperre)
vielfältige Möglichkeiten.

<a name="fig-screenshot-standardansicht-osa-sperre"></a>
![Standardansicht OSA Plugin: Likert
Einstellungsmaske](/images/screenshot-screen-ansicht-einstellungen-likert.svg
"Standardansicht OSA Plugin: Likert Einstellungsmaske")

Jede Darstellung der Frage kann im Bearbeitungsmodus durch die Buttons
bearbeitet oder gelöscht oder nach oben oder unten verschoben werden
(siehe [Standardansicht OSA Plugin:
Bearbeitungsmodus](#fig-screenshot-screen-ansicht-bearbeiten-modus-fragetypologien)).

<a name="fig-screenshot-screen-ansicht-bearbeiten-modus-fragetypologien"></a>
![Standardansicht OSA Plugin:
Bearbeitungsmodus](/images/screenshot-screen-ansicht-bearbeiten-modus-fragetypologien.svg
"Standardansicht OSA Plugin: Bearbeitungsmodus")

Ist eine Bearbeitung durch die Nutzer/innen zum jetzigen Zeitpunkt nicht
möglich erscheint ein
[Durchführungsinformationsbanner](#fig-screenshot-standardansicht-osa-sperre).

<a name="fig-screenshot-standardansicht-osa-sperre"></a>
![Standardansicht OSA Plugin:
Durchführungsinformationsbanner](/images/screenshot-screen-ansicht-osa-sperre.svg
"Standardansicht OSA Plugin: Durchführungsinformationsbanner")

Die [Standardansicht des OSAs aus
Nutzer-/innensicht](#fig-screenshot-standardansicht-osa) wird gezeigt
sollte eine Bearbeitung möglich sein.

<a name="fig-screenshot-standardansicht-osa"></a>
![Standardansicht OSA Plugin](/images/screenshot-screen-ansicht-osa.svg
"Standardansicht OSA Plugin")

Im nächsten Schritt, nach Speicherung der Eingaben durch die
Nutzer/innen, werden die Ergebnisse der ausfüllenden Person bezogen auf
die einzelnen Fragetypologien
[rückgemeldet](#fig-screenshot-screen-ansicht-osa-fragetypologien-ausgefuellt).

<a name="fig-screenshot-screen-ansicht-osa-fragetypologien-ausgefuellt"></a>
![Standardansicht OSA Plugin:
Ergebnisse](/images/screenshot-screen-ansicht-osa-fragetypologien-ausgefuellt.svg
"Standardansicht OSA Plugin: Ergebnisse")

Schlussendlich gibt es Feedback mit individuellen Empfehlungen. Das
Feedback wird bezogen auf die Zugehörigkeit zu einer
(Kompetenz-)Kategorie gegeben. Dabei wird zuerst eine Beschreibung der
Kategorie angezeigt, dann eine grafische Veranschaulichung präsentiert,
das individuelle Feedback mit Vergleichen zu festgelegten Werten durch
die lehrende Person und ein Button zum Erstellen eines zukünftigen
Ergebnisberichts im PDF Format dargeboten (siehe [Standardansicht OSA
Plugin:
Ergebnisse](#fig-screenshot-screen-ansicht-ergebnis-kat-grafik-feedback)).

<a name="fig-screenshot-screen-ansicht-ergebnis-kat-grafik-feedback"></a>
![Standardansicht OSA Plugin: Ergebnisse mit Kategoriebeschreibung,
Grafik, Feedbacktext und Download Button für den Download als
PDF](/images/screenshot-screen-ansicht-ergebnis-kat-grafik-feedback.svg
"Standardansicht OSA Plugin: Ergebnisse mit Kategoriebeschreibung, Grafik, Feedbacktext und Download Button für den Download als PDF")

Eine exemplarische grafische Umsetzung zu den Anforderungen aus dem
Projekt KomDiKoLa mithilfe von D3.js könnte folgendermaßen aussehen:

![Standardansicht OSA Plugin: Exemplarische Umsetzung D3.js
Feedbackgrafik
KomDiKoLa](/images/screenshot-exemplarische-grafik-komdikola.svg
"Standardansicht OSA Plugin: Exemplarische Umsetzung D3.js Feedbackgrafik KomDiKoLa")

### <a name="exemplarischetechnischeumsetzung"></a>Exemplarische technische Umsetzung

#### <a name="technischeimplementierungmodularitaet"></a>Technische Implementierung von Modularität in der Ergebnisdarstellung

Im Folgenden wird anhand von Codebeispielen kurz beschrieben, wie in der
Ergebnisdarstellung technisch Modularität implementiert wird.
Zuallererst werden die eingegebenen Daten der Nutzer/innen aus der
Datenbank geholt. Diese werden an die Funktion
[osa\_calculate\_answer\_data\_for\_boxplot](#fig-screenshot-code-ansicht-osa-calculate-answer-data-for-boxplot)
in der lib.php übergeben. Diese Funktion berechnet alle nötigen Werte,
um später Grafiken für die Auswertung erstellen zu können.

<a name="fig-screenshot-code-ansicht-osa-calculate-answer-data-for-boxplot"></a>
![Codebeispiel OSA Plugin: Funktion
osa\_calculate\_answer\_data\_for\_boxplot](/images/screenshot-code-ansicht-osa-calculate-answer-data-for-boxplot.svg
"Codebeispiel OSA Plugin: Funktion osa_calculate_answer_data_for_boxplot")

Die Rückgabewerte der Funktion
osa\_calculate\_answer\_data\_for\_boxplot werden PHP Variablen
zugeordnet. Dies geschieht für alle Antworten, welche ihrerseits je
einer Fragekategorie zugeordnet sind (siehe [Codebeispiel OSA Plugin:
Zuordnung der Rückgabewerte der Funktion
osa\_calculate\_answer\_data\_for\_boxplot zu PHP
Variablen](#fig-screenshot-code-ansicht-get-data-from-function-and-assign-to-vars-osa-calculate-answer-data-for-boxplot)).

<a name="fig-screenshot-code-ansicht-get-data-from-function-and-assign-to-vars-osa-calculate-answer-data-for-boxplot"></a>
![Codebeispiel OSA Plugin: Zuordnung der Rückgabewerte der Funktion
osa\_calculate\_answer\_data\_for\_boxplot zu PHP
Variablen](/images/screenshot-code-ansicht-get-data-from-function-and-assign-to-vars-osa-calculate-answer-data-for-boxplot.svg
"Codebeispiel OSA Plugin: Zuordnung der Rückgabewerte der Funktion osa_calculate_answer_data_for_boxplot zu PHP Variablen")

Die PHP Variablen werden den mustache Variablen zugeordnet (siehe
[Codebeispiel OSA Plugin: Zuordnung PHP Variable zu mustache
Variable](#fig-screenshot-code-ansicht-assign-var-to-template)) und an
das Template geschickt (siehe [Codebeispiel OSA Plugin: Übergebe
mustache Variable an
Template](#fig-screenshot-code-pass-to-mustache-template)).

<a name="fig-screenshot-code-ansicht-assign-var-to-template"></a>
![Codebeispiel OSA Plugin: Zuordnung PHP Variable zu mustache
Variable](/images/screenshot-code-ansicht-assign-var-to-template.svg
"Codebeispiel OSA Plugin: Zuordnung PHP Variable zu mustache Variable")

Die mustache Variablen werden an das Template viewresults.mustache
übergeben.

<a name="fig-screenshot-code-pass-to-mustache-template"></a>
![Codebeispiel OSA Plugin: Übergebe mustache Variable an
Template](/images/screenshot-code-pass-to-mustache-template.svg
"Codebeispiel OSA Plugin: Übergebe mustache Variable an Template")

Im [Template](#fig-screenshot-code-template-vars-cat-01) wird das
Aussehen der Darstellung der einzelnen Bestandteile -
Kategoriebeschreibung, die grafische Aufbereitung der Ergebnisse und das
individuelle Feedback - in den vorher festgelegten Kategorien definiert.
Die einzelnen Bestandteile werden nur dargestellt, wenn Kategorien
tatsächlich vorhanden und Fragen zugeordnet sind.

Zu den Werten, welche unter anderem benötigt werden, gehören die
Beschreibung der Kategorie `namecat01desc`, die ID des Containers in
welchem die Grafik dargestellt werden soll `namecat01id`, die URL für
die Quelle der D3.js Bibliothek `urld3` und das Feedback `feedback01`.
Zwischen den Script Tags werden JS Variablen definiert die an das
Template boxplot.mustache übergeben werden. Dieses ist für das Aussehen
der Grafik verantwortlich. Das Template boxplot.mustache wird per `{{>
osa/boxplot}}` in das aktuelle Template eingebunden. Das bringt den
Vorteil, dass das Aussehen der jeweiligen Grafik mit einzelnen
Änderungen für alle Kategorien gleichzeitig angepasst werden kann.

<span name="dest:zukuenftigeoptiontemplate">Weitergedacht</span> lässt
sich dieses System soweit anpassen, dass zwar immer alle Variablen der
Variable-Value-Zuordnung, wie beispielsweise `var median =
{{mediancat01}}`, belegt sind aber mithilfe von `{{>
osa/nameofgrafiktemplate}}` die Variablen immer in das gewünschte
Template übergeben werden. Eine weitere Einstellungsoption, welches
Template verwendet werden soll, muss noch programmiert werden und könnte
als weiterer Punkt am Ende zu den
[Einstellungsbuttons](#fig-screenshot-screen-ansicht-hinzufuegen-von-fragetypologien-und-einstellungen)
hinzugefügt werden.

<a name="fig-screenshot-code-template-vars-cat-01"></a>
![Codebeispiel OSA Plugin: Kategorie mit JS Variablen, welche an die
spezifischen D3.js übergeben
werden](/images/screenshot-code-template-vars-cat-01.svg
"Codebeispiel OSA Plugin: Kategorie mit JS Variablen, welche an die spezifischen D3.js übergeben werden")

#### <a name="technischebesonderheitaenderungfragenanordnung"></a>Technische Besonderheit bei der Änderung der Fragenanordnung

Technische Besonderheiten zeigen sich auch bei der Option die
Fragenanordnung zu ändern. Alleine PHP und die Datenbank reichen aus, um
dieses Ziel zu realisieren. Wird der Button zum Verschieben der Frage
nach oben geklickt, wird geprüft welches der nächste Eintrag mit
[kleinerer Sort Id und derselben zugehörigen
Kursmodulid](#fig-screenshot-db-mdl-osa-qtype-collection) ist und dabei
die Werte in der Sort Spalte getauscht
(edit\_questiontype\_move{up,down}.php).

<a name="fig-screenshot-db-mdl-osa-qtype-collection"></a>
![Datenbank OSA Plugin: Tabelle
mdl\_osa\_qtype\_collection](/images/screenshot-db-mdl-osa-qtype-collection.svg
"Datenbank OSA Plugin: Tabelle mdl_osa_qtype_collection")

#### <a name="technischekonzeptionexportpdf"></a>Technische Konzeption Export der Ergebnisse in einer PDF

Für den Export der Ergebnisse im PDF Format werden einerseits die
spezifischen Nutzerdaten der entsprechenden Durchführungsversuche
benötigt, andererseits müssen nicht nur die Beschreibung der
Kompetenzkategorien, sondern auch alle zugehörigen Grafiken, SVG Pfade
im DOM der Ergebnisgrafiken und die individuellen nutzerspezifischen
Rückmeldungen mithilfe von in Moodle integrierten Bibliotheken so
aufbereitet werden, dass am Ende alle Daten mithilfe von TCPDF in eine
PDF grafisch ansprechend gepackt und zur Verfügung gestellt werden
können. Konzeptionell würde dabei folgendermaßen vorgegangen:

1.  Holen der Beschreibung der Kompetenzkategorien aus der Datenbank und
    Speicherung in entsprechenden Variablen.
2.  Holen der Feedbacktexte zu den aktuellen und vergangenen Versuchen
    aus der Datenbank und Speicherung in entsprechenden Variablen.
3.  Für die Verwendung der Ergebnisgrafiken könnte man die D3 Grafiken
    in ein Canvas Element einbetten.
4.  Mithilfe der `toDataUrl()` Methode können die Ergebnisgrafiken dann
    in Data Urls gewandelt werden. Diese Data URLs werden wiederum in
    PHP Variablen gespeichert und an die Datei im osa Verzeichnis
    `/generate_user_pdf.php` übergeben.
5.  Diese Data Urls können mithilfe der `base64_decode()` Funktion in
    ein mit TCPDF verwendbares Format gewandelt und die Ergebnisgrafiken
    somit in der PDF dargestellt werden.

#### <a name="technischespeicherungbilderhtmleditor"></a>Technische Funktion der Speicherung von Bildern aus dem Moodle html Editor

Die Moodle Forms API beschreibt unter anderem die Speicherung von
Dateien, welche beispielsweise mithilfe des Moodle Forms Editor\[9\]
gespeichert werden. Dieser komplexe Prozess der Speicherung und der
Darbietung im Browser läuft vereinfacht erklärt so ab, dass die Datei in
einer Art Zwischenspeicher gespeichert wird bevor sie in das
`moodledata` Verzeichnis verschoben wird. Die Datenbank enthält nur den
Verweis auf die Datei. Für die Darbietung wird die Datei aus dem
`moodledata` Verzeichnis in den Zwischenspeicher kopiert und
anschließend im Browser dargeboten. Im Detail sind dafür mehrere
Schritte nötig:

  - Die Funktion `file_prepare_standard_editor()`bewirkt, dass bereits
    bestehende Dateien in den Zwischenspeicher kopiert werden und der
    Platzhalter, welcher in der Datenbank steht, durch eine in der Form
    verwendbare URL ersetzt wird.
  - Mithilfe der Funktion `osa_edit_questiontype_{questiontypename}`,
    die sich in der lib.php befindet, werden die Datei und Textdaten in
    die Datenbank und in den persistenten Speicher im Verzeichnis
    `moodledata` geschrieben. Die Funktion
    `file_postupdate_standard_editor()` spielt dabei eine besondere
    Rolle, da sie die Dateien im persistenten Speicher speichert und die
    URL der Dateien in der Datenbank mit Platzhaltern ersetzt.
  - In der Datenbank ist der Verweis auf die Datei beispielsweise unter
    dem Eintrag im zugehörigen Datenbankfeld `<img
    src="@@PLUGINFILE@@/small7.png" alt="" width="193" height="128"
    role="presentation" class="img-fluid atto_image_button_middle">` zu
    finden.
  - Die Datei, in diesem Fall `small7.png`, wird unterhalb des
    moodledata Verzeichnisses gespeichert. Der Dateiname ist der SHA1
    hash der Datei.
  - Durch die Verwendung der Funktion `file_rewrite_pluginfile_urls()`
    wird die URL, unter welcher die Datei dargeboten wird, generiert und
    kann im Browser dargestellt werden.
  - Leider besteht beim Generieren und Darbieten der Datei ein noch zu
    lösendes Problem.

## <a name="vorgehensweiseinderprogrammierung"></a>Vorgehensweise in der Programmierung

Die Programmierung des OSAs war von einer agilen Vorgehensweise geprägt.
Dabei wurden verschiedene Hilfsmittel und Methoden verwendet. Unter
anderem wurde die Methode des Extreme Programming praktiziert.
Verschiedene Werkzeuge, wie beispielsweise der Einsatz eines
Kanbanboards mit Kanbankarten unterstützten den Entwicklungsprozess
massiv. Eine der einfachen Kanbankarten aus dem Projekt ist in [Ansicht
einfache Kanbankarte](#fig-screenshot-screen-kanban) zu sehen.

<a name="fig-screenshot-screen-kanban"></a>
![Ansicht einfache Kanbankarte](/images/screenshot-screen-kanban.svg
"Ansicht einfache Kanbankarte")

# <a name="anwendertestszielgruppe"></a>Anwendertests mit der Zielgruppe

Die Zielgruppe des ersten Anwendertests sind Personen, welche OSAs
erstellen und über die Zeit hinweg pflegen sollen. In unserem Fall
handelt es sich dabei um Lehrende und akademische Mitarbeiter/innen von
Hochschulen. Ein erster Anwendertest mit der Zielgruppe wurde
durchgeführt. Folgende Schlussfolgerungen aus den Rückmeldungen der
Testpersonen können gezogen werden:

  - Grundsätzlich der gesamte Prozess der Anlage des OSA Grundgerüsts,
    der Erstellung von verschiedenen Fragetypologien, die Zuordnung der
    Fragetypologien zu Kategorien, das Setzen von Standardwerten für die
    einzelnen Kategorien und das Festlegen von individuellem Feedback
    funktioniert gut.
  - Der Prozess zum Anlegen aus Sicht der Zielgruppe ist logisch
    aufgebaut (siehe [Ansicht OSA Plugin: Buttons Fragetypologien und
    weitere Einstellungen Kategorien und
    Auswertungseinstellungen](#fig-screenshot-screen-ansicht-hinzufuegen-von-fragetypologien-und-einstellungen)).
  - Es besteht eine einfache für die Zielgruppe verständliche
    Möglichkeit Frage-Items der verschiedenen Fragetypologien direkt zu
    bearbeiten.
  - Es besteht der Wunsch bisher bestehende grafische Darstellungen zu
    optimieren.
  - Es wäre wünschenswert eine Option für das einfache Duplizieren von
    Frage-Items verwenden zu können.

# <a name="ausblick"></a>Ergebnisbewertung und Ausblick

Neben den in Kapitel [„Exemplarische technische
Umsetzung“](dest:zukuenftigeoptiontemplate) erwähnten Erweiterung des
Plugins mit Darstellungsformen der Ergebnisse mithilfe von Templates
sind weitere Schritte zur Verbesserung der Funktionalität und des
Umfangs des Plugins geplant. Dazu gehören eine Anpassung der Templates
für eine erweiterte Darstellung der verschiedenen Fragetypologien, eine
einfache Funktion für das Duplizieren von Frage-Items, Backup- und
Wiederherstellungsfunktionen für die komplette Aktivität, automatische
Löschroutinen für gesammelte Nutzerdaten, eine DSGVO-konforme
Exportfunktion für Nutzerdaten zu Forschungszwecken und der Vergleich
von Daten der aktuellen Nutzer/in mit Daten einer bestimmten Gruppe. Die
Einführung von Session Keys würde die Sicherheit in Bezug auf CSRF
Angriffe verbessern.

Grundsätzlich ist das Plugin in der veröffentlichten Version auf jedem Moodle ab Version 4.0 lauffähig. Es wird allerdings ausdrücklich darauf hingewiesen, dass für einen produktiven Einsatz der OSA-Aktivität in Moodle weitere Entwicklungstätigkeiten und Verbesserungen erforderlich sind. Ein Code-Review und ausführliche Softwaretests werden dringend empfohlen. Da das Plugin als Open-Source-Projekt konzipiert und entwickelt wurde, steht es der gesamten Community unter der GNU GPL v3.0-Lizenz zur Weiterentwicklung und Nutzung zur Verfügung (Hinweise: Die adaptierte Version der D3-Grafik zur Darstellung von Boxplots steht unter der MIT-Lizenz.). Auch wenn die Entwicklung durch das Zentrum für Digitalisierung (ZenDi) an der PH Weingarten nicht weitergehen sollte, besteht die Chance, dass andere Hochschulen oder Projekte auf diesen Ergebnissen aufbauen und das Plugin weiterentwickeln werden.

Zusätzlich wäre ein weiteres Plugin für das Moodle Dashboard (siehe
Kapitel [OSA Dashboard](#zusatzosadashboard)) eine lohnenswerte
Zusatzentwicklung für das Online Self Assessment. Dieses könnte auch
eine automatische Erinnerung an das nächste anstehende OSA,
beispielsweise per E-Mail, beinhalten.

# <a name="hinweiseveroeffentlichung"></a>Hinweise zur Veröffentlichung der Dokumentation und des Pluginprogrammcodes

  - **2023-12-08**: Das OSA Plugin befindet sich im Alpha Stadium. Nach
    (Riddell & Brown, 2023) ist Pre-Release Software, zu welchem auch
    das Alpha Stadium zählt, nur für Entwickler und Testpersonen
    geeignet. Es handelt sich um instabile Software, welche Softwarebugs
    enthält. Trotz sorgfältigster Prüfung kann Pre-Release Software im
    Extremfall zu Datenverlust führen.



# <a name="literaturverzeichnis"></a>Literaturverzeichnis

Bostock, M., Ogievetsky, V., & Heer, J. (2011). D3: Data-Driven
Documents. IEEE Transactions on Visualization and Computer Graphics
(Proceedings of InfoVis). Abgerufen von
<http://vis.stanford.edu/papers/d3>

Baars, M., Vink, S., van Gog, T., Bruin, A. de & Paas, F. (2014).
Effects of training self-assessment and using assessment standards on
retrospective and prospective monitoring of problem solving. Learning
and Instruction, 33, 92–107.
<https://doi.org/10.1016/j.learninstruc.2014.04.004>.

Boud, D., & Brew, A. (1995). Developing a typology for learner self
assessment practices. Research and development in Higher Education, 18,
130 – 135.

Diercks, J., Kast, J., Kupka, K., & Bolten, K. (2009). HAW-Navigator –
internetbasierte Orientierungs- und Self-Assessment-Instrumente und ihre
Verbindung mit der Studienberatung an der HAW Hamburg. Zeitschrift für
Beratung und Studium, 4 (1), 15–21.

Lyons, A. (2023, 20. Oktober). Files in forms | moodle developer
resources. Moodle Pty
Ltd. <https://moodledev.io/docs/4.3/apis/subsystems/form/usage/files>

Müller, W., Grassinger, R., Schnebel, S., Stratmann, J., Weitzel, H.,
Aumann, A., Bernhard, G., Gaidetzka, M., Heiberger, L., Kreyer, I.,
Schmidt, C., Uhl, P., Visotschnig, M. & Widmann, J. (2021). Integration
of Digital Competences into a Teacher Education Program: A Sensitive
Approach. Proceedings of the 13th International Conference on Computer
Supported Education - Volume 1: CSEDU, 232–242.
<https://doi.org/10.5220/0010527202320242>.

Petri, P.S., Schütte, N., Beauducel, A. (2022). Mit OSA erfasste
Personenmerkmale und deren Interaktion mit OSA-Rückmeldungen und
Informationselementen. In: Stoll, G., Weis, S. (eds)
Online-Self-Assessments zur Studienfachwahl. Springer, Berlin,
Heidelberg. <https://doi.org/10.1007/978-3-662-63827-9_4>.

Riddell, J., & Brown, P. (2023, 29. November). KDE’s 6th
Megarelease—Beta 1. KDE Community.
<https://kde.org/announcements/megarelease/6/beta1/>.

Schmidt-Atzert, L., Schütz, M. & Stemmler, G. (2019).
Online-Self-Assessments an Hochschulen.

1.  Für den aktuellen Softwarestand siehe Kapitel [Hinweise zur
    Veröffentlichung der Dokumentation und des
    Pluginprogrammcodes](#hinweiseveroeffentlichung)

2.  <https://www.bmbf.de/bmbf/de/forschung/das-wissenschaftssystem/qualitaetsoffensive-lehrerbildung/qualitaetsoffensive-lehrerbildung_node.html>

3.  <https://tegodi.ph-weingarten.de/>

4.  <https://www.qualitaetsoffensive-lehrerbildung.de/lehrerbildung/shareddocs/projekte/teacher-education-goes-digital-tegodi-wissenschaftlich-fundierte-und-forschungsbasierte-vermittlung-digitalisierungsbezogener-kompetenzen-fuer-lehramtsstudierende-lehrkraefte-und-hochschullehrende_01j.html>

5.  <https://joint-research-centre.ec.europa.eu/digcompedu_en>

6.  <https://www.ph-weingarten.de/studium-weiterbildung/einrichtungen/phokus/>

7.  <https://mwk.baden-wuerttemberg.de/fileadmin/redaktion/m-mwk/intern/dateien/pdf/FESt/Landesstrategie_Eignung_und_Auswahl.pdf>

8.  <https://blog.rwth-aachen.de/sam/projekt/>

9.  <https://moodledev.io/docs/apis/subsystems/form/usage/files> (Lyons,
    2023)
