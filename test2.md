# TEST1

1. **Kann eine Klasse mehrere Konstruktoren haben:**
   - a) Ja, genau zwei
   - b) Nein, es gibt nur den default Konstruktor
   - c) Grundsätzlich ja
   - d) Ja, aber nur bei Klassen, die private sind

2. **Was wird ausgegeben, wenn `new Kunde("Angelika", "Villach", "0699462234")` aufgerufen wird:**
   ```java
   public class Kunde {
       String name = "default";
       String adresse = "default";
       String telefon = "default";
       public Kunde(String name, String adresse, String telefon) {
           name = name;
           adresse = adresse;
           telefon = telefon;
           System.out.println("Kundendaten: " + this.name + ", " + this.adresse + ", " + this.telefon);
       }
   }
   ```
   - a) Kundendaten: Lisa, null, null
   - b) Kundendaten: null, null, null
   - c) Kundendaten: default, default, default
   - d) Kundendaten: Lisa, Klagenfurt, 0699462234

3. **Die Methode `private String gibAntwort();` kann direkt (ohne konkretes Objekt) aufgerufen werden von:**
   - a) Allen Objektmethoden
   - b) Allen Methoden
   - c) Allen Klassenmethoden
   - d) Allen Methoden des Objektes, zu dem `gibAntwort()` gehört

4. **Die Methode `public static String gibAntwort();` kann aufgerufen werden von:**
   - a) Allen Methoden des Objektes, zu dem `gibAntwort()` gehört
   - b) Nur von Objektmethoden
   - c) Allen Methoden
   - d) Nur von Klassenmethoden

5. **Das Keyword `this`:**
   - a) Verweist auf das aktuelle Objekt selbst
   - b) Dient nur zum Zugriff auf Klassenvariablen
   - c) Verweist auf die aktuelle Klasse selbst
   - d) Ist ein Typ

## Lösungen:

1. **Kann eine Klasse mehrere Konstruktoren haben?**
   - **Antwort:** c) Grundsätzlich ja

2. **Was wird ausgegeben, wenn `new Kunde("Angelika", "Villach", "0699462234")` aufgerufen wird?**
   - **Antwort:** c) Kundendaten: default, default, default

3. **Die Methode `private String gibAntwort();` kann direkt (ohne konkretes Objekt) aufgerufen werden von:**
   - **Antwort:** d) Allen Methoden des Objektes, zu dem `gibAntwort()` gehört

4. **Die Methode `public static String gibAntwort();` kann aufgerufen werden von:**
   - **Antwort:** c) Allen Methoden

5. **Das Keyword `this`:**
   - **Antwort:** a) Verweist auf das aktuelle Objekt selbst


