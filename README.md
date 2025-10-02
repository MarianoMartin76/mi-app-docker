# Repo Docker + NGINX

Repositorio para prácticas del curso DevOps UTN. Contiene un Dockerfile que levanta un contenedor nginx con un html de ejemplo.


![DockerBadge](https://img.shields.io/badge/docker-257bd6?style=for-the-badge&logo=docker&logoColor=white) ![NGINX](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white&style=for-the-badge)

## Comencemos! 🚀

### Pre-requisitos 📋

Requiere [Docker](https://docs.docker.com/engine/install/) instalado


### Clonar el repo 

```bash
git clone https://github.com/MarianoMartin76/mi-app-docker.git
cd mi-app-docker
```

### Construir la imagen 🔧


```bash
docker build -t mi-app-web:latest .
```

### Probar la imagen localmente ✨


```bash
docker run -d -p 8080:80 --name mi-contenedor mi-app-web:latest
```

### Verifica que funciona accediendo a http://localhost:8080

🤓

#### Licencia

[MIT](https://choosealicense.com/licenses/mit/)
