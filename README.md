En github actions podemos usar condicionales, variables de entorno



# steps
- Si deseamos añadir varias instrucciones a un único step en run debemos añadir "|"

# variables
- Podemos crear nuestras propias variables de entorno
- Github ya viene con variables de entorno, en la cuales 
	podemos consultar el nombre del usuario, la url del repositorio, entre muchas más.
- Ademas de las variables que podemos crear y las variables que nos ofrece github, 
  también podemos pasar variables de forma externa, para ello tendríamos que 
	dirigirnos a settings en security, seleccionar secrets and variables y allí 
	seleccionar actions, una vez echo esto tendremos dos tabs una con secrets y la otra
	con variables, 
	## Secrets, 
	Es para archivos sensibles, como el usuario y contraseña de alguna base de datos,
	aquí tenemos las opciones de environment secrets y repository secrets este ultimo
	nos permite crear variables unicamente para el repositorio en cuestión.
	Para utilizar estos secrets podemos asignarlos a una variable pero hay que tener en 
	cuenta que no los podemos visualizar ya que se mostraran como asteriscos aunque si
	podemos trabajar con ellos 
	## Variables, es para valores que no son estrictamente privados
