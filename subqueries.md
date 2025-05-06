## Subqueries

Eine Subquery ist eine SQL-Abfrage innerhalb einer anderen Abfrage. Beispiel:

```sql
SELECT name
FROM kunden
WHERE id IN (
  SELECT kunde_id
  FROM bestellungen
  WHERE betrag > 100
);
