# Test1

---

### Aufgabe 1:
Komplexe Datentypen in Java:
- a. Können nur über Klassen realisiert werden
- b. Gibt es nicht
- c. Können nur mit Arrays realisiert werden
- d. Können über Arrays und Klassen realisiert werden

---

### Aufgabe 2:
public static String eineVariable; ist:
- a. Eine Variable, die nur positive Zahlen aufnimmt
- b. Eine Klassenvariable für Zahlen
- c. Eine Variable, die nur boolean Werte aufnimmt
- d. Eine Klassenvariable für Text

---

### Aufgabe 3:
Was gibt das folgende Programm aus:

```java
public class Example1 {
    public static void main(String[] args) {
        ArrayList<Integer> names = new ArrayList<Integer>();
        names.add("John");
        names.add("Mary");
        names.add("Peter");
        names.add(1);
        
        for(String tempName : names) {
            System.out.println("" + tempName);
        }
    }
}
```

- a. 1, 1, 1, 1
- b. Das Programm kompiliert nicht
- c. John, Mary, Peter
- d. John, Mary, Peter, 1

---

### Aufgabe 4:
Eine Variable `double a` ist ein:
- a. Primitiver Datentyp, für eine Zahl
- b. Primitiver Datentyp, für Text
- c. Array
- d. Komplexer Datentyp, für eine Zahl

---

### Aufgabe 5:
Gegeben seien folgende zwei Methoden, die im gleichen Block liegen:

```java
public int start(int a, int b) {...some code...}
public int start(int c, int d) {...some code...}
```

- a. Diese Konstellation kann es nicht geben, da die Methoden nicht überladen werden.
- b. Diese Konstellation darf es geben, wenn die Werte der Input-Parameter unterschiedlich sind.
- c. Diese Konstellation könnte es nur geben, wenn double Parameter verwendet werden.
- d. Diese Konstellation kann es geben, da die Methoden überladen werden.

---

### Aufgabe 6:
Nach welchem Prinzip werden in Java primitive Datentypen übergeben?
- a. per Pointer Value
- b. per Value (Wert)
- c. per Pointer (Zeiger)
- d. Parameterübergabe funktioniert nur mit komplexen Datentypen

---

### Aufgabe 7:
**for** und **while**:
- a. Bezeichnen eine Verzweigung (e.g., if)
- b. Sind die einzigen Möglichkeiten, um auf ein Array zuzugreifen
- c. Dienen immer zur Initialisierung eines Programms
- d. Werden für Schleifen benutzt

---

### Aufgabe 8:
Eine **public static** Methode:
- a. Kann nur in der jeweiligen Klasse aufgerufen werden
- b. Wird in allen weiteren Klassen auf einen default-Wert gesetzt
- c. Kann von anderen Klassen aus aufgerufen werden
- d. Darf man nicht erstellen

---

## Lösungen
1. **d.** Können über Arrays und Klassen realisiert werden
2. **d.** Eine Klassenvariable für Text
3. **b.** Das Programm kompiliert nicht
4. **a.** Primitiver Datentyp, für eine Zahl
5. **a.** Diese Konstellation kann es nicht geben, da die Methoden nicht überladen werden.
6. **b.** per Value (Wert)
7. **d.** Werden für Schleifen benutzt
8. **c.** Kann von anderen Klassen aus aufgerufen werden
