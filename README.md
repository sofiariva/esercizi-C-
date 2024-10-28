1
Scrivere un programma che richiede all'utente di riempire una matrice 3 x 3 di interi e la stampa. Il programma modifica la matrice, sostituendo ogni numero pari con la sua metà. Infine, stampa la matrice così modificata.
2
Scrivere un programma che genera una matrice 3x3 inserendo dei numeri progressivi in ogni cella (in figura, a sinistra), la stampa e poi la trasforma in una matrice triangolare superiore (in figura, a destra) avente come elementi le somme degli elementi simmetrici rispetto alla diagonale principale.
3
Scrivere un programma che, partendo da una matrice di interi M e due interi h e k, restituisce il numero di sottomatrici di M di dimensione h x h contenenti esattamente k valori uguali ad 1.
Il file C di partenza è scaricabile da qui:
https://www.dropbox.com/s/xj2zf8axfixw3cn/20210219.c?dl=0
4
Si scriva un programma che, data una matrice M quadrata NxN di interi e due indici di posizione r e c che rappresentano, rispettivamente, una riga e una colonna della matrice, stampa "OK" se tutti gli elementi posizionati sulla stessa riga o sulla stessa colonna dell’elemento in (r, c) sono minori dell'elemento in (r, c), "NON OK" altrimenti.
Si completi quindi il main sottostante come da esempi riportati
M:
1 12 0 7
4  3  5 5
6  4  3 8
7  5  2 4
con r = 2, c = 3 stampa "OK"
con r = 0, c = 2 stampa "NON OK"
con r = 1, c = 1 stampa "NON OK"
link al file C: 
https://www.dropbox.com/s/xgjgf9a0vwf2ugj/20210622.c?dl=0
5
Si scriva un programma che costruisce una matrice di interi e stampa il massimo K per cui è vero che la matrice contiene almeno un quadrato KxK di caselle di valore identico.
Link al file C:
https://www.dropbox.com/s/bjvcrfms04klqwf/20210722.c?dl=0
6
Si scriva un programma che costruisce una matrice di caratteri generati casualmente e stampa il carattere presente più volte nella matrice.
7
Scrivere un programma in C che generi una matrice NxN di elementi casuali. Il programma riordina le righe della matrice facendo in modo che la somma degli elementi in ciascuna riga sia maggiore (o uguale) alla somma degli elementi nella riga successiva.
8
Si consideri una struttura che rappresenta oggetti di tipo Film, caratterizzata da un anno di pubblicazione, un genere, ed un voto medio tra 0 e 10 (potrebbe non essere intero).
typedef struct{
      int anno;
      char genere[L];
      float voto;
} Film;
Si consideri inoltre una struttura di tipo SalaCinema, caratterizzata da una lista di film, dal numero di film in sala e dal prezzo di un biglietto.
typedef struct{
      Film films[N];
      int numero_film_in_sala;
      float prezzo_biglietto;
} SalaCinema;
Si scriva un programma in C che:
legge il numero di film presenti nella sala cinema
riempie l'array di film della sala cinema con tutte le informazioni necessarie
calcola il ricavo stimato della sala cinema sapendo che il numero di persone che vedranno ciascun film dipende dal suo voto (es. voto 5.7, 570 persone previste)
9
Si crei una struttura Persona che contiene le informazioni di base di una persona: nome, cognome, anno di nascita.
Si consideri ora una struttura ListaInvitati che contiene una lista di nomi ed il numero massimo di persone che possono partecipare ad una festa
typedef struct{
      char nomi_invitati[N][L];
      int numero_invitati;
      int numero_partecipanti;
} ListaInvitati;
Si scriva un programma in C che:
legge il numero di invitati
legge il nome degli invitati
legge le informazioni di M persone che si sono presentate alla festa (con M definito in una #define)
scorre la lista di persone contando quante di queste sono invitate e tenendo traccia del numero di partecipanti
10
Scrivere un programma che USANDO DEI PUNTATORI individua gli elementi minimo e massimo di un array di interi.
0 commit comments
Comments
0
 (0)
Comment
You're receiving notifications because you're subscribed to this thread.
