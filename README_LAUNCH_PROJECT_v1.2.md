README --- AIOS UNIVERSAL PROJECT LAUNCH KIT

Versione: v1.2

Sistema: AIOS Project Framework

SCOPO

Questo documento descrive la procedura standard per creare e avviare

un nuovo progetto utilizzando AIOS Universal Project Launch Kit.

Il Launch Kit contiene il kernel operativo dei progetti

ed è progettato per essere autosufficiente.

REGOLA DI ISTANZIAZIONE PROGETTO

Nel Launch Kit i file utilizzano il segnaposto:

PROJECT

Durante la creazione di un progetto reale

PROJECT deve essere sostituito con il nome del progetto.

Esempio:

98_PROJECT_PROTOCOL

→ 98_ADEXIMA_PROTOCOL

00_PROJECT_Regia

→ 00_ADEXIMA_Regia

Questa sostituzione deve essere applicata a tutti i file del Launch Kit.

FLUSSO DI CREAZIONE PROGETTO

1 Copiare o estrarre il Launch Kit in una nuova cartella progetto

2 Rinominare tutti i file sostituendo PROJECT con il nome del progetto

3 Aprire una nuova chat dedicata al progetto

4 Copiare il contenuto del file:

98_UNIVERSAL_PROJECT_INSTRUCTIONS

5 Incollare il blocco di istruzioni come primo messaggio della chat

STRUTTURA CARTELLE STANDARD

00 Fondamenta progetto

90 Collaborazione esterna

97 Sistema dati

98 Sistema tecnico

99 Archivio strategico

ATTIVAZIONE BOOTSTRAP SESSIONE

Per iniziare correttamente una sessione operativa utilizzare:

#start

Sistema: AIOS Project Mode

Operazione: Boot Sequence progetto

Procedura operativa:

1 identificazione contesto sessione

2 identificazione progetto attivo

3 recupero stato del progetto

4 verifica documenti fondamentali

5 individuazione nodo operativo

6 avvio sessione operativa

DOCUMENTI BASE DEL PROGETTO

Durante la Boot Sequence il sistema deve verificare

la presenza dei documenti fondamentali del progetto.

Documenti richiesti:

documento Regia del progetto

(es. 00_NOMEPROGETTO_Regia)

documento Stato del progetto

(es. 00_NOMEPROGETTO_State)

documento System Map del progetto

(es. 00_NOMEPROGETTO_System_Map)

Se questi documenti non sono presenti nella sessione

l\'assistente deve richiedere il caricamento dei file.

GERARCHIA FONTI OPERATIVE

REGIA \> STATE \> REGISTRY

REGIA

fonte direzionale principale del progetto

STATE

snapshot operativo della sessione

REGISTRY

vista sintetica del sistema

AVVIO SESSIONE OPERATIVA

Dopo la Boot Sequence è possibile aprire una sessione operativa.

Esempio:

#session

Macroarea:

Nodo operativo:

Documento di riferimento:

Obiettivo:

SINCRONIZZAZIONE CON AIOS

Ogni progetto rappresenta un nodo operativo

del sistema AIOS.

Le decisioni strutturali devono essere

sincronizzate con la Control Room AIOS

tramite aggiornamento della Regia AIOS

o registrazione nel Radar sistema.

VERSION HISTORY

v1.2

Rimozione riferimenti rigidi ai nomi file

Introduzione regola di istanziazione PROJECT

v1.1

Bootstrap #start completo
