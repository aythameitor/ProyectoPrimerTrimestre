# Proyecto inicial (obesidad en canarias)

  [1.Introduccion](#idIntroduccion) <br/>
  [2.Requisitos](#idRequisitos) <br/>
  [3.Casos de uso](#idCasosDeUso) <br/>
  [4.Diagrama e/r](#idDiagramaer) <br/>
  [5.Diagrama de clases](#idDiagramaClases) <br/>
  [6.Interfaces](#idInterfaces) <br/>

# Introduccion <a name="idIntroduccion"></a>

Mi app debe tener un diseño simple, por lo que todo es bastante grande en relación a la pantalla y hay muchas ventanas separadas, esto se debe a que el margen de edad del usuario promedio varía desde los 25 hasta los 70 años, por lo que asumo que no todos los usuarios tendrán una vista perfecta.

Las herramientas usadas para mi app son angular para el frontend, y un backend con sequelize, nodeJs, mySql y conexiones con RESTful

# Requisitos <a name="idRequisitos"></a>

La app solo requiere de windows 10, un backend funcionando con cualquier ide (preferiblemente visual studio), con los plugins adecuados instalados y la propia aplicación

# Casos de uso <a name="idCasosDeUso"></a>
![picture](img/casosdeuso.PNG)

# Diagrama entidad relación <a name="idDiagramaer"></a>
![picture](img/er.jpeg)
![picture](img/er2.jpeg)

# Diagrama de clases <a name="idDiagramaClases"></a>
![picture](img/diagramaDeClases.PNG)
# Interfaces <a name="idInterfaces"></a>

La app comienza con un mapa para elegir el municipio, en el cual clicamos o elegimos en un combobox el municipio sobre el que queramos la información, tras esto tenemos un login sencillo y luego dependiendo de si somos un alumno/padre, administrador o profesorado nos redirige a las ventanas adecuadas

![picture](img/CapturaMapa.PNG)
![picture](img/CapturaLogin.PNG)
![picture](img/CapturaAlumno.PNG)
![picture](img/CapturaEditarAlumno.PNG)

Cabe aclarar que estas capturas son del prototipo, el programa aun está sometido a cambios, además, en la última captura se muestra la visión de los profesores / administradores para editar alumnos, esa interfaz es la misma para los profesores y las escuelas, pero estas dos últimas solo son accesibles por los administradores, en la barra de navegación irá un menú lateral (se abre por el lado derecho de la pantalla) que nos permitirá cambiar detalles como el tamaño de la letra (referidos todos a accesibilidad)

Con estas capturas queda claro que la aplicación no es difícil de entender y usar, por lo que personas con poca práctica podrían hacer uso de la misma, también cabe aclarar que he usado una paleta de colores fríos para que la aplicación no resulte muy llamativa y darle así un tono mas serio
