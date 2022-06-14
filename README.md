# Dies ist der Quellcode für mein EmbeddedSystems Projekt: Intelligent Room

## Technik

Das System besteht aus mehrere Komponenten:

* der technische Aufbau
    * Das Projekt hat einen Temperatursensor der die Raumtemperatur misst und die Daten an den Microcontroller weitergibt.
    * Außerdem ist ein Gassensor vorhanden, der den aktuellen Gaswert in der Zimmerluft  misst und diesen auch an den Mikrocontroller weitergibt.
    * Es gibt eine rote LED, welche leuchtet wenn Gas/Rauch im Raum ist.
    * Es gibt eine grüne LED, welche leuchtet wenn kein Gas/Rauch im Raum ist.
    
* der Programmcode für den Arduino
    -Das Programm wertet die Daten des Temperatursensor aus und gibt den aktuellen Temperaturwert auf dem seriellen Monitor aus.
    -Das Programm wertet den Analogwert des Gassensors aus und schaltet eine von den beiden Dioden.
    -Der Wert ab wann die Rote LED leuchten soll kann im Programmcode unter max_value angepasst werden.
