# imh-lib-base

Libreria base d elos proyectos generados por imh.

## Tabla de Contenidos

- [Descripción](#descripción)
- [Características](#características)
- [Tecnologías](#tecnologías)
- [Requisitos Previos](#requisitos-previos)
- [Instalación](#instalación)
- [Configuración](#configuración)
- [Ejecución](#ejecución)
- [Pruebas](#pruebas)
- [Contribuir](#contribuir)
- [Licencia](#licencia)

## Descripción

Librería donde se mantendrán las versiones de las dependencias que utilizarán otros proyectos de imh.

Solo contiene el archivo pom.xml y este README.md.

Cualquier cambio de versión de una librería utilizada en proyectos de imh se debe realizar en este proyecto.

## Características

- Mantenimiento de las versiones de librerías mediante el archivo pom.xml de maven
- Uso de tag "properties" para las versiones.
- Uso de tag "dependencyManagement" para las dependencias de los proyectos de imh.
- Incorporación de las dependencias básicas mediante el uso del tag "dependencies" y que se usaran en todos los proyectos de imh.
  - Lombok
  - MapStruct
- Creación del apartado "build" general de todos los proyectos de imh.

## Tecnologías

Lista de tecnologías y herramientas utilizadas en el proyecto:

- Java 21
- Maven 3.8

## Requisitos Previos

Lista de software y herramientas que deben estar instaladas en tu sistema:

- JDK 21 o superior
- Maven 3.8 o superior

## Instalación

Pasos para clonar el repositorio e instalar las dependencias:

```sh
git clone https://github.com/ignaciomorenohojas/imh-lib-base
cd imh-lib-base
mvn clean install
```

## Configuración

No es necesaria ninguna configuración, basta con una compilación para posteriomnte utilizarla en otros proyectos.

## Ejecución
La aplicación no es ejecutable.

## Pruebas
No hay desarrollo realizado, por lo que no son necesarias pruebas unitarias.

## Contribuir
Instrucciones para contribuir al proyecto:

1. Haz un fork del repositorio.
2. Crea una nueva rama (git checkout -b feature/nueva-feature).
3. Realiza los cambios necesarios y realiza commits (git commit -m 'Añadir nueva feature').
4. Sube tus cambios a GitHub (git push origin feature/nueva-feature).
5. Abre un Pull Request.

## Licencia
Información sobre la licencia del proyecto.

