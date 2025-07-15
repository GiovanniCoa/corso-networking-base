# Three-way handshake TCP

Il Three-way handshake è un procedimento fondamentale nel protocollo di comunicazione TCP (Transmission Control Protocol) che consente l'avvio, il mantenimento e la chiusura di una connessione tra due dispositivi su una rete. 

Il processo del Three-way handshake si compone di tre fasi distintive:

1. **Sincronizzazione (SYN)**: Il mittente invia un segmento di sincronizzazione (SYN) al destinatario per iniziare il processo di connessione. Il segmento SYN contiene un numero di sequenza casuale generato dal mittente per sincronizzare i numeri di sequenza tra i due dispositivi. 

2. **Accettazione (SYN-ACK)**: Il destinatario risponde al mittente con un segmento di sincronizzazione e conferma (SYN-ACK). Questo segmento contiene il numero di sequenza generato dal destinatario, insieme al numero di sequenza del mittente incrementato di uno. 

3. **Conferma (ACK)**: Infine, il mittente invia un segmento di conferma (ACK) al destinatario per confermare la ricezione del segmento SYN-ACK. Questo segmento contiene il numero di sequenza del destinatario incrementato di uno. 

Una volta completato il Three-way handshake, la connessione TCP è stabilita e i due dispositivi possono iniziare lo scambio di dati in entrambe le direzioni. 

Durante il mantenimento della connessione, i dispositivi continuano a scambiarsi segmenti di dati e conferme per garantire che i dati vengano consegnati correttamente e in ordine. 

Alla fine della comunicazione, la connessione viene chiusa attraverso un processo simile al Three-way handshake, noto come Four-way handshake, che prevede lo scambio di segmenti FIN per terminare la connessione in modo sincronizzato e ordinato. 

In conclusione, il Three-way handshake TCP svolge un ruolo cruciale nel garantire una comunicazione affidabile e sicura tra i dispositivi su una rete, stabilendo e chiudendo le connessioni in modo coerente e efficiente.