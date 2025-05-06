##Bulkimport?

Ein Bulkimport (Massendatenimport) ist eine Methode, um große Mengen an Daten effizient in eine Datenbank zu laden. In MySQL verwendet man zum Beispiel:

```sql
LOAD DATA INFILE 'pfad/zur/datei.csv'
INTO TABLE tabellenname
FIELDS TERMINATED BY ','
ENCLOSED BY '\"'
LINES TERMINATED BY '\\n'
IGNORE 1 ROWS;
```
