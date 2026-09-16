# Uco_Java
Para la parte del diseño de nuestro proyecto hicimos una clase aparte que se llama Tema.java. Ahí pusimos los colores, las fuentes y los estilos de los botones y de los campos de texto.

Lo hicimos así porque si poníamos el diseño directamente en cada panel, como Estudiantes, Profesores y Notas, después si queríamos cambiar un color o algún estilo nos tocaba cambiarlo en cada uno y podíamos olvidarnos de alguno. Entonces preferimos dejar todo en una sola clase y que los otros paneles simplemente usaran esos estilos.

En esta parte se pueden ver los cuatro pilares de la POO.

El encapsulamiento lo usamos dejando el constructor de Tema como private, así no se pueden crear objetos de esa clase directamente. Solo se pueden usar los métodos que dejamos públicos.

La abstracción se puede ver cuando usamos algo como Tema.boton("Registrar Estudiante"). No necesitamos saber todo lo que hace el botón por dentro, simplemente llamamos al método y este nos devuelve el botón ya diseñado.

La herencia la usamos, por ejemplo, en BotonRedondeado extends JButton. Esto quiere decir que nuestro botón toma las características de un botón normal de Java y nosotros le agregamos otras cosas, como el degradado, las esquinas redondeadas y el efecto cuando pasamos el mouse.

Y el polimorfismo lo usamos con paintComponent. Varias de nuestras clases tienen ese mismo método, pero cada una lo utiliza para pintar algo diferente. Por ejemplo, el botón pinta una cosa, la tarjeta otra y el encabezado otra.

Esta parte es solamente sobre los cambios que hicimos en el diseño de la aplicación. Las clases Persona, Estudiante y Profesor ya estaban hechas y ya tenían herencia y polimorfismo. Nosotros no cambiamos la forma en que funciona esa parte, solamente trabajamos en el diseño de la aplicación.
