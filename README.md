Este es un readme hecho desde el terminal para comandos importantes de git.
El objetivo de este documento es recordarme a mí las funcionalidades, no creo que tenga fines de estudio, porque nada está explicado a profundidad.

Sin embargo, https://www.atlassian.com/git/tutorials/learn-git-with-bitbucket-cloud , en esta página hay una guía detallada para entender git.


# Iniciales

git init: Inicializa un repositorio en la carpeta en la que está ubicado el terminal, sin embargo, también se le puede indicar la ubicación para inicializar el repo ( git init <dirección>)
git commit: Guarda un momento específico del estado del código, pero antes de ejecutarlo, debo hacer uso de git add.
git add: Guarda los archivos específicos que quiero enviar a commit.
- Ejemplo: 
    git add <nombre archivos>
    git commit -m "Este comite contiene los archivos que agregué en el add"

Con lo anterior, hice mi primer commit, sólo con los archivos que anteriormente específiqué que quería agregar

git log --oneline: Me permite ver todos mis commits y sus códigos, a ellos puedo acceder con gitCheckout

git remote: Crea una señalización directa a las ubicaciones remotas
- ejemplo
    git remote alejo www.repoalejo.com

git checkout: Me permite moverme entre ramas y entre commits, al ubicarme en una rama puedo acceder a todos sus commits, en cambio al ubicarme sobre un commit, no tengo acceso a nada más y si quiero empezar a trabajar desde ese commit debo crearle una rama, no crear esa rama genera un "DETACHED mode" que me indica que lo que haga no será tomado en cuenta y será borrado.
- ejemplo:
    git checkout rama1
    git checkout commit1

