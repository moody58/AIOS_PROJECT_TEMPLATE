PROJECT --- BOOT SEQUENCE

Documento: PROJECT_BOOT_SEQUENCE

Versione: v1.1

Sistema: AIOS Project Framework

SCOPO DEL DOCUMENTO

La Boot Sequence definisce la sequenza di attivazione

di un progetto basato sul sistema AIOS.

La sequenza consente di:

• identificare il contesto operativo

• ricostruire lo stato del progetto

• verificare i documenti fondamentali

• individuare il nodo operativo

• avviare la sessione di lavoro

ATTIVAZIONE

La Boot Sequence viene attivata tramite:

#start

SEQUENZA DI AVVIO

1 identificazione contesto sessione

2 identificazione progetto attivo

3 recupero stato progetto

4 verifica documenti fondamentali

5 individuazione nodo operativo

6 avvio sessione operativa

VERIFICA DOCUMENTI BASE

Durante la Boot Sequence il sistema deve verificare

la presenza dei documenti fondamentali del progetto.

Documenti richiesti:

Regia del progetto

(es. 00_NOMEPROGETTO_Regia)

Stato del progetto

(es. 00_NOMEPROGETTO_State)

System Map del progetto

(es. 00_NOMEPROGETTO_System_Map)

Se i documenti non sono presenti

il sistema deve richiederne il caricamento.

GERARCHIA FONTI DI STATO

REGIA \> STATE \> REGISTRY

REGIA

fonte direzionale principale

STATE

snapshot operativo sessione

REGISTRY

vista sintetica sistema

INDIVIDUAZIONE NODO OPERATIVO

Una volta ricostruito il contesto

il sistema individua il nodo operativo

su cui si concentrerà la sessione.

AVVIO SESSIONE OPERATIVA

Dopo la Boot Sequence

la sessione operativa può iniziare.

INTEGRAZIONE CON AIOS

Il progetto rappresenta un nodo operativo

del metasistema AIOS.

Decisioni strutturali rilevanti

devono essere sincronizzate con AIOS

tramite aggiornamento della Regia AIOS

o registrazione nel Radar sistema.

VERSION HISTORY

v1.1

Rimozione riferimenti rigidi ai nomi file

Boot Sequence resa indipendente dal nome progetto

v1.0

Prima definizione Boot Sequence progetti AIOS
