# Libro

ATTRIBUTI:
titolo: String  Titolo del libro
numeroPagine: int Numero totale di pagine, valore strettamente positivo (> 0).
paginaCorrente: int Pagina attuale, vale 0 a libro chiuso; varia tra 1 e numeroPagine a libro aperto.
prezzo: double Prezzo di copertina espresso in euro, deve essere ≥ 0.0.
aperto: boolean Stato del libro, vale true se il libro è aperto, false se è chiuso.

METODI:
libro(titolo, numeroPagine, prezzo) Metodo costruttore, inizializza il libro con i valori ricevuti
getTitolo() : String  Restituisce il titolo.
getNumeroPagine() : int Restituisce le pagine totali.
getPaginaCorrente() : int Restituisce la pagina attuale.
getPrezzo() : double  Restituisce il prezzo corrente.
isAperto() : boolean  Restituisce true se aperto.
setPrezzo(nuovoPrezzo) : void  Aggiorna il prezzo se ≥ 0.
apri() : boolean Apre il libro
chiudi() : boolean Chiude il libron
paginaSuccessiva() Porta alla pagina successiva



