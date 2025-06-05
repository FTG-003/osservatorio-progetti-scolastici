# 🧭 Osservatorio Progetti Scolastici

Uno strumento open-source per supportare docenti e formatori nell'analisi e nella riflessione sui progetti scolastici attraverso dashboard interattive alimentate da dati reali o simulati.

> ✨ Questo progetto nasce da un'ispirazione condivisa grazie al post di [Valentino Grossi su LinkedIn](https://www.linkedin.com/posts/valentino-grossi_genai-dashboard-ai-activity-7336275737932435474-uot7?utm_source=share&utm_medium=member_desktop&rcm=ACoAAA8rfckBph_PCjm20n9kKZ9NAtcI7dK_DwI), durante una formazione sull'uso dell'AI nella didattica. Grazie per aver acceso la miccia!

## 🎯 Obiettivo

Fornire una base semplice ma efficace per:
- raccogliere feedback anonimo da parte degli studenti
- visualizzare i dati su più criteri (soddisfazione, chiarezza, utilità, consigliabilità)
- facilitare il confronto tra progetti
- attivare momenti di riflessione didattica tra colleghi

## 🛠️ Contenuto della repo

```
osservatorio-progetti-scolastici/
├── app/
│   └── dashboard.py            # codice principale della dashboard (es. in Streamlit)
├── data/
│   └── feedback_sample.csv     # template CSV con dati simulati da personalizzare
├── requirements.txt           # dipendenze da installare con pip
├── LICENSE                    # licenza MIT per uso e modifica liberi
└── README.md                  # questo file
```

## 🚀 Come iniziare

1. Clona la repo:
```bash
git clone https://github.com/tuo-utente/osservatorio-progetti-scolastici.git
```

2. Installa le dipendenze:
```bash
pip install -r requirements.txt
```

3. Avvia la dashboard:
```bash
streamlit run app/dashboard.py
```

## 👥 Per chi è pensato

- Insegnanti e formatori
- Coordinatori di dipartimento o referenti PCTO
- Scuole che vogliono attivare pratiche di valutazione partecipata

## 🔁 Adattabilità

- I dati sono anonimi e modificabili
- Il layout può essere personalizzato con altri grafici o criteri
- Si possono integrare strumenti AI per suggerimenti automatici o clustering

## ✨ Licenza

Questo progetto è rilasciato sotto **MIT License**, una licenza permissiva che consente il riutilizzo anche commerciale, a condizione che venga mantenuto l'attributo agli autori originali.

✅ Adatta per:
- progetti educativi condivisi
- remix e fork didattici
- uso in formazione e scuole pubbliche

🔗 [Scopri di più su choosealicense.com](https://choosealicense.com/licenses/mit/)
