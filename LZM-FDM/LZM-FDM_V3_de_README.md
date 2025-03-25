<!--
title: "README zur Lernzielmatrix zum Themenbereich Forschungsdatenmanagement (FDM) V3"

pdf-engine: pdflatex

lang: de

documentclass: scrartcl

toc: true
toc-depth: 2

header-includes:
  - \renewcommand{\contentsname}{Inhaltsverzeichnis}

  - \usepackage{titling}
  - \pretitle{\begin{center}\Huge\bfseries}
  - \posttitle{\end{center}\clearpage}

  - \usepackage{etoolbox}
  - \patchcmd{\tableofcontents}{\end{center}}{\end{center}\clearpage}{}{}

  - \usepackage{enumitem}

  - \setlist[enumerate,1]{nosep, topsep=3pt, partopsep=3pt, parsep=0pt, itemsep=0pt}

  - \setlist[itemize,1]{nosep, topsep=3pt, partopsep=3pt, parsep=0pt, itemsep=0pt}

  - \renewcommand{\baselinestretch}{1.2}

  - \newcommand{\sectionbreak}{\clearpage}

  - \usepackage{xurl}
  - \usepackage{hyperref}
  - \hypersetup{breaklinks=true}
  - \sloppy
-->

# README zur Lernzielmatrix zum Themenbereich Forschungsdatenmanagement (FDM) V3

# Autor:innen

***Britta Petersen***, [ORCID: 0000-0002-0355-2594](https://orcid.org/0000-0002-0355-2594); ***Franziska Altemeier***, [ORCID: 0000-0001-7086-6211](https://orcid.org/0000-0001-7086-6211); ***Sophie Boße***, [ORCID: 0009-0002-6461-8291](https://orcid.org/0009-0002-6461-8291); ***Nina Düvel***, [ORCID: 0000-0003-0877-0483](https://orcid.org/0000-0003-0877-0483); ***Claudia Engelhardt***, [ORCID: 0000-0002-3391-7638](https://orcid.org/0000-0002-3391-7638); ***Mark Fichtner***, [ORCID: 0000-0001-5597-4222](https://orcid.org/0000-0001-5597-4222); ***Canan Hastik***, [ORCID: 0000-0003-1729-4642](https://orcid.org/0000-0003-1729-4642); ***Jan-Michael Haugwitz***, [ORCID: 0009-0007-3576-3947](https://orcid.org/0009-0007-3576-3947); ***Juliane Jacob***, [ORCID: 0000-0002-0443-3570](https://orcid.org/0000-0002-0443-3570); ***Katharina Koch***, [ORCID: 0000-0002-7455-2874](https://orcid.org/0000-0002-7455-2874); ***Alessandra Kuntz***, [ORCID: 0000-0002-8259-2577](https://orcid.org/0000-0002-8259-2577); ***Antje Manske***, [ORCID: 0009-0001-0248-4462](https://orcid.org/0009-0001-0248-4462); ***Andreas Mühlichen***, [ORCID: 0000-0003-3115-4021](https://orcid.org/0000-0003-3115-4021); ***Jorge Murcia Serra***, [ORCID: 0000-0003-3062-7376](https://orcid.org/0000-0003-3062-7376); ***Jochen Ortmeyer***, [ORCID: 0000-0003-2074-8027](https://orcid.org/0000-0003-2074-8027); ***Manuela Richter***, [ORCID: 0000-0003-1060-2622](https://orcid.org/0000-0003-1060-2622); ***Hermann Schranzhofer***, [ORCID: 0000-0003-0249-2726](https://orcid.org/0000-0003-0249-2726); ***Benjamin Slowig***, [ORCID: 0000-0001-5343-2788](https://orcid.org/0000-0001-5343-2788); ***Ute Trautwein-Bruns***, [ORCID: 0000-0003-0531-0182](https://orcid.org/0000-0003-0531-0182); ***Dorothee Urbaum***, [ORCID: 0009-0003-5711-6303](https://orcid.org/0009-0003-5711-6303); ***Anne Voigt***, [ORCID: 0000-0002-2873-3201](https://orcid.org/0000-0002-2873-3201); ***Stephanie Werner***, [ORCID: 0000-0002-0468-8856](https://orcid.org/0000-0002-0468-8856); ***Cord Wiljes***, [ORCID: 0000-0003-2528-5391](https://orcid.org/0000-0003-2528-5391); ***Linda Zollitsch***, [ORCID: 0000-0001-9592-3382](https://orcid.org/0000-0001-9592-3382)  

Als Autor:innen an früheren Versionen außerdem beteiligt:

***Tanja Hörner***, [ORCID: 0000-0003-3280-6941](https://orcid.org/0000-0003-3280-6941), ***Tatiana Kvetnaya*** [ORCID: 0000-0002-5477-1199](https://orcid.org/0000-0002-5477-1199), ***Sandra Schulz***, [ORCID: 0000-0002-2254-6579](https://orcid.org/0000-0002-2254-6579)

---

Die Versionen 1.0 und 2.0 dieser Publikation wurden durch Mitglieder der UAG Schulungen/Fortbildungen der DINI/nestor-AG Forschungsdaten erarbeitet. Die Version 3.0 wurde durch Mitglieder der UAG Schulungen/Fortbildungen der DINI/nestor-AG Forschungsdaten, der Sektion Training & Education (EduTrain) der NFDI e. V. sowie des Projektes Data Literacy Alliance (DALIA) erstellt.

---

**LIZENZHINWEIS**

Falls nicht anders vermerkt, ist die „Lernzielmatrix zum Forschungsdatenmanagement“ unter [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) lizenziert.

---

**ZITATIONSVORSCHLAG**

Petersen, B., Altemeier, F., Boße, S., Düvel, N., Engelhardt, C., Fichtner, M., Hastik, C., Haugwitz, J.-M., Jacob, J., Koch, K., Kuntz,  A., Manske, A., Mühlichen, A., Murcia Serra, J., Ortmeyer, J., Richter, M., Schranzhofer, H., Slowig, B., Trautwein-Bruns, U., Urbaum, D., Voigt, A., Werner, S., Wiljes, C., Zollitsch, L. (2025) Lernzielmatrix zum Themenbereich Forschungsdatenmanagement (FDM) (Version 3). Zenodo. https://doi.org/10.5281/zenodo.15025246

**DOI**: 10.5281/zenodo.15025246

\pagebreak

# Danksagung

Unser herzlicher Dank gilt der großartigen Unterstützung aus der Community!

Nur durch den regen Austausch und das engagierte Mitwirken konnte die Lernzielmatrix zum Forschungsdatenmanagement in Version 3 so umfassend überarbeitet werden. Der offene Dialog und die konstruktive Zusammenarbeit haben es ermöglicht, viele Perspektiven zu integrieren und die Matrix auf ein neues Level zu heben. Die Matrix wurde praxisorientiert durch wertvolle Beiträge und Kommentare aus der Community weiterentwickelt, um aktuellen Anforderungen und Entwicklungen im Bereich der Kompetenzentwicklung im Forschungsdatenmanagement gerecht zu werden. Neben den namentlich genannten Autor:innen hat eine Vielzahl weiterer Community-Mitglieder die Überarbeitung der Lernzielmatrix durch unterschiedliche Beiträge unterstützt und vorangebracht. Für diese großartige Unterstützung und die vielen wertvollen Beiträge möchten wir uns bedanken.

Ein besonderer Dank gilt dem Projekt Data Literacy Alliance (DALIA) für die federführende Organisation des Community-Events 2024 in Darmstadt sowie der kontinuierlichen redaktionellen Arbeit an der Lernzielmatrix.

Wir sind stolz auf diese aktive und engagierte Community und freuen uns auf den weiteren Austausch und die gemeinsame Weiterentwicklung.

Mit anderen Worten: You rock!

Vielen Dank für Eure Zeit und Euer Engagement!

Britta Petersen

für das Redaktionsteam und die UAG Schulungen/Fortbildungen der DINI/nestor AG Forschungsdaten

\pagebreak

# 1 Einleitung und Zielsetzung

Die vorliegende Lernzielmatrix zum Themenbereich Forschungsdatenmanagement (FDM) verfolgt einen generischen Ansatz mit dem Anspruch, über Fach- und Organisationsgrenzen hinaus für Hochschullehrende, Curricula-Verantwortliche und Personen aus dem Fort- und Weiterbildungsbereich eine Hilfestellung zu bieten: Durch den Abgleich von Curricula nationaler und internationaler Schulungsprogramme soll eine Empfehlung zu relevanten Themenbereichen und zielgruppenspezifischen Lernzielen geboten werden, die zur Qualitätssicherung bestehender sowie in Entwicklung befindlicher Lehr- und Lernkonzepte beiträgt. Für die vorliegende dritte Version wurden sämtliche Themen und Lernziele in einem Community-Prozess geprüft, kommentiert, überarbeitet und in eine sprachlich einheitliche Form gebracht. Das Begleitmaterial wurde überarbeitet und erweitert, ein Glossar erarbeitet und im Sinne einer Optimierung im Hinblick auf die FAIR-Prinzipien erste Schritte zu einer formalisierten Bereitstellung der Lernziele als Linked Open Data (LOD) erstellt.

Die Lernzielmatrix zum FDM …

* schafft Transparenz über erwartete Lehr- und Lerninhalte,
* kann als „roter Faden“ im Lernprozess fungieren,
* dient dazu, den Lernprozess gezielt zu steuern und zu reflektieren und
* stellt operationalisierte Lernziele für Prüfungen, Lernfortschrittstests oder Selbsteinschätzungen zur Verfügung.

Die Lernzielmatrix zum FDM unterstützt …

* bei der Auswahl relevanter Inhalte,
* die Entwicklung und fortlaufende Qualitätssicherung von Curricula sowie einzelnen Bildungsangeboten und -materialien und
* bei der Qualifizierung von Lehrenden.

Die Matrix schlägt generische Lernziele zu relevanten FDM-Themenfeldern vor. Diese Lernziele sind auf vier Zielgruppen abgestimmt, für die es strukturierte Ausbildungen bzw. Fortbildungsprogramme gibt: Bachelor, Master, Early Career Researcher und Data Stewards. Die Formulierungen der Lernziele für die unterschiedlichen Zielgruppen unterstützen die Entwicklung und Implementierung von bedarfs- und zielgruppengerechten Lehr- und Lernkonzepten und damit die Förderung von Daten- und FDM-Kompetenzen. Die Lernzielmatrix kann als Arbeitsgrundlage für eine erweiterte fachspezifische Ausgestaltung oder andere individuelle Bedarfe dienen (siehe Abschnitt zu Anwendungsszenarien und -beispielen). Die Matrix ist erweiterbar, wird kontinuierlich verbessert und dient der Community als Diskussions- und Arbeitsgrundlage. Für Feedback zu Verbesserungen, Erweiterungen und Best-Practices ist das Redaktionsteam dankbar. Kontaktmöglichkeiten werden unter “Kontakt” aufgeführt.

\pagebreak

# 2 Adressierte Personengruppen

Die Lernzielmatrix zum FDM richtet sich an alle Personen in der Forschung oder in forschungsnahen Bereichen, die zum Auf- und Ausbau von Kenntnissen und Fähigkeiten im Umgang mit Forschungsdaten beitragen. Insgesamt wird mit der Matrix das Ziel verfolgt, eine Orientierung im Sachgebiet FDM zu bieten und die Entwicklung von Lehr-/Lernmaterial und -veranstaltungen sowie die Integration des Themenbereichs FDM oder einzelner Aspekte in Lehrveranstaltungen, Modulen und Curricula zu unterstützen. Neben der strukturierten Darstellung relevanter Themen liefert die Matrix Vorschläge für operationalisierte Lernziele für unterschiedliche Lernniveaus und Lernenden-Zielgruppen.

Zu den adressierten Personengruppen gehört das Personal an Hochschulen und Forschungseinrichtungen, dessen Aufgabenprofil Aspekte des Forschungsdatenmanagements (FDM) umfasst oder das einen Großteil seines Stellenprofils darauf ausgerichtet hat. Dabei richtet sich die Lernzielmatrix insbesondere an die Personengruppen, die Informationsveranstaltungen und Schulungen zum FDM gestalten, oder andere bei der Konzeption von Lehrveranstaltungen oder Curricula als FDM-Multiplikator:innen begleiten. Auch für Lehrende der Fachbereiche, die Aspekte des FDM in ihre Lehrveranstaltungen integrieren möchten, ist die Matrix eine Unterstützung.

\pagebreak

# 3 Entwicklungsprozess

Im Folgenden wird auf die Entstehung der Lernzielmatrix und den weiteren Entwicklungsprozess bis zur Version 3 eingegangen.

## 3.1 Entwicklung von Versionen 1 und 2

Die Version 1 der Lernzielmatrix zum FDM (Petersen et al., 2022) entstand im Rahmen der Aktivitäten der DINI/nestor AG Forschungsdaten UAG Schulungen/Fortbildungen (kurz: UAG Schulungen/Fortbildungen) mit dem Ziel, auf Basis bereits vorliegender FDM-bezogener Trainingskonzepte und -materialien eine Orientierungshilfe für FDM-relevante Themen zu erarbeiten. Version 1 beinhaltet Vorschläge für Lernziele für verschiedene Qualifikationsstufen zur Förderung der FDM-Kompetenzen, die ausgehend von Engelhardt et al. (2022, Appendix E – Knowledge units and corresponding learning outcomes for the bachelor’s, master’s and PhD degree levels) entwickelt wurden. Ein Redaktionsteam aus Mitgliedern der UAG Schulungen/Fortbildungen sammelte und strukturierte die in deutschsprachigen Trainingskonzepten und -materialien zum Themenbereich FDM[^01] aufgeführten Themen und Lernziele. In mehreren Iterationsschritten erfolgte innerhalb des Redaktionsteams unter Einbezug weiterer Expert:innen eine Sortierung und Zuordnung von Themen und Lernzielen, sowie eine ergebnisorientierte Formulierung der zusammengetragenen Lernziele in Anlehnung an die Lernzieltaxonomie von Bloom (1956) bzw. Anderson und Krathwohl (2001). Die Version 1 der Lernzielmatrix wurde anschließend im September 2022 veröffentlicht (siehe auch Abb. 1 für eine Übersicht zur Entstehungsgeschichte).

In Version 2 (Petersen et al., 2023), die einige Monate nach Version 1 veröffentlicht wurde, gab es keine wesentlichen inhaltlichen, sondern nur redaktionelle Anpassungen. Eine wertvolle Erweiterung war die Übersetzung der Lernzielmatrix ins Englische, welche federführend unter Mitwirkung von Mitgliedern des Konsortiums der Nationalen Forschungsdateninfrastruktur (NFDI) NFDI4Health[^02] erfolgte. Im Zuge der Erweiterung um englische Übersetzungen der Lernziele wurde das Layout der Lernzielmatrix angepasst.

Die Veröffentlichungen der Lernzielmatrix bei Zenodo haben aktuell (Stand 18.02.2025) 11.628 Aufrufe und 9.457 Downloads. Dies zeigt den großen Bedarf und das rege Interesse der FDM-Community an der Lernzielmatrix. Insbesondere zu den Inhalten und ihrer Zuordnung zu den Zielgruppen wurde im Rahmen verschiedener Konferenzen und Workshops diskutiert. Seit 2023 wird die Lernzielmatrix im BMBF-Projekt DALIA[^03] (Data Literacy Alliance) als unterstützendes Werkzeug für die Knowledge-Base für „FAIR data usage and supply“[^04] als föderierte Wissensbasis der NFDI-Sektion Training und Education (EduTrain) diskutiert. Dort werden Lehr-/Lernmaterialien zur Unterstützung des Kulturwandels und der Kompetenzentwicklung für die FAIRe Bereitstellung und Nutzung von Forschungsdaten gesammelt und indiziert. Damit einhergehend wuchs der Bedarf der FDM-Community nach weiterer Vernetzung, gemeinsamen Diskussionen und der Weiterentwicklung der Lernzielmatrix sowie der Veröffentlichung einer neuen Version 3.

[^01]: Train-the-Trainer Konzept zum Thema Forschungsdatenmanagement (Biernacka et al., 2021), Zertifikatskurs Forschungsdatenmanagement NRW (Blümm et al., 2022; TH Köln, 2025; Modulhandbuch: Zentrum für Bibliotheks- und Informationswissenschaftliche Weiterbildung (ZBIW), 2024), Data Train Programm der U Bremen Research Alliance (Hörner et al., 2021; U Bremen Research Alliance, o. D.), data.RWTH an der RWTH Aachen University (Rheinisch-Westfälische Technischen Hochschule (RWTH) Aachen, 2024), eLBB4RDM an der CAU Kiel (Christian-Albrechts-Universität zu Kiel, 2022), Modul „Research Data Management“ an der Universität Bielefeld (Universität Bielefeld, o. D.), FAIR Data Austria (Projektleitung TU Graz; Technische Universität Wien, o. D.)

[^02]: [https://www.nfdi4health.de/en](https://www.nfdi4health.de/en)

[^03]: [https://dalia.education/de](https://dalia.education/de)

[^04]: DALIA Knowledge-Base: [https://search.dalia.education/basic](https://search.dalia.education/basic)

## 3.2 Entwicklung von Version 3

Um Hinweise und Verbesserungsvorschläge von Nutzenden aus der FDM-Community auffangen zu können und mit dem Ziel, eine dritte Version der Lernzielmatrix gemeinsam mit der deutschsprachigen FDM-Community zu erstellen, fand vom 31. Januar bis 1. Februar 2024 in Darmstadt ein Community-Event zur Lernzielmatrix statt[^05]. Dieses wurde gemeinsam von Mitgliedern der UAG Schulungen/Fortbildungen, der DALIA sowie der NFDI-Sektion EduTrain konzipiert, organisiert und durchgeführt. Die Teilnahme an dem Event war offen und kostenfrei für alle Interessierten zugänglich. Angekündigt wurde die Veranstaltung über die DALIA-Webseite, den Rocketchat der NFDI-Sektion EduTrain sowie über Mailinglisten zum FDM in Deutschland. Insgesamt nahmen über 50 Personen an der Veranstaltung teil.

Organisiert als Lunch-to-Lunch Meeting startete das Event mit Inputs zu allgemeinen Grundlagen der Lernzielformulierung sowie Erfahrungsberichten zur Anwendung der Lernzielmatrix aus der Community. In einer ausgedehnten Diskussions- und Arbeitsphase wurden u. a. die Struktur und Inhalte der Matrix diskutiert und Vorschläge zur Überarbeitung formuliert.

Folgende Aspekte und Ziele für die Diskussionen wurden vorab festgelegt und den Teilnehmenden kommuniziert:

* Inhaltliche Prüfung und Aktualisierung der generischen Lernzielmatrix
* Prüfung und Aktualisierung der aufgeführten Themen und Inhalte
* Prüfung und Aktualisierung aufgeführter Lernziele
* Diskussion der Zuordnung von Lernzielen zu Qualifikationsstufen
* Diskussion von Tabellenaufbau, Darstellungsformen, Formalisierung, Speicher- und Publikationsorte

In Anlehnung an die Design-Thinking-Methode erfolgten die Diskussionen in themenbezogenen Gruppen[^06]. Die Gruppenbildung orientierte sich an den sechs in der Lernzielmatrix abgebildeten Themenclustern. Eine zusätzliche siebte Gruppe diskutierte übergeordnete Themen, wie etwa die Struktur der Tabelle, Kodierbarkeit von Items und mögliche Publikationswege. Jede Diskussionsgruppe wurde ständig von einem Mitglied des Event-Organisationsteams durch die Diskussions- und Arbeitsphasen geleitet.

Die Dokumentation der Diskussionen erfolgte schon während der Veranstaltung in allen Gruppen digital. Jeder Gruppe lag ein bereits mit Kommentarspalten vorbereiteter digitaler Auszug des jeweils zu diskutierenden und zu bearbeitenden Themenclusters als Tabelle in einem Online-Cloud-Laufwerk vor, in dem die Teilnehmenden kollaborativ kommentieren und arbeiten konnten.

Alle Teilnehmenden des Community Events wurden eingeladen, sich im Nachgang des Events an der Redaktionsarbeit zur Veröffentlichung der dritten Version der Lernzielmatrix zu beteiligen. Bis zur Veröffentlichung fanden regelmäßige Redaktionstreffen statt, in denen allgemeine Fragen wie Aufbau und Struktur, Aufbau der Lernziele, die einheitliche Verwendung von Begriffen, die Zuordnung von Themen zu Themenbereichen, die Zuweisung von Lernniveaustufen zu in den für die Matrix verwendeten Verben und Weiteres besprochen wurden. In verschiedenen Untergruppen wurden die in der Gesamtredaktion vereinbarten Vorgaben umgesetzt und die Inhalte unter Berücksichtigung der Kommentare aus dem Community Event intensiv überarbeitet. In mehreren Iterationen wurden die Themenzugehörigkeit der Lernziele sowie ihre Vollständigkeit und Redundanz geprüft. Dies erfolgte teamübergreifend und durch den Einsatz von OpenAI’s ChatGPT[^07]. Die Ergebnisse der Arbeit aus dem Community Event und der anschließenden redaktionellen Arbeit wurden vor der Veröffentlichung der NFDI-Sektion EduTrain zur Kommentierung freigegeben. Eingegangene Rückmeldungen wurden im Redaktionsteam besprochen und in die Dokumente eingearbeitet.

![Übersicht zu der Entstehungsgeschichte der Lernzielmatrix zum FDM (*Abbildung steht unter der Lizenz [„Creative Commons Zero“ V 1.0](https://creativecommons.org/publicdomain/zero/1.0/deed.de)*)](./LZM-FDM_V3_de_Entstehungsprozess.jpg)

Im Zusammenhang mit den Arbeiten an der Lernzielmatrix entstand bei den Beteiligten der Wunsch nach einem Glossar zur Erläuterung der in der Matrix verwendeten Begriffe. Dieses Glossar wurde in ständiger Abstimmung mit der Gesamtredaktion in einer eigens eingerichteten Arbeitsgruppe erarbeitet. Das Glossar liegt der Lernzielmatrix in reiner Textform sowie tabellarisch als separates Tabellenblatt in den Dateien LZM-FDM\_V3\_de.xlsx bzw. LZM-FDM\_V3\_de.odt bei. Eine Umsetzung des Glossars als Simple Knowledge Organisation System (SKOS) wird via GitHub[^08] bereitgestellt. Der Entwicklungsprozess des Glossars ist in einem Werkstattbericht (Werkstattbericht-Glossar\_LZM-FDM\_V3\_de.pdf) ausführlich beschrieben. Eine Kurzfassung des Werkstattberichtes steht auch in der README zum oben genannten GitHub Repositorium zur Verfügung.

Neben den Arbeitsgruppen zur Bearbeitung der Lernziele in den Themenclustern, bildeten sich weitere Gruppen, die sich auf die Erstellung von Begleitmaterialien und weitere Themen (Öffentlichkeitsarbeit, Einreichung bei Konferenzen etc.) fokussierten. Eine andere Gruppe beschäftigte sich zudem intensiv damit, wie die Matrix im Hinblick auf das Einhalten der FAIR-Prinzipien verbessert werden kann. Ergebnisse der Diskussionen dieser Gruppe sind im Kapitel “Auf dem Weg zu vernetzten Daten” beschrieben.

Der gesamte Prozess und seine Arbeitsschritte fanden im Zeitraum zwischen Februar 2024 und März 2025 statt.

[^05]: Kurzer Bericht im DALIA-Newsletter: [https://dalia.education/de/newsletter/20240302\_no-2-maerz-2024\#community-event-zur-lernzielmatrix-zum-forschungsdatenmanagement](https://dalia.education/de/newsletter/20240302_no-2-maerz-2024#community-event-zur-lernzielmatrix-zum-forschungsdatenmanagement)

[^06]: Der genaue Ablauf des Events ist hier nachzulesen: [https://liascript.github.io/course/?https://raw.githubusercontent.com/RDM4CAU/LZ4FDM/main/Ziele-und-Methode.md\#1](https://liascript.github.io/course/?https://raw.githubusercontent.com/RDM4CAU/LZ4FDM/main/Ziele-und-Methode.md#1)

[^07]: [https://openai.com/chatgpt/](https://openai.com/chatgpt/)

[^08]: [https://github.com/dini-ag-kim/fdm-lernziele](https://github.com/dini-ag-kim/fdm-lernziele)

\pagebreak

# 4 How-to-use

Die Lernzielmatrix zum FDM ist ein strukturiertes Instrument, das Lehrenden und Lernenden helfen soll, relevante Themenaspekte im Bereich des FDM zu identifizieren und entsprechende Kompetenzen zu vermitteln bzw. zu entwickeln. Die in der Matrix aufgeführten Themen und Lernziele dienen auch als ein mit der Community abgestimmter Rahmen für die inhaltliche Ausrichtung von Lehr-/Lerneinheiten zu Aspekten des FDM.

Da die Lernzielmatrix zum FDM einen generischen Ansatz verfolgt, müssen Nutzende Themen und Lernziele für den eigenen Anwendungsfall individuell auswählen und ggf. anpassen. Die Lernziele der Matrix ersetzen weder ein für einen bestimmten Fachbereich oder eine bestimmte Personengruppe entwickeltes Curriculum noch konkrete Ablaufpläne für Einzelveranstaltungen zum FDM. Die hier aufgeführten Lernziele helfen dabei, relevante Themenaspekte zum FDM sowie dazu passende Lernziele zu identifizieren, auszuwählen, zusammenzustellen und zu gewichten, um eine der jeweiligen Zielgruppe(n) angemessene Vermittlung zu ermöglichen.

Die Themen und Lernziele sind keinesfalls in der in der Matrix angegebenen Reihenfolge nacheinander “abzuarbeiten”. Die Auswahl, Zusammenstellung und Sequenzierung von Themen und Lernzielen zu einem Curriculum oder einer Veranstaltungsplanung mit konkreten Lernaktivitäten und Prüfungsszenarien muss je nach Zielgruppe und fachspezifischen Anforderungen eines konkreten Anwendungsfalls individuell ausgewählt werden. Je nach didaktischem Szenario ist immer wieder eine andere Zusammenstellung und Reihenfolge von Themen und Lernzielen für vorgesehene Bildungsangebote möglich. Es gilt daher stets zu prüfen, welche thematischen Aspekte und welche der dort aufgeführten Lernziele für die eigenen fachspezifischen Anforderungen, den konkreten Anwendungsfall und die Zielgruppe(n) passend sein können.

Nutzende sollten die Themen und Lernziele nicht nur individuell auswählen und sequenzieren, sondern die Lernziele auch im Hinblick auf ihre Fach- oder Anwendungsspezifika anpassen und verfeinern, indem z. B. fachspezifische Bedingungen ergänzt werden. Nur so kann sichergestellt werden, dass die Lernziele optimal auf die spezifischen Anforderungen und Gegebenheiten eines Curriculums bzw. auf individuelle Lehr- oder Weiterbildungsveranstaltungen abgestimmt sind. Allgemeine Hinweise und Hilfestellung zur Formulierung von Lernzielen sowie zur individuellen Anpassung von vorhandenen Lernzielen finden sich im folgenden Abschnitt.

\pagebreak

## 4.1 Formulierung von Lernzielen

Die Formulierung von Lernzielen ist ein wichtiger und zentraler Bestandteil der Planung von Lehr-/Lernszenarien, da sie als Leitfaden für die gesamte didaktische Gestaltung dienen. Klar formulierte Lernziele ermöglichen es, Veranstaltungen gezielt auf die gewünschten Lernergebnisse auszurichten und die Lernprozesse der Lernenden effektiv zu steuern. Sie stellen sicher, dass sowohl für Lehrende als auch für Lernende transparent ist, was am Ende der Veranstaltung erreicht werden soll. Sie bieten eine Grundlage für die Auswahl geeigneter Lehrmethoden und Prüfungsformen.

Für die Gestaltung von Lehre haben Lernziele verschiedene Vorteile:

***Aus Sicht Verantwortlicher von Curricula können Lernziele dabei unterstützen...***

- zu definieren, welche Kenntnisse und Fähigkeiten und welches Fachverständnis in einem Studiengang oder einem Modul erreicht werden soll, also einen Qualifikationsrahmen zu beschreiben.
- eine Einordnung in Strukturvorgaben, z. B. der Kultusministerkonferenz (KMK), des Akkreditierungsrates, den Anforderungen des nationalen und europäischen Qualifikationsrahmens sowie ggf. weiterer fachwissenschaftlicher Vorgaben zu ermöglichen .
- den Vergleich von Bildungsaktivitäten zu ermöglichen und zu verbessern.
- Lernprogramme zielgerichtet aufzubereiten.

***Aus Sicht Lehrender können Lernziele dabei unterstützen...***

- Lernaktivitäten zu planen und zu entwickeln.
- einen sinnvollen Aufbau der Lernaktivitäten zu gestalten und somit einen „roten Faden“ für die Lehre zu entwickeln.
- Lehr- und Lerninhalte zu erzeugen, zu konkretisieren und zu strukturieren.
- die Lernerfolgskontrolle zu erleichtern, indem sie klar beobachtbare und messbare Verhaltensweisen sowie Bewertungskriterien beschreiben.
- die Lerneffizienz zu steigern.

***Aus Sicht Lernender können Lernziele dabei unterstützen...***

- einen Überblick über die in einer Lerneinheit behandelten Inhalte und Anforderungen zu erhalten.
- sich an den Lernzielen zu orientieren und den eigenen Lernfortschritt besser einzuschätzen.
- die Effizienz des Lernens zu steigern.
- das selbstgesteuerte Lernen zu fördern.

\pagebreak

## 4.2 Operationalisierung von Lernzielen

Bei der Formulierung von Lernzielen gilt es generell darauf zu achten, dass die Erreichung des Zieles möglichst eindeutig definiert ist. Wichtig ist hierbei die Formulierung von überprüfbaren, möglichst operationalisierten (s. u.) Lernzielen, mittels derer der Lernerfolg systematisch “gemessen” und evaluiert werden kann. Es gilt, möglichst eindeutige Formulierungen zu finden und Verben zu benutzen, die eine Verhaltensbeobachtung (und damit eine Messbarkeit) möglich machen (vgl. Tabelle 1).

**Tabelle 1**: Beispiel für eindeutige und nicht eindeutige Formulierungen von Lernzielen

| Eindeutige Formulierung  | Nicht eindeutige Formulierung  |
| :---- | :---- |
| benennen, erläutern, anwenden, analysieren, beurteilen, konzipieren | wissen, verstehen, kennen, glauben, vertraut sein mit, interessiert sein an, informiert sein     |
| Beispiel: Lernende können die FAIR-Prinzipien erläutern.  | Beispiel: Lernende sind mit den FAIR-Prinzipien vertraut.  |

Operationalisierte Lernziele bestehen aus einer Inhalts- und einer Handlungskomponente. Die Inhaltskomponente gibt Auskunft darüber, zu welchen konkreten Inhalten Kenntnisse oder Fähigkeiten erworben werden sollen. Die Handlungskomponente beschreibt die Verhaltensweisen, an denen „gemessen“ werden soll, ob Lernende das Lernziel erreicht haben. Nur wenn ein Lernziel ein beobachtbares Verhalten beschreibt, kann die Erreichung des Lernziels überprüft, d. h. “gemessen” werden.

Ein Lernziel gilt als operationalisiert, wenn ...

* tatsächlich beobachtbare Verhaltensweisen der Lernenden beschrieben werden (z. B. "Lernende können die Kriterien nennen" anstatt "Lernende wissen etwas über die Kriterien") und damit
* eine Überprüfbarkeit der Zielerreichung gegeben ist.

Lernziele können dabei unterschiedlich fein ausdifferenziert formuliert werden. Je detaillierter die Formulierung, desto konkreter werden Bedingungen und Bewertungsmaßstäbe für die Zielerreichung angegeben. Die Feinformulierung der hier vorliegenden Lernziele muss dabei durch die Nachnutzenden erfolgen. So kann die Messbarkeit der Erreichung des Lernziels “Lernende können die FAIR-Prinzipien erläutern.” (LZ-ID: 01\_007\_0118) durch die Ergänzung von Bedingungen verschiedentlich konkretisiert werden. Möglich wäre z. B. “Lernende können die FAIR-Prinzipien schriftlich in 3-4 Sätzen erläutern.” oder “Lernende können die FAIR-Prinzipien in Form eines 5-minütigen Kurzvortrags anhand eines selbst gewählten Datensatzes erläutern.”.

\pagebreak

## 4.3 Aufbau der Lernziele in der Matrix

Die Lernzielmatrix zum FDM liefert bewusst grobe Lernziele, deren Satzaufbau immer dem folgenden Schema folgt:

[Lernende können] [Inhaltskomponente] [Handlungskomponente/Verb]

Im Sinne einer einheitlichen Erstellung und zukünftigen Weiterbearbeitung sind die Einzelteile der Lernziele in der Tabelle über die Spalten F, G und H verteilt (siehe Tabelle 2 für die drei Spalten).

**Tabelle 2**: Beispiel zur Lernzielformulierung und der Anwendung des syntaktischen Schematas

| Lernziel Start | Lernziel Inhalt | LZ Verb |
| :---- | :---- | :---- |
| Lernende können | die Eigenschaften offener und restriktiver Lizenzen  | erläutern. |

In Spalte R wird unter der Spaltenüberschrift “Lernziel komplett” jedes Lernziel für ein einfaches Herauskopieren zusätzlich auch komplett zur Verfügung gestellt. Siehe hierzu auch den Abschnitt “Aufbau der Matrix".

Durch die Ergänzung von Bedingungen, unter denen ein beobachtbares Verhalten stattfinden soll (z. B.: unter Anleitung, eigenständig, schriftlich, in Gruppenarbeit, innerhalb eines zeitlichen Rahmens, für das Fach X relevant) können die operationalisierbaren Lernziele der Matrix verfeinert und auf das eigene didaktische Szenario zugeschnitten werden.

## 4.4 Blooms Lernziel-Taxonomie

In der Lernzielmatrix wird für jedes Lernziel eine Lernniveaustufe anhand der Taxonomie von Bloom (1956 bzw. der erweiterten Version von Anderson & Krathwohl, 2001) in der Spalte I (Stufe Bloom) angegeben. Blooms Taxonomie unterteilt Lernziele in verschiedene kognitive Ebenen, die vom einfachen Erinnern und Wissensabruf bis zu komplexeren Prozessen wie Analyse, Synthese und Bewertung reichen. Die Angabe der Lernniveaustufe in der Matrix soll dabei unterstützen, Lernprozesse in eigenen didaktischen Szenarien zu strukturieren und sicherzustellen, dass Lernziele in einer sinnvollen Reihenfolge und mit einem entsprechenden Schwierigkeitsgrad vermittelt werden. Die Zuordnung zu einer Stufe folgt hier anhand der Handlungskomponente, d. h. anhand des jeweils für ein Lernziel genutzten Verbs. Im Sinne einer sprachlichen Harmonisierung nutzt die Lernzielmatrix eine stark beschränkte Auswahl weniger Verben, die jeweils den Bloom’schen Stufen zugewiesen sind. Die Zuordnung ist in Abbildung 2 dargestellt.

![Lernniveaustufen der Lernziel-Taxonomie nach Bloom sowie Auswahl und Zuordnung der für die Lernzielmatrix genutzten Verben (*Abbildung steht unter der Lizenz [„Creative Commons Zero“ V&nbsp;1.0](https://creativecommons.org/publicdomain/zero/1.0/deed.de)*)](./LZM-FDM_V3_de_Lernniveaustufen.jpg)

Darüber hinaus gibt es zahlreiche alternative Verben, die Nutzende für individuell angepasste Lernziele verwenden können. Es existieren diverse Verblisten[^09], die hier als Inspirationshilfe und Orientierung dienen können. Fachspezifische Unterschiede in der Zuordnung eines Verbs zu einer Taxonomiestufe oder auch die doppelte Zuordnung eines Verbs zu verschiedenen Stufen sind möglich. Zu beachten ist, dass die Stufen der Taxonomie nicht gleichbedeutend sind mit der Zuordnung zu einer bestimmten Zielgruppe von Lernenden.

[^09]: z. B. https://lehreladen.rub.de/wp-content/uploads/2022/07/verbliste-sammlung-deutsch.pdf

## 4.5 Kompetenzbereiche

Die Lernzielmatrix stellt verschiedene Kompetenzbereiche zu einem bestimmten Lernziel systematisch dar. Die Kompetenzbereiche Sachkompetenz (SK), Methodenkompetenz (MK), Selbstkompetenz (SeK) und Sozialkompetenz (SoK) sind in den Spalten N–Q den jeweiligen Lernzielen jeweils dichotom zugeordnet. Sie geben an, welche der Kompetenzbereiche durch das jeweilige Lernziel angesprochen werden. Dabei wird unter “Sachkompetenz” eine Sachkenntnis oder fachliches Wissen verstanden, unter “Methodenkompetenz” die Fähigkeit zur Anwendung von Methoden, unter “Selbstkompetenz” die Fähigkeit zu Selbstmanagement und Reflexion und unter "Sozialkompetenz” die Zusammenarbeit und Kommunikation. Die Zuordnung eines Kompetenzbereichs zu einem Lernziel ist dabei jeweils durch ein “x” in der entsprechenden Zelle gekennzeichnet. Ein Lernziel kann mehrere Kompetenzbereiche ansprechen.

Die Angaben zu den Kompetenzbereichen erfolgte nach Einschätzung durch das Redaktionsteam in Orientierung an der Handlungskomponente, d. h. an den jeweils genutzten Verben:

**Tabelle 3**: Kompetenzbereiche und hinweisgebende Verben

| Kompetenzbereich | Handlungskomponente [Verben] | Erläuterung |
| :---- | :---- | :---- |
| Sachkompetenz | benennen, erläutern | Um etwas benennen oder erläutern zu können, ist Sachkompetenz (Sachkenntnisse, fachliches Wissen) nötig. |
| Methodenkompetenz  | anwenden, analysieren, durchführen, entwickeln, konzipieren | Um etwas anwenden, durchführen, analysieren, entwickeln oder konzipieren zu können, ist Methodenkompetenz nötig. |
| Selbstkompetenz | beurteilen, diskutieren, durchführen (bei Lehre & Beratung) | Das Führen von Diskussionen, Bewertungen/Beurteilungen (des eigenen Handelns) sowie Durchführung von Schulungs- und Beratungsmaßnahmen erfordert Selbstkompetenz. |
| Sozialkompetenz  | diskutieren, beurteilen, durchführen, anwenden (in kollaborativen Prozessen) | Das Führen von Diskussionen, Bewertungen/Beurteilungen sowie Durchführung von Schulungs- und Beratungsmaßnahmen erfordert Sozialkompetenz. |

Für die Nutzenden der Lernzielmatrix sollen diese Angaben eine Orientierung bieten, wie Lernziele zusammengestellt und sequenziert werden können, um im Rahmen eines didaktischen Szenarios unterschiedliche Kompetenzbereiche anzusprechen. Es ist dabei zu beachten, dass sich durch die Ergänzung von Bedingungen zu einem bestehenden Lernziel oder durch die Veränderung der Handlungskomponente (Verb) eines Lernziels die durch das Lernziel angesprochenen Kompetenzbereiche möglicherweise gleichsam erweitern oder ändern.

## 4.6 Individuelle Anpassung von Lernzielen

Wie bereits beschrieben, folgen die Lernziele der Matrix dem immer gleichen Aufbau:

[Lernende können] [Inhaltskomponente] [Handlungskomponente/Verb], z. B. Lernende können die FAIR-Prinzipien (Inhaltskomponente) benennen (Handlungskomponente).

Die aufgeführten Lernziele sind sprachlich prägnant, enthalten keine (fach-)spezifischen Bedingungen und nutzen eine eingeschränkte Auswahl an Verben für die Handlungskomponente. Die Lernziele sind zwar direkt nachnutzbar, es ist jedoch sinnvoll, dass sie im Hinblick auf die eigenen Zwecke verfeinert werden.

Die Inhaltskomponenten der vorhandenen Lernziele können sowohl um (fach-)spezifische Bedingungen als auch um Bedingungen, die sich auf Lern- oder Prüfungsformen beziehen, ergänzt werden. Beispiele folgen unten.

Auch die Handlungskomponente (Verb) eines Lernziels kann und darf verändert und angepasst werden. Die Lernzielmatrix nutzt für die Handlungskomponenten nicht die gesamte Bandbreite aller zur Verfügung stehenden Verben, sodass Nutzende der Matrix diese ggf. selbst ergänzen müssen. Darüber hinaus existieren zahlreiche weitere Alternativen für Handlungskomponenten spezifizierende Verben. Für eine individuelle Anpassung der Handlungskomponente empfiehlt sich die Nutzung von Vorschlagslisten mit Verben entlang der Bloom’schen Taxonomie (siehe Fußnote 9).

## 4.7 Beispiele für die Anpassung von Lernzielen

Die folgende Tabelle zeigt eine Reihe von Beispielen für individuelle Anpassungen von Lernzielen. Grundlage ist jeweils ein Lernziel aus der Matrix (mit Verweis auf die Position in der Matrix mit Hilfe der Lernziel ID) in der linken Spalte. Verschiedene mögliche Anpassungen finden sich in der rechten Spalte.

**Tabelle 3**: Beispiele für individuelle Anpassungen von Lernzielen

| Lernziel:  | mögliche Anpassung(en): |
| :---- | :---- |
| Lernende können Funktionen und Verantwortlichkeiten von Personen im Forschungsdatenmanagement (FDM) erläutern. (LZ-ID 01\_003\_0033) | -> Lernende können Funktionen und Verantwortlichkeiten von **Konservator\*innen und Restaurator\*innen** erläutern. (Hastik & Schwenk, 2025) |
|  | -> Lernende können Funktionen und Verantwortlichkeiten von Personen im Forschungsdatenmanagement (FDM) **anhand eines in Gruppenarbeit erstellten Schaubildes** erläutern. |
|  | -> Lernende können Funktionen und Verantwortlichkeiten von Personen im Forschungsdatenmanagement (FDM) **zunächst in Kleingruppen sowie im Anschluss im gesamten Plenum** *diskutieren*. |
| Lernende können Phasen des Forschungsdatenlebenszyklus erläutern. (LZ-ID 01\_005\_0080) | -> Lernende können die Phasen des Forschungsdatenlebenszyklus **in der sozialwissenschaftlichen Forschung** erläutern. |
|  | -> Lernende können die Phasen des Forschungsdatenlebenszyklus **in Bezug auf ein selbst ausgewähltes Experiment des Praktikums** *beschreiben*. |
|  | -> Lernende können die Phasen des Forschungsdatenlebenszyklus **in Bezug auf die Erstellung einer digitalen Edition schriftlich** erläutern. |
| Lernende können eigenständig einen Einreichungsprozess in einem Repositorium durchführen. (LZ-ID 04\_004\_0876) | -> Lernende können eigenständig den Einreichungsprozess **in das Repositorium Pangaea** durchführen. |
|  | -> Lernende können eigenständig den Einreichungsprozess **für einen im Praktikum aufbereiteten Datensatz im institutionellen** Repositorium durchführen.  |
| Lernende können eigenständig Dateibenennungskonventionen entwickeln. (LZ-ID 02\_006\_0329) | -> Lernende können eigenständig eine Dateibenennungskonvention **für die im Semesterprojekt entstehenden Messdaten** entwickeln.  |
|  | -> Lernende können **kollaborativ** eine Dateibenennungskonvention **für die im Projekt gemeinsam genutzten Daten** entwickeln, **die in Form einer README dokumentiert wird**. (*Verknüpfung mit LZ-ID: 02\_006\_0331: “Lernende können eigenständig eine Dokumentation für Dateibennungskonventionen entwickeln.”*)  |

Zu beachten ist, dass sich durch die Ergänzung von Bedingungen oder die Nutzung eines anderen Verbs für die Handlungskomponente ggf. auch die in der Matrix gegebenen Angaben zur Lernniveaustufe nach Bloom ändern. Zudem können sich auch die Angaben zu den durch das Lernziel angesprochenen Kompetenzbereichen verändern. Dies kann an folgendem Beispiel gezeigt werden:

Originales Lernziel: “Lernende können Versionierungsmethoden anwenden.” (LZ-ID-02\_008\_0362).

Dieses Lernziel bezieht sich auf die Fähigkeit der Lernenden, Versionierungsmethoden korrekt zu nutzen. Es spricht Sachkompetenz und Methodenkompetenz an, da die Lernenden sowohl die fachliche Grundlage (Versionierungsmethoden) als auch die Anwendungsmethoden verstehen und umsetzen müssen.

Wenn das Lernziel mit der Bedingung “kollaborativ” verfeinert wird, lautet es: “Lernende können Versionierungsmethoden kollaborativ anwenden.”

Diese Anpassung erweitert das ursprüngliche Ziel um den Aspekt der Zusammenarbeit zwischen den Lernenden. Dadurch wird zusätzlich die Sozialkompetenz angesprochen, da die Lernenden nun nicht nur die technischen Fähigkeiten benötigen, sondern auch in der Lage sein müssen, in einem Team effektiv zu kommunizieren und die Versionierungsmethoden gemeinsam zu nutzen.

Das Verb “anwenden” ist im Rahmen der Lernzielmatrix der Lernniveaustufe 3 zugeordnet. Bei Veränderung der Handlungskomponente des originalen Lernziels durch Austausch des Verbs “anwenden” mit dem Verb “diskutieren”, lautet das Lernziel: “Lernende können Versionierungsmethdoden diskutieren.” Diese Anpassung sorgt dafür, dass dem Lernziel nun die Lernniveaustufe 4 zugewiesen würde. Darüber hinaus erweitern sich auch hier die angesprochenen Kompetenzbereiche, da zum Diskutieren nicht nur Sach- und Methodenkompetenz, sondern auch eine gewisse Sozialkompetenz nötig ist.

\pagebreak

# 5 Aufbau der Lernzielmatrix: Tabellenstruktur

Die Lernzielmatrix zum FDM liegt in tabellarischer Form in den Dateiformaten xlsx und ods vor. Das Tabellenblatt Lernziele wird zusätzlich im csv-Format zur Verfügung gestellt. Die vorliegenden xlsx- und ods-Dateien enthalten jeweils fünf Tabellenblätter, die im Folgenden erläutert werden:

## 5.1 Tabellenblatt *How-to-use*

Das Tabellenblatt How-to-use enthält eine Kurzanleitung zur Nutzung der Matrix.

## 5.2 Tabellenblatt *Index*

Das Tabellenblatt Index gibt einen Überblick über die wichtigsten Themenbereiche des FDM. Zur Verbesserung der Übersichtlichkeit wurden die Themen in Cluster zusammengefasst und durch unterschiedliche Hintergrundfarben voneinander abgehoben. Weder das Clustering noch die Reihenfolge oder die Farbgebung der Themenbereiche folgen einer Bewertung oder Gewichtung der aufgeführten Aspekte. Sie dienen lediglich der einfacheren Erfassbarkeit.

## 5.3 Tabellenblatt *Lernziele*

Das Tabellenblatt Lernziele enthält sämtliche Themencluster, die darin zusammengefassten Themen sowie die dazugehörigen Lernziele.

**Tabelle 4**: Aufbau des Tabellenblatts *Lernziele*

<!-- style="width: 100%; max-width: 100%; color: black; font-size:10px" -->
| Spalte | Spaltenbeschriftung | Spalteninhalt |
| :---- | :---- | :---- |
| A | LZ-ID  | ID des Lernziels  [Themencluster]\_\[Thema\]\_[Lernziel] in Form [00]\_[000]\_[0000] |
| B | Themencluster | Bezeichnung des Themenclusters |
| C | Cl-ID  | ID des Themenclusters  \[Themencluster\] in Form \[00\] |
| D  | Thema | Bezeichnung des Themas |
| E | Th-ID | ID des Themas \[Themencluster\]\_\[Thema\] in Form \[00\]\_\[000\] |
| F | Lernziel Start | Einleitung Lernziel (“Lernende können”) |
| G | Lernziele Inhalt | Inhaltskomponente des Lernziels |
| H | Lernziel Verb  | Handlungskomponente des Lernziels (Verb) |
| I | Stufe (Bloom) | Lernniveaustufe nach Bloom |
| J-M | BA, MA, ECR, DS | Angemessenheit für Zielgruppen von Lernenden  (BA = Studierende im Bachelor, MA = Studierende im Master, ECR = Early Career Researcher, DS = Data Steward) jeweils dichotom mit [x] für zutreffend  |
| N-Q | SK, MK, SeK, SoK  | Kompetenzbereiche, die durch das Lernziel angesprochen werden. (SK = Sachkompetenz, MK = Methodenkompetenz, SeK = Selbstkompetenz, SoK = Sozialkompetenz) jeweils dichotom mit [x] für zutreffend  |
| R | Lernziel komplett | Vollständiges Lernziel (Ergebnis der Verkettung der Spalten F, G und H) |

Die Tabelleninhalte des Tabellenblatts Lernziele sind in gängiger Tabellenkalkulationssoftware über die Kopfzeile filterbar.

**Lernziele (Spalten F–H)**  
Ein Lernziel setzt sich immer aus den drei Spalten F (Lernziel Start), G (Lernziel Inhalt) und H (Lernziel Verb) zusammen.Die Aufteilung der Lernziele über mehrere Spalten dient dazu, die sprachliche Struktur der Lernziele vorzugeben und damit eine sprachlich harmonische Formulierung von Lernzielen zu ermöglichen. Die Lernziele sind je Themencluster in zufälliger Reihenfolge angeordnet. Zusammenstellung und Reihenfolge, in der Lernziele in einem didaktischen Szenario erarbeitet werden, müssen für den eigenen Anwendungsfall selbst definiert werden.

**Spalten J–M: Angemessenheit für Zielgruppen von Lernenden**
Die Spalten J–M stehen für mögliche Zielgruppen von Lernenden. In der Lernzielmatrix wird zwischen vier Lernenden-Zielgruppen unterschieden:

BA = Studierende im Bachelor  
MA = Studierende im Master  
ECR = Early Career Researcher (Promovierende, PostDocs)  
DS = Data Steward

Die Eignung eines Lernziels für eine der Zielgruppen ist jeweils durch ein x gekennzeichnet. Bei den Angaben zur Eignung eines Lernziels für eine bestimmte Zielgruppe handelt es sich um eine Einschätzung von Seiten des Redaktionsteams der Lernzielmatrix. Die Eignung eines Lernziels für eine bestimmte Gruppe von Lernenden sollte individuell für den eigenen Einsatzzweck geprüft und angepasst werden (siehe auch Individuelle Anpassung von Lernzielen).

**Spalten N–Q: Kompetenzbereiche, die durch das Lernziel angesprochen werden**  
Die Kompetenzbereiche Sachkompetenz (SK), Methodenkompetenz (MK), Selbstkompetenz (SeK) und Sozialkompetenz (SoK) sind in den Spalten N–Q den jeweiligen Lernzielen zugeordnet. Für jedes Lernziel wird angegeben, welche Kompetenzbereiche angesprochen werden. Die Zuordnung eines Kompetenzbereichs zu einem Lernziel ist dabei jeweils durch ein x in der entsprechenden Zelle gekennzeichnet.

**Spalte R: Komplette Lernziele**
In Spalte R (Lernziel komplett) werden die Bestandteile der Lernziele beispielsweise in Tabellenkalkulationssoftware mit der Funktion VERKETTEN zusammengeführt. Die Zusammenführung der Bestandteile der Lernziele ist auch an jedem anderen Ort einer Tabelle mit dieser Funktion möglich. Für eine Zusammenführung der Inhalte der Zeile 2 in Tabellenkalkulationssoftware wird eine Funktion grundsätzlich wie folgt aufgebaut: =VERKETTEN(F2," ", G2," ", H2). LibreOffice beispielsweise verwendet das Semikolon als Trennzeichen, daher kann hier die Funktion: =VERKETTEN(F2;" ";G2;" "; H2) genutzt werden.

## 5.4 Tabellenbaltt *Glossar*

Das Tabellenblatt Glossar enthält die im Glossar aufgeführten Begriffe, deren Erläuterungen sowie Quellenverweise. Die Struktur der Tabelle orientiert sich an SKOS (Simple Knowledge Organization System)[^10], einem Standard zur Darstellung kontrollierter Vokabulare für die maschinenlesbare Verarbeitung. Dabei werden Begriffe als Konzepte (skos:Concept) erfasst und mit standardisierten Bezeichnungen sowie Relationen versehen. Jeder Glossareintrag umfasst eine eindeutige ID, die beschriebenen Begriffe auf Deutsch (skos:prefLabel@de) und Englisch (skos:prefLabel@en) sowie eine kontextbezogene Definition (skos:editorialNote). Zudem werden direkte (skos:exactMatch) und indirekte (skos:closeMatch) Quellenangaben unterschieden, um die Herkunft der Begriffsverwendungen transparent zu machen.

**Tabelle 5**: Aufbau des Tabellenblatts *Glossar*

<!-- style="width: 100%; max-width: 100%; color: black; font-size:10px" -->
| Spalte | Spaltenbeschriftung | Spalteninhalt |
| :---- | :---- | :---- |
| A | opake ID für Glossarkonzept (skos:Concept) | opake ID für Glossarkonzept |
| B | Begriff Deutsch (skos:prefLabel\@de) | Begriff Deutsch |
| C | Begriff Englisch (skos:prefLabel\@en) | Begriff Englisch |
| D | Begriffserläuterungen (Glossareintrag) (skos:scopeNote) | Begriffserläuterungen im Nutzungskontext der Lernzielmatrix (Glossareintrag) |
| E | Indirektes Zitat (skos:closeMatch) | Link zu indirektem Zitat |
| F | Quellenangabe des indirekten Zitats (skos:editorialNote) | vollständige Quellenangabe des indirekten Zitats |
| G | Spalte G: Indirektes Zitat (skos:closeMatch) | Link zu indirektem Zitat |
| H | Quellenangabe des indirekten Zitats (skos:editorialNote) | vollständige Quellenangabe des indirekten Zitats |
| I | Direktes Zitat (skos:exactMatch) | Link zu indirektem Zitat |
| J | Quellenangabe des direkten Zitats (skos:editorialNote) | vollständige Quellenangabe des direkten Zitats |

[^10]: [https://www.w3.org/2004/02/skos/](https://www.w3.org/2004/02/skos/)

## 5.5 Tabellenblatt *Änderungen*

Das Tabellenblatt Änderungen dient der Dokumentation, Kontrolle und Transparenz vorgenommener Änderungen und führt diese in Kurzform auf. Es wird mit der vorliegenden, 3. Version der Lernzielmatrix implementiert und wird ab hier für weitere Versionen geführt.

\pagebreak

# 6 Anwendungsszenarien und -beispiele

Die Lernzielmatrix hat sich bereits mit den ersten beiden Versionen als relevantes Werkzeug in der FDM-Landschaft etabliert und wird zunehmend von der Community genutzt. Um mögliche Nutzungsszenarien der Lernzielmatrix aufzuzeigen, werden an dieser Stelle zunächst theoretische Anwendungsszenarien skizziert. Daran anknüpfend folgt eine Einführung in Anwendungsbeispiele aus der Praxis, in denen die Matrix bereits genutzt wurde. Die gesammelten Anwendungsbeispiele befinden sich in einem separaten Tabellendokument im Anhang.

## 6.1 Anwendungsszenarien

Im Folgenden gibt es einen Überblick über prototypische Anwendungsszenarien, in denen die Lernzielmatrix eingesetzt werden kann, mit jeweils einer kurzen Beschreibung des jeweiligen Szenarios.

**Fachspezifische Adaption der Lernzielmatrix**

* Als lehrende Person möchte ich die generischen Lernziele der Matrix nachnutzen, um für meine Lehrveranstaltungen relevante FDM-Themen zu identifizieren. Basierend darauf formuliere ich disziplinspezifische Lernziele für meine Lehrveranstaltungen und richte meine Konzeption danach aus.
* Als Vertreter:in eines NFDI-Konsortiums möchte ich die generische Lernzielmatrix verwenden, um eine fachspezifische Adaption zu erstellen. Dadurch möchte ich einen Ausgangspunkt für die Konzeption unserer Schulungsinhalte und \-formate generieren.

**Entwicklung von Lehr- oder Weiterbildungsveranstaltungen**

* Als Data Steward möchte ich für die von mir begleitete Forschungsgruppe einen Workshop zur Dateibenennung und Ordnerstruktur durchführen. Dabei orientiere ich mich an den Lernzielen zu diesen Themen, die für die Zielgruppe Early Career Researcher ausgeführt sind.
* Als Organisationsteam eines berufsbegleitenden Zertifikatskurses zum FDM möchten wir die Lernzielmatrix nutzen, um Inhalte und Lernziele für die verschiedenen Module zu identifizieren.

**Selbststudium und Kompetenzentwicklung**

* Als forschende Person möchte ich die Lernzielmatrix nutzen, um meine eigenen FDM-Kenntnisse strukturiert weiterzuentwickeln.

**Erstellung und Qualitätssicherung von Lehrmaterialien**

* Als lehrende Person möchte ich die Lernzielmatrix nutzen, um Lehrmaterial zu FDM-Themen zu erstellen. Ich nutze die Themen und Lernziele zur Orientierung, um sicherzustellen, dass Studierende die relevanten Kompetenzen erwerben können.
* Als lehrende Person möchte ich Lehr-/Lernmaterialien zum Thema FDM nachnutzen. Die Lernzielmatrix unterstützt mich bei einer Einschätzung der inhaltlichen Qualität der Materialien.
* Als lehrende Person möchte ich selbst erstelltes Lehr-/Lernmaterial als OER veröffentlichen. Zur Unterstützung der Auffindbarkeit und Einschätzbarkeit meiner Materialien gebe ich die in meinem Material adressierten Lernziele an.

**Curriculumsentwicklung für Hochschulen**

* Als Koordination eines Studiengangs möchte ich die Lernzielmatrix nutzen, um den Lehrplan eines Masterstudiengangs mit Blick auf eine Reakkreditierung systematisch um FDM-Kompetenzen zu ergänzen. So stelle ich sicher, dass Studierende die Fähigkeiten vermittelt bekommen, die sie für ihren weiteren Weg in Forschung und Industrie benötigen.

**PhD-Programme**

* Als Programmmanagerin des Promotionskollegs meiner Hochschule möchte ich eine Summer-School zu den Themen Nachnutzung und Publikation von Forschungsdaten konzipieren. Die Lernzielmatrix unterstützt mich bei der Auswahl passender Lernziele und der Strukturierung meiner Veranstaltung.

## 6.2 Anwendungsbeispiele

Neben den aufgeführten Anwendungsszenarien hat die Lernzielmatrix bereits vielfältige Anwendung in der Praxis erfahren. Die in der Tabelle Anwendungsbeispiele\_LZM-FDM\_V3\_de.xlsx des Begleitmaterials aufgeführten Anwendungsbeispiele umfassen u. a. fachspezifische Adaptionen der NFDI-Konsortien für Beratungen, Lehr-/Lernmaterialien oder die Nutzung der Lernziele als Grundlage für die Erstellung von Bewertungsrastern zu Prüfungsleistungen. Weitere dieser Beispiele aus der Praxis wurden zusammengetragen und in übersichtlicher Tabellenform aufbereitet, sodass sie Interessierten als Anregung für eigene Vorhaben dienen können. Neben der detaillierten Auflistung, die sich im Anhang der Lernzielmatrix befindet, werden diese und weitere Adaptionen überblicksartig auf der Wiki-Seite der Lernzielmatrix auf Forschungsdaten.org[^11] gesammelt. Weitere Beispiele und Adaptionen können dort gerne selbst hinzugefügt oder dem Redaktionsteam der Lernzielmatrix gemeldet werden.

[^11]: [https://www.forschungsdaten.org/index.php/Lernzielmatrix\#Konkrete\_Anwendungen\_/\_Adaptionen](https://www.forschungsdaten.org/index.php/Lernzielmatrix#Konkrete_Anwendungen_/_Adaptionen)

\pagebreak

# 7 Auf dem Weg zu vernetzten Daten

Die FAIR-Prinzipien (FORCE11, 2021; Wilkinson et al., 2016) spielen eine zentrale Rolle im FDM und definieren Anforderungen, die Forschungsdaten für eine langfristige Nachnutzung erfüllen sollten. Dieser Nachhaltigkeitsgedanke ist auch für die Lernzielmatrix von zentraler Bedeutung. Neben der inhaltlichen Aktualisierung und Überarbeitung der Lernziele wurde daher gezielt daran gearbeitet, die Interoperabilität und computerbasierte Nachnutzbarkeit der Lernzielmatrix zu verbessern und sie stärker an den FAIR-Prinzipien auszurichten. Durch eine semantische Erschließung sollen beispielsweise automatisierte Analysen und die Verknüpfung der Lernziele mit digitalen Lehr-/Lernmaterialien optimiert werden. Dabei wird auch die Integration in Portale und Aggregatoren für Open Educational Resources (OER) wie DALIA in Betracht gezogen.

In diesem Kapitel werden Vorschläge formuliert, wie die Lernzielmatrix durch den Einsatz strukturierter und semantisch angereicherter Formate im Sinne der FAIR-Prinzipien künftig verbessert werden kann. Eine strukturierte Übersicht über Themencluster, Themen, Lernziele, Lernniveaustufen und Kompetenzbereiche, abgestimmt auf die relevanten Zielgruppen, bildet dabei die Grundlage für die semantische Anreicherung der Lernzielmatrix. Ziel ist es, sie als Linked Open Data-Modell (LOD-Modell) maschinenlesbar zu machen und so eine nachhaltige, computerbasierte Nachnutzung zu ermöglichen. Die vorherigen Versionen der Lernzielmatrix (Petersen et al., 2022, 2023) waren bereits über eine Digital Object Identifier (DOI) eindeutig identifizierbar und zugänglich. Sie wurden in tabellarischer Form in verschiedenen Dateiformaten, darunter CSV, bereitgestellt und durch eine README-Datei sowie eine klar definierte Lizenzregelung ergänzt. Damit folgen sie bereits in Teilen den FAIR-Prinzipien.

Ein erster Data-Wrangling-Ansatz (Zänkert, o. D.) zeigte das Potenzial für eine computerbasierte Nachnutzung auf Grundlage der Lernzielmatrix in Version 2, machte aber auch Schwachstellen in der Datenqualität sichtbar, etwa fehlende oder unvollständige Werte. Zudem wurde deutlich, dass die bisherige tabellarische Struktur nicht optimal für eine standardisierte, modellierbare und vernetzte Darstellung geeignet ist. Gleichzeitig verdeutlichen die im Zuge dieses Ansatzes entstandenen Visualisierungen[^12] den Mehrwert erweiterter Analyse- und Darstellungsmöglichkeiten: Sie erleichtern das Verständnis der Lernzielmatrix und ermöglichen eine gezielte Anpassung sowie Weiterentwicklung der Lerninhalte. Diese Erkenntnisse führten zu einer verstärkten Sensibilisierung für die Optimierung der Matrix, insbesondere im Hinblick auf Interoperabilität und maschinenlesbare Strukturen.

Strukturelle, formale und technologische Verbesserungsmöglichkeiten wurden deshalb beim Community-Event zur Lernzielmatrix in Darmstadt sowie in der anschließenden redaktionellen Arbeit explizit und von Anfang an mit diskutiert. Dabei wurden konkrete Anforderungen anhand von Beispielen wie die Nachnutzung in der erweiterten Suche des DALIA-Portals und weiteren Anwendungsfällen erörtert. Insgesamt zeigte sich, dass die tabellarische Form der Lernzielmatrix insbesondere in Bezug auf Interoperabilität, maschinelle Nutzbarkeit und präzise Zitierbarkeit den FAIR-Prinzipien nicht ausreichend genügt. Die folgenden zentralen Herausforderungen verdeutlichen den Bedarf an einer semantischen Modellierung der Lernzielmatrix, um ihre Interoperabilität, Referenzierbarkeit und Nachnutzbarkeit nachhaltig zu verbessern:

1. **Statische Datenpräsentation:** Die tabellarische Form bietet eine strukturierte, aber wenig interaktive und vernetzbare Darstellung.

2. **Fehlende persistente Identifikatoren:** Die Lernzielmatrix ist als XLSX- und CSV-Datei über Zenodo mit Metadaten auffindbar. Allerdings besitzen einzelne Bestandteile (z. B. Lernziele oder Themen) keine individuellen, persistenten Identifikatoren wie DOI oder Uniform Resource Identifier (URI), was die feingranulare Referenzierbarkeit in LOD-Umgebungen und Metadaten-Diensten erschwert.

3. **Eingeschränkte maschinelle Zugänglichkeit:** Zwar ist CSV als offenes und weit verbreitetes Format grundsätzlich leicht zugänglich, jedoch würde eine Bereitstellung über eine standardisierte Application Programming Interface (API) oder Web-Schnittstelle die maschinelle Abfrage und Integration in LOD-Umgebungen erheblich verbessern.

4. **Langzeitarchivierung einzelner Bestandteile:** Zenodo ermöglicht durch die DOI-Vergabe eine gewisse Langzeitarchivierung. Ohne eine Infrastruktur für persistente Links auf einzelne Bestandteile der Matrix bleibt deren langfristige Verfügbarkeit jedoch eingeschränkt.

5. **Fehlende semantische Struktur:** Die tabellarische Form enthält weder standardisierte Relationen noch Verknüpfungen mit bestehenden LOD-Vokabularen wie Simple Knowledge Organization System (SKOS) oder Dublin Core. Zudem fehlen ein eindeutiger Namensraum und maschinenlesbare Beschreibungen der Spalteninhalte, was die Interoperabilität einschränkt.

6. **Unklare Workflows für Versionierung und Mehrsprachigkeit:** Es existieren bislang keine klar definierten Prozesse für die Versionierung, Änderungen und die mehrsprachige Bereitstellung der Lernzielmatrix.

Es gibt mehrere Alternativen zu einer rein tabellarischen Bereitstellung der Lernzielmatrix im XLSX-, ODS- oder CSV-Format, die eine bessere Erfüllung der FAIR-Prinzipien ermöglichen und die oben genannten Herausforderungen adressieren. Für eine höhere Interoperabilität und präzisere Referenzierbarkeit der Einzelbestandteile der Matrix eignen sich insbesondere semantische Web-Technologien. Diese gewährleisten, dass Begriffe und ihre Relationen formal definiert, systematisch beschrieben und maschinenlesbar dargestellt werden – etwa durch semantische Modellierungssprachen wie SKOS oder Web Ontology Language (OWL). Die Verwendung von Ontologien und standardisierten Vokabularen fügt eine tiefere semantische Schicht hinzu, die die Interpretation und Verknüpfung mit anderen Datenquellen vereinfacht. Hierfür müssen die Bestandteile der Lernzielmatrix als Konzepte definiert und ihre Relationen formal beschrieben werden. Im Rahmen der semantischen Erschließung wurden bereits Schlüsselkonzepte identifiziert, relevante Metadatenprofile gesichtet und erste Ontologie-Entwürfe erstellt.

Eine naheliegende Möglichkeit ist, die Lernzielmatrix als SKOS zu modellieren. SKOS ist ein W3C-Standard zur Darstellung von Thesauri, Ontologien und Klassifikationssystemen, der vollständig mit LOD und den FAIR-Prinzipien kompatibel ist. SKOS eignet sich besonders gut für die hierarchische Organisation der Lernziele, da es eine einfache Verknüpfung mit Linked Data ermöglicht und eine klare, nachvollziehbare Struktur bietet. Eine Umsetzung der Lernzielmatrix in SKOS kann die Interoperabilität erheblich verbessern, indem:

* URIs für einzelne Begriffe festgelegt werden: Jede Entität in der Matrix (z. B. Lernziele, Themencluster, Themen) erhält eine eindeutige, persistente URI.
* eine LOD-Integration ermöglicht wird: SKOS lässt sich mit bestehenden Ontologien wie Dublin Core, Wikidata oder anderen Bildungsstandards verknüpfen.
* Maschinenlesbarkeit gewährleistet wird: Die Struktur ist für Resource-Description-Framework-Datenbanken (RDF-Datenbanken) und SPARQL-Protocol-And-RDF-Query-Language-Abfragen (SPARQL-Abfragen) optimiert.
* eine strukturierte und standardisierte Semantik verwendet wird: Hierarchische und assoziative Beziehungen werden klar definiert, Mehrsprachigkeit über Labels in mehreren Sprachen sowie klare Provenienzangaben und Referenzierbarkeit einzelner Bestandteile sind möglich.

Um die Lernzielmatrix als Ressource im Sinne von LOD zu etablieren, sind noch einige offene Punkte zu klären: Derzeit existiert noch kein „Single Point of Truth“, was bedeutet, dass eine zentrale, verlässliche Quelle für alle relevanten Daten und Informationen fehlt. Zudem müssen klare Workflows für die Abstimmung, Entwicklung und Pflege eines Modells definiert werden. Auch technische Aspekte wie die Vergabe von Identifikatoren, der Namensraum und Publikationsmöglichkeiten müssen präzise festgelegt werden. Eine SKOS-Version der Lernzielmatrix befindet sich derzeit in der Vorbereitung. Damit diese Entwicklung ein echtes Community-Produkt wird, sind Interessierte herzlich eingeladen, sich einzubringen und mitzumachen.

[^12]: [https://zaesa.github.io/RDM-Lernzielmatrix/](https://zaesa.github.io/RDM-Lernzielmatrix/)

\pagebreak

# 8 Zusammenfassung und Ausblick

Zwischen 2024 und 2025 wurden zahlreiche Schritte unternommen, um die Matrix weiterzuentwickeln und zu etablieren. In regelmäßigen Redaktionstreffen wurde die inhaltliche Struktur geschärft und überarbeitet, daneben wurde ergänzendes Begleitmaterial erstellt, um die Anwendung der Matrix zu erleichtern. Durch die Einführung eines Glossars, das zusätzlich auch als LOD formalisiert in SKOS veröffentlicht wird, sowie die Auflistung von Anwendungsszenarien und -beispielen steigen sowohl die Anwendungsfreundlichkeit, die Wiederverwendbarkeit, als auch die Nachhaltigkeit der Matrix. Darüber hinaus wurde die Matrix durch fachspezifische Auseinandersetzungen (z. B. im Rahmen der NFDI) erweitert und mittels zusätzlicher Übersichten ergänzt. Es wird davon ausgegangen, dass nach der Veröffentlichung der dritten Version der Lernzielmatrix weitere Adaptionen folgen werden.

Die Sichtbarkeit der Lernzielmatrix konnte durch den Aufbau einer Wiki-Seite auf Forschungsdaten.org[^13] gesteigert werden. Für das Jahr 2025 wurden Abstracts für diverse Tagungen eingereicht, um die Neuerungen der Matrix vorzustellen und ihre Bekanntheit innerhalb der Community zu erhöhen. Darüber hinaus wird die neue Version von Redaktionsmitgliedern durch ihre Mitwirkung in den unterschiedlichen Netzwerken, Organisationen und Events beworben.

Die Lernzielmatrix lebt durch das Engagement der Community und wird, wie eingangs erläutert, stetig überarbeitet. Mit der Veröffentlichung dieser deutschsprachigen dritten Version beginnt die Arbeit an einer englischen Übersetzung, um die Lernzielmatrix auch der internationalen FDM-Community zugänglich zu machen. Die englische Version wird ebenfalls über Zenodo veröffentlicht. Für die künftige Version 4 der Lernzielmatrix liegen bereits erste Ideen zur inhaltlichen Erweiterung vor. Das zwischen Dezember 2024 und Januar 2025 eingegangene Feedback aus der Community über einen Call4comments hat beispielsweise folgende Punkte ergeben:

* **Integration von „Critical Thinking“ als Grundthema**  
  Die Fähigkeit zur kritischen Reflexion im Umgang mit Forschungsdaten soll künftig in der Matrix verankert werden. Geplante Ergänzungen umfassen Aspekte wie methodische Transparenz sowie den bewussten Umgang mit Unsicherheiten und Bias.  
* **Erweiterung um das Querschnittsthema „Ressourcen und Nachhaltigkeit“**  
  Ein nachhaltiger Umgang mit technischen, personellen und ökologischen Ressourcen soll in der Matrix thematisiert werden. Mögliche Punkte sind ressourcenschonende Speicherung und Verarbeitung von Forschungsdaten und nachhaltige Infrastrukturen.

Diese und andere Erweiterungen können beispielsweise im Rahmen von Tagungen mit der Community diskutiert werden, um sie bedarfsgerecht auszugestalten und in zukünftige Versionen der Matrix einfließen zu lassen. Ein erfolgreicher Weiterentwicklungsprozess der Lernzielmatrix ist untrennbar mit einer aktiven Community verbunden. Der kontinuierliche Austausch innerhalb der FDM-Community hat dazu beigetragen, Bedarfe zu identifizieren, neue Themen zu erschließen und die Matrix bedarfsgerecht weiterzuentwickeln. Zentrale Aspekte dabei sind die transparente offene Kommunikation über Inhalte und Entwicklungen, die Möglichkeit zur aktiven Mitgestaltung und die Einbeziehung und Vernetzung mit Expert:innen. Denn nur durch eine engagierte, disziplinübergreifende Community, die ihr Wissen teilt, kann die Lernzielmatrix als lebendiges, praxisnahes und zukunftsorientiertes Werkzeug weiterbestehen.

# 9 Kontakt

Neuigkeiten zur Lernzielmatrix werden sowohl über die Mailingliste "Umgang mit Forschungsdaten” ([https://www.listserv.dfn.de/sympa/info/forschungsdaten](https://www.listserv.dfn.de/sympa/info/forschungsdaten)), den Mailverteiler von der NFDI-Sektion EduTrain als auch über die Seite der Lernzielmatrix auf Forschungsdaten.org ([https://www.forschungsdaten.org/index.php/Lernzielmatrix](https://www.forschungsdaten.org/index.php/Lernzielmatrix)) verbreitet. Bei Fragen, Anmerkungen oder eigenen Anwendungsbeispielen der Matrix, die auf Forschungsdaten.org aufgeführt werden sollen, kann das Redaktionsteam über den E-Mail-Verteiler der DINI/nestor AG Forschungsdaten UAG Schulungen/Fortbildungen kontaktiert werden: [uag-fdm-schulung@dini.de](mailto:uag-fdm-schulung@dini.de). Alternativ können Anwendungsbeispiele nach Erstellung eines Accounts eigenständig auf Forschungsdaten.org eingetragen werden, um so einen Beitrag zur Sichtbarkeit zu leisten.  
Auch das Kommentieren und Mitwirken via [https://github.com/dini-ag-kim/fdm-lernziele](https://github.com/dini-ag-kim/fdm-lernziele) ist herzlich willkommen.

[^13]: [https://www.forschungsdaten.org/index.php/Lernzielmatrix](https://www.forschungsdaten.org/index.php/Lernzielmatrix)

\pagebreak

# 10 Literaturverzeichnis

Anderson, L. W., & Krathwohl, D. (Hrsg.). (2001). A taxonomy for learning, teaching, and assessing: A revision of Bloom’s taxonomy of educational objectives. Longman.

Biernacka, K., Buchholz, P., Danker, S. A., Dolzycka, D., Engelhardt, C., Helbig, K., Jacob, J., Neumann, J., Odebrecht, C., Petersen, B., Slowig, B., Trautwein-Bruns, U., Wiljes, C., & Wuttke, U. (2021). Train-the-Trainer-Konzept zum Thema Forschungsdatenmanagement (Version 4). Zenodo. [https://doi.org/10.5281/zenodo.5773203](https://doi.org/10.5281/zenodo.5773203)

Bloom, B. S. (Hrsg.). (1956). Taxonomy of educational objectives: The classification of educational goals: Handbook I, cognitive domain. Longmans.

Blümm, M., Förstner, K. U., Lanczek, M., Lindstädt, B., Müller, R., Nickenig, U., Rehwald, S., Slowig, B., & Stegemann, J. (2022). Der Zertifikatskurs Forschungsdatenmanagement als adaptierbares Aus- und Weiterbildungsangebot. In V. Heuveline & N. Bisheh (Hrsg.),   
E-Science-Tage 2021: Share your research data (S. 414–420). heiBOOKS. [https://doi.org/10.11588/heibooks.979.c13758](https://doi.org/10.11588/heibooks.979.c13758)

Christian-Albrechts-Universität zu Kiel. (2022). Forschungsdatenmanagement: eLBB4RDM. Christian-Albrechts-Universität zu Kiel. [https://www.fdm.uni-kiel.de/de/aktivitaeten/projekte/Projekt%20eLBB4RDM](https://www.fdm.uni-kiel.de/de/aktivitaeten/projekte/Projekt%20eLBB4RDM)

Engelhardt, C., Barthauer, R., Biernacka, K., Coffey, A., Cornet, R., Danciu, A., Demchenko, Y., Downes, S., Erdmann, C., Garbuglia, F., Germer, K., Helbig, K., Hellström, M., Hettne, K., Hibbert, D., Jetten, M., Karimova, Y., Hansen, K. K., Kuusniemi, M. E., … Zhou, B. (2022). How to be FAIR with your data: A teaching and training handbook for higher education institutions. Georg-August-Universtität Göttingen. [https://doi.org/10.17875/gup2022-1915](https://doi.org/10.17875/gup2022-1915)

FORCE11. (2021). Guiding principles for findable, accessible, interoperable and re-usable data publishing version b1.0. FORCE11. [https://force11.org/info/guiding-principles-for-findable-accessible-interoperable-and-re-usable-data-publishing-version-b1-0/](https://force11.org/info/guiding-principles-for-findable-accessible-interoperable-and-re-usable-data-publishing-version-b1-0/) 

Hastik, C., & Schwenk, G. A. (2025). SODa BeratungsCamp Modul 1 \- Arbeiten mit strukturierten Daten in der Konservierungs- und Restaurierungsdokumentation \- Didaktisches Konzept (Version 1). Zenodo. [https://doi.org/10.5281/zenodo.14860999](https://doi.org/10.5281/zenodo.14860999)

Hörner, T., Glöckner, F. O., Drechsler, R., & Pigeot, I. (2021). Disziplinübergreifendes Modell zur Ausbildung von Forschungsdatenmanagement und Data Science Kompetenzen: „Data Train – Training in Research Data Management and Data Science“. Bausteine Forschungsdatenmanagement, 3, 56–69. [https://doi.org/10.17192/bfdm.2021.3.8343](https://doi.org/10.17192/bfdm.2021.3.8343)

Petersen, B., Engelhardt, C., Hörner, T., Jacob, J., Kvetnaya, T., Mühlichen, A., Schranzhofer, H., Schulz, S., Slowig, B., Trautwein-Bruns, U., Voigt, A., & Wiljes, C. (2022). Lernzielmatrix zum Themenbereich Forschungsdatenmanagement (FDM) für die Zielgruppen Studierende, PhDs und Data Stewards (Version 1). Zenodo. [https://doi.org/10.5281/zenodo.7034478](https://doi.org/10.5281/zenodo.7034478)

Petersen, B., Engelhardt, C., Hörner, T., Jacob, J., Kvetnaya, T., Mühlichen, A., Schranzhofer, H., Schulz, S., Slowig, B., Trautwein-Bruns, U., Voigt, A., & Wiljes, C. (2023). Lernzielmatrix zum Themenbereich Forschungsdatenmanagement (FDM) für die Zielgruppen Studierende, PhDs und Data Stewards (Version 2). Zenodo. [https://doi.org/10.5281/zenodo.8010617](https://doi.org/10.5281/zenodo.8010617)

Rheinisch-Westfälische Technischen Hochschule (RWTH) Aachen. (2024). Data Literacy. RWTH Aachen University, Center für Lehr- und Lernservices. [https://dataliteracy.rwth-aachen.de/](https://dataliteracy.rwth-aachen.de/)

Technische Universität Wien. (o. D.). FAIR Data Austria. Cluster Forschungsdaten. [https://forschungsdaten.at/fda/](https://forschungsdaten.at/fda/)

TH Köln. (2025). Zertifikatskurs Forschungsdatenmanagement. TH Köln. [https://www.th-koeln.de/weiterbildung/zertifikatskurs-forschungsdatenmanagement\_82048.php](https://www.th-koeln.de/weiterbildung/zertifikatskurs-forschungsdatenmanagement_82048.php) 

U Bremen Research Alliance. (o. D.). Data Train: Training in Research Data Management and Data Science. U Bremen Research Alliance. [https://www.bremen-research.de/data-train/](https://www.bremen-research.de/data-train/)

Universität Bielefeld. (o. D.). Modul 39-M-Inf-RDM Research Data Management, Studieninformation, Universität Bielefeld. Universität Bielefeld. [https://ekvv.uni-bielefeld.de/sinfo/publ/modul/79251504](https://ekvv.uni-bielefeld.de/sinfo/publ/modul/79251504)

Wilkinson, M. D., Dumontier, M., Aalbersberg, Ij. J., Appleton, G., Axton, M., Baak, A., Blomberg, N., Boiten, J.-W., da Silva Santos, L. B., Bourne, P. E., Bouwman, J., Brookes, A. J., Clark, T., Crosas, M., Dillo, I., Dumon, O., Edmunds, S., Evelo, C. T., Finkers, R., … Mons, B. (2016). The FAIR Guiding Principles for scientific data management and stewardship. Scientific Data, 3(1), Artikel 160018\. [https://doi.org/10.1038/sdata.2016.18](https://doi.org/10.1038/sdata.2016.18)

Zänkert, S. (o. D.). Lernzielmatrix \- Kurzübersicht. GitHub. [https://zaesa.github.io/RDM-Lernzielmatrix/](https://zaesa.github.io/RDM-Lernzielmatrix/)

Zentrum für Bibliotheks- und Informationswissenschaftliche Weiterbildung (ZBIW). (2024). Zertifikatskurs Forschungsdatenmanagement. [https://www.th-koeln.de/mam/downloads/deutsch/weiterbildung/zbiw/angebote/zbiw\_modulhandbuch\_zk\_fdm\_2024-25.pdf](https://www.th-koeln.de/mam/downloads/deutsch/weiterbildung/zbiw/angebote/zbiw_modulhandbuch_zk_fdm_2024-25.pdf)
