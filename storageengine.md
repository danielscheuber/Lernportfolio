## Storage Engine

Eine Storage Engine ist die Komponente im DBMS, die bestimmt, **wie** Daten physisch gespeichert, gelesen und geschrieben werden. In MySQL z. B.:

- `InnoDB` – unterstützt Transaktionen, Fremdschlüssel, ACID-konform
- `MyISAM` – schneller, aber ohne Transaktionen oder FK-Unterstützung
