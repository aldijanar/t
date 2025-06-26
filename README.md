Naravno! Evo odgovora na pitanja sa svih prikazanih zadataka, jasno i precizno objašnjenih:

---

### **Zadatak 1**

**a) Pretraživanje u širinu (BFS)**
BFS je algoritam koji istražuje sve susjede trenutnog čvora prije nego što pređe na njihove susjede.
**Primjer:** Traženje najkraćeg puta u labirintu – BFS prvo obiđe sve ćelije udaljene 1 korak, pa 2 koraka, itd.

**b) Pretraživanje u dubinu (DFS)**
DFS ide što dublje moguće u jednom pravcu prije nego što se vrati nazad i istraži drugi pravac.
**Primjer:** U istom labirintu, DFS ide pravo dok ne naiđe na zid, zatim se vraća i pokušava druge puteve.

**c) Perceptron**
Perceptron je osnovna jedinica neuronske mreže koja prima ulaze, množi ih sa težinama, sabira i primjenjuje aktivacijsku funkciju (npr. step funkciju).
**Princip rada:** Ako je suma veća od praga, izlaz je 1, u suprotnom 0.

**d) Backpropagation algoritam**
To je metoda učenja kod višeslojnih neuronskih mreža. Računa grešku na izlazu i propagira je unazad kroz mrežu da bi ažurirao težine koristeći gradijentni spust.

**e) Aktivacijske funkcije u neuronskim mrežama**
Omogućavaju nelinearnost mreži.
**Primjeri:**

* **Sigmoid**: $f(x) = \frac{1}{1 + e^{-x}}$, koristi se za vrijednosti između 0 i 1.
* **ReLU**: $f(x) = \max(0, x)$, koristi se zbog efikasnosti i rjeđe izaziva zasićenje.

---

### **Zadatak 3**

**a) Alfa presjek i jezgra fuzzy skupa**

* **Alfa presjek**: Sadrži sve članove fuzzy skupa čija je pripadnost veća ili jednaka od alfa vrijednosti (npr. 0.5).
* **Jezgra fuzzy skupa**: Sadrži sve elemente čija je vrijednost pripadnosti tačno 1.

**b) Primjena genetskih algoritama i adaptivnog fuzzy regulatora**

* **Genetski algoritmi**: Optimizuju rješenja problema (npr. raspored voznog parka).
* **Adaptivni fuzzy regulator**: Automatski podešava pravila fuzzy sistema prema podacima iz okoline (npr. automatsko grijanje prostorije).

**c) Šta je to fuzzy skup i lingvistička varijabla**

* **Fuzzy skup**: Skup sa neodređenim granicama pripadnosti (npr. “visok” čovjek).
* **Lingvistička varijabla**: Promjenjiva koja ima vrijednosti izražene riječima (npr. temperatura = {hladno, toplo, vruće}).
  **Primjer:** Mjerenje temperature – vrijednost 28°C može pripadati i skupu “toplo” i “vruće” sa različitim stepenom pripadnosti.

---

### **Zadatak 4**

**a) Faziﬁkacija, zaključivanje, kompozicija i defaziﬁkacija**

* **Faziﬁkacija**: Pretvaranje konkretnih ulaza u fuzzy vrijednosti.
* **Zaključivanje**: Primjena fuzzy pravila na fazifikovane ulaze.
* **Kompozicija**: Kombinacija više fuzzy pravila.
* **Defaziﬁkacija**: Pretvaranje fuzzy izlaza u stvarnu vrijednost.

**b) Fuzzy skup “brojevi oko 4”**
Definisati funkciju pripadnosti za U = {1, 2, ..., 8}, npr:

* 4: pripadnost 1
* 3 i 5: pripadnost 0.7
* 2 i 6: pripadnost 0.4
* 1 i 7: pripadnost 0.2
* 8: pripadnost 0

**c) Kardinalni broj fuzzy skupa**
Zbroj svih vrijednosti pripadnosti:
$K = 0.2 + 0.4 + 0.7 + 1 + 0.7 + 0.4 + 0.2 = 3.6$
Relativni kardinalni broj:
$3.6 / 8 = 0.45$

---

### **Zadatak 6**

**a) Podjela neuronskih mreža sa aspekta učenja**

* **Supervizirano**: Mreža uči na osnovu ulazno-izlaznih parova.
* **Nadzirano (unsupervised)**: Mreža sama otkriva strukturu podataka.
* **Pojačano (reinforcement)**: Uči na osnovu nagrade/kazne.

**b) Dimenzionalnost neuronskih mreža**
Broj ulaza, skrivenih slojeva i neurona u svakom sloju.

**c) Prenosna funkcija višeslojne linearne mreže**
Funkcija koja određuje izlaz svakog neurona (npr. ReLU, tanh). Linearna mreža bez nelinearnosti ne može riješiti nelinearne probleme.

**d) Genetička mutacija**
U genetskim algoritmima predstavlja promjenu (slučajnu) dijela rješenja.
**Glavne karakteristike:** varijabilnost, istraživanje rješenja, sprečava stagnaciju.

---

### **Zadatak 7**

**a) Oblici izvođenja zaključaka iz podataka**

* **Deduktivno**: Od općeg ka pojedinačnom
* **Induktivno**: Od konkretnih primjera ka općim pravilima
* **Abduktivno**: Zaključivanje najboljeg objašnjenja

**b) Visina fuzzy skupa i normalizacija**

* **Visina**: Najveća vrijednost funkcije pripadnosti.
* **Normalizacija**: Prilagođavanje skupa da visina bude 1.

**c) Fuzzy zaključivanje**
Primjena fuzzy pravila na fazifikovane ulaze da bi se dobio fuzzy izlaz.

**d) Agregacija fuzzy pravila**
Spajanje rezultata više pravila, npr. pomoću maksimuma, minimuma ili zbrajanja.

---

Ako želiš i skice ili grafikone za ove odgovore, mogu ih pripremiti posebno.
