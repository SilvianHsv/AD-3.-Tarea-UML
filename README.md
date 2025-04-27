# AD-3.-Tarea-UML

ENUNCIADO:

    En esta actividad, diseñarás y desarrollarás un sistema de gestión de torneos de eSports,
     aplicando Programación Orientada a Objetos (POO) y utilizando diagramas UML 
     para modelar su estructura y funcionalidad. 

    Para ello, trabajarás en dos aspectos clave del análisis y diseño de software: 

1. Modelado de funcionalidad con diagramas de casos de uso 
 Representarás las principales interacciones entre los usuarios y el sistema. 
 Identificarás los actores (administradores, jugadores y sistema) y sus casos de uso. 
 Definirás relaciones como inclusión (<>) y extensión (<>) en los casos de uso cuando sea necesario. 

2. Modelado estructural con diagramas de clases 
 Diseñarás la estructura del sistema definiendo las clases principales y sus relaciones. 
 Diferenciarás los tipos de clases en Entidad, Control e Interfaz. 
 Establecerás atributos, métodos y asociaciones entre clases.

PASOS A SEGUIR PARA REALIZAR LA ACTIVIDAD

Para completar esta actividad de manera estructurada y eficiente, sigue estos pasos en orden secuencial.

 1. Análisis del problema y requisitos del sistema antes de modelar,
  es fundamental comprender qué hace el sistema y qué se espera de él. 

     Lee atentamente los requisitos y responde estas preguntas clave:
         • ¿Quiénes son los actores que interactúan con el sistema? 
         • ¿Cuáles son las acciones que cada actor puede realizar? 
         • ¿Cómo se relacionan entre sí las entidades del sistema?

  2. Identificación de los casos de uso y elaboración del diagrama.
     Ahora, debes definir qué interacciones existen entre los actores y el sistema. 

    Debes elaborar los correspondientes a la Gestión de equipos y jugadores.
       • Registrar equipo. 
       • Añadir jugadores a un equipo.
       • Consultar lista de equipos y jugadores.

EXPLICACIONES:

En el caso del diagrama "Diagrama de caso de uso" he elegido representar el diagrama
con dos actores y tres casos de uso. El primer actor "Gestor de equipos" va a ejecutar
los tres casos de uso "Registrar equipos", "Añadir jugadores" y "Consultar lista de equipo
y jugadores". He analizado que el segundo actor "Jugador" una vez que está añadido a 
un equipo puede efectuar el caso de uso "Consultar lista de equipo
y jugadores", realizando esta acción con un <<include>>

En el caso del diagrama "Diagrama de clases" he elegido representar el diagrama 
con una clase "GestorEquipos" que tendrá sus atributos y sus métodos. En los atributos
tendrá un atributo arraylist de los equipos. Esta clase tendrá como métodos los casos de usos
mencionados anteriormente. Esta clase controlará otra clase llamada "Equipo" que tendrá sus atributos 
y los métodos de "Añadir Jugador" y "Consultador Jugadores". Relacionada con la clase equipo 
va a estar la clase "Jugador" que tendrá sus atributos y como método "Obtener datos" que va a ofrecer
al jugador los datos del equipo.
