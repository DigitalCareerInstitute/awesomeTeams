# awesomeTeams
Team generator for our x-mas party

## A dus_fbw9 project

## Neues:

### JSON funktionen

Oft muss man Daten irgendwo speichern, z.B. in einer Datenbank. Da eine Datenbank
normalerweise *Strings* speichert, muss man die Werte aus unserer JavaScript app
erstmal in *Strings* konvertieren. Hierzu kann man die **JSON** Funtionen benutzen.

  - **JSON.stringify()** Macht aus einem javascript wert ({},[],'string',123) einen string: '{}', '[]', '"string"', '123'

  - **JSON.parse()** Macht aus einem JSON-String wieder einen javascript wert

### localStorage

Chrome und co. bringen eine eigene kleine, ganz einfache Datenbank mit, die dazu
dient, Daten fuer eine App oder Website zu speichern.

  - **localStorage.setItem(key,value)** Speichert den *string* "value" unter dem Schluessel "key" in der datenbank

  - **localStorage.getItem(key)** Ruft den *String*_ der unter dem Schluessel "key" gespeichert ist wieder ab

### Die Kombination

Um daten in localStorage zu speichern muessen wir zuerst die daten mittels JSON.stringify "verpacken"

Um sie wieder benutzen zu koennen muessen wir sie mittels JSON.parse wieder "entpacken"

Um das ganze zu vereinfachen bereiten wir uns eine 'save' und eine 'load' funktion vor
