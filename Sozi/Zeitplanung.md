**Ziel: Es soll der beste Bestellzeitpunkt für eine Ware ermittelt werden**

- Bestände müssen ständig überwacht werden
- Warenmenge bestimmt durch Nachfrage in absehbarer Zeit

### Lagerbestandsarten
**Höchstbestand:** ist die Menge an Waren, die ein Lagerort höchstens aufnehmen kann

**Ermittlung: HB = EB + BM**
*Höchstbestand =  Bestand + optimale Bestellmenge*

**Eiserner Bestand / Mindestbestand: (EB)**
Notreserven für unvorhergesehene Ereignisse, d.h.
- der Absatz war höher als geplant oder
- der Lieferant ist im Verzug

Ermittlung: Erfahrungswerte, Schätzwerte

**Meldebestand:** ist die Stückzahl vom Meldebestand erreicht,
muss man dringend bestellen
$MB = EB + (LZ * A)$
$Meldebestand = Eiserner Bestand + (Lieferzeit * täglicher Absatz)$

### Bestellrythmusverfahren

vereinfachung der Zeitplanung:
- es werden jeden Tag Waren Verkauft (kein Sa. / So.)
- es wird von einem Artikel jeden Tag dieselbe Menge verkauft
- Ware kann unbegrentzt gelagert werden
- Lieferant liefert pünktlich
- Lagerort bleibt unverändert (HB, EB)

Aufgabe
gegeben:
	A = 3 Stk
	LZ = 8 Tage
	HB = 45 Stk
	EB = 6 Stk
	MB ist 16.10

**Mindestbestand:** 6 Stk
**Meldebestand:** 30 Stk
**Höchstbestand:** 45 Stk
**optimale Bestellmenge:** 39 Stk

**Lagerbewegung**                        **Bedarfsmeldung**

| Datum | Eingang | Ausgang | Bestand | angef. Menge | Hilfe     |
| ----- | ------- | ------- | ------- | ------------ | --------- |
| 16.10 |         | 3       | 30      | 39           | bestellen |
| 17.10 |         | 3       | 27      |              | lz        |
| 18.10 |         | 3       | 24      |              | lz        |
| 19.10 |         | 3       | 21      |              | lz        |
| 20.10 |         | 3       | 18      |              | lz        |
| 21.10 |         | 3       | 15      |              | lz        |
| 22.10 |         | 3       | 12      |              | lz        |
| 23.10 | 39      | 3       | 45      |              | lieferung |
| 24.10 |         | 3       | 42      |              | verkauf   |
| 25.10 |         | 3       | 39      |              | verkauf   |
| 26.10 |         | 3       | 36      |              | verkauf   |
| 27.10 |         | 3       | 33      |              | verkauf   |
| 28.10 |         | 3       | 30      | 39           | bestellen |
| 29.10 |         | 3       | 27      |              | lz        |
| 30.10 |         | 3       | 24      |              | lz        |
| 31.10 |         | 3       | 21      |              | lz        |
| 01.11 |         | 3       | 18      |              | lz        |
| 02.11 |         | 3       | 15      |              | lz        |
| 03.11 |         | 3       | 12      |              | lz        |
| 04.11 | 39      | 3       | 45      |              | lieferung |
| 05.11 |         | 3       | 42      |              | verkauf   |
| 06.11 |         | 3       | 39      |              | verkauf   |
| 07.11 |         | 3       | 36      |              | verkauf   |
| 08.11 |         | 3       | 33      |              | verkauf   |

![[Bestellrythmus]]