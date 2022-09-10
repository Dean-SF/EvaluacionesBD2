# Quiz #2
**Fecha: 09/09/2022**  
**Autor: Deyan Sanabria Fallas #2021046131**

# 1. Explique el concepto de shard, replica y partition
## Shard/Partition
Del dataset de la base, se agarran partes y se dividen entre cada uno de los nodos. Deben distribuirse de forma uniforme. El tamaño de esas partes dependen de la memoria, puesto que el objetivo es que cada uno de los shard/replicas puedan entrar en memoria.

## Replica
Las réplicas o la replicación es una forma de asegurar la seguridad de la base de datos, de tal forma que, en caso de caídas o algún desastre, la base de datos no se mantenga caída o se pierdan datos. Replicas seria cada uno de los nodos que **replican** a la base original. También nos puede servir para distribuir el “workload” al poder habilitar replicas que hagan solo lectura y reciban Queries de obtención de datos.

# 2. Explique la diferencia entre Strong Consistency y Eventual Consistency
## Strong Consistency
El strong consistency asegura que siempre se tiene la última versión de los datos. Si se llega a hacer un update de algún dato en el master y justo la replica esta leyendo datos, el strong consistency asegura que este dato será el ultimo que estaba por llegar. 

## Eventual Consistency
El eventual consistency asegura que la última versión de los datos llegue de manera eventual. Si se hace un update en un nodo master y la replica esta por leer datos, es muy posible que este dato no sea el ultimo, pero el dato de ese update llegara tarde o temprano a la réplica.

# 3. ¿En que consiste warm replicas y hot replicas?
## Hot replica
Fuerza Strong consistency, por lo que asegura que siempre tenga la versión más actual de los datos. Siempre están esperando nada más.

<div style="page-break-after: always"></div>

## Warm replica
Tiene eventual consistency y permiten hacer lectura, por lo que están dispuestos a dar información pero puede que no sea la más actual.

# 4. ¿En que consiste consiste switch over y fail over?
## Switch Over
Te avisa si en algún nodo de un sistema se cayó por algún motivo, para que una persona vaya físicamente a arreglar el problema. Por lo que se hace de forma manual

## Fail over
Automáticamente reconoce caídas de nodos dentro del sistema y hará las acciones necesarias para recuperar ese nodo.


