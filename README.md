# 📊 Metode istraživanja masovne komunikacije

> **Sveobuhvatan udžbenik statistike za društvene znanosti s primjerima iz hrvatskih medija**

---

## 📖 O projektu

Ovo je kompletan hrvatski udžbenik statistike dizajniran specifično za studente masovne komunikacije, novinarstva i medijskih studija. Knjiga koristi **realne primjere iz hrvatskog medijskog prostora** (HRT, Nova TV, Index.hr, Večernji.hr, Instagram, Facebook) kako bi apstraktne statističke koncepte učinila pristupačnima i relevantnima.

**Trenutno:** ~19,000 riječi | 3 poglavlja | Quarto format s R vizualizacijama

---

## 📚 Sadržaj

### [📄 Poglavlje 2: Deskriptivna statistika](./Deskriptivna_statistika.qmd)
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

### [📄 Poglavlje 3: Osnove statističkog zaključivanja](./Osnove_statistickog_zakljucivanja.qmd)
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

### [📄 Poglavlje 4: Statistički testovi u praksi](./Statisticki_testovi_u_praksi.qmd)
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

## 🎯 Buduća poglavlja

Knjiga je u aktivnom razvoju. Planirana su sljedeća poglavlja:

- [ ] **Poglavlje 5:** Napredna regresija i moderacija
- [ ] **Poglavlje 6:** Logistička regresija za binarne ishode
- [ ] **Poglavlje 7:** Analiza vremenskih serija
- [ ] **Poglavlje 8:** Faktorska analiza
- [ ] **Poglavlje 9:** Uvod u Bayesian statistiku

---

## 🎨 Ključne značajke

### ✅ **Quarto format**
Sva poglavlja u .qmd formatu s podrškom za HTML, PDF i DOCX izlaz

### ✅ **Crno-bijeli grafovi**
Profesionalni grafovi optimizirani za ispis i akademske publikacije

### ✅ **Skriven R kod**
Kod je skriven u izlaznim dokumentima (`echo: false`) za čitljivost

### ✅ **Hrvatski primjeri**
- 📺 HRT Dnevnik gledanost
- 📰 Index.hr engagement metrics
- 📱 Instagram influencer analytics
- 🎬 Nova TV prime time ratings
- 💬 Facebook dijeljenje sadržaja

### ✅ **Akademski stil**
- Formalna proza bez bullet pointa u glavnom tekstu
- LaTeX formule za sve statističke koncepte
- Tablice s konvencijama interpretacije

---

## 🚀 Kako koristiti

### Preduvjeti

```r
# Instalacija potrebnih paketa
install.packages(c("ggplot2", "dplyr", "scales"))
```

### Renderiranje poglavlja

```bash
# Renderiranje svih formata (HTML + PDF + DOCX)
quarto render Deskriptivna_statistika.qmd

# Samo HTML
quarto render Deskriptivna_statistika.qmd --to html

# Samo PDF
quarto render Deskriptivna_statistika.qmd --to pdf
```

### Napomena za PDF

PDF format koristi `babel-lang: english` zbog kompatibilnosti s TinyTeX. Hrvatski tekst renderira se ispravno.

---

## 📊 Statistika projekta

| Metrika | Vrijednost |
|:--------|:-----------|
| **Ukupno riječi** | ~19,000 |
| **Broj poglavlja** | 3 (u razvoju) |
| **Grafova** | 20+ |
| **Formule (LaTeX)** | 30+ |
| **Primjeri iz hrvatskih medija** | 40+ |

---

## 📁 Struktura datoteka

```
📦 Metodologija-za-komunikologe/
│
├── 📄 Deskriptivna_statistika.qmd           (~6,750 riječi)
├── 📄 Osnove_statistickog_zakljucivanja.qmd (~5,700 riječi)
├── 📄 Statisticki_testovi_u_praksi.qmd      (~6,500 riječi)
│
├── 📘 README.md                             (ovaj dokument)
│
└── 📁 [buduća poglavlja...]
```

---

## 🎓 Za koga je ova knjiga?

- **Studenti** – Masovne komunikacije, novinarstvo, PR, medijski studiji
- **Istraživači** – Medijska analiza, audience research
- **Praktičari** – Data-driven novinarstvo, media analytics
- **Nastavnici** – Kompletan nastavni materijal

---

## 🎯 Pedagoški pristup

Svaka sekcija slijedi strukturu:

1. **📖 Motivacija** – Zašto nam treba ovaj koncept?
2. **🔬 Formalizacija** – Matematička definicija i formula
3. **📊 Primjer** – Primjena na hrvatskim medijskim podacima
4. **✨ Interpretacija** – Što brojke znače u praksi?

---

## 🌟 Najvažnija lekcija

> **Statistička značajnost ≠ Praktična značajnost**
> 
> Uvijek izvještavajte:
> - Deskriptivne statistike (M, SD, N)
> - Testnu statistiku i p-vrijednost
> - Veličinu efekta (d, η², V, r)
> - Intervale pouzdanosti
> - **Kontekst** – što brojke znače u stvarnom svijetu

---

## 📝 YAML konfiguracija za poglavlja

Sva poglavlja koriste standardiziranu konfiguraciju:

```yaml
---
title: "Naslov poglavlja"
format:
  html:
    toc: true
    format-links: [pdf, docx]
  pdf:
    babel-lang: english
    geometry: margin=2.5cm
  docx:
    toc: true
lang: hr
execute:
  echo: false
---
```

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
