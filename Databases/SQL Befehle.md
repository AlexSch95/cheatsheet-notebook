Disclaimer: hier kann es von DBMS zu DBMS minimale unterschiede geben. (z.B. LIMIT oder TOP) Im Zweifelsfall am besten einfach die Doku des jeweiligen DBMS prüfen.

[SQLite3 Documentation](https://www.sqlite.org/docs.html)
[MySQL Documentation](https://dev.mysql.com/doc/)
[MySQL Connector - Python](https://dev.mysql.com/doc/connector-python/en/connector-python-introduction.html)

---
|Befehl|Description|
|---|---|
|`SELECT * FROM table_name`|Alle Daten aus einer Tabelle auswählen|
|`SELECT column1, column2 FROM table_name`|Bestimmte Spalten aus einer Tabelle auswählen|
|`SELECT DISTINCT column FROM table_name`|Einzigartige Werte aus einer Spalte auswählen|
|`WHERE column = 'value'`|Filtert Ergebnisse nach einer Bedingung|
|`ORDER BY column ASC/DESC`|Sortiert Ergebnisse auf- oder absteigend|
|`GROUP BY column`|Gruppiert Ergebnisse nach einer Spalte|
|`HAVING condition`|Filtert gruppierte Ergebnisse|
|`INSERT INTO table_name (col1, col2) VALUES (val1, val2)`|Fügt neue Datensätze in eine Tabelle ein|
|`UPDATE table_name SET column = value WHERE condition`|Aktualisiert bestehende Datensätze|
|`DELETE FROM table_name WHERE condition`|Löscht Datensätze aus einer Tabelle|
|`CREATE TABLE table_name (col1 datatype, col2 datatype)`|Erstellt eine neue Tabelle|
|`ALTER TABLE table_name ADD column datatype`|Fügt eine Spalte zu einer Tabelle hinzu|
|`DROP TABLE table_name`|Löscht eine gesamte Tabelle|
|`CREATE INDEX index_name ON table_name (column)`|Erstellt einen Index für schnelleren Zugriff|
|`JOIN table2 ON table1.column = table2.column`|Verbindet Daten aus mehreren Tabellen|
|`INNER JOIN`|Gibt nur übereinstimmende Datensätze zurück|
|`LEFT JOIN`|Gibt alle Datensätze der linken Tabelle zurück|
|`COUNT(column)`|Zählt die Anzahl der Datensätze|
|`SUM(column)`|Berechnet die Summe einer Spalte|
|`AVG(column)`|Berechnet den Durchschnitt einer Spalte|