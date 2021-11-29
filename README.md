lista delle indicazione chat-tpsit


-FINE DELLE STRINGHE DI COMUNICAZIONE= ”/n”

SERVER= si accende e rimane in attesa sulla porta 6789  ip 10.22.9.5;
CLIENT= accensione dei client;
CLIENT=  inizializzare inserendo il nome nome del client;
SERVER= immagazzina il nome e fa controllo di esso(Non ci possono essere due nomi uguali) ;
SERVER= collega i due client glielo fa notare inviando un messaggio di collegamento effettuato e rimane in attesa della comunicazione;
CLIENT= riceve il collegamento e inizia a chattare
SERVER= Controllo nel caso in cui ci sia solo un client(impossibile avviare una chat);
CLIENT=in caso volesse chiudere la chat “CHIUDI/n”
CLIENT=input stringa da inoltrare;
SERVER=controlli dei nomi tramite FOR, invio messaggio ai client con il nome diverso dal client mittente;
messaggi che iniziano con “P: username:messaggio” privato, “A:messaggio”tutti
