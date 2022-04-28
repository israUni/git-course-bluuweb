# Curso de Git con @bluuweb

### Comandos básicos de GIT:

```git init```
Sirve para iniciar nuestro registro/repositorio de GIT

```git add .```
Añadimos o creamos nuestro primer "elemento" en el "árbol" de nuestro repositorio

```git commit -m "Your descriptive comment here"```
Añadimos un comentario ***descriptivo*** de lo que hicimos/modificamos en nuestro proyecto

```git log oneline```
Nos permite verificar las elementos/commits creados de nuestro repositorio

```git remote add origin https://github.com/israUni/git-course-bluuweb.git```
Después de crear nuestro repositorio en github.com, podremos enlazar nuestro proyecto a dicho repositorio

```git push```
Ayuda a subir los cambios a nuestro repositorio

```git clone https://github.com/israUni/git-course-bluuweb.git```
Comando para clonar un repositorio existente en github.com

Dentro del desarrollo de aplicaciones, generalmente se hace uso del archivo *.gitignore*, donde establecemos las carpetas/archivos que no queremos que git les de seguimiento, por ejemplo:
```
app.js // Ignora el archivo app.js
*.css // Ignora todos los archivos con extensión .css
node_modules // Ignora toda la carpeta con el nombre node_modules
```
