# 🎉 PartyHub

**Organizza la festa perfetta, calcola la spesa senza stress.**

PartyHub è un'applicazione mobile e web sviluppata in **Flutter** pensata per rivoluzionare l'organizzazione di feste, cene ed eventi tra amici. Dimentica i fogli di calcolo infiniti e le chat intasate: PartyHub gestisce tutto, dalle preferenze alimentari al calcolo millimetrico della cassa comune.

## ✨ Core Features

* **🚪 Stanze Virtuali in Real-Time:** Crea una stanza per il tuo evento, condividi il codice a 6 cifre e gestisci gli invitati tramite una vera e propria "Lista d'Attesa" con permessi di admin. Tutto sincronizzato in tempo reale tramite Firebase.
* **📊 Sondaggi Intelligenti:** Fai votare agli invitati cosa vogliono mangiare o bere, organizzando le scelte tramite un sistema pulito a "Macro-Categorie" (Primi Piatti, Carne, Bevande, ecc.).
* **🧠 AI Engine & Bilanciamento Spesa:** Il vero motore dell'app. Un algoritmo matematico avanzato che calcola automaticamente la lista della spesa. Bilancia le porzioni in base ai pesi degli alimenti vincenti (es. se vince sia la costata che la salsiccia, scala automaticamente le dosi in modo proporzionale per non sprecare cibo) e previene errori matematici.
* **🥗 Gestione Intolleranze:** Un sistema sicuro e "KISS" (Keep It Simple) per tracciare le allergie degli invitati, tenendo la salute di tutti al primo posto.
* **🎨 UI/UX Moderna & "Bubbly":** Un'interfaccia utente curata nei minimi dettagli. Gradienti vibranti, componenti in *glassmorphism*, bordi ultra-arrotondati e una dashboard a matrice progettata per essere tanto bella quanto facile da usare. 
* **🌐 Network Awareness:** Un indicatore globale a comparsa che avvisa istantaneamente l'utente in caso di disconnessione dalla rete, prevenendo voti o azioni perse.

## 🛠️ Tech Stack
* **Framework:** [Flutter](https://flutter.dev/) (Android, iOS, Web)
* **Backend & Database:** Firebase Auth, Cloud Firestore (Real-time NoSQL)
* **Architettura:** Gestione dello stato tramite Stream e Provider, con un focus forte sulle *Security Rules* e la scalabilità NoSQL.
