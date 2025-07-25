# 🏁 RaceStrategyAI

**RaceStrategyAI** è un'applicazione intelligente che utilizza modelli di Machine Learning per prevedere la miglior strategia di gara e qualifica in un weekend di Formula 1, basandosi principalmente sui dati delle prove libere (FP1, FP2, FP3) e su dati storici stagionali di team e piloti.

## 🎯 Obiettivo

Fornire un supporto strategico predittivo e interattivo per appassionati, analisti e partecipanti a fantasy games F1, utilizzando dati pubblici e tecniche di analisi avanzata.

## 🔧 Funzionalità previste (MVP)
- Interfaccia grafica semplice per caricare o incollare dati delle FP
- Analisi dei long run e short run per valutare ritmo e degrado gomme
- Modello ML per suggerire strategia ottimale (gomme, pit stop, aggressività)
- Visualizzazioni interattive per confronto tra team e scenari

## 📊 Dati utilizzati
- Tempi delle libere (FP1–FP3)
- Posizione in classifica e punti stagione
- Storico prestazioni su circuiti simili
- (Futuro) Meteo e variabili esterne

## 🧠 Tecnologie
- Python / Streamlit (o PyQt / Flask)
- Pandas, Scikit-learn / XGBoost
- Matplotlib / Plotly
- (Opzionale) Web scraping/API per dati live

## 🚀 Roadmap
- [x] Parser per dati FP da CSV o HTML
- [ ] Strategia baseline tramite euristiche
- [ ] Modello ML supervisionato (test con dati storici)
- [ ] Simulatore interattivo “what if”
- [ ] Versione deployata come web app

## 🏎️ Credits
Un progetto sperimentale creato per esplorare l’applicazione del ML nel motorsport, a partire dalla prospettiva degli spettatori.

