04/02/2026
	Se utiliza siempre
	el CREATE
	para crear una tabla 

CREATE TABLE -> Nombretabla 
- Debe de ser descriptivo 


  SELECT --> FROM 
  - De esa manera contenemos la informacion y la recolectamos 

SELECT * FROM * --> Da todos los resultados 


UPDATE ---> Se utiliza en vez  de select para tomar de~ donde  Y que es lo que vamos a actualizar ~
DELETE --> Se puede decir ~que y de donde ~

FOREIGN  -KEY 
PRIMARY  - KEY
DELETE   FROM  USUARIO1; PARA LOS REGISTROS
DROP TABLE USUARIO1(Nombre de la tabla);

---

- Entidades
- Autor
- Libro
- Editorial
- Usuario 


Formulario 
id
Nombre
Nacionalidad
Biografia

int (0) --> 



---
RELACIONES PRINCIPALES Y CARDINALIDADES

AUTOR -> Relacion entre Autor pueden escirivir varios libors para cada libro un autor principal responsable de la obra
PUBLICA ---> Relacional entre editorial y libro donde una historial public multiples historias pero cada libro es oublicado en una editaroal con cada edicion
PRESTAMO-> un usuario puede tener multiples prestamos porque existen copias diferentes,se puede establecer esa relaciom,que se puede tomar con el identificador
DETALLE DEL PRESTAMO->Es la tabla intermediaria que necesita para poder llevar un control y registro 

---
ATRIBUTOS CLAVE EN EL MODELO 

- Tipos de clave
1. Clave primaria (pk)-> Identifica univocamente cada registro en una editorial

 