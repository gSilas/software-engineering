## Version Control System
### <u> Definition </u>

### Zentrale VCS
* Zentrale Kopie des gesamten Projekts auf Server
* durch Rechteverwaltung wird dafür gesorgt, dass nur berechtigte Personen neue Versionen in das Archiv legen können
* Versionsgeschichte ist hierbei nur im Repository vorhanden
* benötigte Dateien werden auds dem zentralen Repo geladen

### Pros
* benötigt wenig lokalen Speicher
* nur ein Repository muss beachtet werden, das zentrale

### Cons
* gesamtes Projekt nur auf dem Server
* Änderungskonflikte müssen manuell aussortiert werden
* keine lokalen Historien

### Beispiele
* SVN, CVS

---
### Dezentrale VCS
* dezentrale (lokale) Kopien des gesamten Projekts
* Jeder, der an dem verwalteten Projekt arbeitet, hat sein eigenes (lokales) Repository und arbeitet an diesem
* Versionsgeschichte ist dadurch auf Repos verteilt
* Änderungen können lokal verfolgt werden
* kein Konflikt, wenn mehrere Benutzer dieselbe Version einer Datei ändern, denn widersprechenden Versionen existieren zunächst parallel und können weiter geändert und gemerged werden

### Pros
* Änderungen sind sehr schnell möglich aufgrund des lokalen Repos  _ Ausnahme: pushing und pulling zum Server _
* Commits können gesammelt werden und dann gesammelt in das Netwerkrepo gepusht werden
* arbeiten am Projekt komplett offline möglich  
_ Ausnahme: pushing und pulling zum Server _
* da jeder Programmierer über das komplette Projekt verfügt können einzelne Commits an einzelne Programmierer zur Überprufung weitergegeben werden (Verhindert Fehler bei offenen Repos)

### Cons
* Server braucht viel Speicher bei sich oft ändernden großen Binärdateien (komplette History gespeichert)
* Herunterladen der gesamten Historie benötigt bei großen Projekten viel Zeit und Speicherplatz

### Beispiele
* Git, Mercurial

---
### Persönlicher Favorit
* ** GIT **
* ##### Gründe
  * Git ist sehr gut, sehr schnell, sehr geil
  * GitHub
  * OpenSource
