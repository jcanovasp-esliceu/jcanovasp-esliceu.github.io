## Algoritmes de Planificació

### FIFO (First In, First Out)
- *Serveix els processos en ordre d'arribada.*
- **Resultats i Estadístiques:** 
  - Es basa en donar prioritat als processos que han arribat primer, seguint l'ordre cronològic de la seva arribada.

### Round Robin
- *Reparteix el temps entre tots els processos actius.*
- **Quantum:** És el temps de CPU assignat a cada procés.
- Els processos s'executen fins que:
  - S'acaba el quantum de temps assignat.
  - El procés queda bloquejat esperant una operació d'E/S.
  - Si el procés finalitza abans del quantum, la CPU és assignada a un altre procés.
- Quan es crea un procés, passa al final de la cua dels processos preparats.

### SJF (Shortest Job First)
- *El SO mira la cua de processos preparats i agafa primer el que tingui un temps d'execució més petit.*
- **Dues Modalitats:**
  - *Preemtive:* Dona prioritat a un procés més curt, permetent que un procés més curt prengui la CPU al procés més llarg que arriba posteriorment.
  - *Non-preemtive:* Espera fins que finalitzi el procés actual, fins i tot si és més llarg que altres pendents.
