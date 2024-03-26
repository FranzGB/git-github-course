# Git & Github Tutorial
[Version en Ingles](README.md)

## Git

### ¿Qué es Git?

Git es un sistema de control de versiones distribuido que te permite rastrear cambios en tu código. Fue creado por Linus Torvalds en 2005. Git se utiliza para almacenar el historial de tu código y te permite colaborar con otros desarrolladores. Es una herramienta poderosa que puede ayudarte a gestionar tu código y realizar un seguimiento de los cambios.

### ¿Por qué usar Git?

Git es una herramienta poderosa que puede ayudarte a gestionar tu código y colaborar con otros desarrolladores. Te permite rastrear cambios en tu código y revertir a versiones anteriores si es necesario. Git también te permite trabajar en diferentes características o correcciones de errores de forma paralela sin interferir en el trabajo de los demás. Es una excelente herramienta para gestionar tu código y colaborar con otros desarrolladores.

### Instalación de Git

Para instalar Git, puedes descargarlo desde el [sitio web oficial](https://git-scm.com/downloads). Git está disponible para los sistemas operativos Windows, Mac y Linux. Una vez que hayas descargado el instalador, puedes seguir las instrucciones de instalación para instalar Git en tu máquina.

### [Cheat Sheet de Git](https://www.git-tower.com/blog/media/pages/posts/git-cheat-sheet/b5d32c23dc-1710861692/git-cheat-sheet-large01.avif)

### Glosario

- **Repositorio**: Un repositorio es una colección de archivos y carpetas que conforman un proyecto. Contiene todo el historial del proyecto y te permite rastrear cambios en tu código.
- **Commit**: Un commit es una instantánea del código en un punto específico en el tiempo. Registra los cambios realizados en el código y te permite revertir a versiones anteriores si es necesario.
- **Branch**: Un branch es una línea de desarrollo separada en un repositorio de Git. Te permite trabajar en diferentes características o correcciones de errores de forma paralela sin interferir en el trabajo de los demás.
- **Merge**: Un merge es el proceso de combinar dos branches en uno solo. Te permite integrar cambios de un branch en otro branch.
- **Pull Request [PR]**: Un pull request es una solicitud para fusionar cambios de un branch en otro branch. Te permite revisar los cambios antes de fusionarlos en el branch principal.
- **Stage**: El stage es un área de almacenamiento temporal en Git donde puedes agregar cambios antes de confirmarlos en el repositorio.
- **Head**: El término HEAD se refiere a la instantánea actual del branch en el que estás trabajando, esencialmente apuntando al último commit realizado en ese branch.
- **Stash**: El stash es un área de almacenamiento temporal en Git donde puedes guardar cambios que no están listos para ser confirmados. Te permite guardar cambios y aplicarlos más tarde.
- **Remote**: Un remote es una copia de un repositorio de Git que se encuentra alojado en un servidor. Te permite colaborar con otros desarrolladores y compartir tu código con ellos.

### Comandos básicos de Git

#### Comandos locales (Fáciles)

1. `git init`: Inicializa un nuevo repositorio de Git.
2. `git status`: Verifica el estado del repositorio.
3. `git add .`: Agrega todos los archivos al área de preparación (staging area).
4. `git commit -m "mensaje"`: Confirma los cambios en el repositorio.
5. `git log`: Muestra el historial de commits.
6. `git checkout <branch>`: Cambia a un branch diferente. Si deseas crear un nuevo branch, utiliza el comando `git checkout -b <branch>`. También puedes cambiar a un commit diferente utilizando `git checkout <commit-hash>`.
7. `git branch`: Lista todos los branches en el repositorio.
8. `git merge <branch>`: Fusiona los cambios de un branch en otro branch.

#### Comandos remotos (Fáciles)

1. `git clone url`: Clona un repositorio remoto.
2. `git remote add <alias> <url>`: Agrega un repositorio remoto al repositorio local.
3. `git push origin <branch>`: Envía los cambios a un repositorio remoto.
4. `git pull origin <branch>`: Obtiene los cambios de un repositorio remoto.

#### Comandos avanzados de Git

1. `git rebase <branch>`: Rebasea los cambios de un branch en otro branch.
2. `git cherry-pick <commit-hash>`: Aplica los cambios de un commit específico al branch actual.
3. `git reset --hard <commit-hash>`: Restablece el repositorio a un commit específico.
4. `git push --force origin <branch>`: Envía los cambios al repositorio remoto de forma forzada. Utiliza este comando con precaución, ya que puede sobrescribir cambios en el repositorio remoto. Una alternativa más segura es utilizar `git push --force-with-lease origin <branch>`. Si el branch remoto tiene el mismo valor que el branch remoto en tu máquina local, sobrescribirás el branch remoto. Si no tiene el mismo valor, indica un cambio que alguien más realizó en el branch remoto mientras estabas trabajando en tu código y, por lo tanto, no sobrescribirás ningún código.
5. `git fetch`: Obtiene los cambios de un repositorio remoto sin fusionarlos en el repositorio local.
6. `git stash`: Guarda cambios que no están listos para ser confirmados. Puedes aplicar los cambios más tarde utilizando `git stash apply`.
7. `git commit --amend`: Modifica el último commit con nuevos cambios.

## Github

### ¿Qué es Github?

GitHub es una plataforma basada en la web que te permite alojar tus repositorios de Git en línea. Proporciona una interfaz gráfica para gestionar tu código y colaborar con otros desarrolladores. GitHub es ampliamente utilizado por los desarrolladores para compartir su código, colaborar en proyectos y contribuir a proyectos de código abierto. Es una herramienta poderosa que puede ayudarte a gestionar tu código y colaborar con otros desarrolladores.

### ¿Por qué usar Github?

GitHub es una herramienta poderosa que puede ayudarte a gestionar tu código y colaborar con otros desarrolladores. Proporciona una interfaz gráfica para gestionar tu código y te permite colaborar con otros desarrolladores. GitHub también ofrece características como issues, pull requests y project boards que pueden ayudarte a gestionar tus proyectos de manera más efectiva. Es una excelente herramienta para gestionar tu código y colaborar con otros desarrolladores.

### Crear un repositorio en Github

Aquí tienes una guía paso a paso sobre cómo crear un nuevo repositorio en GitHub:

#### 1. Inicia sesión en GitHub
Primero, debes iniciar sesión en tu cuenta de GitHub. Si no tienes una cuenta, deberás crear una en [github.com](https://github.com/).

#### 2. Crea un nuevo repositorio
- Una vez que hayas iniciado sesión, ve a tu panel de control de GitHub. Puedes crear un nuevo repositorio haciendo clic en el icono "+" en la esquina superior derecha de la página y seleccionando "New repository" en el menú desplegable.
- Alternativamente, puedes ir directamente a la página de creación de repositorios utilizando esta URL: [https://github.com/new](https://github.com/new).

#### 3. Configura tu repositorio
- **Nombre del repositorio**: Ingresa un nombre único para tu repositorio. Este nombre formará parte de la URL de tu repositorio.
- **Descripción** (opcional): Proporciona una breve descripción de tu proyecto. Esto ayuda a otros a comprender de qué se trata tu proyecto y se puede encontrar en los resultados de búsqueda.
- **Visibilidad**: Elige si tu repositorio será público (visible para cualquiera) o privado (visible solo para ti y aquellos a quienes les otorgues acceso).
- **Inicializar este repositorio con**: Aunque es opcional, a menudo es útil inicializar el repositorio con un archivo README, que puede incluir información sobre tu proyecto. También puedes agregar un archivo `.gitignore`, que especifica archivos no rastreados intencionalmente para ignorar, y elegir una licencia para tu proyecto.

#### 4. Crea el repositorio
- Después de configurar tu repositorio, haz clic en el botón "Create repository" en la parte inferior de la página.

#### 5. Clona el repositorio (opcional)
- Una vez que se haya creado el repositorio, es posible que desees clonarlo en tu máquina local para comenzar a trabajar en tu proyecto. Puedes hacer esto haciendo clic en el botón "Code" en la página de tu repositorio, copiando la URL proporcionada y luego utilizando el comando `git clone <repository-url>` en tu terminal o símbolo del sistema.

#### Puntos clave
- **README.md**: Un archivo Markdown donde puedes presentar y explicar tu proyecto. Admite formato y puede contener imágenes, enlaces y documentación estructurada.
- **.gitignore**: Un archivo de texto que enumera archivos o directorios que Git debe ignorar. Útil para excluir archivos de configuración local, directorios de compilación o archivos que contienen información confidencial.
- **Licencia**: Elegir una licencia es importante si tienes la intención de compartir tu código. Define cómo otros pueden usar, modificar y distribuir tu código.

### Fork
Un fork en Git es esencialmente una copia de un repositorio que te permite experimentar libremente con cambios sin afectar el proyecto original. Este concepto se utiliza ampliamente en el desarrollo de código abierto en plataformas como GitHub, donde hacer un fork de un repositorio te permite hacer tus propias modificaciones, agregar nuevas características o corregir errores en el proyecto de forma independiente al repositorio principal.

