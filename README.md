# Gestionale Back-end per Concessionaria di Automobili

Questo progetto è un sistema di gestione back-end sviluppato per un sito web di una concessionaria di automobili, progettato per gestire sia automobili nuove che usate. Il sistema fornisce funzionalità avanzate per la gestione del inventario.

## Tecnologie Utilizzate

- **PHP**
- **Laravel**
- **HTML**
- **SCSS**

## Funzionalità Principali

- Gestione dell'inventario: Aggiunta, modifica e eliminazione di automobili nel database, inclusi dettagli come modello, anno di produzione, prezzo e altro ancora.

## Installazione e Configurazione

1. Clona il repository sul tuo sistema locale.
2. Assicurati di avere PHP e Composer installati sul tuo sistema.
3. Esegui `composer install` per installare le dipendenze del progetto.
4. Copia il file `.env.example` in un nuovo file chiamato `.env` e imposta le variabili d'ambiente necessarie come il database e le credenziali SMTP.
5. Esegui `php artisan key:generate` per generare la chiave dell'applicazione.
6. Esegui `php artisan migrate` per eseguire le migrazioni del database.
7. Avvia il server locale utilizzando `php artisan serve`.
8. Accedi al sistema tramite il tuo browser all'indirizzo `http://localhost:8000`.
