# Fehlerkategorien

### <u> Compilerfehler </u>
Fehler in der Sprache, die den Compiler daran
hindern, dass Programm zu übersetzen
#### Behebung
* Compiler Errors vor Ausführung des Codes bemerkbar
* Lassen sich (meist) auf eine präzise Codezeile zurückverfolgen
* meistens durch IDE visualisiert

#### Beispiele
  * Typos
  * Klammersetzung
  * Typsystemfehler
---
### <u> Laufzeitfehler </u>
Fehler, die während der Ausführung des Codes auftreten.
Laufzeitfehler werden in der Regel automatisch erkannt.
#### Behebung
* Bei Auftreten des Problems kommt i.d.R eine Exception
* Stacktrace der Exception gibt Aufschluss über den Context (Call-Reihenfolge)
* Stacktrace verweist auf entsprechende Codezeile
* Verstehen, warum an dieser Stelle der Fehler aufgetreten ist, ist schwieriger -> Schrittweises Debuggen

#### Beispiele
  * Value out of Range
  * Division by Zero
  * Null Pointer References
---
### <u> Logische Fehler </u>
Fehler, bei denen sich das Programm nicht wie
erwartet verhält. Kein Fehler im Code, sondern im Verständnis des Programmierers.
#### Behebung
* Fehler entsteht, weil das Codeverständnis bei der
Programmierung nicht ausreichte
* Debug-Methoden helfen dabei, Codeverständnis aufzubauen
* Abhängig von Symptom und Komplexität des Codes kommen verschiedenste Debugging-Methoden zum Einsatz
* Am Ende jedoch muss der Entwickler verstehen, warum er einen Fehler gemacht hat

#### Beispiele
  * Falsches Ergebnis
  * Falsches Ergebnis
