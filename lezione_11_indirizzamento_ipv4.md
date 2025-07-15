# Indirizzamento IPv4

L'indirizzamento IPv4 è un sistema utilizzato per assegnare un identificatore univoco a ogni dispositivo connesso a una rete Internet. Questo identificatore, chiamato indirizzo IP, è formato da 32 bit divisi in quattro ottetti separati da punti. 

## Classi di indirizzi IPv4

Gli indirizzi IPv4 sono suddivisi in classi in base alla loro grandezza e alla quantità di host che possono supportare. Le classi di indirizzi IPv4 sono:
- Classe A: indirizzi che iniziano con un numero compreso tra 1 e 126. Queste reti possono ospitare un numero molto elevato di host.
- Classe B: indirizzi che iniziano con un numero compreso tra 128 e 191. Queste reti possono ospitare un numero moderato di host.
- Classe C: indirizzi che iniziano con un numero compreso tra 192 e 223. Queste reti possono ospitare un numero limitato di host.
- Classe D: indirizzi che iniziano con un numero compreso tra 224 e 239. Queste reti sono riservate per il multicast.
- Classe E: indirizzi che iniziano con un numero compreso tra 240 e 255. Queste reti sono riservate per usi sperimentali.

## Subnetting

Il subnetting è una tecnica utilizzata per suddividere una rete IP in sottoreti più piccole. Questo permette di ottimizzare l'utilizzo degli indirizzi IP e di migliorare le prestazioni della rete. Per effettuare il subnetting è necessario utilizzare una maschera di sottorete, che determina quanti bit dell'indirizzo IP sono utilizzati per l'identificazione della rete e quanti per l'identificazione dell'host.

## CIDR

CIDR (Classless Inter-Domain Routing) è un metodo per rappresentare gli indirizzi IP e le relative maschere di sottorete in forma compatta. Invece di utilizzare le tradizionali classi di indirizzi IPv4, CIDR utilizza una notazione che specifica il numero di bit utilizzati per l'identificazione della rete e dell'host. Ad esempio, un indirizzo IP con la notazione CIDR 192.168.1.0/24 indica che i primi 24 bit dell'indirizzo sono utilizzati per identificare la rete e i rimanenti 8 bit per identificare l'host.

In conclusione, l'indirizzamento IPv4 è un elemento fondamentale per il funzionamento di Internet, e la conoscenza delle classi di indirizzi, del subnetting e del CIDR è essenziale per la corretta configurazione e gestione di una rete IP.