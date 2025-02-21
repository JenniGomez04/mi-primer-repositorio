# mi-primer-repositorio-
Trabajo de Git y GitHub 

NOMBRE: Jennifer Andrea Gómez Restrepo

¿Qué es Git y cuál es su función en el desarrollo de software?
Git es un sistema de control de versiones distribuido que permite gestionar cambios en el código, facilitando la recuperación de versiones anteriores y la colaboración entre desarrolladores.

Diferencias entre Git y otros sistemas de control de versiones:

Git es distribuido, lo que permite trabajar sin conexión, a diferencia de SVN, que es centralizado.
Git maneja mejor las ramas y es más rápido.
Usa hashing (SHA-1) para mayor seguridad.
¿Qué es el branching en Git?
El branching permite crear ramas para trabajar en cambios sin afectar la versión principal, facilitando el trabajo paralelo y la seguridad del código.

Diferencia entre Git y GitHub:

Git es un sistema de control de versiones local.
GitHub es una plataforma en la nube que usa Git para alojar repositorios y facilitar la colaboración.
Características principales de GitHub:

Alojamiento de repositorios Git.
Control de versiones.
Integraciones con otras herramientas.
Seguridad y gestión de acceso.
GitHub Actions para automatización.
Ventajas de Git sobre métodos tradicionales:

Historial completo de cambios.
Mejor gestión del trabajo en equipo.
Trabajo sin conexión con copias locales.
Mayor velocidad y seguridad.
Repositorios en Git:

Local: En la computadora del usuario.
Remoto: En un servidor o la nube.
Público: Accesible para cualquiera.
Privado: Acceso restringido.
Principales comandos de Git:


Inicialización y configuración
git init → Inicializa un nuevo repositorio en la carpeta actual.
git config --global user.name "Tu Nombre" → Configura tu nombre de usuario.
git config --global user.email "tuemail@example.com" → Configura tu correo electrónico.

Trabajando con repositorios
git clone <URL> → Clona un repositorio remoto en la máquina local.
git remote add origin <URL> → Conecta un repositorio local con un repositorio remoto.
git remote -v → Muestra las conexiones con repositorios remotos.

Manejo de archivos
git status → Muestra el estado del repositorio y los cambios pendientes.
git add <archivo> → Agrega un archivo al área de preparación (staging).
git add . → Agrega todos los archivos modificados al área de preparación.
git reset <archivo> → Quita un archivo del área de preparación.

Guardando cambios
git commit -m "Mensaje" → Guarda los cambios en el historial del repositorio.
git commit -am "Mensaje" → Agrega y guarda cambios en un solo comando (solo para archivos ya en seguimiento).

Manejo de ramas (branching)
git branch → Muestra las ramas existentes.
git branch <nombre> → Crea una nueva rama.
git checkout <rama> → Cambia a otra rama.
git checkout -b <rama> → Crea y cambia a una nueva rama.
git merge <rama> → Fusiona la rama especificada con la actual.
git branch -d <rama> → Elimina una rama local.

Sincronización con repositorio remoto
git pull origin <rama> → Descarga y fusiona los cambios del repositorio remoto.
git push origin <rama> → Sube los cambios al repositorio remoto.
git push -u origin <rama> → Sube los cambios y establece la rama remota como predeterminada.

Historial y revisión de cambios
git log → Muestra el historial de commits.
git log --oneline → Muestra el historial de commits en una sola línea.
git diff → Muestra las diferencias entre archivos modificados y la última versión confirmada.
git show <ID_commit> → Muestra los cambios de un commit específico.

Deshacer cambios
git checkout -- <archivo> → Revierte los cambios en un archivo no confirmado.
git reset --soft HEAD~1 → Deshace el último commit pero mantiene los cambios en el área de preparación.
git reset --hard HEAD~1 → Elimina el último commit y los cambios asociados.

Etiquetas (tags)
git tag <nombre> → Crea una etiqueta en el commit actual.
git tag -a <nombre> -m "Mensaje" → Crea una etiqueta anotada con un mensaje.
git push origin --tags → Sube las etiquetas al repositorio remoto.

Issues en GitHub:
Permiten reportar errores, solicitar mejoras y discutir cambios en el código.

