# Tasques Fonamentals dels Sistemes Operatius: Gestió dels Processos

Benvinguts a aquesta presentació centrada en una de les funcions crucials dels sistemes operatius: la gestió dels processos!

## Definició de Procés

Dins de l'univers dels sistemes operatius, un procés no és només un conjunt de tasques o instruccions; és l'essència mateixa de l'execució. Un procés pot ser una sola aplicació o un conjunt d'elles, i el sistema operatiu es fa càrrec de la seva gestió, des de la seva càrrega a la memòria fins a la seva execució al processador.

## Gestió Eficient

Què passa quan múltiples processos competeixen per recursos limitats? Aquí és on entra en joc la planificació: el sistema operatiu es converteix en un àrbitre just i distribueix la capacitat del processador entre els diferents processos en execució.

## Creació i Destrució

Crear un procés és només el començament. Amb un Identificador de Procés (PID) assignat, cada procés compta amb un Bloc de Control de Procés (PCB) que conté informació crucial per a la seva gestió, incloent-hi el seu estat i els recursos assignats.

Destrueixar un procés també és una part fonamental. Des de finalitzar un procés en segon pla fins a bloquejar-lo o reprendre'l, el control i maneig dels processos actius és un repte que els sistemes operatius enfronten constantment.

## Planificació: Qui té el temps de la CPU?

La clau per a un sistema operatiu eficient radica en el seu planificador. Aquest decideix qui pren el relleu en l'execució, basant-se en algoritmes com FIFO, Round Robin, SJF, SRT o prioritats assignades a cada procés.

## Modalitats de Planificació

La planificació preemptiva dóna preferència a processos més curts, mentre que la no preemptiva espera que finalitzi el procés actual, independentment de la seva durada. A més, assignar prioritats als processos determina qui té prioritat per utilitzar la CPU.

En aquesta presentació, explorarem com aquests conceptes clau de la gestió de processos en els sistemes operatius treballen en harmonia per mantenir l'estabilitat, l'eficiència i el rendiment del sistema.

Preparem-nos per endinsar-nos en el fascinant món de la gestió de processos en els sistemes operatius!
