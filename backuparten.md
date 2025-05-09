## Backuparten ##

Es gibt drei wesentliche Backuparten in Datenbanksystemen:

1. **Vollbackup**  
   Ein vollständiges Abbild der gesamten Datenbank. Es sichert alle Tabellen, Daten und Strukturen.

2. **Inkrementelles Backup**  
   Sichert nur die Änderungen seit dem letzten Backup (egal ob Voll oder inkrementell). Es ist speicher- und zeiteffizient, aber aufwendiger bei der Wiederherstellung.

3. **Differenzielles Backup**  
   Sichert alle Änderungen seit dem letzten **Vollbackup**. Die Wiederherstellung ist schneller als bei inkrementellen Backups, benötigt aber mehr Speicherplatz.

Backups sind entscheidend zur Vermeidung von Datenverlusten, besonders bei Systemabstürzen oder Benutzerfehlern.
