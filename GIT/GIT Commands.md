
---
##### Häufig verwendete GIT-Befehle
|Befehl     |  Description   |
| --- | --- |
|  `git init`   |   lokales GIT Repo initialisieren für aktuelles Verzeichnis  |
|  `git status`   |   Status anzeigen |
|  `git add .`   |   Alle Dateien zum nächsten Commit hinzufügen |
|  `git remote -v`   |   Remote Origins anzeigen  |
|  `git pull`   |   aktuellen Stand aus dem Remote Repo pullen  |
|  `git clone <Link zum Repository>`   |   Remote Repo ins aktuelle verzeichnis Clonen  |
|  `git commit -m "<Comment>"`   |   Commit erstellen mit Kommentar  |
|  `git remote add <Origin-name> <Link zum Repository>`   |   Remote-Ziel (origin) festlegen  |
|  `git push -u <Origin-name> <Branchname>`    |  Pushen auf Ziel "origin" und branch "main"  |
|  `git checkout -b feature/<Branchname>`    |   Branch anlegen  |
|  `git checkout feature/<Branchname>`    |   Branch wechseln  |


---
##### Nice-to-know
Mit folgendem Befehl kann der Standard Branch Name von "master" auf "main" geändert werden. Einfach in der GIT Bash einfügen. (Danke Joel!)

`git config --global init.defaultBranch main`

---

##### Links
[GitHub New Repo (direkter Link um ein neues Repository anzulegen)](https://github.com/new/)
[GitHub Cheatsheet PDF](https://education.github.com/git-cheat-sheet-education.pdf)
