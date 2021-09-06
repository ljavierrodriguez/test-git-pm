### Iniciar Proyecto GIT

    $ git init

### Saber el estado del respositorio

    $ git status

### Preparar archivos (unstage)

    $ git add <file>
    $ git add -A
    $ git add .
    $ git add *

### Guardar archivos en el repositorio

    # me abre un editor
    $ git commit 
    # guardo automaticamente con un mensaje
    $ git commit -m "Añadiendo mi archivo README.md 2"


### Saber configuracion de usuario de git

    $ git config user.name
    $ git config user.email

### Configurar name y email en git de manera local y global

    $ git config user.name "Nombre Usuario"
    $ git config user.email "email@domain.com"

    $ git config --global user.name "Nombre Usuario"
    $ git config --global user.email "email@domain.com"

### Mostrar historial de Commits

    $ git log