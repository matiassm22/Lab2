# Laboratorio 2 - Aplicaciones y Tecnologías Web

##  Equipo Machin

* Matías Muñoz
* Andrés Leiva
* Alem Rodriguez
* Dario Ubilla
* Vicente Galleguillos

---

##  Descripción del Proyecto

Este proyecto consiste en el desarrollo de un sitio web estático que presenta la información de un equipo de trabajo, incluyendo el portafolio individual de cada integrante.

El sitio fue desarrollado utilizando HTML y CSS, y posteriormente desplegado mediante Docker, permitiendo su ejecución en un contenedor independiente del sistema operativo.

---

##  Contenido del Sitio

El proyecto incluye las siguientes secciones:

*  Página principal (index.html): presentación del equipo

*  Páginas de integrantes:

  * Información personal
  * Portafolio de proyectos con descripción
  * Lenguajes de programación
  * Motores de base de datos
  * Intereses

*  Sección Docker (docker.html):
  Explicación de Docker, requisitos, instalación y uso

*  Sección Comandos (comandos.html):
  Comandos esenciales para trabajar con Docker

---

##  Tecnologías Utilizadas

* HTML
* CSS3
* Docker
* Nginx

---

##  Ejecución con Docker

1. Construir la imagen:

docker build -t lab2 .

2. Ejecutar el contenedor:

docker run -d -p 8081:80 lab2

3. Abrir en el navegador:

http://localhost:8081

---

##  Estructura del Proyecto

Lab2/
│
├── index.html
├── docker.html
├── comandos.html
├── integrante1.html
├── integrante2.html
├── integrante3.html
├── integrante4.html
├── integrante5.html
├── styles.css
├── Dockerfile
└── img/

---