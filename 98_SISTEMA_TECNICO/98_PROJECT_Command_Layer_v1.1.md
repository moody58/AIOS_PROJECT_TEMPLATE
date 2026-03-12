PROJECT --- COMMAND LAYER

Versione: v1.1

Sistema: AIOS Project Framework

SCOPO DEL DOCUMENTO

Il Command Layer definisce l\'interfaccia conversazionale

utilizzata per controllare le sessioni operative

dei progetti basati sul sistema AIOS.

Il Command Layer rappresenta la shell operativa del progetto.

CONCETTO DI COMMAND LAYER

Il sistema utilizza trigger conversazionali

per attivare comportamenti specifici.

Questi trigger funzionano come comandi operativi

simili a quelli utilizzati nei sistemi operativi.

TRIGGER OPERATIVI PRINCIPALI

#start

avvio Boot Sequence progetto

#session

apertura sessione operativa

#state

snapshot stato progetto

#switch

trasferimento sessione tra chat

#log

generazione Incident Report

#help

richiamo guida operativa

#quick

modalità operativa veloce

#deep

modalità analisi approfondita

PRINCIPI OPERATIVI

I trigger non sostituiscono il linguaggio naturale

ma lo supportano.

Possono essere combinati per definire rapidamente

il contesto operativo.

Esempio:

#start

#session

#deep

RELAZIONE CON BOOT SEQUENCE

Il trigger #start attiva la Boot Sequence del progetto.

La Boot Sequence ricostruisce:

• contesto della sessione

• progetto attivo

• stato del progetto

• nodo operativo corrente

RELAZIONE CON I PROTOCOLLI

Il Command Layer attiva i principali protocolli del sistema:

Project Protocol

Boot Sequence

Anchor System

CQD Protocol

STP Protocol

Incident Management

RUOLO NEL SISTEMA PROGETTO

Il Command Layer mantiene ordine nelle conversazioni

e permette di attivare rapidamente i protocolli

del sistema progetto.

EVOLUZIONE DEL COMMAND LAYER

Il set di trigger deve rimanere stabile.

Nuovi trigger possono essere introdotti

solo quando emergono nuove funzioni sistemiche.

VERSION HISTORY

v1.1

Rimozione riferimenti a nomi file specifici

Command Layer reso indipendente dal nome progetto

v1.0

Prima definizione Command Layer progetti AIOS
