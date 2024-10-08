# Configuración inicial Git
`git init`  
Crea Repositorio Git (carpeta) lugar donde se va a guardar todo el historial de cambios realizados de codigo y tambien guarda un estado del software en cada uno de los cambios


## Configuración básica global
|       |                                           |
|-------|-------------------------------------------|  
|Nombre |`git config --global user.name "Nombre"`   |
|Email  |`git config --global user.email "email"`   |
|Editor |`git config --global core.editor "vim"`    |

## Ver configuración 
|       |                                  |
|-------|----------------------------------|  
|Nombre |`git config user.name "Nombre"`   |
|Email  |`git config user.email "email"`   |
|Editor |`git config core.editor "vim"`    |
|Ayuda  |`git global --help`               |  

# Comandos Git  
|                                               |                                  |
|-----------------------------------------------|----------------------------------|  
|Abrir carpeta                                  |`open .` o `start .c`             |
|Abrir IDE                                      |`code .`                          |
|Muestra estado del proyecto                    |`git status`                      |
|Agrega los cambios del proyecto                |`git add archivo`                 |
|Confirma los cambios del proyecto              |`git commit -m "mensaje"`         |
|Elimina el último commit                       |`git reset --hard HEAD^ `         |
|Renombra archivo                               |`git mv archivo nuevoArchivo`     |
|Muestra todos los commits                      |`git log`                         |
|Agrega todos los archivos de la carpeta        |`git add .`                       |
|Agrega todo los archivos del proyecto          |`git add -A`                      |
|Elimina archivo del stage                      |`git restore --staged archivo`    |
|Restaura los cambios del archivo               |`git checkout archivo`            |
|Muestra detalles del commit                    |`git show idcommit`               |
|Muestra los commit por linea                   |`git log --oneline`               |
|Muestra todos los commits de un archivo        |`git log archivo`                 |
|Muestra todos los commits hechos por autor     |`git log --author="autor"`        |
|Busca todos los commits por palabra            |`git log --grep="palabra"`        |
|Muestra todos los commits de forma grafica     |`git log --graph`                 |
|Muetra como se encontraba el proyecto          |`git checkout idcommit`           |
|Cambia a la rama master                        |`git checkout master`             |
|Muestra todas las ramas del proyecto           |`git branch`                      |
|Crea nueva rama                                |`git checkout -b nuevaRama`       |
|Elimina una rama                               |`git branch -d rama`              |
|Crea nueva rama                                |`git switch -c nuevaRama`         |
|Cambia de rama                                 |`git switch rama`                 |
|Muestra diferencias entre las ramas            |`git diff rama`                   |
|Fusiona rama                                   |`git merge rama`                  |
|Verifica si esta siendo sincronizada en la nube|`git remote -v `                  |
|Sincroniza con la nube                         |`git remote add origin url`       |
|Sube a la nube                                 |`git push origin rama`            |
|Da informacion de cambios en la nube           |`git fetch`                       |
|Baja de la nube                                |`git pull origin rama`            |
|Clona repositorio                              |`git clone url`                       |