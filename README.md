
# Práctica 1: Docker y GitHub Codespaces

## 1. Objetivo

Configurar un entorno de desarrollo utilizando Docker, Docker Compose, Visual Studio Code y GitHub Codespaces, y verificar el funcionamiento de los contenedores.

## 2. Herramientas utilizadas

- Docker
- Docker Compose
- Visual Studio Code
- Extensión Docker de Microsoft
- Git y GitHub
- GitHub Codespaces

## 3. Configuración del entorno

Se creó un repositorio de GitHub denominado `Practicadocker-1` y se configuró el entorno de desarrollo mediante el archivo `.devcontainer/devcontainer.json`.

La configuración utiliza una imagen base de Ubuntu 22.04 e incluye la característica Docker-in-Docker y la extensión de Docker para Visual Studio Code.

## 4. Pruebas realizadas

### Verificación de Docker

Comando ejecutado:

`docker --version`

Resultado en Codespaces: Docker 29.9.1.

### Verificación de Docker Compose

Comando ejecutado:

`docker compose version`

Resultado: Docker Compose v2.40.3.

### Ejecución de un contenedor de prueba

Comando ejecutado:

`docker run hello-world`

Resultado: ejecución satisfactoria. Se descargó la imagen de prueba y apareció el mensaje `Hello from Docker!`.

### Aplicación de ejemplo

También se ejecutó el proyecto de ejemplo `getting-started-todo-app` en el entorno local. Se verificó su funcionamiento desde el navegador y se probó la creación de una tarea.

## 5. Estructura del repositorio

- `.devcontainer/devcontainer.json`: configuración del entorno de desarrollo.
- `README.md`: documentación de la práctica.

## 6. Conclusión

Se logró configurar GitHub Codespaces con una imagen base de Ubuntu 22.04 y comprobar el funcionamiento de Docker y Docker Compose mediante comandos y la ejecución de un contenedor de prueba.

Las pruebas permitieron verificar el funcionamiento del entorno configurado.
