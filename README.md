### Tarea C3B

---

A. Diseñe una maquina de estados finitos de algún proceso, maquina, dispositivo, etc. Que demuestre su comprensión de la implementación de las mismas.

Factorice su FSM y utilice por lo menos una vez la arquitectura Moore y Mealy. 

* Archivo .circ [Ver el archivo](https://github.com/UMG-GT/c3b-erickespa/blob/main/Tarea_C3B/Tarea_C3B_inspeccion_calidad.circ)

* Archivo de excel [Ver el archivo](https://github.com/UMG-GT/c3b-erickespa/blob/main/Tarea_C3B/TAREA_3CB.xlsx)

* Link al Video [Link](https://www.youtube.com/watch?v=XfGKBM5JVvk)

---

La sfm que realice es la de una maquina que inspecciona la calidad de un producto

## sfm moore

la sfm moore se encarga de la parte donde ingresa el producto S0 y este es revisado visualmente en la primera parte S1, si es aprovado avanza a la siguiente parte S2 y si es rechazado la maquina avanza a la parte S3. En la parte S2 el producto se inspecciona en sus dimensiones, si es aprovado avanza a la parte S4 si es rechazado avanza a la parte S3.

---

## sfm mealy

la sfm mealy se encarga de la banda transportadora donde dependiendo si el producto es aceptado o rechazado este es separado o marcado dependiendo de cual sea el protocolo configurado. en S0 la sfm esta apagada al momento de encederla avanza a la siguiente fase S1, aca se analiza si el producto fue aceptado o rechazado. Si fue rechazado avanza a la fase S3 donde inicia el protocolo para productos rechazados. Si fue aceptado avanza a la fase S2 donde inicia el protocolo para productos aceptados.
