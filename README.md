Grupo25-Laboratorio-1
Integrantes:

Sebastian Castro - 202004569-0
Benjamin Rivero - 202073531-k
Fernando Delgado - 201804571-3

Para la tarea se implemento dos servidores regionales en tres maquinas disponibles, para ejecutarlo deben ejecutar el comando "make docker-regional" en las maquinas dist099 y dist131, el servidor central se implemento en la maquina dist100, para ejecutarlo debe ejecutar el comando "make docker-central". Cabe mencionar que nuestra implementacion omite la cola rabbit, dado que no se logro su correcta funcionamiento, pero la logica de esta se llevo a cabo con gRPC. Note que las maquinas corresponde a dist99, dist100 y dist131, dado que la dist130 se encuentra caida en estos momentos y se informo al ayudante, pero todavia no hay respuesta.

Cada servidor_regional tendra su propio archivo de parametros de inicio, inicialmente todos tienen lo mismo almacenado, para probar mas casos modificar estos.
