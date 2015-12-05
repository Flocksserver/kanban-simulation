# Kanban-Spiel Simulation Papierflieger bauen
Lean Production Simulation

Im Rahmen einer Masterveranstaltung an der Hochschule Hannover entstand der hier veröffentlichte Vortrag. Es ist eine Simulation bzw. ein Spiel, das mit einer Gruppe bzw. mit mehreren Gruppen durchgeführt werden kann. Ziel ist es, den Unterschied von Push- und Pullverfahren zu erleben, zu messen und auszuwerten. Die Materialien können uneingeschränkt verwendet werden. Ich würde mich jedoch freuen, wenn ich bei Verwendung benachrichtigt werde.

Bei Fragen/Anmerkungen gerne per Mail melden. flocksserver@gmail.com

# Spielanleitung
Geschätzte Spielzeit: 30-45 Minuten

Ziel des Vortrags ist:
> Unterschiede der Verfahren *Push* und *Pull* erleben, Metriken anwenden und vergleichen.

Dies soll mit Hilfe einer konstruierten Produktionslinie geschehen. Das entstehende Produkt ist ein Papierflieger, der in vier Produktionsschritten (siehe [Anleitung Papierflieger](https://github.com/Flocksserver/kanban-simulation/blob/master/Material/Anleitung_Papierflieger_bauen.jpg)) erstellt werden soll. Die Teilnehmer der Simulation werden in Gruppen aufgeteilt. Jede Gruppe besteht aus vier Projektmitarbeitern, einem Logistiker, einem Manager und je nach gewählter Gruppengröße eine variable Anzahl an Beobachtern. Die vier Projektmitarbeiter setzen sich an einer langen Tischreihe auf die eine Seite, alle anderen Teilnehmer der Gruppe auf die andere. Es ist darauf zu achten, dass genügend Platz zwischen den einzelnen Projektmitarbeitern zur Verfügung steht. Zum Dokumentieren der Ergebnisse eines Durchlaufs wird der Gruppe eine Metrikliste ausgeteilt. Diese wird vom Manager am Ende jedes Durchgangs gemeinsam mit der Gruppe ausgefüllt (siehe [Metrikliste](https://github.com/Flocksserver/kanban-simulation/blob/master/Material/MetrikBogen.pdf)). Es werden zwei Durchgänge gespielt - ein Durchgang im Push- und einer im Pull-Verfahren.

## Das Push-Verfahren
Eine Spielrunde dauert fünf Minuten. Jeder Produktionsschritt wird vom jeweiligen Mitarbeiter durchgeführt. Die Produktionsschritte sind durch zwei Freiflächen, einen Ein- sowie einen Ausgang verbunden. Für diese, zwischen den Mitarbeitern befindlichen Bereiche, muss genügend Platz vorhanden sein. Der Prozess ist eine Prozesskette. Aus diesem Grund wird nach dem *"first in first out"*-Prinzip produziert. Der Logistiker wird vom Manager verbal gesteuert und transportiert Zwischenprodukte vom Aus- in den jeweiligen Eingang. Hierbei darf mehr als ein einzelnes Produkt gleichzeitig transportiert werden. Jedoch darf der Logistiker nicht eigenmächtig agieren, sondern befolgt die Steuerungsschritte des Managers. Als Visualisierungshilfe wird das Plakat zum Push-Vorgang (siehe [Visualisierung Push-Vorgang](https://github.com/Flocksserver/kanban-simulation/blob/master/Material/Anleitung_Push-Vorgang.jpg)) verwendet. Um die auf der Metrikliste geforderten Durchlaufzeiten zu messen, soll vorzugsweise vom Manager in Minute 0:30 sowie 3:30 ein farbiges Papier in den Produktionsschritt mit eingefügt werden. Dies bedeutet, dass dieses Blatt auf den Stapel mit dem Rohmaterial (Papierstapel) gelegt werden muss.

Die nachfolgende Tabelle stellt die Aufgabenverteilung für die verschiedenen Rollen in einer Übersicht dar.

|     Rolle   |      Aufgabe     |
| :------------- | :------------- | 
| **Projektmitarbeiter**      | Jeder Projektmitarbeiter führt den Schritt, dem er zugeteilt ist, gewissenhaft durch. | 
| **Manager**     |  Steuert verbal den Logistiker. <br> Füllt Metrikliste aus.<br> Kontrolliert FIFO.<br> Fügt bei Minute 0:30 und 3:30 das farbige Papier dem  Prozess zu.|
| **Logistiker** |  Erhält vom Manager verbal Anweisung von welchem Ausgang in welchen Eingang Material transportiert werden soll. Ihm ist erlaubt, bei einem Vorgang den gesamten Bestand des Ausgangs aufzunehmen.|
| **Beobachter** | Notiert Auffälligkeiten. <br> Übernimmt gegebenenfalls Aufgaben zur Zeitmessung.|
Das Zeitnehmen der fünf Minuten kann für alle Gruppen gemeinsam geschehen oder durch die Gruppe selbst durchgeführt werden. Diese Aufgabe innerhalb der Gruppe kann ein Beobachter oder der Manager übernehmen. Das Messen der Durchlaufzeiten kann ebenfalls an Beobachter verteilt werden. Die Metrikliste nach dieser Runde wird von der Gruppe selbständig mit allen Gruppenmitgliedern zusammen ausgefüllt.

## Das Pull-Verfahren
Äquivalent zum Push-Verfahren ist der Zeitrahmen von fünf Minuten gesetzt. Des Weiteren sind die vier Prozessschritte und Mitarbeiter unverändert. Ein elementarer Unterschied wird bezüglich der Ein- und Ausgänge und deren Verwendung eingeführt. Es existiert ein Übergabebereich mit kombiniertem Ein- und Ausgang. Diese beiden Bereiche werden zusammengelegt. Zusätzlich wird die Regel eingeführt, dass sich der Projektmitarbeiter erst neues Material zum Verarbeiten nehmen darf, wenn sein Ausgang leer ist. Der Logistiker entfällt und wechselt in die Rolle eines Beobachters. Zur Visualisierungshilfe kann hier erneut ein Plakat dienen (siehe [Visualisierung Pull-Vorgang](https://github.com/Flocksserver/kanban-simulation/blob/master/Material/Anleitung_Pull-Vorgang.jpg)). Auch beim Pull-Vorgang sollen Durchlaufzeiten ermittelt werden. Aus diesem Grund sollen die farbigen Blätter in Minute 0:30 und 3:30 dem Prozess zugeführt werden. Am Ende des Durchgangs wird die Metrikliste vervollständigt. Die verschiedenen Aufgaben der Rollen im Pull-Verfahren werden in folgender Tabelle zusammengefasst.

|     Rolle   |      Aufgabe     |
| :------------- | :------------- | 
| **Projektmitarbeiter**      | Jeder Projektmitarbeiter führt den Schritt, dem er zugeteilt ist, gewissenhaft durch. <br> Der Mitarbeiter nimmt nur dann aus seinem Eingang neues Material, wenn sein Ausgang leer ist. | 
| **Manager**     |  Füllt Metrikliste aus.<br> Fügt bei Minute 0:30 und 3:30 das farbige Papier dem  Prozess zu.|
| **Logistiker** |  Diese Rolle entfällt. Der Logistiker wird zum Beobachter.|
| **Beobachter** | Notiert Auffälligkeiten. <br> Übernimmt gegebenenfalls Aufgaben zur Zeitmessung.|
Das Zeitnehmen und die dazugehörigen Aufgaben können zwischen den Beobachtern aufgeteilt werden.

## Ergebnissicherung
Jede Gruppe bespricht intern die Unterschiede der jeweiligen Durchläufe sowie deren Vor- und Nachteile. Der Manager einer Gruppe stellt seine Metrikliste und die zusammengetragenen Unterschiede allen Teilnehmern vor. Hierfür kann ein vorbereitetes Flipchart zur Hilfe genommen werden (siehe [Ergebnisse](https://github.com/Flocksserver/kanban-simulation/blob/master/Ergebnisse/Ergebnis_einer_Gruppe.jpg)). Folgende Nachteile des Push-Verfahrens sollten als Ergebnissicherung mindestens genannt werden:

+ Viele unfertige Produkte
+ Lange Durchlaufzeiten
+ Bei laufender Änderung hoher Ausschuss
+ Einführung eines neuen Features dauert (Durchlaufzeit)
+ Spätes Erkennen von Fehlern teuer
+ Hoher Aufwand für Logistik und Management
+ Kosten für mehr Mitarbeiter
+ Arbeit des einzelnen Mitarbeiters