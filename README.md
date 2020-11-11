# Git Rezepte

## Git Repository anlegen

- Neues Verzeichnis anlegen (`mkdir myproject`)
- In das neue Verzeichnis wechseln (`cd myproject`)
- Git Repository im Verzeichnis anlegen (`git init`)

## Commit erzeugen

- Eine Datei anlegen, ändern oder löschen
  - z.B. `touch neuedatei.txt`
- neuedatei.txt in den Index aufnehemen (`git add neuedatei.txt`)
- Commit erstellen (`git commit -m "Beschreibung der Änderung`)

## Branch anlegen und Working Copy Stand wechseln

- Branch anlegen (`git branch branchname hash`)
- Working Copy auf diesen Stand setzen (`git checkout branchname`)
