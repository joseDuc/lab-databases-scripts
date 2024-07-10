# Cuestion-1  Grado y cardinalidad

### peliculas
Grado=> id_pelicula, anio , pais_origen, id_director, id_gerero <br>
Cardinalidad=> 10 filas
### directores
Grado=> id_director, nombre
<br>
Cardinalidad=> 8 filas

### actores
Grado=> id_Actor,nombre
<br>
Cardinalidad=> 19 filas

### generos
Grado=> id_genero,nombre
<br>
Cardinalidad=> 5 filas

### pelicula_actorPrincipal (intermedia)
Grado=> id_pelicula,id_actor
<br>
Cardinalidad=> 10 filas

### pelicula_actorSecundario (intermedia)
Grado=> id_pelicula,id_actor
<br>
los dos atributos son foreign key a sus respectivas tablas
<br>
Cardinalidad=> 10 filas

-----------------------------------------------------------------
### coches
Grado=> id_coche, id_marca, modelo, anio
<br>
Cardinalidad=> 10 filas

### coche_marcas
Grado=> id_marca, nombre
<br>
Cardinalidad=> 10 filas

### coche_propietarios
Grado=> id_propietario, nombre, direccion
<br>
Cardinalidad=> 10 filas

### coche_talleres
Grado=> id_taller, nombre
<br>
Cardinalidad=> 10 filas

### coche_propietario (intermedia)
Grado=> id_coche, id_propietario
<br>
Los dos atributos son foreing key a sus respectivas tablas
<br>
Cardinalidad=> 10 filas

### coche_taller (intermedia)
Grado=> id_coche, id_taller
Los dos atributos son foreing key a sus respectivas tablas
<br>
Cardinalidad=> 10 filas


-----------------------------------------------------------------
### equiposFutbol
Grado=> id_equipo, nombre, id_estadio, id_entrenador, id_ciudad
<br>
Cardinalidad=> 10 filas

### futbol_estadios
Grado=> id_estadio, nombre
<br>
Cardinalidad=> 10 filas

### futbol_entrenadores
Grado=> id_entrenador, nombre
<br>
Cardinalidad=> 10 filas

### ciuadades
Grado=> id_ciudad, nombre
<br>
Cardinalidad=> 9 filas

### equipoFutbol_jugador  (intermedia)
Grado=> id_equipo, id_jugador
<br>
los dos atributos son foreign key a sus respectivas tablas
<br>
Cardinalidad=> 30 filas

-----------------------------------------------------------------
### canciones
Grado=> id_cancion, titulo, anio_lanzamiento, duracion, id_album, id_artista, id_compositor
<br>
Cardinalidad=> 10 filas

### artistas
Grado=> id_artista, nombre
<br>
Cardinalidad=> 7 filas

### cancion_album
Grado=> id_album, id_Artista, nombre
<br>
Cardinalidad=> 9 filas

### compositor
Grado=> id_compositor, nombre
<br>
Cardinalidad=> 9 filas


-----------------------------------------------------------------
### animales
Grado=> id_animal, nombre, edad
<br>
Cardinalidad=> 10 filas

### animal_especies
Grado=> id_especie, nombre
<br>
Cardinalidad=> 2 filas

### animal_propietarios
Grado=> id_propetario, nombre, direccion
<br>
Cardinalidad=> 10 filas

### animal_veterinarios
Grado=> id_veterinario, nombre, direccion
<br>
Cardinalidad=> 10 filas

### animal_propietario (intermedia)
Grado=>id_animal, id_propietario
<br>
Cardinalidad=> 10 filas

### animal_veterinario (intermedia)
Grado=>id_animal, id_veterinario
<br>
Cardinalidad=> 10 filas