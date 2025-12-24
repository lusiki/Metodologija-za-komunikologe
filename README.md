# 📊 Metode istraživanja masovne komunikacije

> **Sveobuhvatan udžbenik statistike za društvene znanosti s primjerima iz hrvatskih medija**

---

## 📖 O projektu

Ovo je kompletan hrvatski udžbenik statistike dizajniran specifično za studente masovne komunikacije, novinarstva i medijskih studija. Knjiga koristi **realne primjere iz hrvatskog medijskog prostora** (HRT, Nova TV, Index.hr, Večernji.hr, Instagram, Facebook) kako bi apstraktne statističke koncepte učinila pristupačnima i relevantnima.

**Trenutno:** ~19,000 riječi | 3 poglavlja | Quarto format s R vizualizacijama

---

## 📚 Sadržaj

### [📄 Poglavlje 2: Deskriptivna statistika](https://raw.githack.com/lusiki/Metodologija-za-komunikologe/main/Deskriptivna%20statistika.html)
**~6,750 riječi**

Temeljno poglavlje koje pokriva sve ključne koncepte deskriptivne statistike kroz primjere iz hrvatskih medija.

- **Mjere centralne tendencije**
  - Aritmetička sredina, medijana, modus
  - HRT Dnevnik gledanost, Index.hr komentari
  - Kada koristiti koju mjeru

- **Mjere disperzije**
  - Raspon, interkvartilni raspon, varijanca, standardna devijacija
  - HRT Player outlier analiza, RTL teme
  - Vizualizacija varijabilnosti (box plotovi)

- **Standardizacija i Z-rezultati**
  - Empirijsko pravilo (68-95-99.7)
  - Usporedba različitih mjernih skala
  - Detekcija outliera

- **Korelacije**
  - Pearsonov koeficijent korelacije
  - Primjeri pozitivne, negativne i nulte korelacije
  - Korelacija ≠ uzročnost

---

### [📄 Poglavlje 3: Osnove statističkog zaključivanja](https://raw.githack.com/lusiki/Metodologija-za-komunikologe/main/Osnove%20statisti%C4%8Dkog%20zaklju%C4%8Divanja.html)
**~5,700 riječi**

Poglavlje koje gradi most između uzorka i populacije – temelj inferencijalne statistike.

- **Od uzorka do populacije**
  - Normalna distribucija i njene karakteristike
  - Empirijsko pravilo za normalnu distribuciju
  - Index.hr vrijeme čitanja

- **Centralni granični teorem**
  - Uzorkovna distribucija prosjeka
  - Tri ključna rezultata CGT-a
  - HRT satisfakcija gledatelja

- **Standardna pogreška**
  - Razlika između SD i SE
  - Intervali pouzdanosti (95% CI)
  - Večernji.hr broj komentara

- **Uvod u testiranje hipoteza**
  - Nulta vs. alternativna hipoteza
  - Logika statističkog testa
  - P-vrijednost i razina značajnosti

---

### [📄 Poglavlje 4: Statistički testovi u praksi](https://raw.githack.com/lusiki/Metodologija-za-komunikologe/main/Statisticki%20testovi.html)
**~6,500 riječi**

Praktična primjena statističkih testova s detaljnim primjerima i interpretacijama.

- **T-test i ANOVA**
  - Jedan-uzorkovni t-test (Nova TV vrijeme gledanja)
  - Nezavisni t-test (senzacionalni vs. informativni naslovi)
  - Zavisni t-test (fact-check kredibilitet)
  - ANOVA za usporedbu više grupa (HRT/Nova TV/Index.hr/Facebook)
  - Post-hoc testovi (Tukey HSD)
  - Cohenov d i η² veličine efekta

- **Hi-kvadrat i korelacije**
  - Hi-kvadrat test nezavisnosti
  - Kontingencijske tablice (platforma × tip sadržaja)
  - Cramér's V veličina efekta
  - Pearsonova korelacija (Instagram influenceri)

- **Regresija i interpretacija**
  - Jednostavna linearna regresija
  - Višestruka regresija (HRT gledanost)
  - R² i interpretacija koeficijenata
  - Statistička vs. praktična značajnost


---
### [📄 Poglavlje 5: Računalna analiza teksta](https://raw.githack.com/lusiki/Metodologija-za-komunikologe/main/Racunalna%20analiza%20teksta.html)
**~14,000 riječi**
Sveobuhvatni pregled računalne analize teksta u istraživanju masovne komunikacije.
- **Priprema podataka**
  - Tokenizacija i strategije raščlambe
  - Stemizacija vs. lematizacija
  - Izazovi hrvatskog jezika (morfologija, slobodan redoslijed)
- **Reprezentacija teksta**
  - Bag-of-Words i matrica dokument-termin
  - TF-IDF (formule i interpretacija)
  - Matrica supojavljivanja
- **Pristupi analizi**
  - Nadzirano učenje (Accuracy, Precision, Recall, F1)
  - Tematsko modeliranje LDA (Dirichlet distribucije)
  - Analiza sentimenta i ekstrakcija entiteta NER
- **Diskurzivna analiza**
  - N-grami i kolokacije (PMI, t-score)
  - Analiza okvira (Entmanova definicija framinga)
  - Mreže riječi (betweenness centrality)
  
  
---
### [📄 Poglavlje 6: Mrežna analiza](https://raw.githack.com/lusiki/Metodologija-za-komunikologe/main/Racunalna%20analiza%20teksta.html)
**~XX,000 riječi**

1. **Uvod: Relacijska perspektiva**
   1.1 Promjena paradigme (atributi vs. relacije)
   1.2 Temeljni koncepti (Čvorovi i Veze)
   1.3 Povijesni razvoj (Moreno, Milgram, Barabási)
2. **Osnovni elementi i vrste mreža**
   2.1 Usmjerenost (Directed vs. Undirected)
   2.2 Težina veze (Weighted vs. Binary)
   2.3 Matrični prikaz (Adjacency Matrix)
3. **Mjere centralnosti**
   3.1 Stupanj centralnosti (Degree - In/Out)
   3.2 Međuposredovanje (Betweenness - Gatekeepers)
   3.3 Bliskost (Closeness - Efficiency)
   3.4 Svojstvena vektorska centralnost (Eigenvector - PageRank logic)
4. **Struktura mreže na makro razini**
   4.1 Gustoća (Density)
   4.2 Fenomen malog svijeta (Small World)
   4.3 Mreže bez skale (Scale-Free / Power Law)
5. **Grupe, klasteri i zajednice**
   5.1 Klike
   5.2 Homofilija (Birds of a feather)
   5.3 Modularnost i detekcija zajednica (Louvain)
   5.4 Strukturne rupe (Burt)
6. **Vizualizacija mreža**
   6.1 Algoritmi rasporeda (Force-directed)
   6.2 Problem "dlakave lopte" (Hairball effect)
   6.3 Alati (Gephi, UCINET)
7. **Metodološki problemi i ograničenja**
   7.1 Problem granica
   7.2 Nedostajući podaci
   7.3 Etički izazovi (Anonimizacija)

---







---







## 🎯 Buduća poglavlja

Knjiga je u aktivnom razvoju. Planirana su sljedeća poglavlja:

- [ ] **Poglavlje 5:** Napredna regresija i moderacija
- [ ] **Poglavlje 6:** Logistička regresija za binarne ishode
- [ ] **Poglavlje 7:** Analiza vremenskih serija
- [ ] **Poglavlje 8:** Faktorska analiza
- [ ] **Poglavlje 9:** Uvod u Bayesian statistiku


---

## 🎓 Za koga je ova knjiga?

- **Studenti** – Masovne komunikacije, novinarstvo, PR, medijski studiji
- **Istraživači** – Medijska analiza, audience research
- **Praktičari** – Data-driven novinarstvo, media analytics
- **Nastavnici** – Kompletan nastavni materijal



---

## 📄 Licenca

Ovaj materijal je namijenjen obrazovnim svrhama.

---

**Zadnje ažurirano:** Prosinac 2024  
**Verzija:** 2.0  
**Status:** 🚧 U aktivnom razvoju

---

<div align="center">

### 🎓 Sretan studij statistike! 📊

*"The best thing about being a statistician is that you get to play in everyone's backyard."*  
— John Tukey

</div>
