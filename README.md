EJERCICIOS GIT.

2.0 cd EjGit # Me situo en la carpeta que quiero que sea mi Repositorio local
    git init # Lo inicializo
2.1 Crear Repositorio remoto en GitHub 
2.2 git	clone git@github.com:plopez76/campusciff2.git # Clonar Repositorio en local
2.3 touch README.md # Creo el archivo README.md
    notepad README.md #Cambi� por defecto el editor de texto a notepad porque me resulta mas amigable; el comando que                        utilic� fue: git config --global core.editor notepad.
    git add README.md #a�ado README.md a Staging area
2.4 git commit -m'commit inicial' subo README.md a mi repositorio local
2.5 git push -u origin master #Subo README.md a mi repositorio remoto
