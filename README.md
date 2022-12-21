# Guión práctica 1 (Git)
 ## Comandos empregados:

 ```bash
 git init
 ```
> 1. Inicialización do repo local
------------------------------------------------------------------------
  ```bash
  git add .
  ```
> 2. Pasamos los cambios al "staging area"
------------------------------------------------------------------------
  ```bash
  git commit -m ""
  ```
> 3. Se envían los cambios al repositorio local y se le agrega un mensaje.
------------------------------------------------------------------------
  ```bash
  git log --oneline
  ```
> 4. Muestra todos los "commit" realizados al repositorio junto a su descripción.
------------------------------------------------------------------------
  ```bash
  git branch -M main
  ```
> 5. Cambia o nome do MASTER a main.
------------------------------------------------------------------------
  ```bash
  git remote add origin *url*
  ```
> 6. Añade un repositorio remoto que refleje el local.
------------------------------------------------------------------------
  ```bash
  git push -u origin main
  ```
> 7. Envía a información do repositorio local ao repositorio remoto. 
