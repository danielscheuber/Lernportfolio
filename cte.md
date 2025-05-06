## CTE

Ein **Common Table Expression (CTE)** ist ein temporäres Ergebnis, das in einer Abfrage verwendet werden kann. Beispiel:

```sql
WITH topkunden AS (
  SELECT kunde_id, COUNT(*) AS bestellungen
  FROM bestellungen
  GROUP BY kunde_id
)
SELECT * FROM topkunden WHERE bestellungen > 10;
