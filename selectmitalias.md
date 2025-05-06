## `SELECT` mit Alias

Ein Alias ist ein Alternativname für Spalten oder Tabellen. Beispiel:

```sql
SELECT vorname AS "Vorname", nachname AS "Nachname"
FROM kunden;
```

Auch Tabellen können Aliase haben:

```sql
SELECT k.name, b.datum
FROM kunden k
JOIN bestellungen b ON k.id = b.kunde_id;
