<<<<<<< HEAD:gitcommands.md
# 📘 Comandos Git con Explicación

## 🔧 Inicialización y Configuración

| Comando | Descripción |
|--------|-------------|
| `git init` | Inicializa un nuevo repositorio Git en el directorio actual. |
| `git config` | Configura opciones como nombre de usuario, correo, editor, etc. |
| `git config --global user.name "Tu Nombre"` | Define el nombre de usuario global para los commits. |
| `git config --global user.email "email@ejemplo.com"` | Define el correo electrónico global para los commits. |
| `git config --list` | Muestra la configuración actual de Git. |

---

## 📥 Repositorios Remotos

| Comando | Descripción |
|--------|-------------|
| `git clone <url>` | Clona un repositorio remoto a tu equipo local. |
| `git remote -v` | Muestra las URL de los repositorios remotos configurados. |
| `git remote add origin <url>` | Asocia el repositorio local con uno remoto llamado `origin`. |
| `git push origin <rama>` | Sube los commits de una rama al repositorio remoto. |
| `git pull` | Descarga y fusiona los cambios del remoto. |
| `git fetch` | Descarga los cambios del remoto sin fusionar. |

---

## 🧠 Control de Versiones

| Comando | Descripción |
|--------|-------------|
| `git add <archivo>` | Agrega un archivo al área de staging (preparación). |
| `git add .` | Agrega todos los archivos modificados al staging. |
| `git commit -m "Mensaje"` | Guarda los cambios con un mensaje descriptivo. |
| `git status` | Muestra el estado actual del repositorio. |
| `git log` | Muestra el historial de commits. |
| `git diff` | Muestra diferencias entre archivos modificados y el último commit. |

---

## 🌿 Ramas (Branches)

| Comando | Descripción |
|--------|-------------|
| `git branch` | Lista todas las ramas locales. |
| `git branch <nombre>` | Crea una nueva rama. |
| `git checkout <rama>` | Cambia a otra rama. |
| `git checkout -b <rama>` | Crea y cambia a una nueva rama. |
| `git merge <rama>` | Fusiona una rama con la actual. |
| `git branch -d <rama>` | Elimina una rama local (si ya se fusionó). |

---

## 📦 Comandos Útiles

| Comando | Descripción |
|--------|-------------|
| `git reset <archivo>` | Quita un archivo del área de staging. |
| `git reset --hard` | Revierte el directorio al último commit (elimina cambios locales). ⚠️ |
| `git clean -f` | Elimina archivos no rastreados. ⚠️ |
| `git stash` | Guarda temporalmente los cambios sin confirmar. |
| `git stash pop` | Recupera los cambios guardados con `stash`. |
| `git rebase <rama>` | Reescribe el historial de una rama para mantenerlo lineal. |

---

## 🔍 Inspección y Ayuda

| Comando | Descripción |
|--------|-------------|
| `git show` | Muestra los detalles de un commit específico. |
| `git blame <archivo>` | Muestra quién modificó cada línea del archivo. |
| `git help` | Muestra ayuda general de Git. También funciona como `git help <comando>`. |

---

## ✅ Ejemplo de Flujo de Trabajo

```bash
git init
git add .
git commit -m "Primer commit"
git remote add origin https://github.com/usuario/repositorio.git
git push -u origin main
=======
git init : "Inicializa un repositorio en la PC"
git commit : "Sincroniza la información del repositorio Local y en la Nube"

>>>>>>> b299ae25f718c571086cc39e65a8dbce11d478b1:gitcommandsruben.md
