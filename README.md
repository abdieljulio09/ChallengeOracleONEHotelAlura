# Challenge-Oracle-ONE-Hotel-Alura-JAVA-DB
Ultimo challenge del programa Oracle ONE ,en donde se solicito crear una app desktop en el lenguaje JAVA que permitiera añadir,editar,eliminar 
datos y alojarlos en una base de datos mysql;

*Ventana login: 

-Contrasta los datos almacenados en la base de datos para autenticar el usuario,indicandole si las credenciales no son validas.

![Capturar_2022_06_30_07_55_13_813](https://user-images.githubusercontent.com/94617066/176664695-94474a18-3606-4bbb-9a16-f147b8e30a79.png)


*Ventana Home:

-Provee 2 opciones , tanto para agendar una nueva reserva/huesped como para realizar una busqueda de los mismos.

![Capturar_2022_06_30_07_55_55_427](https://user-images.githubusercontent.com/94617066/176665102-4292752f-6131-4412-9ca9-83a9cb50cdbc.png)


*Ventana agendar reserva:

-valida si los campos estan vacios y si las fechas ingresadas son validas para agendar una nueva reserva.

-muestra el valor de la reserva de acuerdo a una tasa diaria establecida por el negocio en base a los dias de permanencia.

![Capturar_2022_06_30_07_56_54_220](https://user-images.githubusercontent.com/94617066/176665736-c626538a-ebf0-41cd-af70-e5798f2e6d81.png)


*Ventana registro huesped:

-valida si los campos estan vacios

-en cada campo solo se pueden ingresar datos de acuerdo al dato que pida el campo(letras,numeros)

-en caso de exito , se notifica al usuario que los datos han sido guardados correctamente en la base de datos.

![Capturar_2022_06_30_07_57_58_195](https://user-images.githubusercontent.com/94617066/176666461-f41fbeaf-45a8-478d-a352-4b04652d22cf.png)
![Capturar_2022_06_30_07_57_34_19](https://user-images.githubusercontent.com/94617066/176666499-e0af3583-0609-4479-a58a-c6b8fb098121.png)
![Capturar_2022_06_30_08_05_46_635](https://user-images.githubusercontent.com/94617066/176666713-565883fa-3299-4758-acc6-1697dc6c0014.png)

*Ventana Busqueda:

-lista todos los huespedes y reservas registrados en la base de datos
![Capturar_2022_06_30_08_06_14_956](https://user-images.githubusercontent.com/94617066/176667804-4c7224ab-eadc-46ff-9ec9-01f3d5259004.png)
![Capturar_2022_06_30_08_06_19_578](https://user-images.githubusercontent.com/94617066/176667843-327dd9ab-1a89-42ed-aa2a-19ab524769ce.png)

-permite buscar un huesped por apellido o una reserva por nro de id
![Capturar_2022_06_30_08_07_58_923](https://user-images.githubusercontent.com/94617066/176667954-774d8566-2fbf-4a91-af83-e31c733b00b6.png)
![Capturar_2022_06_30_08_08_11_426](https://user-images.githubusercontent.com/94617066/176668000-9b979c3e-e187-4e3b-907b-269fe46e7003.png)

-permite la edicion,eliminacion de datos del huesped/reserva

-si un huesped es eliminado , la reserva asociada al mismo se elimina automaticamente y viceversa.

-se notifica al usuario en caso de modificacion de datos exitosa

![Capturar_2022_06_30_08_06_49_278](https://user-images.githubusercontent.com/94617066/176668082-c4df467f-fd32-4acd-97c6-bac7ff5d0e68.png)
![Capturar_2022_06_30_08_07_13_379](https://user-images.githubusercontent.com/94617066/176668142-c3af23f2-3938-4e22-b70b-2ab0d546ce99.png)
![Capturar_2022_06_30_08_07_33_54](https://user-images.githubusercontent.com/94617066/176668185-d402abd8-8441-4ff3-b183-345c7ad78cfe.png)
![Capturar_2022_06_30_08_07_40_246](https://user-images.githubusercontent.com/94617066/176668405-9bce7dee-3525-45d0-93bf-4a5b32de82d4.png)


// Puede encontrar el .jar ejecutable en la carpeta "/lib"


**Recursos utilizados**

-Librerias "mchange" y "c3po" ---> para crear pool de conexiones

-Libreria "jcalendar" ----> manejar fechas

-Base de datos relacional creada en mysql 

-Heroku --> host de la base de datos (para poder acceder de forma online)




