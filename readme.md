# Boolzapp

Andiamo a realizzare la versione Web di una nota applicazione

# Milestone 1

-Inizio a creare una struttura Html+Css
-Creiamo un ciclo v-for in Html con all'interno le informazioni (avatar, nome) e le inseriamo nell'aside

# Milestone 2

-inseriamo nell'header dell'utente selezionato il nome e la foto che lo contraddistinguono.
-inseriamo i vari messaggi dall'array contacts all'interno dei due contenitori (messaggio inviato e messaggio ricevuto)
-creiamo un evento che al click di un contatto dell'aside verranno mostrati i diversi messaggi a destra nel contenitore (inviati e ricevuti)

# Milestone 3

-facciamo in modo che scrivendo un messaggio nell'input send-msg venga aggiunto all'array contacts tramite la creazione di un evento che gli pusherà il nuovo messaggio. Creo anche una funzione con setTimeout per la risposta.
-il messaggio comparirà verde (inviato) o bianco (ricevuto) tramite lo status (received, sent)

# Milestone 4

-Creiamo una funzione che andremo ad inserire all'interno di un evento. Questa funzione dovrà filtrare i vari nomi dall'array contacts e ritornarli in base a quanto scritto altrimenti non comparirà nulla.