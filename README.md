# Dusty
Dusty ist ein LEGO Spike Roboter, der autonom durch den Raum navigiert, ohne Hindernisse zu berühren. Er sammelt gezielt Objekte ein und meidet nicht definierte Gegenstände. Mit präziser Sensorik und intelligenter Software sorgt er für effiziente Navigation und Kategorisierung verschiedener Objekte.

## 1 Allgemeine Informationen
Wie der Name bereits verrät, basiert Dusty auf der Idee eines Saugroboters. Saugroboter nehmen Schmutz auf, erkennen nicht-schmutzartige Partikel und navigieren sicher durch einen Raum. Sobald sie ein Hindernis wahrnehmen, ändern sie dynamisch ihre Richtung und weichen Kollisionen, beispielsweise mit Wänden, aus.

Um diese grundlegenden Funktionen auf einen LEGO Spike Roboter zu übertragen, haben wir die folgende Idee entwickelt: Dusty soll ein mobiler Roboter mit guter Wendigkeit sein. Ein Distanzsensor erkennt größere Hindernisse wie Wände, woraufhin der Roboter seine Fahrtrichtung entsprechend anpasst oder sich dreht. Die Unterscheidung von Objekten erfolgt über einen Farbsensor, der auf den Boden ausgerichtet ist. Dieser kann dort liegende Objekte anhand ihrer Farbe identifizieren. Durch gezielte Programmierung wird festgelegt, welche Farben als Schmutz und welche als Hindernis gelten. Wird eine Farbe als Hindernis erkannt, reagiert Dusty erneut mit einer Richtungsänderung oder Drehung. „Schmutz“ hingegen soll eingesaugt werden. Dafür benötigt Dusty eine Saugfunktion sowie einen Behälter zur Aufnahme des aufgesammelten Schmutzes.

Im Folgenden wird die Umsetzung dieser Idee detailliert beschrieben.

## 2 Gebrauchte LEGO Teile
Nachfolgend finden Sie eine Liste der LEGO-Steine, die für den Bau des Roboters benötigt werden:

1x Large Hub
1x Distance Sensor
1x Color Sensor
1x Rubber band ø33, yellow
1x Damper 2m
2x Large Motor
2x Medium Motor
2x Panel 11x19
2x Ball cup ø19
2x Ball ø19
2x Technic frame 5x7
2x Angular beam 90 degrees w/4 snaps
2x Biscuit 1x3x3, magenta
2x Double conical wheel z36
2x Cross axle 3m
2x Bush for cross axle Cross axle 9m
2x Ball w/friction snap
2x Connector peg 3m
4x Wheel ø88
4x Technic 13m beam
4x Technic 11m beam
4x 1/4 Circle gear rack 11x11
4x Tube, w/ double 4.85 hole
4x Connector peg cross axle w.fric.
6x Technic 5m beam
6x Connector peg w/friction 3m
7x Technic 7m beam
8x Technic 15m beam
8x 1/2 bush
10x Technic 9m beam
50x Connector peg w/friction

## 3 Aufbau
## 3.1 Die Basis
Zu Beginn unseres Projekts haben wir zunächst eine stabile Basis konstruiert, die ausreichend Platz für den Large Hub, die Motoren sowie den Distanzsensor bietet. Dafür haben wir zwei Panel 11x19 verwendet.
Um den Roboter durch den Raum bewegen zu können, haben wir ein Antriebssystem entwickelt, das aus zwei unabhängig gesteuerten Rädern (Wheel Dia.56 ) besteht. Jedes Rad ist mit einem eigenen großen Motor ausgestattet welche am hinteren Panel auf der Unterseite befestigt wurden. An der Vorderseite haben wir einen Ball Cup mit Ball angebracht. Dieser wurde mit Hilfe eines Beam Frame 5x7 sicher an den Panels befestigt, um den Höhenunterschied auszugleichen.
 Anschließend haben wir den Large Hub auf der Oberseite der Panels positioniert, sodass dieser zentral aufliegt.
Diese Konstruktion sorgt für ausreichend Stabilität und ermöglicht sowohl die Vorwärts- und Rückwärtsbewegung als auch das Drehen des Roboters. 
Bei korrekter Umsetzung ergibt sich folgendes Ergebnis:
![image](https://github.com/user-attachments/assets/a76d6821-3bbe-4f6e-ae9b-d600c7fdb614)
 
Es ist darauf zu achten, die Motoren mit dem large Hub zu verbinden. Der Motor vom linken Rad (von vorne betrachtet) wird mit Ausgang A und das rechte Rad mit Ausgang B verbunden. 

## 3.2 Distanzsensor
Um den Distanzsensor in einer optimalen Höhe zu platzieren, wurde eine Erhöhung aus mehreren Technic Beams konstruiert:
•	3x  Technic 7m Beams
•	1x Technic 13m Beam
•	2x Technic 11m Beams
•	1x Technic 13m Beam
Diese Elemente wurden übereinander positioniert und der Distanzsensor darauf befestigt. Zur sicheren Montage wurden zwei Angular Beams (90 Degrees w/4 Snaps) verwendet, jeweils einer pro Seite.

![image](https://github.com/user-attachments/assets/223e45d3-411d-4c90-83dd-0fa906e3a6f3)

Der Sensor wurde ebenfalls mit dem Computer an Ausgang C verbunden.

## 3.3 Einsaugfunktion mit Farbsensor
Schritt 1: Anbringen des Farbsensors
Zunächst wurden beidseitig jeweils ein Technic 3m Beam mittig neben dem Large Hub befestigt. Anschließend wurden an den Außenseiten jeweils ein Technic 9m Beams montiert. Daneben wurde ein Technic 11m Beam positioniert, sodass das erste Loch über das Pannel geht. An dieser Stelle wurden jeweils ein Biscuit 1x3x3 (magenta) angebracht, an denen jeweils ein Medium Motor befestigt wurde.
Die drei Beams wurden anschließend durch ein Technic 5m Beams verbunden. Alle Teile wurden mit Connector Pegs w/Friction gesichert.

![image](https://github.com/user-attachments/assets/d82c8f35-0f7a-489e-bcd8-f1b370f22317)

An den Biscuit 1x3x3 werden jeweils ein Medium Motor befestigt.

![image](https://github.com/user-attachments/assets/1c4f1761-6420-4b14-8d31-a775ed5ab9b0)

Wir haben Mittig auf der Unterseite zwei Technic 15m Beams befestigt, sodass sie etwa zur Hälfte vorne herausragen. Zur Verlängerung wurden daran jeweils zwei Technic 7m Beams vorne angebaut. 
 An der vorderen Unterseite wurde der Farbsensor befestigt. In diesem Schritt wurden ebenfalls alle Teile mit Hilfe von Connector peg w/friction befestigt.
 
![image](https://github.com/user-attachments/assets/37abd06e-be86-45a9-8a75-ecd4400ed1a7)

Schritt 2: Anbringen der Räder für die Saugfunktion
Zuerst wurden an den Medium Motoren folgende Teile an der Unterseite befestigt:

 ![image](https://github.com/user-attachments/assets/daacbb2b-c354-4ceb-8362-9a0b81d1230d)

Anschließend wurde jeweils ein Double Conical Wheel Z36 und danach ein Wheel Ø86 daran montiert.

 ![image](https://github.com/user-attachments/assets/621394f8-7df0-4c7b-9240-7e829eec14eb)

Nun wird noch auf die Oberseite des Medium Motors jweils ein Technic 5m beam befestigt. Auf der Innenseite kommt jeweils ein Ball w/friction snap. Anschließen kommt nochmal jeweils ein ein Technic 5m beam oben drauf, welche mit Connector peg 3m verbunden 
Um die Ball w/friction snap wurde ein Gummiband gespannt. Dies sorgt dafür, dass sich die Räder nach dem Einsammeln eines Steins wieder in ihre Ausgangsposition zurückbewegen.

![image](https://github.com/user-attachments/assets/fad8a1a1-9f4d-4d39-a004-67e18f2724f3)
![image](https://github.com/user-attachments/assets/cbbcffcb-37ca-4001-a8fb-1b3305d3270d)


## 3.4 Auffangnetz
Als letzten Schritt haben wir auf der Unterseite noch eine Art Auffangkorb angebaut, um die eingesammelten Steine aufzufangen. Dafür haben wir mit Legosteinen eine U-Form gebaut. 

 
## 4 Programmierung
Im Folgenden werden die einzelnen Programmierschritte, die zum Erstellen eines "Dusty's" nötig sind, erläutert. Die Programmierung erfolgte anhand des Tools LEGO SPIKE Prime (Scratch).
Hier zu sehen ist der gesamte Code. Die einzelnen Abschnitte und deren Funktionen bzw. Bedeutung wird anschließend erklärt.

<img width="670" alt="image" src="https://github.com/user-attachments/assets/2be6866f-62c0-46a3-95f7-cd1a5d095839" />

## 4.1 Basisfunktion
Die Basisfunktion besteht zunächst aus dem Baustein „When program starts“ um einen Initiator zu schaffen. Anschließend wird die Information gegeben, dass die beiden großen Motoren, welche für die Bewegung der großen Räder zuständig sind, am Hub an Position A und B angeschlossen sind. Nachfolgend wird eine „forever“-Schleife initiiert, welche verschiedene Funktionen in sich integriert. Diese definieren gemeinsam das grundsätzliche Bewegungskonzept von Dusty. Demnach fährt Dusty immer vorwärts, solange nichts anderes befohlen wird, da die Funktion „Vorwärts fahren“ in der Schleife ohne weitere Bedingungen steht (nähere Beschreibung, siehe 4.2 Vorwärts fahren). Anschließend wird bereits der Distanzsensor anhand einer „if“-Funktion integriert. Der Distanzsensor wurde an Anschluss C des Hubs angeschlossen. Die weitere Formulierung impliziert, dass sobald etwas näher am Distanzsensor als 20 cm ist, wird die Funktion „Return“ ausgeführt. Grundsätzlich bedeutet diese, dass der Roboter kurz rückwärts fährt, sich dreht und wieder vorwärts fährt(nähere Beschreibung, siehe 4.3 Return). Auch der Farbsensor wird anhand einer „if-else“-Funktion integriert. Dieser wurde an Anschluss F des Hubs angeschlossen. Die „if“-Funktion sorgt dafür, dass die Funktion „Einsaugen“ ausgeführt wird, wenn der Farbsensor die Farbe blau erkennt. Andernfalls („else“) wird die Funktion „Kein Schmutz“ ausgeführt. Die bereits kurz beschriebenen Funktionen werden im Anschluss näher erläutert.

<img width="215" alt="image" src="https://github.com/user-attachments/assets/62bd10f6-efa0-467d-b154-58e7240b027b" />

## 4.2 Vorwärts fahren
Diese Funktion wurde von uns selbst definiert. Sie bezieht sich auf die beiden großen Motoren, welche am Hub an Position A und B angeschlossen sind. Die Schnelligkeit wird über den Motoren-Baustein „set movement speed to 25%“ festgelegt. Nach einigen Testläufen hielten wir die Geschwindigkeit von 25% für angemessen. Allerdings kann eine adäquate Geschwindigkeit je nach Boden, auf welchem Dusty fährt, verschieden sein. Zusätzlich wurde mit dem folgenden Baustein noch die Richtung der Bewegung anhand des Pfeils festgelegt. Dieser zeigt für Dusty nach vorne.

![image](https://github.com/user-attachments/assets/ca5cb064-a9a2-44ff-af3c-5099d5f57969)

## 4.3 Return
Auch die „Return“-Funktion wurde von uns definiert. Sie kommt zum Einsatz, wenn der Distanzsensor ein Hindernis bei 20cm Entfernung identifiziert. Den beiden großen Motoren (A + B) wird der Befehl erteilt, für 5cm rückwärts zu fahren (Pfeil in entgegengesetzte Richtung wie für den Vorwärts-Befehl). Nachdem die kurze Rückwärtsfahrt beendet ist, soll sich der Roboter für eine Rotation des Motors nach rechts bewegen. Durch die „Vorwärts“-Funktion in der forever-Schleife fährt Dusty anschließend direkt wieder vorwärts.

![image](https://github.com/user-attachments/assets/ab347aa4-72b2-4fbc-8c47-3ecdad8c3659)

## 4.4 Einsaugfunktion
Die „Einsaug“-Funktion kommt zum Einsatz, wenn der Farbsensor die Farbe blau erkennt. Diese selbst definierte Funktion startet zwei kleine Motoren (E + D), an welchen ebenfalls zwei große Räder angeschlossen sind. Diese sind für die Saugfunktion zuständig. Hierfür wurde festgelegt, dass sie sich für zwei Sekunden in entgegengesetzte Richtungen drehen. In dieser Zeit sollte der blaue "Schmutz durch die Räder in den Innenraum des Roboters gesaugt worden sein. Anschließend werden die beiden Motoren (E + D) gestoppt, damit die Räder aufhören sich zu drehen. Das alles geschieht während der Roboter normal vorwärts fährt.

<img width="109" alt="image" src="https://github.com/user-attachments/assets/31f5676e-8b6b-4b2a-82e5-9910ac3931b0" />

## 4.5 Kein Schmutz
Die selbst definierte Funktion „Kein Schmutz“ enthält 5 if-Funktionen mit ähnlichem Aufbau. Für jede if-Funktion wurde eine Farbe, die der Farbsensor (an F angeschlossen) erkennen kann, definiert. Hierbei ausgeschlossen wurde die Farbe blau, da blau bereits als "Schmutz" definiert wurde. Für jede erkannte Farbe, die nicht blau ist, wird anschließend die „Return“-Funktion ausgeführt, welche oben bereits erklärt wurde (4.3 Return). Dadurch fährt Dusty nicht einfach über die Hindernisse, die nicht als Schmutz identifiziert wurden, sondern umfährt diese.

![image](https://github.com/user-attachments/assets/df2d0631-09ca-4461-98dd-ea17780433c0)

## 5 Limitationen und Anpassungen
Während zahlreichen Probedurchläufen trafen wir häufig auf zwei Probleme, die anhand weniger Handgriffe umgangen bzw. gelöst werden konnten. Um Dusty möglichst flexibel einsetzbar zu gestalten, sollen diese kurz thematisiert werden.
 1) Je nach dem auf welchem Boden Dusty fährt, können einige Anpassungen getroffen werden. Aufgrund der direkten Ausrichtung des Farbsensors auf den Boden, kann es dazu kommen, dass dieser dauerhaft die Farbe Gelb bei hellen Böden oder die Farbe schwarz bei dunklen Böden erkennt. Daher könnten je nach Umgebung aus der if-Funktion, welche nicht-schmutzige Teile identifiziert (Funktion "Kein Schmutz", siehe 4.5 Kein Schmutz), die Farben des Bodens ausgeschlossen werden, um die Funktionstüchtigkeit von Dusty zu gewährleisten.
 2) Des Weiteren ergaben sich Probleme mit den Rädern, welche für die grundsätzliche Bewegung von Dusty zuständig waren. Durch die Bauweise von Dusty liegt auf diesen eher wenig Gewicht. Das führt dazu, dass sie vor allem bei Drehungen (Funktion "Return", 4.3 Return) sehr schnell durchdrehen. Dadurch wird wiederum der gewünschte Winkel der Drehung nicht vollständig erreicht. Eine mögliche Lösung dieses Problems ist das Verwenden zusätzlicher Gewichte. Externe Gewichte können so auf Dusty platziert werden, dass deren Hauptbelastung auf die Räder übertragen wird und sie daher eine bessere Verbindung zum Boden bekommen.

## 6 Fazit
Anhand des beschriebenen Aufbaus sowie der aufgeschlüsselten Programmierung konnte die ursprüngliche Idee eines Saugroboters realisiert werden. 


