# Deutsche-Feuerwehr-Bezeichnungen
Eine JSON-Libary für Bezeichnungen in der deutschen Feuerwehr



## Dienstgrade und Funktionen
Dienstgrade und Funktionen sind gesammelt in der Datei
```url
dienstgrade-funktionen.json
```
Die Struktur ist wie folgend aufgebaut:
```json
[
    {
       "name":"Ausgeschriebene Bezeichnung",
       "abbreviation":"Abkürzung",
       "unique-rank":"0"
    },
    {
       "name":"a",
       "abbreviation":"b",
       "unique-rank":"1"
    }
]
```

## Dienstgrade
Dienstgrade sind sortiert und nach "Wichtigkeit" (unique-rank) in folgender Datei zu finden:
```
dienstgrade.json
```
Die Struktur ist wie folgend aufgebaut:
```json
[
    {
       "name":"Jugenfeuerwehr",
       "type":"Mannschaftsdienstgrade",
       "unique-rank":"0"
    },
    [...]
]
```
