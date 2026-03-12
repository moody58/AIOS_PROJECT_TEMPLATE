PROJECT --- FILE SYSTEM GUIDE

Documento: 98_PROJECT_File_System_Guide

Versione: v1.0

Sistema: AIOS Project Framework

Tipo: Guida struttura file progetto

1 --- SCOPO DEL DOCUMENTO

Il presente documento definisce la struttura standard

del file system per i progetti basati sul sistema AIOS.

La struttura ha tre obiettivi principali:

• garantire ordine e coerenza documentale

• permettere duplicazione rapida dei progetti

• separare contenuti operativi, tecnici e storici

2 --- PRINCIPIO DI STRUTTURA

Il sistema utilizza macroaree numeriche

per mantenere la struttura stabile tra progetti diversi.

Le macroaree sono progettate per essere:

• replicabili

• indipendenti dal tipo di progetto

• compatibili con evoluzioni future

3 --- MACROAREE STANDARD

La struttura universale prevede le seguenti macroaree.

00 --- CORE PROGETTO

Contiene i documenti fondamentali del progetto.

Tipicamente include:

00_PROJECT_Regia

00_PROJECT_State

00_PROJECT_System_Map

Questa area rappresenta

il centro operativo del progetto.

90 --- SCAMBIO ESTERNO

Area utilizzata per materiali provenienti dall\'esterno.

Esempi:

• documenti ricevuti da clienti

• materiali forniti da partner

• file di riferimento esterni

Questa cartella serve come zona di ingresso

per contenuti non ancora integrati nel sistema.

97 --- SISTEMA DATI

Area dedicata a dataset,

strutture dati o modelli informativi.

Può contenere:

• database progetto

• dataset strutturati

• modelli di analisi

• pipeline dati

Non tutti i progetti utilizzano questa area,

ma la struttura la prevede per compatibilità futura.

98 --- SISTEMA TECNICO

Contiene i protocolli tecnici

che governano il funzionamento del progetto.

Tipicamente include:

98_PROJECT_PROTOCOL

98_PROJECT_Command_Layer

98_PROJECT_CQD_Protocol

98_PROJECT_STP_Protocol

98_PROJECT_Anchor_System

98_PROJECT_Sistema_Fonti

98_PROJECT_Incident_Management

98_PROJECT_File_System_Guide

98_PROJECT_Radar

Questa area costituisce

il kernel tecnico del progetto.

99 --- ARCHIVIO STRATEGICO

Contiene documenti non più attivi

ma rilevanti per la memoria storica del progetto.

Include:

• versioni precedenti dei documenti

• analisi superate

• decisioni archiviate

I documenti presenti in questa cartella

non sono operativi.

4 --- BACKUP ESTERNO

Il sistema prevede una cartella esterna denominata:

PROJECT_BACKUP

Questa cartella non fa parte della struttura interna

del progetto ma viene utilizzata per:

• backup periodici

• snapshot di sicurezza

• archiviazione versioni complete del progetto

Il backup è responsabilità operativa dell\'utente

e non è gestito automaticamente dal sistema.

5 --- PRINCIPI OPERATIVI

La struttura file segue alcuni principi fondamentali.

Stabilità

Le macroaree non devono cambiare

tra progetti diversi.

Coerenza

Ogni documento deve essere collocato

nella macroarea corretta.

Versionamento

I documenti devono mantenere

versione nel nome file.

Separazione

Documenti operativi, tecnici e storici

devono rimanere separati.

6 --- DUPLICAZIONE PROGETTI

Il Launch Kit utilizza questa struttura

per permettere la creazione rapida

di nuovi progetti.

Procedura tipica:

1 duplicare il Launch Kit

2 rinominare i documenti PROJECT

3 avviare la Regia del progetto

4 iniziare le sessioni operative

VERSION HISTORY

v1.0 --- Prima definizione della struttura universale

del file system per progetti basati su AIOS.
