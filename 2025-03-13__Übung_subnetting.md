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
17.0.0.0/28                         Host 14          Subnetzmaske 255.255.255.240

Habe dann 16 verwendbare Subnetze mit je 14 Hosts - Verwenden tun wir nur die 10 nötigen Subnetze mit 14 Hosts

Die 10 Netze in verwendung mit den verwendeten 12 Hosts

Subnetz  1: 17.0.0.0/28   - 17.0.0.15/28    14 nutzbare Hosts    Subnetzmaske 255.255.255.240
Subnetz  2: 17.0.0.16/28  - 17.0.0.31/28    14 nutzbare Hosts    Subnetzmaske 255.255.255.240
Subnetz  3: 17.0.0.32/28  - 17.0.0.47/28    14 nutzbare Hosts    Subnetzmaske 255.255.255.240
Subnetz  4: 17.0.0.48/28  - 17.0.0.63/28    14 nutzbare Hosts    Subnetzmaske 255.255.255.240
Subnetz  5: 17.0.0.64/28  - 17.0.0.79/28    14 nutzbare Hosts    Subnetzmaske 255.255.255.240
Subnetz  6: 17.0.0.80/28  - 17.0.0.95/28    14 nutzbare Hosts    Subnetzmaske 255.255.255.240
Subnetz  7: 17.0.0.96/28  - 17.0.0.111/28   14 nutzbare Hosts    Subnetzmaske 255.255.255.240
Subnetz  8: 17.0.0.112/28 - 17.0.0.127/28   14 nutzbare Hosts    Subnetzmaske 255.255.255.240
Subnetz  9: 17.0.0.128/28 - 17.0.0.143/28   14 nutzbare Hosts    Subnetzmaske 255.255.255.240
Subnetz 10: 17.0.0.144/28 - 17.0.0.159/28   14 nutzbare Hosts    Subnetzmaske 255.255.255.240

Die restlichen 6 Netze die nicht verwendet werden (falls das Netz weiter so geteilt worden ist)  

Subnetz 11: 17.0.0.160/28 - 17.0.0.175/28   14 nutzbare Hosts    Subnetzmaske 255.255.255.240
Subnetz 12: 17.0.0.176/28 - 17.0.0.191/28   14 nutzbare Hosts    Subnetzmaske 255.255.255.240
Subnetz 13: 17.0.0.192/28 - 17.0.0.207/28   14 nutzbare Hosts    Subnetzmaske 255.255.255.240
Subnetz 14: 17.0.0.208/28 - 17.0.0.223/28   14 nutzbare Hosts    Subnetzmaske 255.255.255.240
Subnetz 15: 17.0.0.224/28 - 17.0.0.239/28   14 nutzbare Hosts    Subnetzmaske 255.255.255.240
Subnetz 16: 17.0.0.240/28 - 17.0.0.255/28   14 nutzbare Hosts    Subnetzmaske 255.255.255.240

## Übung 5

Bestimmen Sie die Subnetmaske mit folgenden Angaben:

Netzadresse: 210.52.190.0
Subnetze: Anzahl 5
Mindestanzahl von Hosts je Subnetz: 10

**Antwort**
210.52.190.0/27 = 8 Subnetze mit je 30 Hosts          Subnetzmaske: 255.255.255.224
Davon werden nur 5 Subnetze verwendet

Die 5 Netze in verwendung mit den verwendeten 10 Hosts

Subnetz  1: 210.52.190.0/27    - 210.52.190.31/27     30 nutzbare Hosts    Subnetzmaske 255.255.255.224
Subnetz  2: 210.52.190.32/27   - 210.52.190.63/27     30 nutzbare Hosts    Subnetzmaske 255.255.255.224
Subnetz  3: 210.52.190.64/27   - 210.52.190.95/27     30 nutzbare Hosts    Subnetzmaske 255.255.255.224
Subnetz  4: 210.52.190.96/27   - 210.52.190.127/27    30 nutzbare Hosts    Subnetzmaske 255.255.255.224
Subnetz  5: 210.52.190.128/27  - 210.52.190.159/27    30 nutzbare Hosts    Subnetzmaske 255.255.255.224

Die restlichen 3 Netze die nicht verwendet werden (falls das Netz weiter so geteilt worden ist)  

Subnetz  6: 210.52.190.160/27  - 210.52.190.191/27    30 nutzbare Hosts    Subnetzmaske 255.255.255.224
Subnetz  7: 210.52.190.192/27  - 210.52.190.223/27    30 nutzbare Hosts    Subnetzmaske 255.255.255.224
Subnetz  8: 210.52.190.224/27  - 210.52.190.255/27    30 nutzbare Hosts    Subnetzmaske 255.255.255.224

## Übung 6

Teile  ein /30 Netz auf!    Wozu werden diese /30 Netze am häufigsten verwendet?
Antwort:


**Antwort**
64 mögliche Subnetze     /30 = 2 Hosts nutzbar     Verwendung: für eine einzelne Router-zu-Router-Verbindung verwendet 
Bsp. 192.168.0.0/30
Subnetz  1 192.168.0.0/30   - 192.168.0.3/30        Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz  2 192.168.0.4/30   - 192.168.0.7/30        Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz  3 192.168.0.8/30   - 192.168.0.11/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz  4 192.168.0.12/30  - 192.168.0.15/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz  5 192.168.0.16/30  - 192.168.0.19/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz  6 192.168.0.20/30  - 192.168.0.23/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz  7 192.168.0.24/30  - 192.168.0.27/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz  8 192.168.0.28/30  - 192.168.0.31/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz  9 192.168.0.32/30  - 192.168.0.35/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 10 192.168.0.36/30  - 192.168.0.39/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 11 192.168.0.40/30  - 192.168.0.43/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 12 192.168.0.44/30  - 192.168.0.47/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 13 192.168.0.48/30  - 192.168.0.51/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 14 192.168.0.52/30  - 192.168.0.55/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 15 192.168.0.56/30  - 192.168.0.59/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 16 192.168.0.60/30  - 192.168.0.63/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 17 192.168.0.64/30  - 192.168.0.67/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 18 192.168.0.68/30  - 192.168.0.71/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 19 192.168.0.72/30  - 192.168.0.75/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 20 192.168.0.76/30  - 192.168.0.79/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 21 192.168.0.80/30  - 192.168.0.83/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 22 192.168.0.84/30  - 192.168.0.87/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 23 192.168.0.88/30  - 192.168.0.91/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 24 192.168.0.92/30  - 192.168.0.95/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 25 192.168.0.96/30  - 192.168.0.99/30       Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 26 192.168.0.100/30 - 192.168.0.103/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 27 192.168.0.104/30 - 192.168.0.107/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 28 192.168.0.108/30 - 192.168.0.111/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 29 192.168.0.112/30 - 192.168.0.115/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 30 192.168.0.116/30 - 192.168.0.119/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 31 192.168.0.120/30 - 192.168.0.123/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 32 192.168.0.124/30 - 192.168.0.127/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 33 192.168.0.128/30 - 192.168.0.131/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 34 192.168.0.132/30 - 192.168.0.135/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 35 192.168.0.136/30 - 192.168.0.139/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 36 192.168.0.140/30 - 192.168.0.143/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 37 192.168.0.144/30 - 192.168.0.147/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 38 192.168.0.148/30 - 192.168.0.151/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 39 192.168.0.152/30 - 192.168.0.155/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 40 192.168.0.156/30 - 192.168.0.159/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 41 192.168.0.160/30 - 192.168.0.163/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 42 192.168.0.164/30 - 192.168.0.167/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 43 192.168.0.168/30 - 192.168.0.171/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 44 192.168.0.172/30 - 192.168.0.175/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 45 192.168.0.176/30 - 192.168.0.179/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 46 192.168.0.180/30 - 192.168.0.183/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 47 192.168.0.184/30 - 192.168.0.187/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 48 192.168.0.188/30 - 192.168.0.191/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 49 192.168.0.192/30 - 192.168.0.195/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 50 192.168.0.196/30 - 192.168.0.199/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 51 192.168.0.200/30 - 192.168.0.203/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 52 192.168.0.204/30 - 192.168.0.207/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 53 192.168.0.208/30 - 192.168.0.211/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 54 192.168.0.212/30 - 192.168.0.215/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 55 192.168.0.216/30 - 192.168.0.219/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 56 192.168.0.220/30 - 192.168.0.223/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 57 192.168.0.224/30 - 192.168.0.227/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 58 192.168.0.228/30 - 192.168.0.231/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 59 192.168.0.232/30 - 192.168.0.235/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 60 192.168.0.236/30 - 192.168.0.239/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 61 192.168.0.240/30 - 192.168.0.243/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 62 192.168.0.244/30 - 192.168.0.247/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 63 192.168.0.248/30 - 192.168.0.251/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252
Subnetz 64 192.168.0.252/30 - 192.168.0.255/30      Je 2 Nutzbare Hosts   Subnetzmaske: 255.255.255.252

## Übung 7

Nennen Sie den jeweiligen Netz- und Hostanteil der Klassen A, B und C

**Antwort**
Eine IPv4-Adresse besteht aus 32 Bit
Jede Adressklasse hat eine feste Aufteilung zwischen Netz- und Hostanteil.
Klase A hat 8 Bit Netzanteil und 24 Bit Hostanteil (für sehr große Netwerke)
Klase B hat 16 Bit Netzanteil und 16 Bit Hostanteil (für mittelgroße Netzwerke)
Klase C hat 24 Bit Netzanteil und 8 Bit Hostanteil (für kleine Netwerke)


