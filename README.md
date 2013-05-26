code.inMotion-MainWeb
=====================

Main web for code.inMotion project

<p>/*
Paso inicial configurar tu cuenta<br>
**/</p>

 $ git config --global user.email "you@example.com"
 $ git config --global user.name  "Your Name"


/*
Clonar el repositorio 
**/


 $ git clone https://github.com/darknautic/code.inMotion-MainWeb.git
 $ cd code.inMotion-MainWeb/
 $ git status
  # On branch master
	nothing to commit, working directory clean
	
/* 

"git status" te dira en que branch estas trabajando y que archivos 
ya modificaste o has agregado.

si quieres hacer un "commit" al branch,
agrega el archivo ( nuevo o modificado ) con el comando "git add"
para que se agregue a la lista de modificaciones que seran enviadas.

**/	

$ git add modified_file.txt
$ git add new_file.txt


/*   commit to master branch
**/

$ git commit -m "comentario"
$ git push origin master



/*
 "git log"   te permite ver tus eventos
**/


