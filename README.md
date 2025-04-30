# Facultate: Exerciții Java

Acest depozit conține toate exercițiile și temele realizate în cadrul cursurilor de **Programare Java** la facultate: laboratoare, teme practice și proiecte de semestru.

---

## 📂 Structura proiectului

```
/facultate
├─ lab2/          # Laborator 2: Clase și Obiecte
│   ├─ app1Lab1/  # Exemplul 1: clasa Car
│   └─ lab1app2/  # Exemplul 2: clasa Student
│
├─ lab5-6/        # Laboratoarele 5-6: Colecții și Generics
│
├─ lab7/          # Laborator 7: Moștenire și Polimorfism
│
├─ lab9-10/       # Laboratoarele 9-10: I/O și Excepții
│
├─ ex/            # Exerciții adiționale (recursivitate, algoritmi)
├─ ex6/           # Exercițiul 6: GUI simplu și Structuri de date
├─ SafeAlert/     # Proiect semestru: Aplicație de alertare
│
├─ TP1.pdf        # Tema Practică 1 (enunț și cerințe)
├─ TP2.pdf        # Tema Practică 2 (enunț și cerințe)
└─ README.md      # Documentația proiectului
```

> **Notă:** Fiecare folder conține fișiere `.java` și, după caz, resurse adiționale (configurații, fișiere de date, etc.).

---

## 🛠️ Tehnologii și Unelte

- **Java SE 8 / 11**
- Compilare & rulare cu `javac` și `java` din JDK
- (Opțional) Import ca proiect **Maven** / **Gradle** în IntelliJ IDEA sau Eclipse
- Swing (pentru interfață grafică în ex6 și SafeAlert)

---

## 🚀 Instrucțiuni de rulare

Pentru orice laborator sau exercițiu Java:

```bash
# 1. Navighează în directorul exercițiului
cd <folder>

# 2. Creează (dacă nu există) directorul de output
mkdir -p bin

# 3. Compilează fișierele .java
javac -d bin src/*.java
# Dacă sursele sunt direct în folder:
# javac -d bin *.java

# 4. Rulează clasa principală
java -cp bin <pachet>.MainClass
```

> **Sugestie:** Pentru mai multă rapiditate, importă proiectul în IDE-ul preferat și rulează din interfața grafică.

---

## 📖 Descrieri detaliate pe laborator

### lab2/ – Clase și Obiecte
- **Obiective:** Definirea claselor, a membrilor (atribute și metode), folosirea constructorilor și a suprasarcinii (overloading) și a modificatorilor de acces.
- **Exemple:** `Car` (viteza, accelerează), `Student` (nume, medie) și utilizarea lor în metoda `main`.

### lab5-6/ – Colecții și Generics
- **Obiective:** Familiarizarea cu `List`, `Set`, `Map` din `java.util`.
- **Generics:** Siguranța tipurilor la compile-time.
- **Lambda & funcționale:** `Predicate`, `Function`, expresii lambda pentru filtrări și transformări.

### lab7/ – Moștenire și Polimorfism
- **Obiective:** Crearea ierarhiilor de clase (superclass & subclass), folosirea `abstract` și a interfețelor.
- **Polimorfism dinamic:** Override de metode și apeluri la metodele părinte (`super`).
- **Model:** `Animal` cu clase derivate `Dog`, `Cat`.

### lab9-10/ – I/O și Excepții
- **I/O:** Citire și scriere în fișiere text folosind `FileReader`, `FileWriter`, `BufferedReader`.
- **Excepții:** Tratarea cu `try-catch-finally`, definirea excepțiilor personalizate (extind `Exception`).
- **Exerciții:** Parsarea CSV și raportarea erorilor de format.

### ex/ – Exerciții adiționale
- **Recursivitate:** Factorial, Fibonacci.
- **Algoritmi:** Căutare binară, sortări (bule, selecție).
- **Structuri date:** Implementarea manuală a `Stack` și `Queue`.

### ex6/ – GUI Simplu și Structuri de date
- **Swing UI:** `JFrame`, `JPanel`, `JButton`, `JTextField`.
- **Layout Managers:** `BorderLayout`, `GridLayout`.
- **MVC simplificat:** Separarea logicii de business de interfață.

### SafeAlert/ – Proiect Semestru
- **Scop:** Aplicație de alertare a utilizatorului (ex. alarmă, notificări la condiții).
- **Persistență:** Serializare de obiecte sau fișiere CSV.
- **Design Patterns:** Singleton pentru managerul de alertă.
- **Componente:** Formulare complexe, validări și generare de evenimente.

---

## 🤝 Contribuții

Contribuțiile sunt binevenite!  
- Pentru bug reports și sugestii, deschide un **Issue**.  
- Pentru noi exerciții sau optimizări, trimite un **Pull Request**.

---

## 📄 Licență

Distribuit sub licența **MIT**. Vezi [LICENSE](LICENSE) pentru textul complet.

---

*Document actualizat de Vladislav Manole*

