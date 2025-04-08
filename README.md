# Actividades
## 1.Inicializacion de un repositorio GIT
**Objetivo**: Aprender a crear un repositorio local
**Instrucciones**
1. Abrir una Terminal
2. Navegar a la carpeta del proyecto
```bash
cd mi_proyecto
```
3. Inicializar el repositorio GIT con el comando:
```bash
git init
```
4. Verificar el estado con:
```
git status
```

## 2. Realizar el primer commit
**Objetivo**: Realizar el primer commit local
**Instrucciones**
1. Crear un archivo index.html o README.md.
2. Agregar contenido a los archivos.
3. Usar `git add .` para agregar el archivo al area de preparacion.
4. Realizar un commit con el comando 
```bash
git commit -m "Primer commit"
```
5. Verificar el estado con el comando
```bash
git log
```
Para asegurarse de que el commit se realizo correctamente

## 3. Creacion y conexion a un repositorio GITHUB
**Objetivo**: Crear un repositorio remoto en github y vincular con el repositorio local
**Instrucciones**
1. Crear una cuenta en GITHUB [GITHUB](https://github.com)
2. Crear un nuevo repositorio en GITHUB (sin inicializar el README ni archivos).
3. En la terminal, agregar el repositorio remoto
```
git remote add origin su_direccion_url_github
```
4. Verificar que se haya agregado correctamente
```bash
git remote -v
```
5. Sube el primer commit a GITHUB con
```bash
git push origin master
```

## 4. Crear y trabajar con ramas
**Objetivo**: Aprender a crear y trabajar con ramas
**Instrucciones**
1. Crear una nueva rama llamada `ramaDesarrollo`

```bash
git branch ramaDesarollo
```

2. Cambiar a la `ramaDesarollo` con:
```bash
git checkout ramaDesarrollo
```

3. Realizar cambios en sus archivos

4. Agrega y realizar un commit de los cambios con:
```bash
git add .
git commit -m "Cambios en la ramaDesarrollo"
```
5. Volver a la rama `master`
```bash
git checkout master
```
6. Fusionar la `ramaDesarrollo` a `master`
```bash
git merge ramaDesarrollo
```
