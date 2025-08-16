# UZOP-project
# 🧠 Early-Stage Alzheimer's Disease Prediction Using Machine Learning Models

Ovaj projekt je izrađen u sklopu kolegija **Uvod u znanost o podacima** i temelji se na repliciranju i proširivanju rezultata iz znanstvenog članka *“Early-Stage Alzheimer's Disease Prediction Using Machine Learning Models”*. Glavni cilj je izgraditi modele strojnog učenja za predikciju ranih stadija Alzheimerove bolesti na temelju kliničkih i demografskih podataka pacijenata.

## 🔍 Faza 1: Priprema i vizualizacija podataka

U ovoj fazi projekta cilj je bio:
- Učitati podatke iz dostupnog skupa i filtrirati ih na **prve posjete svakog pacijenta**
- Pozabaviti se s nedostajućim i stršećim vrijednostima
- Ispitati osnovne informacije o podacima (broj redaka, tipovi podataka, distribucije)
- Normalizirati vrijednosti i pripremiti podatke za analizu
- Vizualizirati podatke koristeći metode poput:
  - Korelacijske matrice
  - Scatter plotova za svaki par značajki (zasebno obojeni pacijenti s Alzheimerom i bez njega)
  - Box-plotova za usporedbu godina pacijenata

## 🧪 Faza 2: Replikacija i evaluacija modela

- Istrenirani su modeli korišteni u izvornom znanstvenom članku:
  - **Logistička regresija**
  - **Random Forest**
  - **SVM**
- Evaluacija je provedena pomoću klasičnih metrika:
  - Točnost, preciznost, F1-score
  - AUC/ROC krivulje
  - Konfuzijske matrice
- Rezultati su uspoređeni s onima iz originalnog rada

## 🚀 Faza 3: Poboljšanje rezultata

U trećoj fazi projekta cilj je bio unaprijediti rezultate prethodnih faza kroz:
- Testiranje novih modela: **XGBoost**, **LightGBM**, itd.
- Proširenje skupa značajki (npr. dodatna obrada CDR vrijednosti)
- Optimizaciju hiperparametara koristeći **GridSearchCV**
- Daljnju evaluaciju uz detaljnije usporedbe metrika i vizualizaciju rezultata
