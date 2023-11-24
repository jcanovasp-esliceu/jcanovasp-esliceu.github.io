## Planificació de Processos en Sistemes Operatius

- **Quan hi ha múltiples processos:** El sistema operatiu ha de decidir quin procés s'executa en cada moment, una tasca crítica per a la gestió eficient del sistema.
  
- **Planificador (Scheduler):** És l'eina responsable de prendre aquestes decisions, gestionant quins processos accedeixen al temps de CPU.

- **Temps Crucials en la Planificació:**
  - *Temps de Resposta:* Quant triga el sistema operatiu a respondre a una sol·licitud.
  - *Temps de Servei:* El temps total que implica atendre una petició, incloent-hi el temps d'espera i d'execució a la CPU.
  - *Temps de Processador:* És el temps de servei menys el temps d'espera a la cua, un indicador crític d'eficiència.
  - *Temps d'Espera:* El temps que un procés passa a la cua esperant ser atès, afectant directament el seu temps de processador.

- **Mètriques Clau:**
  - *Eficiència:* Es mesura com el temps de processador dividit pel temps total.
  - *Rendiment:* Indica la quantitat de processos executats per unitat de temps, reflectint la capacitat del sistema per gestionar-los.

- **Algoritmes de Planificació basats en l'Assignació de CPU:**
  - *FIFO:* Primer que arriba, primer que surt.
  - *Round Robin:* Reparteix el temps de CPU entre els processos en espera.
  - *SJF (Shortest Job First):* Dona prioritat als processos més curts.
  - *SRT (Shortest Remaining Time):* Executa primer els processos amb menys temps restant.
  
- **Prioritats:** Assignar prioritats als processos per determinar l'ordre d'execució, essencial per a la gestió de la càrrega de treball del sistema.
