# DemoSuggestHTML_JS
Demo html/js per l'utilizzo del servizio SUGGEST e SUGGESTFREE di autocompletamento degli indirizzi italiani 

Ambiente di sviluppo
  - NetBeans IDE 8.1
  
Librerie js
  - JQuery 2.2.4
  - JQueryUI 1.11.4

Endpoint della libreria da includere nella sezione js di inizializzazione per il servizio Suggest 
    http://ec2-46-137-97-173.eu-west-1.compute.amazonaws.com/suggest/js/1.0/suggest.js
    
Endpoint della libreria da includere nella sezione js di inizializzazione per il servizio Suggest Free 
        http://ec2-46-137-97-173.eu-west-1.compute.amazonaws.com/suggest/js/1.0/suggest_free.js

Per l'utilizzo registrarsi sul sito http://streetmaster.it e richiedere la chiave per il servizio SUGGEST o SUGGEST Free.

Il servizio SUGGEST permette di effettuare in maniera gratuita 1800 chiamate mensili.
Il servizio SUGGEST Free permette di effettuare in maniera gratuita 140000 chiamate mensili. 

Per volumi di utilizzo maggiori consultare nel sito i piani di utilizzo.
Se non viene utilizzata una chiave valida il servizio restituisce nel menu a tendina un avviso.

Il servizio ha una copertura a livello di strada su tutto il territorio nazionale.
La base dati di riferimento è costantemente aggiornata con le variazioni amministrative e postali ufficiali.

Output di base Suggest free:
  - comune\\cap\provincia\frazione verificato e corretto in tutti i suoi compomenti
  
Output di base Suggest :  
  - output di base Suggest Free
  - indirizzo verificato e corretto in tutti i suoi compomenti
  
Informazioni aggiuntive SUGGEST  
 - codice istat del comune
 - codice istat della regione
 - geocodifica xy
 - scomposizione dell'indirizzo in Denominazione urbanistica e Toponimo 
 
Per ogni domanda o chiarimento manda una mail a supporto@streetmaster.it
