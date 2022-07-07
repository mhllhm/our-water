# OUR WATER

Un progetto che prova ad offrire uno strumento per aiutarci a rispettare uno dei beni più preziosi che abbiamo, l'acqua.

Sempre più di questi tempi, assistiamo a un estremizzazione di uno degli elementi cardini della vita.
Sentiamo notizie che descrivono scenari dove l'acqua non c'è a sufficienza, c'è in eccessiva abbondanza oppure c'è ma con un tasso di inquinamento eccessivamente alto.

Per poter invertire questa tendenza estrema, Our Water, si propone come un progetto di tutti, open source, per poter sfruttare l'ingegno al fine di ritrovare un equilibrio anche attraverso strumenti moderni.

Gli obiettivi di questo progetto sono:
- Creare degli strumenti per monitorare:
  - la quantità di acqua nel territorio e il suo cambiamento nel tempo
  - la qualità dell'acqua e il suo cambiamento nel tempo
  - la portata dei corsi d'acqua in tempo reale
  - la mal gestione dell'uso di acqua
- Creare degli strumenti per permettere di avere una piattaforma digitale dell'acqua che aiuti a scegliere decisioni più consapevoli
- Creare degli strumenti per poter aver una base dati nazionale, libera a participazione volontaria e libera:
  - dare la possibilità di segnalare situazioni pericolose (es alluvioni o esondazioni)
  
- Dare la possibilità di far interagire vari dati e strumenti:
  - poter mandare notifiche alle persone con bollettini di emergenze


Possibile prototipo di infrastruttura digitale:
- Endpoint dove gli vari apparati possono mandare i loro dati
- Elaboratori di dati che possono trasformare vari protocolli, in una struttura dati condivisa e comune
- Rappresentazione in Digital Twin della struttura di monitoraggio
- Endpoint dove sviluppatori e applicazioni, possano richiedere i dati, attuali e storici

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```