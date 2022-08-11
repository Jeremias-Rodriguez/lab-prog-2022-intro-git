Semaforo: Los semaforos en java son usados para restringir el numero de hilos que pueijnaaaaaden acceder a un recurso. Conceptualmente mantiene un numero de permisos.
Se importa con: java.util.concurrent.Semaphore
Se usa acquire() para adquirir un permiso, si no hay permisos disponibles el hilo se bloquea hasta que haya un permiso disponible.
Se usa release() para añadir/liberar un permiso, que podria liberar un hilo bloqueado.
