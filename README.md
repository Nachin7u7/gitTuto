git init <- iniciar git en el reporitorio LOCAL (crea la carpeta .git)
git add . <- añade todos los archivos (-A tambien es valido)
git add <archivo> <- añade archivo especifico
git commit -m "<mensaje>" <- commitear cambios
git branch <nombre del branch> <- crear branch
git remote add origin <url> <- añadir destino de repositorio remoto (a que repo va a ir los files)
git push <nombre del destino (generalmente origin)> <nombre del branch> <- subir al repositorio REMOTO
git pull --rebase <nombre del destino URL> <nombre del branch> <- jalar los datos del repositorio REMOTO