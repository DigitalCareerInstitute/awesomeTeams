# awesomeTeams
Team generator for our x-mas party

## A dus_fbw9 project

## Neues:

  - **JSON.stringify()** Macht aus einem javascript wert ({},[],'string',123) einen string: '{}', '[]', '"string"', '123'

  - **JSON.parse()** Macht aus einem JSON-String wieder einen javascript wert

  - **localStorage.setItem(key,value)** Speichert den *string* "value" unter dem Schluessel "key" in der datenbank

  - **localStorage.getItem(key)** Ruft den *String*_ der unter dem Schluessel "key" gespeichert ist wieder ab

  Um daten in localStorage zu speichern muessen wir zuerst die daten mittels JSON.stringify "verpacken"

  Um sie wieder benutzen zu koennen muessen wir sie mittels JSON.parse wieder "entpacken"

  Um das ganze zu vereinfachen bereiten wir uns eine 'save' und eine 'load' funktion vor
