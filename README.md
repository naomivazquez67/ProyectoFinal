# ProyectoFinal
Webscraper
Equipo 14

Integrantes: Fernández Sánchez Yahir Sebastián Rosete Launizar Elideth Vazquez Huesca Naomi Barroso Mateos Carlos Rafael

Instrucciones:

Primeramente lo que debemos hacer es cambiar la ruta de nuestra variable "path" que aparece en las funciones "Buscador_Precios_Selenium_PalaciodeHierro(producto)","Buscador_Precios_Selenium_Sanborns(producto)", "Buscador_Precios_Selenium_BA(producto)", a la dirección en donde se ubica el webdriver en el ordenador.

Posterior a lo anterior es necesario tener en consideración que debemos ejecutar nuestro codigo por partes, la primera parte debemos ejecutarla de la linea 1 a la linea 305 (parte del codigo correspondiente a las funciones), esta primera parte nos generara el archivo excel y abrira las paginas correspondientes a las tiendas en linea de Palacio de Hierro, Sanborns y Bodega Aurrera obteniendo la informacion de los productos solicitada como son el URL, los nombres y los precios, seguido de esto una vez que se haya generado el excel debemos buscar este mismo en nuestro ordenador y obtener su correspondiente ruta, la cual deberemos de modificar en la variable "archivo" que se encuentra almacenada en la linea 309, una vez realizada dicha modificacion correremos el codigo de la linea 306 a la linea 363, los cual nos servira para imprimir las consultas que se podran ver en la consola de python y posterior a las consultas se podrán visualizar las graficas realizadas.
