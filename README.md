# MI NUEVO PRY CON COMANDOS GIT
# COMANDOS CREAR ARCHIVO

# 1. CREAR UNA CARPETA Y ENTRAR EN ELLA 
###### mkdir miPrimerPryConComandos  -> crear carpeta con nombre
###### cd miPrimerPryConComandos     -> entrar en esa CARPETA


# 2. INICIALIZAR GIT 
###### git init    -> Inicializar GIT

# 3. CREAR ARCHIVOS
###### echo "# MI NUEVO PRY CON COMANDOS GIT" > README.md 

# 4. AGREGAR Y HACER COMMIT
###### git add .   ->> todos los cambios
###### git commit -m "mi primer commit"   ->> subir comit con nombre
###### git push origin main  -> subir de la rama main

###### git add nombreDelArchivo  ->> solo un archivo en especifico
###### git add app.js    -> si solo quiero agregar ese archivo
###### git commit -m "Actualizo funciones en app.js" --> ese archivo con nombre del commit
###### git push origin main  -> subir de la rama main


# 4. LOGUEARSE EN GIT (si es que no se tiene) 
###### gh auth login
###### --Elige: GitHub.com
###### --Método: HTTPS
###### --Luego: Login with a web browser
###### --Abre el navegador y copia el código que te da la terminal

# 5. CREAR REPOSITORIO EN GITHUB 
###### gh repo create miPrimerPryConComandos --public --source=. --remote=origin --push

# -------------------- RAMAS -----------
###### git branch  --> ver ramas existentes
###### git branch main  --> crear nueva rama (main)
###### git checkout main  --> camboiar de rama 
###### git push origin nombre-rama  --> subir la nueva rama
###### git push origin main
 