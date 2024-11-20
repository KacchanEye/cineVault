# 🎬 CineVault   ##LAVORI IN CORSO##

**CineVault** è un'applicazione web che consente agli utenti di cercare film, visualizzarne i dettagli e scoprire informazioni principali come anno di uscita, poster e trama.  
È costruita con **React** e utilizza un'API per recuperare i dati sui film.

---

## 🚀 Funzionalità

- **Ricerca film**: Cerca film per titolo utilizzando un campo di input.
- **Elenco risultati**: Visualizza un elenco di film corrispondenti con poster, titolo e anno.
- **Dettagli film**: Mostra informazioni dettagliate su un film selezionato (es. trama, regista, cast).
- **Design responsive**: Ottimizzato per dispositivi desktop e mobile.

---

## 🛠️ Tecnologie utilizzate

### **Frontend**
- **React**
- **Axios** o **Fetch API** per le richieste API.
- **Tailwind CSS** per lo stile.

### **Backend/API**
- **The Movie Database (TMDb)**
---

## 📦 Installazione

Segui questi passaggi per configurare ed eseguire il progetto in locale:

1. **Clona il repository:**
   ```
   git clone https://github.com/KacchanEye/cineVault.git
   cd cineVault
   ```
2. **Installa le dipendenze:**
   ```
   npm install
   ```
3. **Configura l'API Key:**

    Registra un account su TMDb e ottieni una API Key.
    Crea un file .env nella root del progetto e aggiungi:
    ```
    REACT_APP_API_KEY=la_tua_api_key
    ```

 4. **Avvia l'applicazione:**
    ```
    npm start
    ```
 5. **Accedi all'app: Apri il browser e vai su http://localhost:3000.**

📂 Struttura del progetto
bash
Copia codice
src/
├── components/
│   ├── SearchBar.js        # Campo di input per la ricerca
│   ├── MovieList.js        # Elenco di film trovati
│   ├── MovieCard.js        # Card per ogni film con titolo e poster
│   └── MovieDetails.js     # Dettagli di un singolo film
├── api/
│   └── tmdb.js             # File per gestire le richieste API
├── App.js                  # Componente principale dell'app
├── styles/
│   └── App.css             # Stile globale dell'applicazione
└── index.js                # Punto di ingresso principale
🤝 Contributi
Contribuzioni, segnalazioni di bug e suggerimenti sono benvenuti!

Fai un fork del progetto.
Crea un nuovo branch:
```
git checkout -b feature/la-tua-feature
```
Effettua le modifiche e crea un commit:
```
git commit -m "Aggiunta della nuova funzionalità"
```
Fai un push sul tuo branch:
```
git push origin feature/la-tua-feature
```
Invia una Pull Request.

📃 Licenza
Questo progetto è distribuito sotto la licenza MIT. Consulta il file LICENSE per maggiori dettagli.

📧 Contatti
Se hai domande o suggerimenti, sentiti libero di contattarmi:

GitHub: https://github.com/KacchanEye
