## Was sind Aggregatsfunktionen?

Aggregatsfunktionen fassen mehrere Zeilen zu einem einzigen Wert zusammen. Sie sind hilfreich, um Statistiken oder Zusammenfassungen über Daten zu erstellen. Typische Aggregatsfunktionen sind:

- `COUNT()` – zählt die Anzahl der Zeilen
- `SUM()` – berechnet die Gesamtsumme
- `AVG()` – liefert den Durchschnitt
- `MIN()` – gibt den kleinsten Wert zurück
- `MAX()` – gibt den größten Wert zurück

Diese Funktionen werden meist mit `GROUP BY` verwendet, um Daten nach Kategorien zusammenzufassen. Beispiel: Wie viele Bestellungen hat jeder Kunde? → `GROUP BY KundeID`.
