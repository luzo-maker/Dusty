# Dusty
Dusty ist ein LEGO Spike Roboter, der autonom durch den Raum navigiert, ohne Hindernisse zu berühren. Er sammelt gezielt blaue Objekte und meidet andersfarbige Gegenstände, die als Müll gelten. Mit präziser Sensorik und intelligenter Software sorgt er für effiziente Navigation und Farberkennung.

## 1 Allgemeine Informationen:

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


## 3 Basis 
In diesem Abschnitt wird die Bauanleitungen für die Basis des Roboters, die als Grundlage für die weiteren Schritte dient erläutert. Zudem wird der Code, der den Roboter vorwärts bewegt dargelegt.

3.1 Aufbau der Basis
Zu Beginn des Projekts wird eine Basis mit ausreichend Platz für den Large Hub, den Motoren sowie dem distance Sensor benötigt. Daher wurde eine Basis aus zwei Panel 11x19, welche mit Connector peg w/friction verbunden wurden gebaut. Vorne befindet sich ein Ball cup mit ball. 
Diese Konstruktion sorgt für ausreichend Stabilität und ermöglicht es dem Roboter, sich auf dem Boden zu drehen, eine wesentliche Eigenschaft, um den Kontakt mit Hindernissen zu vermeiden.
Um den Roboter durch den Raum bewegen zu können, wird ein Antrieb benötigt. Dafür eignen sich zwei Räder, die jeweils mit einem eigenen Motor ausgestattet sind. Zwei Motoren sind erforderlich, damit der Roboter sich drehen kann, ohne seine Position zu verändern. Aus Stabilitätsgründen werden die Räder an der Rückseite des Roboters montiert – auf der Seite, auf der der Computer positioniert ist. 

Das linke Bild zeigt die benötigten Bausteine für ein Rad. Für das zweite Rad werden identische Bausteine verwendet, wobei es spiegelverkehrt aufgebaut werden muss. Das fertige Ergebnis ist im rechten Bild zu sehen.

Nach der Fertigstellung werden die Räder an der Basis befestigt. Dabei ist darauf zu achten, die Räder mit dem Computer zu verbinden. Das linke Rad wird mit Ausgang A und das rechte Rad mit Ausgang B verbunden. Bei korrekter Umsetzung ergibt sich folgendes Ergebnis:
 
## 4 Programmierung
Im Folgenden werden die einzelnen Programmierschritte, die zum erstellen eines "Dusty's" nötig sind, erläutert. Die Programmierung 
