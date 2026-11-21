# Control de Rescate y Adopción - Maquetación HTML5

Unidad 2 - Desarrollo de Sistemas Informáticos (UTM).

## Estructura
- index.html: Dashboard principal
- reportar.html: Formulario de nuevo rescate
- rescates.html: Listado de casos
- assets/img/: imágenes

## Gitflow
git checkout develop
git checkout -b feature/maquetacion-html
git add .
git commit -m "feat: maquetación HTML5 semántica (index, reportar, rescates)"
git push -u origin feature/maquetacion-html
git checkout develop
git merge feature/maquetacion-html
git push origin develop
