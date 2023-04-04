# The commands you need for git

Immer git bash in Terminal in VS Code benutzen.

## 1. Ein neues Repository auf Pc speichern (lokal)

- git clone ...(https link von repository oder ssh link wenn man ssh key hat)

## 2. Track uncomitted changes

- mit git status wird angezeigt welche Dateien bearbeitet wurden und welche Dateien neu dazugekommen sind. Aber noch nicht mit git gespeichert wurden.(also noch nicht ins Repository geladen wurden)

## 3. Hinzufügen zum Speicherprozess bzw um sie dann im folgenden zu comitten/speichern

- git add .       --> speichert alle changes die gemacht wurden
- git add dateiname    --> speichert die changes nur von diesem file 

## 4. Speichern von Änderungen (lokal)--> ist also noch nicht live auf github !!

- git commit -m "Hier kommt commit message hin" -m "Hier kommt wahlweise noch description hin"
--> Es werden alle changes die geaddet wurden automatisch gespeichert

## 5. Hochladen der Änderung auf Github

- git push "name des repository" "ordner des repositorys"
- git push ist deafult befehl --> pusht dann in aktuelles repository und in main ordner !!!
