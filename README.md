## [Máster en Ingeniería Web por la Universidad Politécnica de Madrid (miw-upm)](http://miw.etsisi.upm.es)

## Arquitectura y Patrones de aplicaciones Web (APAW).
> Este proyecto es un apoyo docente de la asignatura y contiene ejemplos prácticos sobre Spring

### Tecnologías necesarias
`Java` `Maven` `GitHub` `GitHub Actions` `Spring-Boot` `GitHub Packages` `Docker` `Spring Cloud` `Eureka`

### :gear: Instalación del proyecto
1. Clonar el repositorio en tu equipo, **mediante consola**:
```sh
cd <folder path>
git clone https://github.com/miw-upm/apaw-eureka
```
2. Importar el proyecto mediante **IntelliJ IDEA**  
   * **Open**, y seleccionar la carpeta del proyecto.

### :gear: Ejecución en local con IntelliJ
* Ejecutar la clase **Application**

### :gear: Ejecución en local con Docker, debe tener la red _apawnet_ ya creada
* Ejecutar en el proyecto la siguiente secuencia de comandos de Docker compose
```sh
docker network create apawnet
docker compose up --build -d
```

* Cliente Web: http://localhost:8761
* Datos de instancias: http://localhost:8761/eureka/apps

