# Comuni italiani e stradario - Autocomplete 
## Suggest HTML/JS 
Comuni italiani e stradario. Soluzione html/js per l'utilizzo del servizio SUGGEST e SUGGESTFREE di autocomplete. 

###Ambiente di sviluppo
  - NetBeans IDE 8.1
  
###Librerie js
  - JQuery 2.2.4
  - JQueryUI 1.11.4

###Endpoint
Endpoint della libreria da includere nella sezione js di inizializzazione per il servizio Suggest 
```
    https://streetmaster.streetmaster.it/suggest/js/1.2/suggest.js
``` 
Endpoint della libreria da includere nella sezione js di inizializzazione per il servizio Suggest Free 
```
    https://streetmaster.streetmaster.it/suggest/js/1.2/suggest_free.js
```
### Key
Per l'utilizzo registrarsi sul sito http://streetmaster.it e richiedere la chiave per il servizio SUGGEST o SUGGEST Free.
La versione free permette di fare l'autocompletamento delle informazioni di comune\cap\provincia\frazione

### Condizioni
Il servizio SUGGEST permette di effettuare in maniera gratuita 1800 chiamate mensili.
Il servizio SUGGEST Free permette di effettuare in maniera gratuita 140000 chiamate mensili. 

Per volumi di utilizzo maggiori consultare nel sito i piani di utilizzo.
Se non viene utilizzata una chiave valida il servizio restituisce nel menu a tendina un avviso.

Il servizio ha una copertura a livello di strada su tutto il territorio nazionale.
La base dati di riferimento è costantemente aggiornata con le variazioni amministrative e postali ufficiali.

### Ouput
L'autocompletamento del comune si attiva in automatico appenal'utente comincia a scrivere nel textbox

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

### Aggiornamenti base dati comunale
  - 01/01/2016 Istituzione
  - 05/12/2066 Inserimento nuovi comuni di Alpago e Val di Zoldo
  - 05/12/2016 Soppressione comuni di Zoldo Alto,Forno di Zoldo,Prestine, Ivano-Francena,Farra d'Alpago,Pieve d'Alpago,Puos d'Alpago
  - 08/05/2017 Inserimento nuovi comuni di Abetone Cutigliano,San Marcello Piteglio,Valfornace,Colli al Metauro,Terre Roveresche,Alta Valle Intelvi,Terre del Reno
  - 08/05/2017 Soppressione comuni di Selve Marcone,Cavallasca,Acquacanina,Abetone,Cutigliano,San Marcello Pistoiese,Piteglio,San Giovanni D'Asso,Fiordimonte,Pievebovigliana,Piagge,Barchi,Orciano Di Pesaro,San Giorgio Di Pesaro,Montemaggiore Al Metauro,Saltara,Serrungarina,Mirabello,Sant'Agostino,Lanzo D'Intelvi,Pellio Intelvi,Ramponio Verna
  - 06/12/2017 Adeguamento struttura amministrativa della Sardegna. Soppressione delle provincie di Medio Campidano,Carbonia-Iglesias, Olbia-Tempio, Ogliastra e creazione della provincia Sud Sardegna
  - 18/06/2018 Inserimento nuovi comuni di Alta Val Tidone, Alluvioni Piovera, Alto Sermenza, Cellio con Breia, Montalto Carpasio, Sen Jean di Fassa, Valvarrone, Borgo Mantovano, Centro Valle Intelvi, Castelgerundo, Casali del Manco, Laterina Pergine Valdarno, Rio, Val Liona, Sermide e Felonica. Cambio di provincia per Sappada.
  - 18/06/2018 Soppressione comuni di Caminata, Nibbiano, Pecorara, Gavazzana, Alluvioni Canbio', Piovera, Rima San Giuseppe, Rimasco, Breia, Cellio, Sabbia, Carpasio, Montalto Ligure, Pozza di Fassa, Vigo di Fassa, Introzzo, Tremenico, Vestreno, Pieve di Coriano, Revere, Villa Poma, Felonica, Sermide, Casasco d'Intelvi, Castiglione d'Intelvi, San Fedele d'Intelvi, Camairago, Cavacurta, Casole Bruzio, Pedace, Serra Pedace, Spezzano Piccolo, Trenta, Laterina, Pergine Valdarno, Rio Marina, Rio nell'Elba, Grancona, San Germano dei Berici
  - 19/11/2018 Inserimento nuovi comuni di Fiumicello Villa Vicentina, Treppo Ligosullo, Corigliano-Calabro, Barbarano Mossano e Borgo Veneto
  - 19/11/2018 Soppressione comuni di Villa Vicentina, Fiumicello, Ligosullo, Treppo Carnico, Rossano, Corigliano Calabro, Mossano, Barbarano Vicentino, Megliadino San Fidenzio, Santa Margherita d'Adige e Saletto 
  - 18/06/2019 Inserimento nuovi comuni di Valle Cannobina,Val di Chy,Valchiusa,Quaregna Cerreto,Valdilana,Gattico-Veruno,Lu e Cuccaro Monferrato,Terre d'Adige,Riva del Po,Tresignana,Sorbolo Mezzani,Barberino Tavarnelle,Borgocarbonara,Solbiate con Cagno,Piadena Drizzona,Colli Verdi,Vermezzo con Zelo,Cadrezzate con Osmate,Sassocorvaro Auditore,Borgo Valbelluna,Pieve del Grappa,Valbrenta,Valstagna,Lusiana Conco,Colceresa. Cambio di nome per Negrar di Valpolicella e San Giorgio Bigarello
  - 18/06/2019 Soppressione comuni di Cavaglio-Spoccia,Cursolo-Orasso,Falmenta,Alice Superiore,Lugnacco,Pecco,Vico Canavese,Trausella,Meugliano,Cerreto Castello,Quaregna,Mosso,Soprana,Trivero,Valle Mosso,Camo,Valmala,Castellar,Gattico,Veruno,Riva Valdobbia,Lu,Cuccaro Monferrato,Zambana,Nave San Rocco,Berra,Ro,Formignana,Tresigallo,Mezzani,Sorbolo,Barberino Val d'Elsa,Tavarnelle Val di Pesa,Borgofranco sul Po,Carbonara di Po,Bigarello,Solbiate,Cagno,Piadena,Drizzona,Ca' d'Andrea,Canevino,Ruino,Valverde(PV),Vermezzo,Zelo Surrigone,Cadrezzate,Osmate,Auditore,Sassocorvaro,Lentiai,Mel,Trichiana,Crespano del Grappa,Paderno del Grappa,Campolongo sul Brenta,Cismon del Grappa,San Nazario,Valstagna,Lusiana,Conco,Mason Vicentino,Molvena              
  - 09/12/2019 Soppressione comuni di Presicce e Acquarica del Capo
  - 09/12/2019 Creazione comune di Presicce-Acquarica
  - 25/05/2020 Soppressione comuni Castelfondo,Fondo,Malosco,Cagno',Revo,Romallo,Cloz,Brez,Carano,daiano,Varena,Faedo,Vendrogno
  - 25/05/2020 Creazione comuni di Novella,Borgo d'Anaunia,Ville di Fiemme
  - 25/05/2020 Riorganizzazione cap della provincia di Milano
  - 07/12/2020 Soppressione comune di Monteciccardo
  - 25/08/2021 Creazione comune di Misiliscemi (TP) e cambio di provincia per Montecopiolo e Sassofeltrio
  - 20/04/2022 Variazione cap Staletti e varie frazioni di Casalfiumanese,Ragusa, Riva del Garda. Plati', Chiaramonte Gulfi,Potenza,Isola del Giglio e Celico
  - 28/02/2023 Soppressione dei comuni di Bardello(VA), Bregano(VA), Malgesso (VA), Moransengo(AT) e Tonengo (AT)
  - 28/02/2023 Creazione dei comuni di Bardello con Malgesso e Bregano (VA) e Moransengo-Tonengo (AT)
  - 06/02/2024 Incorporazione del comune di Albaredo Arnaboldi in quello di Campospinoso con cammbio di denominazione in Campospinoso Albaredo (PV). 
  - 06/02/2024 Soppressione dei comuni di Gambugliano(VI), Quero Vas (BL), Alano di Piave (BL), Vighizzolo d'Este (PD), Carceri (PD), Ronago (CO), Uggiate-Trevano (CO)
  - 06/02/2024 Inserimento nuovi comuni di Uggiante con Ronago (CO),Setteville (BL) e Santa Caterina d'Este (PD)
      
### Support
Per ogni domanda o chiarimento manda una mail a supporto@streetmaster.it


