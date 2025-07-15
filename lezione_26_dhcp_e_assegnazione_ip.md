# DHCP e assegnazione IP

Il Dynamic Host Configuration Protocol (DHCP) è un protocollo di rete utilizzato per assegnare automaticamente indirizzi IP ai dispositivi connessi a una rete. Questo processo è essenziale per garantire che ogni dispositivo abbia un indirizzo IP univoco e possa comunicare efficacemente con altri dispositivi sulla rete.

## Processo di assegnazione

Il processo di assegnazione di un indirizzo IP tramite DHCP è piuttosto semplice. Quando un dispositivo si connette alla rete, invia una richiesta al server DHCP per ottenere un indirizzo IP. Il server DHCP quindi assegna un indirizzo IP disponibile dal pool di indirizzi configurati e lo invia al dispositivo. Questo processo avviene in modo trasparente e automatico, senza richiedere alcun intervento da parte dell'utente.

## Lease

Un concetto importante da comprendere nel contesto di DHCP è il concetto di "lease". Un lease è il periodo di tempo per il quale un indirizzo IP viene assegnato a un dispositivo. Durante questo periodo, il dispositivo può utilizzare l'indirizzo IP per comunicare sulla rete. Alla scadenza del lease, il dispositivo deve rinnovare la richiesta per mantenere l'indirizzo IP assegnato.

## Riserve

È possibile configurare il server DHCP per riservare specifici indirizzi IP per determinati dispositivi sulla rete. Questo è utile quando si desidera garantire che un determinato dispositivo riceva sempre lo stesso indirizzo IP ogni volta che si connette alla rete. Le riserve consentono di mantenere una certa coerenza nella configurazione degli indirizzi IP dei dispositivi sulla rete.

## Relè

In alcuni casi, può essere necessario utilizzare un relay DHCP per consentire ai dispositivi di ottenere un indirizzo IP da un server DHCP situato in un'altra rete. Il relay DHCP agisce come un intermediario tra il dispositivo e il server DHCP, trasmettendo le richieste di assegnazione di indirizzi IP da un'area di rete all'altra. Questo è particolarmente utile in ambienti di rete complessi in cui più server DHCP sono presenti su reti separate.

In conclusione, il DHCP svolge un ruolo fondamentale nell'assegnazione degli indirizzi IP sui dispositivi in una rete. Comprendere il processo, il concetto di lease, l'uso delle riserve e la funzione dei relay DHCP è essenziale per garantire una corretta configurazione e gestione degli indirizzi IP sulla rete.