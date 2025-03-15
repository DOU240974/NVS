# Übung Subnetting

## Übung 1

Bilde aus dem Netz 192.168.0.0 /24 4 Subnetze. Netze mit Mindestzahl an nutzbaren Host aber nicht darunter wählen: Netz a mit 20, Netz b mit 15, Netz c mit 30, und das Netz d mit den Rest Anteil der Netzwerkadressen.

**Antwort**
a: 0-31, 192.168.0.0/27
b: 32-63, 192.168.0.32/27
c: 64-95, 192.168.0.64/26
d: 128-255, 192.168.0.128/25 

## Übung 2

Teile das Netz 193.170.20.0 /24 in 8 gleich große Netze! Erstelle eine Tabelle mit folgenden Angaben:
Netzwerkadresse,               nutzbare Hosts,                    Broadcastadresse,              Subnetzmaske.

**Antwort**
0-31,    193.170.20.0/27         Host 30                           193.170.20.31/27               255.255.255.224
32-63,   193.170.20.32/27        Host 30                           193.170.20.63/27               255.255.255.224
64-95,   193.170.20.64/27        Host 30                           193.170.20.95/27               255.255.255.224
96-127,  193.170.20.96/27        Host 30                           193.170.20.127/27              255.255.255.224
128-159, 193.170.20.128/27       Host 30                           193.170.20.159/27              255.255.255.224
160-191, 193.170.20.160/27       Host 30                           193.170.20.191/27              255.255.255.224
192-223, 193.170.20.192/27       Host 30                           193.170.20.223/27              255.255.255.224
224-255, 193.170.20.224/27       Host 30                           193.170.20.255/27              255.255.255.224

## Übung 3

172.28.40.0 /26 Teile wie folgt auf: 2 Netze!
Erstelle eine Tabelle mit folgenden Angaben:
Netzwerkadresse,               nutzbare Hosts,                    Broadcastadresse,              Subnetzmaske.

**Antwort**
0-127,   172.28.40.0/25           Host 126                        172.28.40.127/25              255.255.255.128
128-255, 172.28.40.128/25         Host 126                        172.28.40.255/25              255.255.255.128

## Übung 4

Wie lautet die Subnetzmaske bei der Netzadresse: 17.0.0.0 mit 10 verwendbaren Subnetzen, sowie mit mindestens 12 Hosts je Subnetz?
Antwort in Sätzen, wie sie zu dieser Lösung kommen; und erstelle eine Tabelle:

**Antwort**
17.0.0.0/28                         Host 14 
## Übung 5

Bestimmen Sie die Subnetmaske mit folgenden Angaben:

Netzadresse: 210.52.190.0
Subnetze: Anzahl 5
Mindestanzahl von Hosts je Subnetz: 10

**Antwort**

## Übung 6

Teile  ein /30 Netz auf!    Wozu werden diese /30 Netze am häufigsten verwendet?
Antwort:

**Antwort**

## Übung 7

Nennen Sie den jeweiligen Netz- und Hostanteil der Klassen A, B und C

**Antwort**
