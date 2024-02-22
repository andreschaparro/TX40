# PCB TX40

Este repositorio, contiene el diseño en Kicad de una placa para aislar las entradas de un controlador *BRAHMA*.

La entradas, cierran 5V en el PCB, y activan o desactivan 2 reles que se accionaran sobre el controlador original.

Esto es necesario, para que los sensores trabajen con niveles de tension segura.

Originalmente, el controlador tiene una fuente switching no aislada galvanicamente (LNK304) y produce que las entradas del mismo no tengan tensiones de trabajo seguras.
