# IAC Lab 01 - Despliegue Web con Docker y Nginx

## Descripción

Este proyecto consiste en el despliegue de dos aplicaciones web estáticas utilizando Docker y Nginx.  
Cada aplicación muestra un contenido HTML diferente:

- Web01 → muestra "Web 01"
- Web02 → muestra "Web 02"

---

## Estructura del Proyecto
│
├── docker-compose.yml
├── README.md
└── src/
├── web01/
│ ├── Dockerfile
│ └── index.html
│
└── web02/
├── Dockerfile
└── index.html

---

## Tecnologías utilizadas

- Docker
- Docker Compose
- Nginx

---

## Despliegue

### 1. Construir y levantar los contenedores

```bash
docker compose up -d --build