## Beziehungsarten

In relationalen Datenbanken gibt es verschiedene Arten von Beziehungen zwischen Tabellen. Diese beschreiben, wie Datensätze zueinander in Verbindung stehen. Die drei Haupttypen sind:

### 1. 1:1-Beziehung (Eins zu Eins)
Ein Datensatz in Tabelle A gehört genau zu einem Datensatz in Tabelle B.  
**Beispiel:** Jeder Mitarbeiter hat genau einen Spind.

```
Tabelle: Mitarbeiter      Tabelle: Spind
ID_Mitarbeiter ───────▶ ID_Spind
```

### 2. 1:n-Beziehung (Eins zu Viele)
Ein Datensatz in Tabelle A kann mit mehreren Datensätzen in Tabelle B verknüpft sein.  
**Beispiel:** Ein Kunde hat mehrere Bestellungen.

```
Tabelle: Kunde           Tabelle: Bestellung
ID_Kunde ───────▶ FK_Kunde
```

### 3. n:m-Beziehung (Viele zu Viele)
Mehrere Datensätze in Tabelle A können mit mehreren in Tabelle B verbunden sein.  
Diese Beziehung benötigt eine **Zwischentabelle** (auch Verknüpfungstabelle genannt).  
**Beispiel:** Schüler besuchen mehrere Kurse, und ein Kurs hat mehrere Schüler.

```
Tabelle: Schüler        Tabelle: Kurse
ID_Schüler              ID_Kurs
    ▲                        ▲
    │                        │
    └──── Zwischentabelle ──┘
            (z. B. Kursteilnahmen)
```
