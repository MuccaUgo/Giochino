# Il cortile di Giochino
Due giocatori online, una Principessa e un Cavaliere. Aprite lo stesso link. Toccate un ruolo libero e poi il terreno del cortile per muovervi. Esci libera il posto. Se si perde la connessione, il posto torna disponibile dopo 24 secondi dall’ultimo aggiornamento.

Il frontend è un file HTML autonomo. Il backend Supabase assegna i posti in una transazione e conserva le posizioni dei due personaggi. Il progetto dedicato è già configurato in duo/config.js con la sola chiave pubblica. Lo schema del database è in duo/roles.sql.

Per pubblicare su GitHub Pages, usa la radice del branch main come origine. index.html contiene il gioco pronto. Dopo le modifiche a duo esegui node scripts/build.mjs. Per verificare il contenuto pubblicabile, esegui npm test.
