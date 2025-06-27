# ¿Qué es _Git_?

**Git** es un sistema de control de versiones que sirve para:

* Guardar el historial de los cambios que se hacen en los archivos, código o documentos.
* Volver a versiones anteriores.
* Trabajar en equipo sin pisar el trabajo entre compañeros.
* Crear ramas para probar cosas sin afectar el resto del proyecto.
  Se Utiliza localmente, desde la terminal o con programas como GitKraken, VSCode, GitHub Desktop, etc.

# ¿Qué es _GitHub_?

**GitHub** es una plataforma online para guardar proyectos Git.

* Guarda en línea los repositorios, para mantener una copia de seguridad y acceder desde cualquier lugar.
* Colaborar con otros, hacer revisiones de código, sugerencias y comentarios.
* Mostrar los trabajos (portfolio, proyectos personales, etc)
* Revisar el código, aprobar cambios en proyectos compartidos.
* Cotrol de acceso, público o privado.
  GitHub utiliza Git por detrás para almacenar los proyectos.

## Comandos básicos de GIT

**git init** : Inicializa un repositorio en la carpeta actual.

**git clone <URL>** : Clona un repositorio remot (como uno en GitHub) en tu PC. Copia todos los archivos del hitorial.

**git commit -m "Mensaje"** : Registra los cambios agregados con un mensaje descriptivo. Es como sacar una 'foto' del estado actual.

**git status** : Muestra el estado de los archivos: si hay cambios sin guardar, sin hacer commit.

**git add .** : Agrega todos los archivos modificados al área de preparación.

**git push** : Envía los commits locales al repositorio remoto (como GitHub).

**git pull** : Trae los cambios desde el repositorio remoto y los fusiona con el código local.

**git fetch** : Descarga los cambios del repositorio remoto pero no los fusiona. (Sirve para ver si hay algo nuevo en el código local).

**git merge** : Fusiona cambios de una rama con la rama actual (como por ejemplo combinar lo que descargó con git fetch).

**git log** : Muestra un historial de commits del repositorio.

**git diff** : Muestra los cambios entre archivos (por ejemplo, entre lo que hay en la carpeta local y lo que está guardado en Git).

### Otros comandos útiles

**git remote -v** : Muestra las URL's de los repositorios remotos configurados.

**git remote add origin <URL>** : Asocia el repositorio local con un repositorio remoto, como GitHub.

**git reset --hard HEAD** : Revierte todos los archivos a su último commit. Con este comando hay que tener cuidado porque se pierden todos los cambios no guardados.

**git stash** : Guarda cambios no se ejecutaron con commit para ser recuperados luego. Sirve para cambiar de rama sin perder el trabajo.

**git stash pop** : Recupera los datos guardados con _stash_

**git config --global user.name _"Tu nombre"_** : Configura tu nombre de usuario para los commits.

**git config --global user.email "tu@email"** : Configura tu email para los commits.

# Trabajo con ramas

**git branch** : Muestra las ramas existentes y en cuál estás.

**git branc <nombre>** : Crea una nueva rama.

**git checkout <rama>** : Cambia de rama.

**git checkout -b <rama>** : Crea y cambia una nueva rama en un solo paso.

**git merge <rama>** : fusiona la rama especificada con la rama actual.

**git branch -d <rama>** : Elimina una rama local.



