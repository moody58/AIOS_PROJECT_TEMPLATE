PROJECT — Runtime Bridge

Versione 1.0



Scopo



Questo documento definisce la relazione tra il progetto

e il metasistema AIOS.



Architettura



AIOS

↓

PROJECT

↓

REGIA

↓

PROTOCOLLI

↓

MACROAREE OPERATIVE



Ruolo del Runtime Bridge



Il documento:



• collega il progetto al runtime AIOS

• preserva le personalizzazioni del progetto

• evita conflitti tra protocolli universali e locali



Boot sessione



Durante #start il sistema:



1 identifica il progetto

2 verifica il Kernel Manifest

3 recupera lo Stato Progetto

4 attiva la sessione operativa



Relazione con AIOS



Se una decisione della Regia progetto modifica:



• struttura del progetto

• architettura del sistema

• protocolli operativi

• priorità strategiche



il sistema deve verificare se è necessario aggiornare

la Regia AIOS.

