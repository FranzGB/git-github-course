# Git & Github Tutorial
[Spanish Version](README_ES.md)
# Tutorial de Git y Github
## Git

### ¿Qué es Git?

Git es un sistema de control de versiones distribuido que te permite rastrear cambios en tu código. Fue creado por Linus Torvalds en 2005. Git se utiliza para almacenar el historial de tu código y te permite colaborar con otros desarrolladores. Es una herramienta poderosa que puede ayudarte a gestionar tu código y realizar un seguimiento de los cambios.

### ¿Por qué usar Git?

Git es una herramienta poderosa que puede ayudarte a gestionar tu código y colaborar con otros desarrolladores. Te permite rastrear cambios en tu código y revertir a versiones anteriores si es necesario. Git también te permite trabajar en diferentes características o correcciones de errores de forma paralela sin interferir en el trabajo de los demás. Es una gran herramienta para gestionar tu código y colaborar con otros desarrolladores.

### Instalación de Git

Para instalar Git, puedes descargarlo desde el [sitio web oficial](https://git-scm.com/downloads). Git está disponible para los sistemas operativos Windows, Mac y Linux. Una vez que hayas descargado el instalador, puedes seguir las instrucciones de instalación para instalar Git en tu máquina.

### [Hoja de referencia de Git](https://www.git-tower.com/blog/media/pages/posts/git-cheat-sheet/b5d32c23dc-1710861692/git-cheat-sheet-large01.avif)

### Glosario

- **Repositorio**: Un repositorio es una colección de archivos y carpetas que conforman un proyecto. Contiene todo el historial del proyecto y te permite rastrear cambios en tu código.
- **Commit**: Un commit es una instantánea del código en un punto específico en el tiempo. Registra los cambios realizados en el código y te permite revertir a versiones anteriores si es necesario.
- **Branch**: Un branch es una línea de desarrollo separada en un repositorio de Git. Te permite trabajar en diferentes características o correcciones de errores de forma paralela sin interferir en el trabajo de los demás.
- **Merge**: Un merge es el proceso de combinar dos branches en uno solo. Te permite integrar cambios de un branch en otro branch.
- **Pull Request [PR]**: Un pull request es una solicitud para fusionar cambios de un branch en otro branch. Te permite revisar los cambios antes de fusionarlos en el branch principal.
- **Stage**: El stage es un área de almacenamiento temporal en Git donde puedes agregar cambios antes de confirmarlos en el repositorio.
- **Stash**: El stash es un área de almacenamiento temporal en Git donde puedes guardar cambios que no están listos para ser confirmados. Te permite guardar cambios y aplicarlos más tarde.
- **Remote**: Un remote es una copia de un repositorio de Git que se encuentra alojado en un servidor. Te permite colaborar con otros desarrolladores y compartir tu código con ellos.

### Comandos básicos de Git

#### Comandos locales (Fácil)

1. `git init`: Inicializa un nuevo repositorio de Git
1. `git add .`: Agrega todos los archivos al área de preparación
1. `git commit -m "mensaje"`: Confirma los cambios en el repositorio
1. `git status`: Verifica el estado del repositorio
1. `git log`: Muestra el historial de commits
1. `git branch`: Lista todas las ramas en el repositorio
1. `git checkout <branch>`: Cambia a una rama diferente. Si deseas crear una nueva rama, utiliza el comando `git checkout -b <branch>`. También puedes cambiar a un commit diferente utilizando `git checkout <commit-hash>`.
1. `git merge <branch>`: Fusiona los cambios de una rama en otra rama.
1. `git commit --amend`: Modifica el commit más reciente, permitiéndote cambiar el mensaje del commit o agregar cambios adicionales.

#### Comandos remotos (Fácil)

1. `git clone url`: Clona un repositorio remoto
1. `git remote add <alias> <url>`: Agrega un repositorio remoto al repositorio local
1. `git push origin <branch>`: Envía los cambios a un repositorio remoto
1. `git pull origin <branch>`: Obtiene los cambios de un repositorio remoto

#### Comandos avanzados de Git

1. `git rebase <branch>`: Rebase los cambios de una rama en otra rama
1. `git cherry-pick <commit-hash>`: Aplica los cambios de un commit específico a la rama actual
1. `git reset --hard <commit-hash>`: Restablece el repositorio a un commit específico
1. `git push --force origin <branch>`: Envía los cambios al repositorio remoto de forma forzada. Utiliza este comando con precaución, ya que puede sobrescribir cambios en el repositorio remoto. Una alternativa más segura es utilizar `git push --force-with-lease origin <branch>`. Si la rama remota tiene el mismo valor que la rama remota en tu máquina local, sobrescribirás el remoto. Si no tiene el mismo valor, indica un cambio que alguien más realizó en la rama remota mientras estabas trabajando en tu código y, por lo tanto, no sobrescribirá ningún código.
1. `git fetch`: Obtiene los cambios de un repositorio remoto sin fusionarlos en el repositorio local.
1. `git stash`: Guarda los cambios que no están listos para ser confirmados. Puedes aplicar los cambios más tarde utilizando `git stash apply`.


### Recursos útiles de Git

## Github

### ¿Qué es Github?

GitHub es una plataforma basada en web que te permite alojar tus repositorios de Git en línea. Proporciona una interfaz gráfica para gestionar tu código y colaborar con otros desarrolladores. GitHub es ampliamente utilizado por los desarrolladores para compartir su código, colaborar en proyectos y contribuir a proyectos de código abierto. Es una herramienta poderosa que puede ayudarte a gestionar tu código y colaborar con otros desarrolladores.

### ¿Por qué usar Github?

GitHub es una herramienta poderosa que puede ayudarte a gestionar tu código y colaborar con otros desarrolladores. Proporciona una interfaz gráfica para gestionar tu código y te permite colaborar con otros desarrolladores. GitHub también ofrece características como issues, pull requests y project boards que pueden ayudarte a gestionar tus proyectos de manera más efectiva. Es una gran herramienta para gestionar tu código y colaborar con otros desarrolladores.

### Creación de un repositorio en Github
