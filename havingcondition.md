## HAVING Condition

Die `HAVING`-Bedingung wird zusammen mit `GROUP BY` verwendet, um Gruppenergebnisse zu filtern. `WHERE` filtert **vor** der Gruppierung, `HAVING` **nach** der Gruppierung:

```sql
SELECT kunde_id, COUNT(*) AS bestellungen
FROM bestellungen
GROUP BY kunde_id
HAVING COUNT(*) > 5;
```
