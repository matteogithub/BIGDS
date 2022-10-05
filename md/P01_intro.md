---
marp: true
---

<!-- footer: M. Fraschini - Università degli Studi di Cagliari - AA 2022-2023 -->

<!-- paginate: true -->

<!-- size: 4:3 -->


# Introduzione a Python

Basi di informatica, gestione dati e statistica (BIGDS)

---

# Python 

- Python è uno dei *più diffusi* linguaggi di programmazione e ha una *curva di apprendimento* pressoché piatta. Enorme disponibilità di *librerie*: NumPy, Pandas, scikit-learn...

- Funzionale e orientato agli oggetti
- Consolidato nel tempo
- Semplice e versatile

---

# Download

https://www.python.org/downloads/

**Dipendenza dal SO**

---

# IDE – Integrated Development Enviroment

Windows (multipiattaforma)

- **pycharm**: https://www.jetbrains.com/pycharm/
- **wing**: http://wingware.com/downloads
- **spyder**: https://www.spyder-ide.org/

---

# Setup e primo programma

- Preferenze del IDE
- Creazione di un nuovo progetto

Primo programma: `print("Hello world")`

dove ```print``` rappresenta una funzione predefinita

- Ogni istruzione termina con un *a capo*
- Importanza della *indentazione*


---

# I commenti

```Python
# Il mio primo programma
print("Hello world")
```


---

# Variabili

Contenitori che posso *accogliere* al loro interno dei dati (*tipo e nome*)

**Esempio**:
`print("Matteo insegna Informatica")`
`print("Federica insegna Matematica")`

con le **variabili** e operatore di **assegnamento**:
```Python
char_nome = "Matteo"
char_materia = "Informatica"
print(char_nome + " insegna " + char_materia)
char_nome = "Federica"
char_materia = "Matematica"
print(char_nome + " insegna " + char_materia)
```

---

# Differenti tipo di dato

La definizione degli *oggetti* (variabili) ha come conseguenza l'assegnazione di uno specifico spazio in *memoria centrale*

**Stringa** ```"Matteo insegna Informatica"```

***Numeri*** 
```anni = 49```

***Boolean*** ```True``` o ```False```

---

# Le stringhe

```Python
frase = "Matteo insegna Informatica"
print(frase + " e Statistica")
```

---

# Le stringhe e funzioni

```Python
frase = "Matteo insegna Informatica"
print(frase.lower())
```

```Python
frase = "Matteo insegna Informatica"
print(frase.upper())
```

```Python
frase = "Matteo insegna Informatica"
print(frase.replace("Matteo", "Luca"))
```

---

# Le stringhe e funzioni

```Python
frase = "Matteo insegna Informatica"
print(len(frase))
```

```Python
frase = "Matteo insegna Informatica"
print(frase[0])
```
Python usa lo 0 come indice del primo elemento di una stringa

---

# Numeri

```Python
print(1)
print(1.234)
print(-1)
print(-1 + 1)
print(4 / 2)
print(4 % 3)
```

```Python
num = 3
print(num)
```

---

# Numeri e stringhe

```Python
frase = "Matteo insegna Informatica"
anni = 49
print(frase + " e ha " + str(anni) + " anni")
```

---

# Numeri e funzioni

```Python
num = -3
print(abs(num))
```

```Python
num = 3
print(pow(num, 2))
```

```Python
num = 3.3
print(round(num))
```

```Python
from math import *
num = 3.3
print(sqrt(num))
```
---

# Input da utente 

```input()```

```Python
nome = input("Inserisci il tuo nome: ")
print("Ciao " + nome + "!")
```
La variabile di nome input conterrà il nome inserito dall'utente

---

# Calcolatrice


```Python
num_1 = input("Inserisci un numero: ")
num_2 = input("Inserisci un altro numero: ")
risultato = int(num_1) + int(num_2)
print(risultato)
```
...ma attenzione!
```Python
num_1 = input("Inserisci un numero: ")
num_2 = input("Inserisci un altro numero: ")
risultato = float(num_1) + float(num_2)
print(risultato)
```

---


# Domande?

www.menti.com