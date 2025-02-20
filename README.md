# Material práctico #1
`(Fundamentos de programación)`

## Indicaciones:
● Recuerda que debes de visualizar el contenido de las clases pre grabadas de
Fundamentos de Programación (Desde: Aproximacion a la industria de
videojuegos. Hasta: Creando un escenario simple.).  
● Tendrás que realizar un escenario en 3D. Las temáticas que puedes escoger
son: Cementerio, Bosque nocturno (debe de incluir animales y estructuras),
Pantano misterioso, o Ciudad Post-Apocalíptica.  
### Indicaciones:   
● Busca recursos alusivos a la temática seleccionada en la Asset Store.
### Recuerda:   
○ La versión del paquete debe compatible con Unity 2022.3.22.
○ El paquete debe de ser compatible con la plantilla del proyecto (Built-in,
URP o HDRP).   
● Importa los recursos a tu proyecto. Los recursos descargados deben de incluir:
○ Modelo que represente al jugador.   
○ Modelos alusivos a la temática del escenario (Ej. Si es Cementerio -
Árboles torcidos, Iglesia, Lapidas, Tumbas, etc…).  
○ Modelos/Props para decorar el entorno (Ej. Si es Cementerio - Cajas,
Velas, Lámparas, Calaveras, etc…).  
● Crea tu escenario bajo la temática seleccionada, con los recursos
implementados:  
○ El escenario debe de ser construido con Terrain. Elementos como:
Árboles, Follaje, Rocas, Flores, etc… Tendrán que ser ubicados con las
herramientas de personalización de Terrain.  
○ El escenario debe de tener al menos 30 elementos ubicados de manera
manual.  
○ Deberán de existir elementos que implementen algún tipo de luz.
A tener en cuenta:  
● Organizar la jerarquía de la escena.
○ Recuerda hacer uso de los objetos vacíos a modo de carpeta dentro de la
escena.  
○ Las carpetas no deberán tener posiciones, rotaciones o escalas
contaminadas. Únicamente se acepta alguna contaminación en estos
parámetros si se realizó posterior al almacenamiento de los objetos.
● Manejar prefabs para instancias repetitivas.  
○ Instancias iguales e incluidas múltiples veces en el entorno tienen que ser
manejadas por prefabs.  
○ El componente transform de los prefabs no debe de estar contaminado (en
el modelo. Las instancias de la escena, obviamente, pueden cambiar).
● Escenario transitable.  
○ El escenario debe de ser funcional. Debe de contener colliders para
permitir su navegación.  
○ Ninguno de los colliders debería de ser Mesh Collider. Solo se admiten
colliders primitivos. 
○ Prueba la funcionalidad con el paquete de la Actividad #2.
