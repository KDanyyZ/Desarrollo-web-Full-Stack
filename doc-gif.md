
## Para inicializar un repositorio en GIT:

git init

## Para dar segu

Cuando unicializamos un repo los archivos inicialmente estan en estado "Untracked" / sin seguimiento

git add index.html (Esto le da seguimiento al archivo index.html)

git add . (Esto le da seguimiento a todos los archivos de tu directorio root (raiz))

## Para exceotuar o NO dar seguimiento archivos:

O pueden ignorar archivos creando en la raiz el archivo . gitignore

##versionar

Para versionar el codigo debe estar añadido, el codigo q se versiona es el que esta añadido hasta el momento

git commint -m "Primera version en GIT" (cra una version en tu repositorio)

## Para cambiar el nombre del branch principal (opcional)

git branch -M main

## Configuramos una direccion remota para nuestro repositorio local

git remote add origin https://github.com/KDanyyZ/Desarrollo-web-Full-Stack.git

## Enviar el codigo a la direccion remota
git push -u origin main

## Como subir cambios a GitHub?

git add.
git commit -m "description"
git push

## Para crear una rama usamos

git checkout -b <Nombre-rama>

## Para movernos entre ramas

git checkout Nombre-rama
