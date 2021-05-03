# Clase 11

## Máquinas virtuales

Es un software capaz de contener en su interior un SO.
Permiten probar otros SO, ejecutar programas antiguos, ofrecen un entorno de seguridad.

Existen dos tipos de máquinas virtuales, las de **sistemas** (emulan una computadora completa) y las de **procesos** (emula solo un proceso en concreto, puede ser de utilidad al desarrollar aplicaciones).

El lugar dónde la máquina virtual es creada se llama hypervisor.

**Hypervisor** -> Es una capa de software que se instala sobre la parte física de la computadora y asigna parte de la memoria, CPU etc.

![hypervisor](hypervisor.png)

El hypervisor de tipo 1 (como VmWare y Hyper-V) es conocido como "bare-metal" o nativo. Las máquinas virtuales en él tienen acceso directo al hardware, son independientes. Tienen una mayor escalabilidad.
Son más rápidos y seguros.

El hypervisor de tipo 2 (como VmWorkstation o VirtualBox) es conocido como "hosted". Su estabilidad y rendimiento son menores, ya que la carga es soportada por el sistema operativo. Un problema en una máquina puede afectar a otra.
Es más lento.

## Contenedores