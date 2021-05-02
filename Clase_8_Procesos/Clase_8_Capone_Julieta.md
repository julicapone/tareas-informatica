# Clase 8

## Procesos

Lo que se inicia cuando queremos que la computadora realice una instrucción, es la ejecución de un programa.
Se ejecutan uno a la vez.
Son efímeros (se crean y se terminan).

Se crean de varias formas:
**Por el usuario, de manera interactiva.**
**En segundo plano, como llamadas al sistema.**

Tienen estados:
- Nuevo

- Preparado (cargado en memoria)

- En ejecución 

- Bloqueado

- Terminado

**IPC** -> Inter process -> mecanismos de comunicación entre procesos.
Existen 2

Memoria compartida -> Se establece un espacio en memoria que será compartido por los procesos.

Pasos de mensajes -> Avisos que puede enviar un proceso a otro, el intermediario es el Kernel.

**Planificación de procesos**

- FIFO -> First In, First Out -> Primero el que lo solicite primero.

- SJF -> Shortest Job First -> Primero el que menor tiempo lleve.

- SRTF -> Shortest Remaining Time First -> Primero el que menor tiempo lleve, solo que puede interrumpir un proceso para que entre uno todavía más corto.

- Round Robin -> Existe una cantidad de tiempo establecida (quantum) para cada proceso.

**Hilos || Thread**

Los hilos de ejecución que comparten los mismos recursos, sumados a estos recursos, son en conjunto conocidos como un proceso, es decir que un proceso puede dividirse en hilos.

**Procesadores monolíticos vs multinúcleos**

Los monolíticos son más predecibles, no presentan errores.
Los multihilos trabajan en paralelo y tienen más capacidad de respuesta pero pueden tener errores.



