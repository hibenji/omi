# Test3

---

### Aufgabe 1:
Gegeben ist folgende Klassenstruktur:

```java
public class Pflanze {

    public double groesse;
    public boolean tiefWurzler;
    public static String someVar;

    public Pflanze() {
        System.out.println("Neue Pflanze erstellt.");
    }

    public void sprich() {
        System.out.println("Ich bin eine Pflanze.");
    }
}

public class Blume extends Pflanze {

    public String bluetenFarbe;

    public Blume() {
        System.out.println("Neue Blume erstellt.");
    }

    public void sprich() {
        System.out.println("Ich bin eine Blume.");
    }
}
```

**Frage:**
Was wird ausgegeben, wenn der Konstruktor der Klasse **Blume** aufgerufen wird?
- a. Neue Blume erstellt
- b. Nichts
- c. Neue Pflanze erstellt., Neue Blume erstellt
- d. Neue Pflanze erstellt

---

### Aufgabe 2:
Gegeben ist folgende Klassenstruktur:

```java
public class Pflanze {

    public double groesse;
    public boolean tiefWurzler;
    public static String someVar;

    public Pflanze() {
        System.out.println("Neue Pflanze erstellt.");
    }

    public void sprich() {
        System.out.println("Ich bin eine Pflanze.");
    }
}

public class Blume extends Pflanze {

    public String bluetenFarbe;

    public Blume() {
        System.out.println("Neue Blume erstellt.");
    }

    public void sprich() {
        System.out.println("Ich bin eine Blume.");
    }
}
```

**Frage:**
Die Methode **sprich()** der Klasse **Pflanze** hat ohne konkretes Objekt Zugriff auf folgende Variablen:
- a. groesse, tiefWurzler
- b. someVar
- c. groesse, tiefWurzler, someVar, bluetenFarbe
- d. groesse, tiefWurzler, someVar

---

### Aufgabe 3:
Gegeben ist folgende Klassenstruktur:

```java
public class Pflanze {

    public double groesse;
    public boolean tiefWurzler;
    public static String someVar;

    public Pflanze() {
        System.out.println("Neue Pflanze erstellt.");
    }

    public void sprich() {
        System.out.println("Ich bin eine Pflanze.");
    }
}

public class Blume extends Pflanze {

    public String bluetenFarbe;

    public Blume() {
        System.out.println("Neue Blume erstellt.");
    }

    public void sprich() {
        System.out.println("Ich bin eine Blume.");
    }
}
```

**Frage:**
Die Methode **sprich()** wird in der Klasse **Blume**:
- a. Überschrieben
- b. Überladen
- c. Automatisch aufgerufen
- d. Als Konstruktor definiert

---

### Aufgabe 4:
Gegeben ist folgende Klassenstruktur:

```java
public class Pflanze {

    public double groesse;
    public boolean tiefWurzler;
    public static String someVar;

    public Pflanze() {
        System.out.println("Neue Pflanze erstellt.");
    }

    public void sprich() {
        System.out.println("Ich bin eine Pflanze.");
    }
}

public class Blume extends Pflanze {

    public String bluetenFarbe;

    public Blume() {
        System.out.println("Neue Blume erstellt.");
    }

    public void sprich() {
        System.out.println("Ich bin eine Blume.");
    }
}
```

**Frage:**
Eine **static** Methode in der Klasse **Pflanze** hätte ohne konkretes Objekt Zugriff auf folgende Variablen:
- a. groesse, tiefWurzler, someVar, bluetenFarbe
- b. someVar
- c. groesse, tiefWurzler
- d. groesse, tiefWurzler, someVar

---

### Aufgabe 5:
Gegeben ist folgende Klassenstruktur:

```java
public class Pflanze {

    public double groesse;
    public boolean tiefWurzler;
    public static String someVar;

    public Pflanze() {
        System.out.println("Neue Pflanze erstellt.");
    }

    public void sprich() {
        System.out.println("Ich bin eine Pflanze.");
    }
}

public class Blume extends Pflanze {

    public String bluetenFarbe;

    public Blume() {
        System.out.println("Neue Blume erstellt.");
    }

    public void sprich() {
        System.out.println("Ich bin eine Blume.");
    }
}
```

**Frage:**
Was wird ausgegeben, wenn die Methode **sprich()** der Klasse **Blume** aufgerufen wird:
- a. Ich bin eine Blume
- b. Ich bin eine Pflanze
- c. Nichts
- d. Ich bin eine Pflanze, Ich bin eine Blume

---

### Aufgabe 6:
Mit dem Schlüsselwort **extends**:
- a. Kann zur Laufzeit der Typ eines Objekts überprüft werden.
- b. Wird eine interne Klasse definiert, die öffentlich (public) sichtbar ist.
- c. Kann man in Java nichts anfangen.
- d. Kann eine Klasse durch eine Unterklasse erweitert werden.

---

## Lösungen

1. **c. Neue Pflanze erstellt., Neue Blume erstellt**
2. **a. groesse, tiefWurzler**
3. **a. Überschrieben**
4. **b. someVar**
5. **a. Ich bin eine Blume**
6. **d. Kann eine Klasse durch eine Unterklasse erweitert werden**

