# Java - Übung 1
## ToDo Applikation

Erstelle ein Projekt, in welchem alle Dateien für die Übung abgelegt werden, mit dem Namen:
>com.virtrel.java.todo

**Achte auf folgende Eigenschaften**
>* Korrekte Namensgebung und Schreibweise für Variablen, Methoden & Klassen
>* Korrekte Zugriffsberechtigung für Variablen, Methoden & Klassen

**Zeitvorgabe für die Übung**
> 3 Stunden

**Punkteverteilung**
>* 30 Punkte für Punkt 1. Applikation
>* 40 Punkte für Punkt 2. Überprüfung
>* 40 Punkte für Punkt 3. Sortierung

### **1. Applikation**

Für die Applikation wird die Klasse __*Main*__ mit der Methode __*main*__ verwendet.

Die Applikation wird ein Konsolenmenü benötigt, welches wie folgt aufgebaut ist:
>1. Aufgabe erstellen
>2. Aufgabe entfernen
>3. Liste sortieren
>4. Liste leeren
>5. Liste ausgeben
>6. Programm beenden

Eine Aufgabe soll folgende Werte für die Eingabe besitzen:
>* Bezeichnung [Maximal 50 Zeichen; Eingabe: Pflicht]
>* Beschreibung [Maximal 250 Zeichen; Eingabe: Optional]
>* Priorität [1-5; Eingabe: Pflicht]
>* Dauer [00:00:00 - 23:59:59; Eingabe Optional]
>* Fälligkeitsdatum [29.10.2018 - 31.12.2099; Eingabe Optional]

Beim erstellen einer Aufgabe [Menüpunkt 1], soll eine *ArrayList* verwendet werden.

Beim entfernen einer Aufgabe [Menüpunkt 2], wird eine Zahl als Eingabe erwartet. Beispiel: Wird *1* eingegeben, dann soll das Element an der Indexstelle *0* von der ArrayList gelöscht werden.

Beim leeren der Liste [Menüpunkt 4], soll das ArrayList-Objekt gelöscht werden, damit beim hinzufügen einer Aufgabe [Menüpunkt 1], das Objekt erneut erstellt werden muss.

Beim ausgeben der Liste [Menüpunkt 5], soll die Liste mit all ihren Eigenschaften in der Konsole ausgegeben werden.

Wird das Programm beendet [Menüpunkt 6], dann soll sich die Konsole schließen.

### **2. Überprüfung**

Für die Überprüfung der eingegeben Daten, soll ein *Interface* und die dazugehörigen *abstrakten Methoden* erstellt werden.

Für jede Eingabe, die bei der Erstellung einer Aufgabe getätigt wird, soll eine Methode erstellt werden, welche überprüft ob die eingegebenen Daten den Vorgaben entsprechen.

Nur bei einer korrekten Eingabe, wird die nächste Eigenschaft einer Aufgabe angenommen. Bei einer fehlerhaften Eingabe, soll eine aussagekräftige Fehlermeldung angezeigt werden und der Benutzer soll anschließend die fehlerhafte Eingabe ausbessern können.

### **3. Sortierung**

Bei der Sortierung [Menüpunkt 3], sollen die Elemente in der Liste nach der Priorität sortiert werden.