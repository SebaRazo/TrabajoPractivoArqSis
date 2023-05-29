# Trabajo Práctico Arquitectura de Sistemas

## Integrantes del equipo:
- Alfonso Garay 
- Carvi Pedro 
- -Brandelero Ezequiel 
- -Razovich Sebastián


## Descripción
Este repositorio contiene el Trabajo Práctico de Arquitectura de Sistemas.

## Instrucciones para correr el proyecto

### Requisitos
- Docker instalado en tu máquina.

### Pasos para correr la aplicación
1. Asegúrate de tener Docker instalado en tu máquina. 
2. Clona este repositorio en tu máquina local: git clone https://github.com/SebaRazo/TrabajoPractivoArqSis.git
3. Navega hasta la carpeta raíz del proyecto: cd TrabajoPractivoArqSis
4. Crea un archivo docker-compose.yml con el siguiente contenido:
    version: '3'
    services:
      web:
        image: sebarazo/trabajopractivoarqsist-web:tp
        ports:
          - 80:80
  Esto utilizará la imagen disponible en Docker Hub.
  
5. Ejecuta el siguiente comando para descargar y ejecutar la imagen desde Docker Hub: docker-compose up
     Esto descargará automáticamente la imagen desde Docker Hub y levantará la aplicación en un contenedor Docker. 
     El puerto 80 del contenedor estará mapeado al puerto 80 del host.
6. Abre tu navegador web y visita http://localhost para acceder al proyecto.
  
Link imagen DockerHub: https://hub.docker.com/r/sebarazo/trabajopractivoarqsist-web
