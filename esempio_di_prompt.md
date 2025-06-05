# 💡 Prompt per generare la tua Dashboard AI con ChatGPT

Questo prompt ti permette di creare una dashboard interattiva in HTML a partire da un file CSV, con l’aiuto di un assistente AI come ChatGPT.
È ottimizzato per l’uso educativo e pensato per essere pubblicato su GitHub Pages senza necessità di backend.

---

## 🌟 Obiettivi del Prompt

* Creare una dashboard didattica in HTML + JavaScript
* Visualizzare dati da un questionario scolastico (es. valutazione progetti)
* Usare grafici interattivi per facilitare la riflessione educativa
* Generare codice statico compatibile con ambienti come GitHub Pages

---

## 🧪 Prompt consigliato (secondo le best practice OpenAI)

```
## Prompt: Esperto in Visualizzazione Dati Educativi e Sviluppo Frontend

**Ruolo:** Agisci come un esperto in visualizzazione dati educativi e sviluppo frontend con una profonda conoscenza di HTML, JavaScript, Chart.js e principi di accessibilità web.

**Obiettivo:** Creare un file HTML statico, autonomo e immediatamente utilizzabile per visualizzare in modo chiaro, interattivo e accessibile i risultati di un questionario scolastico. Questo file deve consentire agli educatori di analizzare facilmente i dati raccolti e identificare tendenze e aree di miglioramento nei progetti scolastici.

**Contesto:** Abbiamo un file CSV locale contenente i risultati di un questionario somministrato per valutare diversi progetti scolastici. Ogni riga del CSV rappresenta un progetto e include le seguenti colonne, con valori che variano da 1 a 5:

*   `Soddisfazione`: Valutazione della soddisfazione degli studenti per il progetto.
*   `Chiarezza`: Valutazione della chiarezza degli obiettivi e delle istruzioni del progetto.
*   `Utilità pratica`: Valutazione dell'utilità pratica del progetto per la vita degli studenti.
*   `Raccomandazione`: Valutazione della probabilità che gli studenti raccomandino il progetto ad altri.

**Compiti:**

1.  **Caricamento Dati:** Implementare una soluzione JavaScript per caricare e parsare *automaticamente* il file CSV *locale* (senza richiedere all'utente di selezionarlo tramite un input file). Idealmente, il file CSV sarà incluso nella stessa cartella del file HTML o specificato tramite un percorso relativo. Gestire eventuali errori durante il caricamento e il parsing del CSV.

2.  **Calcolo Medie:** Calcolare la media dei punteggi per *ciascuna metrica* (Soddisfazione, Chiarezza, Utilità Pratica, Raccomandazione) attraverso *tutti i progetti*.

3.  **Tabella Riassuntiva:** Generare una tabella HTML ben formattata che mostri:
    *   Il nome di ciascun progetto (assumendo che la prima colonna del CSV contenga il nome del progetto).
    *   La media dei punteggi calcolata per ciascuna metrica per quel progetto.
    *   Un totale medio complessivo per ciascun progetto.
    *   Assicurarsi che la tabella sia semanticamente corretta (usando tag `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`) e stilizzata in modo chiaro e leggibile.

4.  **Visualizzazione Grafica (Chart.js):** Utilizzare la libreria Chart.js per creare visualizzazioni grafiche interattive dei dati. Includere *almeno quattro* dei seguenti tipi di grafici, scegliendo quelli più adatti a rappresentare i dati in modo efficace:
    *   **Grafico a barre:** Per confrontare le medie delle diverse metriche tra i vari progetti.
    *   **Grafico radar:** Per visualizzare i punti di forza e di debolezza di ciascun progetto su tutte le metriche.
    *   **Grafico a torta:** (Se appropriato) per mostrare la distribuzione dei punteggi all'interno di una singola metrica.
    *   **Grafico a boxplot o a linee:** (Se appropriato) per mostrare la distribuzione e la variabilità dei punteggi per ogni metrica.
    *   **Considerare l'uso di grafici combinati** per presentare i dati in maniera più completa e intuitiva.
    *   Ogni grafico deve essere corredato di titoli, etichette e legenda chiare.

5.  **HTML Statico:** Il risultato finale deve essere *un singolo file HTML*, completamente autonomo. Non deve richiedere server-side scripting o database. Tutte le risorse (JavaScript, CSS, immagini - se necessarie) devono essere incluse direttamente nel file HTML (inline) o caricate da CDN.

6.  **Accessibilità:** Il design deve essere *accessibile* a utenti con disabilità. Ciò include:
    *   Utilizzo di markup HTML semantico.
    *   Fornitura di testo alternativo per le immagini.
    *   Assicurarsi che il contrasto dei colori sia sufficiente.
    *   Considerare l'uso di ARIA attributes ove necessario.
    *   Garantire che la pagina sia navigabile tramite tastiera.

7.  **Responsività:** Il layout deve essere *responsivo* e adattarsi a diverse dimensioni di schermo (desktop, tablet, mobile). Utilizzare media queries CSS per ottimizzare la visualizzazione su diversi dispositivi.

8.  **Estetica Adatta:** Il design visivo deve essere pulito, professionale e *adatto a un ambiente scolastico*. Scegliere colori e font appropriati e utilizzare uno stile coerente in tutta la pagina. Evitare elementi di distrazione.

9. **Commenti e Documentazione:** Il codice deve essere ben commentato e facilmente comprensibile. Spiegare le scelte di implementazione e fornire istruzioni su come modificare o estendere il codice.

**Output desiderato:** Un singolo file `risultati.html` contenente tutto il codice HTML, CSS e JavaScript necessario per implementare le funzionalità sopra descritte.

**Considerazioni aggiuntive:**

*   Assumi che il file CSV sia denominato `dati.csv` e si trovi nella stessa cartella del file HTML. Se necessario, spiega come modificare il codice per specificare un percorso diverso.
*   Privilegia la chiarezza e la leggibilità del codice rispetto alla brevità.
*   Utilizza le funzionalità più recenti di HTML, CSS e JavaScript, ma assicurati che il codice sia compatibile con browser moderni.
*   Sii creativo e proattivo nella scelta delle visualizzazioni grafiche più efficaci.

---

## ✏️ Adattalo al tuo contesto

* Modifica i criteri di valutazione in base al tuo progetto
* Aggiungi colonne nel CSV (es. "note libere", "classe", "insegnante")
* Chiedi all’AI varianti: dark mode, esportazione PDF, filtri per classe

---

## 🔎 Esempio reale di implementazione

* 🔗 [Live Demo su GitHub Pages](https://ftg-003.github.io/osservatorio-progetti-scolastici/)
* 📁 [Codice completo su GitHub](https://github.com/FTG-003/osservatorio-progetti-scolastici)

Questa dashboard è stata generata a partire dal prompt sopra, poi rifinita e collegata a dati reali/simulati.

---

## 🤝 Condividi la tua versione!

Hai remixato o migliorato questa dashboard?
Apri una pull request o tagga il progetto: ci interessa far crescere una rete di pratiche open nella scuola!

---

*Creato da [@FTG-003](https://github.com/FTG-003) con il supporto di Gino AI. Contribuiamo insieme a una scuola più aperta, dati-driven e accessibile.*

