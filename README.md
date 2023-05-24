# flow1-ejercicio
Primer ejercicio con Node-Red

## Introducción

En esta ocaciòn se realizo un ejercicio con NodeRed para comenzar a conccer su funcionamiento. Realizamos el flow 1, donde aqui hicimos que se conectara un nodo Inject con un nodo Debug para generar un TimeStamp cada 1 segundo. Con esto pudimos ver como se ve la pestaña Debug en funcionamiento.

## Material Necesario

Para realizar este flow necesitas lo siguiente

- [Ubuntu 20.04](https://releases.ubuntu.com/20.04/)
- [Docker Engine](https://docs.docker.com/engine/install/ubuntu/#install-using-the-convenience-script)
- [NodeRed](https://nodered.org/docs/getting-started/local)

## Material de referencia

En los siguientes enlaces puedes encontrar cursos en la plataforma de edu.codigoiot.com que te permitirán realizar las configuraciones necesarias

- [Instalación de Virutal Box y Ubuntu 20.04](https://edu.codigoiot.com/course/view.php?id=812)
- [Introducción a Docker](https://edu.codigoiot.com/course/view.php?id=996)
- [Aplicacion multicontenedor de servidor IoT con Docker compose](https://edu.codigoiot.com/mod/lesson/view.php?id=3889&pageid=3804&startlastseen=no)
- [Introducción a NodeRed](https://edu.codigoiot.com/course/view.php?id=278)

## Instrucciones

### Requisitos previos

Requisitos previos:
1. Tener instalado Docker Engine.
2. Tener instaldo nodeRed por Docker Compose
3. Tener el contenedor de NodeRed con el volumen de data activado

### Instrucciones de preparación del entorno

Para ejecutar este flow, es necesario lo siguiente
1. Arrancar el contenedor de NodeRed con el comando
        
        docker start $(docker ps -a -q)

2. Dirigirse a [localhost:1880](localhost:1880)
3. Importar el flow desde el repositorio
4. Hacer clic en el boton Deploy

### Instrucciones de operación

Para observar el resutlado de este flow, sólo es necesario abrir la pestaña Debug y anteriormente haber creado nos nodos de Inject y Debug.

## Resultados

A continuación puede verse una vista previa del resultado de este flow.

![](https://github.com/EberGiovanni/flow1-ejercicio/blob/main/Imagenes/Captura%20desde%202023-05-23%2021-26-32.png?raw=true)

## Evidencias

- [YouTube](https://youtu.be/8U-K6bgMQwE)

