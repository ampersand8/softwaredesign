## Software-Engineering Entwurf
#### by Simon Peter

---

## Inhalt

  * Für was ist der Software Entwurf?
  * Was ist ein Software Entwurf?
  * Entwicklungsrichtung
  * Methoden des Entwurfs

---

## Komplexe Software ist frustrierend!

  RAGE ANGRY IMAGE

----

## Für was ist der Software Entwurf?

  * Vereinfachung durch Strukturen
  * Wiederverwendbarkeit
  * Kommunikation

---

## Was ist ein Software Entwurf?

  * Ziele
    1. Gliederung des Systems in handhabbare Einheiten
    1. Festlegung der Lösungsstruktur
    1. Hierarchische Gliederung
  * Die Tätigkeit Charakteristiken eines Systems oder einer Komponente zu definieren.
  * Resultat: Architektur

---

## Entwicklungsrichtung

  * <em>top-down</em><br>
    Üblicher Ansatz
  * <em>bottom-up</em><br>
    Spezielle Anforderungen bei Implementierung
  * <em>outside-in</em><br>
    Festgelegte Schnittstelle
  * <em>inside-out</em><br>
    Funktionserweiterung bestehender Systeme

---

## Aspekte des Architekturentwurfs

  * Modularisierung
  * Kopplung und Zusammenhalt
  * Information Hiding
  * Trennung von Zustaendigkeiten
  * Hierarchische Gliederung

----

### Modularisierung

  * Ziele
    * Struktur von Modulen einfach
    * Implementierung austauschbar
    * Aenderungen ohne Modifikation von Schnittstellen
  * Modularten
    * Funktionale Module
    * Datenobjektmodule
    * Datentypmodule

----

### Kopplung und Zusammenhalt

  * Geringe Kopplung
  * Hoher Zusammenhalt
  * Bessere Wartbarkeit, Verstaendlicher Code

----

### Information Hiding

  * Need to know
  * Weniger Missbrauch
  * Kontrolliertes Datenhandling

Amazon - Jeff Bezos around 2002
  * All teams will henceforth expose their data and functionality through service interfaces.
  * Teams must communicate with each other through these interfaces.

> Anyone who doesn't do this will be fired.

----

### Trennung von Zustaendigkeiten



---

## Architekturmuster

  * Schichtenarchitektur
  * Pipes und Filter
  * Model-View-Controller
  * Microservices

----

### Schichtenarchitektur

  * Leicht verstaendlich
  * Lose Kopplung
  * Aufteilung in Subtasks
  * protokollbasierte Schichten
  * objektorientierte Schichten

----

### Pipes und Filter

```bash
ls -al | grep important | awk '{print $2}'
```

  * Datenfliessband Verarbeitung
  * Datenformat
  * Fehlerfall

----

### Model-View-Controller

  * Grafische- und Webanwendungen
  * Beliebte Frameworks - Spring, Django
PICTURE OF MVC MODEL

----

### Microservices

  * Vom Monolith zu Microservices
  * Verteilt
  * Overengineering Small Apps
  * Skalieren in Wirklichkeit

IMAGE OF NETFLIX MICROSERVICES CONNECTION GRAPH

---

## Aspekte des Software Enwurfs

  * Kompatibilitaet
  * Erweiterbarkeit
  * Fehlertoleranz
  * Wartbarkeit
  * Modularitaet
  * Wiederverwendbarkeit
  * Sicherheit
  * Performanz
  * Portabilitaet
  * Skalierbarkeit

---

## Quellen

https://plus.google.com/+RipRowan/posts/eVeouesvaVX
Software Engineering, Jochen Ludewig - Horst Lichter
