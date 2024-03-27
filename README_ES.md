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
- **Pull Request [PR]**: Un pull request es una solicitud para fusionar cambios de un branch en otro branch. Te permite revisar los cambios antes de fusionarlos en el branch principal. Esto es un termino exclusivo de Github.
- **Stage**: El stage es un área de almacenamiento temporal en Git donde puedes agregar cambios antes de confirmarlos en el repositorio.
- **Head**: El término HEAD se refiere a la instantánea actual del branch en el que estás trabajando, esencialmente apuntando al último commit realizado en ese branch.
- **Stash**: El stash es un área de almacenamiento temporal en Git donde puedes guardar cambios que no están listos para ser confirmados. Te permite guardar cambios y aplicarlos más tarde.
- **Remote**: Un remote es una copia de un repositorio de Git que se encuentra alojado en un servidor. Te permite colaborar con otros desarrolladores y compartir tu código con ellos.

![Git Distributed System](https://codelikethis.com/lessons/git/git.png)

### Comandos básicos de Git

#### Comandos locales (Fáciles)

1. `git init`: Inicializa un nuevo repositorio de Git.
2. `git status`: Verifica el estado del repositorio.
3. `git add .`: Agrega todos los archivos al área de preparación (staging area).
4. `git commit -m "mensaje"`: Confirma los cambios en el repositorio.
5. `git commit --amend`: Modifica el último commit con nuevos cambios.
6. `git log`: Muestra el historial de commits.
7. `git checkout <branch>`: Cambia a un branch diferente. Si deseas crear un nuevo branch, utiliza el comando `git checkout -b <branch>`. También puedes cambiar a un commit diferente utilizando `git checkout <commit-hash>`.
8. `git branch`: Lista todos los branches en el repositorio.
9. `git merge <branch>`: Fusiona los cambios de un branch en otro branch.

#### Comandos remotos (Fáciles)

1. `git clone url`: Clona un repositorio remoto.
2. `git remote add <alias> <url>`: Agrega un repositorio remoto al repositorio local.
3. `git push origin <branch>`: Envía los cambios a un repositorio remoto.
4. `git pull origin <branch>`: Obtiene los cambios de un repositorio remoto.

#### Comandos avanzados de Git

1. `git rebase <branch>`: Rebasea los cambios de un branch en otro branch.
2. `git cherry-pick <commit-hash>`: Aplica los cambios de un commit específico al branch actual.
3. `git reset --hard <commit-hash>`: Restablece el repositorio a un commit específico. Existen tres tipos de reset: `--soft`, `--mixed` y `--hard`. `--soft` mantiene los cambios en el área de preparación, `--mixed` mantiene los cambios en el área de trabajo y `--hard` elimina los cambios. Por defecto, es decir si no pasas una flag, se utiliza `--mixed`.
4. `git push --force origin <branch>`: Envía los cambios al repositorio remoto de forma forzada. Utiliza este comando con precaución, ya que puede sobrescribir cambios en el repositorio remoto. Una alternativa más segura es utilizar `git push --force-with-lease origin <branch>`. Con esta flag, si el branch remoto tiene el mismo valor que el branch remoto en tu máquina local, sobrescribirás el branch remoto. Si no tiene el mismo valor, indica un cambio que alguien más realizó en el branch remoto mientras estabas trabajando en tu código y, por lo tanto, no sobrescribirás ningún código.
5. `git stash`: Guarda cambios que no están listos para ser confirmados. Puedes aplicar los cambios más tarde utilizando `git stash apply`.

## Github

### ¿Qué es Github?

GitHub es una plataforma basada en la web que te permite alojar tus repositorios de Git en línea. Proporciona una interfaz gráfica para gestionar tu código y colaborar con otros desarrolladores. GitHub es ampliamente utilizado por los desarrolladores para compartir su código, colaborar en proyectos y contribuir a proyectos de código abierto. Es una herramienta poderosa que puede ayudarte a gestionar tu código y colaborar con otros desarrolladores.

### ¿Por qué usar Github?

Github es una de los servidores web más populares para alojar repositorios de Git. Muchos repositorios de código abierto están alojados en Github, lo que facilita la colaboración y la contribución a proyectos de código abierto. Github proporciona una serie de características útiles, como la gestión de problemas, pull requests, ramas y colaboración en equipo. También ofrece integración con herramientas de CI/CD, como Github Actions, y la posibilidad de automatizar tareas en tu repositorio.

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

### Issues

Los issues en GitHub son una forma de realizar un seguimiento de tareas, mejoras, errores y otras solicitudes de trabajo en tu repositorio. Puedes crear issues para discutir y realizar un seguimiento de problemas específicos en tu proyecto. Los issues pueden asignarse a colaboradores, etiquetarse, comentarse y cerrarse una vez que se hayan resuelto.

### Pro Tips

1. Usa la herramienta Github CLI para interactuar con Github desde la línea de comandos. Puedes instalarla desde [aquí](https://cli.github.com/). Comandos utiles:
    - `gh auth`: Autentica tu sesión de Github.
    - `gh repo create <nombre-repositorio>`: Crea un nuevo repositorio en Github.
    - `gh pr create`: Crea un nuevo pull request.
    - `gh issue create`: Crea un nuevo issue.
    - `gh repo clone <nombre-repositorio>`: Clona un repositorio de Github.

2. Utiliza alias en Git para abreviar comandos comunes. Puedes configurar alias en tu archivo `.gitconfig` para abreviar comandos largos y repetitivos. Por ejemplo, puedes configurar un alias `co` para `checkout` o `ci` para `commit`. Esto te permite escribir menos y ser más eficiente al trabajar con Git.

3. Utiliza las Github Actions para automatizar tareas en tu repositorio de Github. Puedes configurar acciones para ejecutar pruebas, realizar despliegues, notificar a los colaboradores y mucho más. Puedes encontrar más información sobre las Github Actions en la [documentación oficial](https://docs.github.com/en/actions).

4. Github Codespaces te permite crear un entorno de desarrollo basado en la nube directamente desde tu navegador. Puedes acceder a tu código, editar archivos y ejecutar comandos en un entorno de desarrollo completamente funcional sin necesidad de configurar un entorno local. Puedes obtener más información sobre Github Codespaces en la [documentación oficial](https://docs.github.com/en/codespaces).

5. Github Projects te permite organizar y priorizar tu trabajo en Github. Puedes crear tableros de proyectos, agregar tarjetas para tareas y problemas, y colaborar con otros miembros del equipo en un entorno visual. Puedes obtener más información sobre Github Projects en la [documentación oficial](https://docs.github.com/en/issues/organizing-your-work-with-project-boards/about-project-boards).

6. Como estudiantes o profesores, puedes obtener beneficios adicionales de Github a través de [GitHub Education](https://education.github.com/). Esto incluye acceso a herramientas y recursos gratuitos para la educación, así como la posibilidad de obtener paquetes de Github Pro gratuitos. Y acceso a Github Copilot de manera gratuita.

### Buenas prácticas

- **Escribe mensajes de commit significativos**: Utiliza mensajes de commit claros y descriptivos que expliquen los cambios realizados en el commit. Esto facilita la revisión del historial de commits y la comprensión de los cambios realizados en el proyecto. Los mensajes del commit por lo general se hacen en tiempo presente y en imperativo. Ejemplo: "Agrega función de autenticación" en lugar de "Agregó función de autenticación".
- **Crea branches para nuevas características o correcciones de errores**: Utiliza branches separados para trabajar en nuevas características o correcciones de errores. Esto te permite trabajar en paralelo sin interferir en el trabajo de los demás y facilita la revisión de los cambios antes de fusionarlos en el branch principal.
- **Realiza pull requests para revisión de código**: Antes de fusionar cambios en el branch principal, crea un pull request para que otros revisen tus cambios. Esto te permite obtener comentarios y sugerencias sobre tus cambios antes de fusionarlos en el proyecto.
- **Utiliza issues para realizar un seguimiento de tareas**: Utiliza issues para realizar un seguimiento de tareas, mejoras, errores y otras solicitudes de trabajo en tu proyecto. Esto te ayuda a organizar y priorizar el trabajo en tu proyecto y a mantener un registro de los problemas que necesitan ser abordados.
- **Commit temprano y con frecuencia**: Realiza commits con frecuencia para rastrear los cambios en tu proyecto y evitar la pérdida de trabajo. Esto te permite revertir a versiones anteriores si es necesario y facilita la colaboración con otros desarrolladores.

### Recursos adicionales

[Git Handbook](https://guides.github.com/introduction/git-handbook/)
[Git Best Practices](https://sethrobertson.github.io/GitBestPractices/)
[Pro Git Book](https://git-scm.com/book/en/v2)
