# Einfache eingebaute Datentypen:
## 1. **int**
- kann eine beliebige Größe haben
- kann positiv oder negativ sein
- man weist einfach eine ganze Zahl einer Variablen zu, z.B.: i = 1000

**Funktionen:**
- nach int wandeln: int("10")
- +, -, *, /, // (ganzzahlige Divison), % (Divisonsrest) , ** (potenzieren)

## 2. float
- kann ebenfalls eine beliebige Größe haben
- Zuweisung per Zahl mit Punkt: f = 1000.0

**Funktionen:**
- nach float wandeln: float("10")
- alle Operatoren wie bei int
- round(f,n) n Anzahl der Nachkommastellen

## 3. string
- kann beliebige Länge haben
- wird per Doppel-Quotes oder Single-Quotes geschrieben: s = "Ein String", s = 'Ein String'
- mehrzeilige Strings mit 3 Single Quotes möglich

**Funktionen:**
- nach String wandeln: str(100)
- aneinanderhängen von Strings: a= "String1 " + "String2"
- str.format() "Dies ist die {}. Zahl".format(10)
- str.isalnum(), str.isalpha(), str.isdigit(), 
- str.islower(), str.isupper() -> str.lower(), str.upper()
- str.strip() remove Whitespace
- str.split(), str.splitlines() aufteilen am Zeichen/Zeilenende 
- str.startswidth("text") string startet mit "text"
