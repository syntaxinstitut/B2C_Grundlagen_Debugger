# Debugger Aufgaben

`Grundlagen mit Kotlin` `Debugger`

Heute sollt ihr, nachdem ihr erste Programmierkenntnisse gesammelt habt, lernen euren Code systematisch zu durchleuchten 
und Fehler zu finden.

<p align="center">
<img src=img/mac.png width="66%" alt=""/>
</p>
<p align="center">
   <b>Abbildung:</b> Code wird systematisch von Fehlern befreit <a href="https://www.pexels.com/de-de/">Quelle</a>
</p>


## Aufgabe 1
> Schreib deinen Code in die Datei _Aufgabe1/src/Main.kt_

Probiere aus: Setze Breakpoints und entferne sie, wenn du nichts gefunden hast, an unterschiedlichen Stellen im code und 
schreibe Kommentare, wenn du aber einen Fehler gefunden 
hast:

```kotlin
fun main() {
    var x = 10
    var y = 0

    if (y != 0) {
        var result = x / y
        println("Das Ergebnis ist: $result")
    } else {
        println("Division durch Null ist nicht erlaubt.")
    }
}
```


## Aufgabe 2
> Schreib deinen Code in die Datei _Aufgabe2/src/Main.kt_

Setze nochmals Breakpoints an verschiedenen Stellen, um den Code zu überwachen und sicherzustellen, dass alles wie 
erwartet funktioniert. Gehe dafür jetzt aber von breakpoint zu breakpoint (behalte die breakpoints) und bereinige den 
code.

```kotlin
fun main() {
    var a = 5
    var b = 0

    var quotient = a / b

    if (b != 0) {
        var result = a / b
        println("Das Ergebnis ist: $result")
    } else {
        println("Division durch Null ist nicht erlaubt.")
    }
}
```
#### Viel Erfolg 🚀 

<p align="end">
  <a href="https://www.syntax-institut.de/">
    <img src="img/si.png" width="10%" alt=""/>
  </a>
</p>
