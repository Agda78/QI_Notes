# Script appunti
Tali script sono stati scritti in concomitanza con gli appunti. Quando necessario, venivano scritti dei circuiti che poi sono stati utilizzati all'interno degli appunti stessi. 
Tali circuiti sono stati scritti con una libreria IBM, tale libreria è [Qiskit](https://www.ibm.com/quantum/qiskit).

## Guida all'utilizzo degli script
Gli script sono stati definiti mediante dei notebook .ipynb. Tali notebook possono essere aperti sia in locale che online sulle diverse piattaforme apposite.

### Guida all'installazione dell'ambiente
Se si vuole runnare in locale gli algoritmi per il disegno degli algoritmi utilizzati bisogna installare le librerie apposite. Per evitare mismatch vi è il file `requirements.txt`, tale file permette di poter installare tutte le librerie richieste (che sia sull'interprete globale o su quello virtuale), mediante il comando:
```shell
pip install -r requirements.txt 
```
Dopo l'intallazione sarà possibile utilizzare come interprete interno dei notebook il python su cui sono state installate tali librerie