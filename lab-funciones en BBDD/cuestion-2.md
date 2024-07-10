# Modelo conceptual de BBDD

Ejemplo de una  biblioteca
<br>
![imagen modelo](./imagenes/ModeloConceptual.png)

<br>

## Cardinalidad 
Existen las entidades independientes: libros, autores, generos y miembros.
<br>
Y las tablas intermedias: libro_autor, libro_genero y prestamos.
<br><br>
La relación entre libro_genero/libro es de muchos/muchos.<br>
La relación entre libro_autor/libros es de muchos/muchos.<br>

La relación entre prestamos/miembros es de uno/uno.<br>
La relación entre miembros/prestamos es de uno/muchos.<br>
La relación entre prestamos/libros es de uno/uno.<br>
La relación entre libros/prestamos es de uno/muchos.<br>