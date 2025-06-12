.. _link-section:

=======
Manuale
=======

NethLink è un'applicazione desktop basata su Electron che permette di gestire le chiamate VoIP direttamente dal computer. 
Questa applicazione nasce per portare la Phone Island di NethVoice CTI fuori dal browser nel sistema operativo del PC dell'utente, 
eliminando la necessità di utilizzare il tab di NethVoice CTI per gestire le telefonate.

L'applicazione è disponibile per i seguenti sistemi operativi:

* Windows
* macOS
* Linux (AppImage), non ufficialmente supportato

Installazione
=============

NethLink è disponibile come applicazione desktop indipendente. Per installarlo:

1. Accedere a NethVoice CTI
2. Navigare alla sezione "Impostazioni → Dispositivi"
3. Effettuare il download dell'applicazione nella versione appropriata per il proprio sistema operativo
4. Installare l'applicazione seguendo le istruzioni specifiche del sistema operativo

NethLink è disponibile per il download dal sito ufficiale: `nethserver.github.io/nethlink <https://nethserver.github.io/nethlink/>`_

Caratteristiche principali
==========================

* Gestione completa delle chiamate dal desktop
* Integrazione con il sistema telefonico NethVoice
* Supporto per audio bidirezionale
* Indicatori di stato della chiamata
* Gestione della rubrica
* Supporto per più account
* Notifiche di sistema integrate
* Ricerca in rubrica
* Gestione numeri brevi
* Visualizzazione chiamate perse
* Integrazione con la tray bar del sistema operativo
* Possibilità di utilizzo contemporaneo con NethVoice CTI
* Scorciatoie da tastiera personalizzabili
* Menu contestuale nel campo di composizione
* Supporto per il copia e incolla dei numeri di telefono
* Integrazione con il sistema di notifiche del sistema operativo

Requisiti di sistema
====================

* Sistemi operativi supportato:

  * Windows (Windows 10 o successivo)
  * macOS (10.15 Catalina o successivo)
* Microfono e altoparlanti/cuffie funzionanti
* Connessione internet stabile
* Account NethVoice configurato

Configurazione
==============

La configurazione di NethLink è semplice e richiede solo:

1. Inserire il dominio di NethVoice CTI
2. Inserire le proprie credenziali utente
3. Inserire la password

Una volta configurato, la Phone Island di NethVoice CTI verrà automaticamente eseguita in NethLink invece che nel browser.

Configurazione audio
--------------------

Per garantire una qualità ottimale delle chiamate:

1. Selezionare il dispositivo di input (microfono) desiderato
2. Selezionare il dispositivo di output (altoparlanti/cuffie) desiderato
3. Eseguire il test audio per verificare la configurazione
4. Regolare i livelli del volume secondo necessità

Configurazione delle scorciatoie da tastiera
--------------------------------------------

NethLink permette di personalizzare le scorciatoie da tastiera per le operazioni più comuni:

1. Accedere a "Profilo → Impostazioni → Scorciatoie"
2. Selezionare l'operazione da configurare
3. Premere la combinazione di tasti desiderata
4. Salvare le impostazioni

Le scorciatoie disponibili includono:

* Avvio chiamata
* Terminazione chiamata
* Attivazione/disattivazione microfono
* Attivazione/disattivazione altoparlante
* Risposta a una chiamata in arrivo
* Rifiuto di una chiamata in arrivo

Utilizzo
========

Effettuare una chiamata
-----------------------

Ci sono diversi modi per effettuare una chiamata:

1. Selezionare il contatto dalla rubrica
2. Cliccare sull'icona del telefono accanto al contatto
3. Attendere la risposta
4. Utilizzare i controlli durante la chiamata:

   - Muto
   - Altoparlante
   - Termina chiamata

In alternativa è possibile:

* Digitare il numero nel campo di composizione e premere Invio
* Utilizzare la scorciatoia da tastiera configurata
* Selezionare un numero di telefono nel sistema operativo e utilizzare la scorciatoia
* Utilizzare il menu contestuale nel campo di composizione per incollare un numero

Ricevere una chiamata
---------------------

1. All'arrivo di una chiamata, apparirà una notifica
2. Cliccare su "Rispondi" per accettare la chiamata
3. Cliccare su "Rifiuta" per declinare la chiamata
4. Utilizzare i controlli durante la chiamata

Gestione rubrica
----------------

* Aggiungere nuovi contatti
* Modificare contatti esistenti
* Organizzare contatti in gruppi
* Ricercare contatti
* Importare/esportare contatti

Menu contestuale
----------------

Il campo di composizione supporta un menu contestuale (tasto destro) che permette di:
* Incollare un numero di telefono
* Copiare il numero selezionato
* Cancellare il contenuto del campo
* Utilizzare le scorciatoie da tastiera configurate

Notifiche
---------

NethLink utilizza il sistema di notifiche del sistema operativo per:
* Avvisare di chiamate in arrivo
* Mostrare lo stato delle chiamate
* Informare su eventi importanti
* Permettere risposte rapide alle notifiche

Risoluzione problemi
====================

Problemi audio
--------------

* Verificare che i dispositivi audio siano correttamente collegati
* Controllare le impostazioni del browser per i permessi audio
* Eseguire il test audio nella sezione configurazione
* Verificare che non ci siano altre applicazioni che utilizzano i dispositivi audio

Problemi di connessione
-----------------------

* Verificare la connessione internet e la risoluzione DNS
* Controllare le credenziali di accesso
* Verificare che il centralino sia raggiungibile

Note importanti
===============

* NethLink può essere utilizzato contemporaneamente a NethVoice CTI
* Le chiamate possono essere effettuate da entrambe le interfacce
* Le chiamate in arrivo verranno ricevute solo sul dispositivo impostato come principale
* NethLink utilizza le notifiche di sistema per gli avvisi (es. chiamata in arrivo)
* L'applicazione rimane sempre accessibile dalla tray bar del sistema operativo
* NethLink è attualmente in versione BETA e verrà arricchito con ulteriori funzionalità
