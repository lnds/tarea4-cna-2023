# Tarea 4 (opcional)

Haz un fork de este repo.

# Prerequisitos

Tener una cuenta en dockerhub.

# Actividad

Configura los secrets: `DOCKER_USERNAME` y `DOCKER_PASSWORD`. Para esto navega hasta `settings` / `Security` / `Secrets and variables` / `Actions`.

Basándose en el github action `.github/workflows/frontend-publish.yml` debes crear otros dos actions para publicar las imágenes para `users-svc` y para `ws-service`.

Crea las acciones, prúebalas y asegurate que quedan publicadas en docker-hub.

Manda un Pull Request con las acciones creadas.

Agrega una imagen de docker-hub donde se vean las imagenes creadas.

Agrega los nombres de los miembros del equipo a este archivo.

IMPORTANTE: la linea 26 dice:

               images: lnds/labcna-chat-frontend

Deben cambiar `lnds` por el nombre de usuario de ustedes en docker-hub.



## Respuestas:

Integrantes:
-Bryan Vicente Soto Astudillo

Imagenes de evidencia:
-Actions ejecutados github.png
-validacion_dockerhub.png
