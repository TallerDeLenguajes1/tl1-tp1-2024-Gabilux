 #tp1 
El archivo .gitignore, es un archivo de texto que le dice a Git qué archivos o carpetas ignorar en un proyecto.

Un archivo local .gitignore generalmente se coloca en el directorio raíz de un proyecto. 
También se puede crear un archivo global .gitignore, y cualquier entrada en ese archivo se ignorará en todos los
repositorios de Git.

Para crear un archivo .gitignore local, se debe crear un archivo de texto y asígnale el nombre ".gitignore" 
(se debe incluir el . al principio). Luego, se esdita este archivo según sea necesario. 
Cada nueva línea debe incluir un archivo o carpeta adicional que quieras que Git lo ignore.

  Las entradas de este archivo también pueden seguir un patrón coincidente:

* se utiliza como una coincidencia comodín.
/ se usa para ignorar las rutas relativas al archivo .gitignore.
# es usado para agregar comentarios