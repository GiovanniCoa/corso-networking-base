# Livello 4 – Trasporto

Il livello 4 del modello OSI, noto come livello di trasporto, è responsabile dell'effettivo trasferimento dei dati tra mittente e destinatario. In questo articolo approfondiremo i concetti fondamentali del livello 4, tra cui TCP e UDP, porte e controllo di flusso.

## TCP e UDP

Il protocollo TCP (Transmission Control Protocol) è un protocollo di trasporto affidabile e orientato alla connessione. TCP garantisce che i dati vengano consegnati correttamente e in ordine, gestendo la ritrasmissione dei pacchetti persi e il controllo di flusso per evitare la congestione di rete.

Dall'altro lato, UDP (User Datagram Protocol) è un protocollo di trasporto non affidabile e senza connessione. UDP è spesso utilizzato per applicazioni in cui la perdita di alcuni pacchetti non è critica, come la trasmissione di audio e video in tempo reale.

## Porte

Le porte sono numeri di 16 bit utilizzati per identificare i diversi servizi e applicazioni su un host. Le porte vengono utilizzate insieme agli indirizzi IP per instradare correttamente i pacchetti al servizio desiderato. Le porte vanno da 0 a 65535 e sono divise in tre categorie: porte ben note (0-1023), porte registrate (1024-49151) e porte dinamiche o private (49152-65535).

## Controllo di Flusso

Il controllo di flusso è un meccanismo utilizzato per regolare il flusso di dati tra mittente e destinatario, garantendo che il destinatario sia in grado di elaborare i dati alla velocità desiderata. Il controllo di flusso prevenire la congestione di rete e ottimizza le prestazioni del trasferimento dei dati.

In conclusione, il livello 4 del modello OSI gestisce l'effettivo trasferimento dei dati tra mittente e destinatario, utilizzando protocolli come TCP e UDP, identificando i servizi tramite le porte e regolando il flusso dei dati per garantire un trasferimento efficiente. Questi concetti sono fondamentali per comprendere il funzionamento della comunicazione nei sistemi di rete moderni.