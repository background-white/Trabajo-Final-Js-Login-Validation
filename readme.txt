TRABAJO INTEGRADOR

Construir un Proyecto Web llamado POKEMON FAVORITES.

Esta página debe tener 5 secciones:
Login
Sign Up (Registro)
Profile (donde se pueden editar datos del usuario y el usuario puede eliminar su cuenta).
Pokemon List.
Pokemon Favorites.

LOGIN

En la sección login, el usuario que ingrese debe ingresar su nombre de usuario y su password y si es el correcto cargar la página de Pokemon Favorites de ese usuario.

La página de Login debe contener un botón para acceder a la sección de Registro en caso no tenga un usuario creado.

SIGN UP

Para el registro, se deben considerar los siguientes campos:
	Nombre completo
	Correo electrónico
	Nombre de usuario (Ejemplo: pokemaster)
	Contraseña
Confirmar contraseña

Cuando se termine de crear el usuario, debe salir un mensaje de éxito y se debe cargar la página Pokemon List indicando un mensaje de bienvenida.

NAVBAR (SOLO VISIBLE EN LAS PÁGINAS ENTRE LAS QUE SE PUEDE NAVEGAR)

Tanto la Pokemon List, el Profile y la sección de Pokemon Favorites deben ser accesibles a través de un navbar ya sea en el header o a un lado de la página.

PROFILE

Contiene la información del usuario, desde aquí el usuario puede editar su información haciendo click en el botón editar o decidir borrar su cuenta haciendo clic en el botón borrar. En ambos casos se debe solicitar confirmación al usuario antes de ejecutar el cambio. Si se borra debería ir al LOGIN.





POKEMON LIST

Esta página es similar a la que hicimos en clase: Debe mostrar un selector con los nombres de los pokemones de la generación 1 y una imagen del pokemon con su nombre al medio de la pantalla.

Debe existir un botón: “agregar a favoritos” para agregarlo a la base de datos de pokemons favoritos y se debe solicitar confirmación del usuario.

Al tenerlo de favorito el background del nombre del pokemon debe cambiar de color para que el usuario pueda distinguir que dicho pokemon es parte de sus favoritos.

POKEMON FAVORITES

La sección de Pokemon Favorites debe mostrar en pantalla una serie de cards con la información de los pokemons favoritos del usuario (por lo menos nombre y foto), debe incluir un botón en cada card para quitar al pokemon de la lista de favoritos.

Si el usuario confirma que desea eliminar al pokemon de la lista, el pokemon ya no se debe renderizar en pantalla.

API

Para manejar el CRUD de usuarios, crear una API que se conecte a una base de datos en MongoDB que almacene los usuarios y su información. 

Toda función de crear, modificar, leer los datos de usuario o eliminar deben venir de una consulta a la API desde nuestro proyecto Web.

La lista de pokémons favoritos también debe actualizarse en la base de datos y ser consultada desde ahí
