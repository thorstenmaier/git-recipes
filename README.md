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

## Zwei Stände (Branches) zusammenbringen

- Merge ausführen (`git merge name_des_anderen_branches`)

## Konflikt auflösen

### Wann tritt ein Konflikt auf?

Konflikt tritt auf, falls auf beiden Branches ein und dieselbe Zeile in einer Datei verändert wurde.

### Was müssen wir tun?

- Wir starten einen Merge (`git merge anderer_branch`)
- Git meldet einen Konflikt
- Konflikt beseitigen
  - Datei mit Konflikt öffnen
  - Merge-Marker entfernen
  - Die beiden Inhalte vereinen - im Zweifel mit Kollegen sprechen ;-)
- Datei speichern
- Datei als konfliktfrei kennzeichnen (`git add dateiname`)
- Commit abschließen (`git commit`)
