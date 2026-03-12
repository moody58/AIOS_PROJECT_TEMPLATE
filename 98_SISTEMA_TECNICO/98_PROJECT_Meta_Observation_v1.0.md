# Scopo del documento

Il Meta-Observation Engine di progetto replica il comportamento del
Meta-Observation

definito nel sistema AIOS, adattandolo al contesto operativo dei singoli
progetti.

Il suo compito è monitorare il flusso delle sessioni operative e
suggerire azioni

correttive per mantenere coerenza metodologica, stabilità operativa e
continuità

tra conversazione e sistema documentale del progetto.

# Principio operativo

Il Meta-Observation di progetto non interrompe la conversazione ma
suggerisce

azioni quando rileva eventi rilevanti.

Può suggerire:

#state

#session

#switch

#log

oppure l\'uso di anchor strutturali.

# Eventi di cristallizzazione

Quando nella conversazione emergono nodi strutturali il sistema
suggerisce

la cristallizzazione tramite anchor.

Eventi principali:

Decisione confermata

→ suggerire anchor

#DECISION.contesto

Struttura definita

→ suggerire anchor

#STRUCTURE.contesto

Segmento documentale validato

→ suggerire anchor

#DOC.\<docID\>.\<sezione\>

Documento finale generato

→ suggerire anchor

#DOC.NomeDocumento_versione

# Anchor documentali e docID

Durante la costruzione dei documenti il progetto utilizza un
identificatore

logico di documento (docID).

Formato:

#DOC.\<docID\>.\<sezione\>

Esempio:

#DOC.protocollo_operativo.introduzione

#DOC.protocollo_operativo.trigger_operativi

#DOC.protocollo_operativo.cqd_pipeline

Questi anchor rappresentano segmenti validati del documento e restano
nella chat

fino alla generazione del documento finale.

# Cluster documentali

Tutti gli anchor che condividono lo stesso docID appartengono allo
stesso cluster

documentale.

Il cluster rappresenta il contenitore logico delle sezioni che
comporranno il

documento finale.

# Generazione documento

Quando il documento viene consolidato:

1\. i segmenti #DOC vengono aggregati

2\. il documento viene generato

3\. viene eseguito CQD

4\. il documento viene versionato

5\. viene generato l\'anchor finale

Esempio:

#DOC.NomeDocumento_vX.X

# Regola indice documentale

Solo i documenti finali versionati possono entrare nell\'indice del
progetto.

Gli anchor di tipo:

#DOC.\<docID\>.\<sezione\>

restano riferimenti conversazionali e non vengono indicizzati.

# Throttling anchor

Per evitare eccesso di anchor il sistema suggerisce anchor solo quando:

• una decisione è confermata

• una struttura è stabilizzata

• un segmento documentale è validato

• un documento finale viene generato

# Collegamento Radar progetto

Insight strategici rilevanti possono essere suggeriti per registrazione
nel

Radar evolutivo del progetto.
