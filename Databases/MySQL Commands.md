
---

GIT-Bash mit Administratorrechten starten, folgender Befehl installiert lokal einen MySQL Dienst: `choco install mysql`

---

##### Befehle um den lokalen MySQL Dienst zu konfigurieren, etc.
|Befehl     |  Description   |
| --- | --- |
|  `mysql -u root -p`   |   MySQL Login  |
|  `SHOW DATABASES;`   |   Datenbanken anzeigen |
|  `CREATE DATABASE <db_name>;`   |   Datenbank erstellen  |
|  `CREATE USER '<username>'@'localhost' IDENTIFIED BY '<password>';`   |   User anlegen + PW setzen  |
|  `GRANT ALL PRIVILEGES ON <db_name>.* TO '<username>'@'localhost';`   |   Berechtigungen für User festlegen  |
|  `FLUSH PRIVILEGES;`   |   ?  |
|  `USE <db_name>;`    |   Datenbank aktivieren  |
|  `SHOW TABLES;`    |   Tabellen anzeigen  |