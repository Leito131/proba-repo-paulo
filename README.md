# Guión práctica 1 (Git)
 ## Comandos empregados:

 ```bash
 git init
 ```
> 1. Inicialización do repo local
-------------------------------------------------------------------------
  ```bash
  git add .
  ```
> 2. Pasamos los cambios al "staging area"
-------------------------------------------------------------------------
  ```bash
  git commit -m ""
  ```
> 3. Se envían los cambios al repositorio local y se le agrega un mensaje.
-------------------------------------------------------------------------
  ```bash
  git log --oneline
  ```
> 4. Muestra todos los "commit" realizados al repositorio junto a su descripción.
-------------------------------------------------------------------------
  ```bash
  git branch -M main
  ```
> 5. Cambia o nome do MASTER a main.
-------------------------------------------------------------------------
  ```bash
  git remote add origin *url*
  ```
> 6. Añade un repositorio remoto que refleje el local.
-------------------------------------------------------------------------
  ```bash
  git push -u origin main
  ```
> 7. Envía a información do repositorio local ao repositorio remoto. 
-------------------------------------------------------------------------

# Guión práctica 2 (Git)

```bash
git clone "url"
```
> 1. Nos permite clonar el repositorio de GIT y añadirlo a nuestro repositorio local.
-------------------------------------------------------------------------
> 2. Creamos un CSS en GitHub de ejemplo para traerlo desde el repositorio remoto al repositorio local.
-------------------------------------------------------------------------
```bash
git pull --all
```
> 3. Este comando nos permite volcar todo el repositorio remoto a nuestro repositorio local, incluyendo el archivo que hemos creado.
-------------------------------------------------------------------------

# Guión práctica 3 (Git)

```bash
git show
```
> 1. Este comando nos muestra las diferencias entre los dos últimos "commit" realizados.
-------------------------------------------------------------------------
```bash
git diff
```
> 2. Este comando nos muestra las diferencias entre el último "commit" y el estado actual del proyecto.
-------------------------------------------------------------------------
```bash
git commit --amend
```
> 3. Este comando nos permite modificar el último "commit" realizado sin necesidad de generar otro.
-------------------------------------------------------------------------
```bash
git config --global color.ui auto
```
> 4. Este comando activa el coloreado automático para mayor legibilidad de las salidas de la consola al ejecutar unos comandos específicos.
-------------------------------------------------------------------------

