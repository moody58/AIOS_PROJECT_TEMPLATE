PROJECT — Kernel Manifest

Versione 1.0



Scopo

Questo documento dichiara il runtime del progetto e la sua integrazione

con il metasistema AIOS.



Architettura del sistema



AIOS\_RUNTIME

↓

PROJECT\_PROTOCOL

↓

PROJECT\_INSTANCE\_PROTOCOL

↓

PROJECT\_STATE

↓

Documenti operativi



Runtime dichiarato



Metasistema: AIOS

Template di origine: AIOS Universal Project Template

Istanza progetto: definita dal nome repository



Funzione del Kernel Manifest



Il Kernel Manifest permette al sistema AIOS di:



• identificare il progetto

• stabilire la gerarchia dei protocolli

• evitare conflitti tra sistema e progetto

• mantenere coerenza tra metasistema e istanza



Nota



Questo documento ha funzione dichiarativa e non sostituisce

i protocolli operativi del progetto.

