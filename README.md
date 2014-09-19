##SISTEMAS Y TECNOLOGÍAS WEB: Tareas Iniciales

**Autora:** Noelia Rodríguez Martín

**Fecha:** 18 de septiembre de 2014

**Details:** Instalamos rvm, las gemas sinatra y twitter, también git, creamos una cuenta en github, creamos un tutorial en formato Markdown y 
generamos un HTML de Markdown con kramdown.

###Instalación de Ruby

Ruby es un lenguaje de programación interpretado, reflexivo y orientado a objetos.

En primer lugar instalamos ruby, ya lo había instalado el año pasado por lo que no tuve ningún problema, para ello utilizamos el siguiente 
comando: 

`sudo apt-get install ruby`

![Alt text](https://raw.githubusercontent.com/alu0100724622/tareas_iniciales/master/imag/ruby.png)

###Instalación de rvm

Rvm es una herramienta que permite instalar fácilmente, gestionar y trabajar con múltiples entornos de Ruby.

Para instalar rvm previamente necesito tener instalado 'curl' y en mi caso no lo tengo, por lo que lo instalamos: 

`sudo apt-get install curl` 

![Alt text](https://raw.githubusercontent.com/alu0100724622/tareas_iniciales/master/imag/curl.png)

Y una vez que ya disponemos de esta herramienta ya podemos instalar rvm: 

`\curl -#L https://get.rvm.io | bash -s stable --autolibs=3 --ruby`

![Alt text](https://raw.githubusercontent.com/alu0100724622/tareas_iniciales/master/imag/rvm.png)
								
**NOTA:** debemos cerciorarnos que el usuario no es administrador ni tampoco root. 

A continuación vamos al fichero '~/.bash_profile' y añadimos la siguiente línea sin borrar nada de lo que ya teniamos: 

`source #HOME/.rvm/scripts/rvm`

Esto es importante hacerlo para que el rvm se ejecute cada vez que enciendes la máquina, porque si no lo ponemos no se ejecuta al reiniciar.

![Alt text](https://raw.githubusercontent.com/alu0100724622/tareas_iniciales/master/imag/bash_profile.png)
								
##Instalación de Bundler

Bundler permite instalar diferentes gemas para un proyecto ruby, que las especificamos dentro de un fichero Gemfile.

En primer lugar instalamos bundler con el siguiente comando: 

`sudo gem install bundler`

![Alt text](https://raw.githubusercontent.com/alu0100724622/tareas_iniciales/master/imag/bundler.png)
								
Y luego podemos comprobar que bundler funciona con un proyecto, utilizaremos un proyecto del año pasado.

![Alt text](https://raw.githubusercontent.com/alu0100724622/tareas_iniciales/master/imag/comp_bundler.png)
								
##Instalación de Sinatra

Sinatra es un framework para aplicaciones web de software libre y código abierto, y lenguaje específico del dominio escrito en Ruby.

Para instalar dicha gema nos basta solo con poner: 

`sudo gem install sinatra`

![Alt text](https://raw.githubusercontent.com/alu0100724622/tareas_iniciales/master/imag/sinatra.png)

##Instalación de Twitter

Twitter es un servicio de microblogging.

Y con Twitter es igual que en el caso anterior pero cambiando dicho nombre: 

`sudo gem install twitter`

![Alt text](https://raw.githubusercontent.com/alu0100724622/tareas_iniciales/master/imag/twitter.png)

##Instalación de Git

Git es un controlador de versiones de nuestros directorios de trabajo, y es muy sencillo instalarlo para ello ejecutamos el siguiente
comando: 

`sudo apt-get install git`

![Alt text](https://raw.githubusercontent.com/alu0100724622/tareas_iniciales/master/imag/git.png)
