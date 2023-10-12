**Schema-E-R-Biblioteca**
Analisi:
Una biblioteca deve gestire tutte le informazioni sui i volumi, utenti e prestiti.
Entità che vogliamo utilizzare:
1. Libro: codiceISBN, titolo, lingua, editore, annoDiPubblicazione, categoria;
2. Autore: nome, cognome, data, luogoDiNascita, biografia, idAutore;
3. Collocazione: sezione, numeroScaffale, numeroPosto;
4. Utente: nome, cognome, data, luogoDiNascita, numeroTessera;
5. Prestito: dataInizio, dataDiRiconsegna, idPrestito;
Esempio:
Bill prende in prestito un libro, e lo tiene per tre giorni. 
Schema ER:
