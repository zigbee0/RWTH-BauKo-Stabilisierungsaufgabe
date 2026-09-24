# RWTH-BauKo-Stabilisierungsaufgabe
Dies ist eine Webseite mit Javascript, auf der Sie die Stabilisierungsaufgabe üben können, die häufig in der Prüfung des Bauko-Moduls an der RWTH vorkommt.

## Mechanisches Modell
- Räumliches Gelenkstabwerk: alle Knoten gelenkig, Auflagerknoten unverschieblich (a = 3).
- Abzählkriterium: p<sub>erf</sub> = 3·k − p<sub>vorh</sub> (k ohne Auflagerknoten, p<sub>vorh</sub> inkl. Stützen). Es ist nur **notwendig**, nicht hinreichend.
- Geprüft wird deshalb zusätzlich der Rang der Gleichgewichtsmatrix: Rang < 3k ⇒ kinematisch verschieblich, linear abhängige Verbände ⇒ überzählig (statisch unbestimmt).
- **Scheibenstabilisierung:** Jede Decke muss eine starre Scheibe sein; je Geschoss mindestens drei Wandscheiben, die weder alle parallel sind noch sich alle in einem Punkt schneiden.
- **Reihenstabilisierung:** Decke schubweich; jede Reihe braucht in jedem Geschoss und in jedem zusammenhängenden Wandabschnitt einen eigenen Verband.
- Ein Verband ist immer die Diagonale genau eines vorhandenen Decken- oder Wandfeldes.
