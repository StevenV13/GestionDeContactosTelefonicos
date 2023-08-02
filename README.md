# GestionDeContactosTelefonicos
Se necesita desarrollar un programa para gestionar una lista de contactos telefónicos. Cada contacto tiene un nombre, un número de teléfono, una Coleccion de Correos y un Diccionario que almacenara las redes sociales del contacto donde la red social sera la clave del diccionario ( Ejem: {'"acebook": "link_facebook_profile"} ).  


El proyecto consiste en el desarrollo de un programa para gestionar una lista de contactos telefónicos utilizando
una estructura de árbol binario de búsqueda. Cada contacto está compuesto por su nombre, número de teléfono,
correos electrónicos y perfiles de redes sociales, almacenados en un diccionario.


El programa ofrece diversas funcionalidades para interactuar con la lista de contactos. La clase "ArbolContacto" 
se encarga de manejar las operaciones fundamentales del árbol binario, como inserción, búsqueda y eliminación de contactos. Además,
permite realizar recorridos en el árbol en distintos órdenes (inorden, preorden, postorden) para obtener los contactos ordenados de diversas maneras.
Dentro de esta estructura, la clase "Contacto" proporciona la estructura básica para almacenar la información de un contacto, incluyendo su nombre,
número de teléfono, correos electrónicos y perfiles de redes sociales. La clase "Nodo" es esencial para construir el árbol binario de búsqueda, 
almacena objetos de la clase "Contacto" y establece las conexiones entre los nodos, permitiendo operaciones eficientes.
La clase principal "Main" (Practica_ArbolesBinarios) actúa como punto de entrada del programa y facilita la interacción con el usuario.
A través de una interfaz sencilla, se pueden agregar, buscar, eliminar y modificar información de los contactos. Además,
ofrece funciones para recorrer el árbol y obtener estadísticas como el número de contactos y niveles del árbol.

Los métodos principales dentro de la clase "ArbolContacto" son:

ArbolContacto: Implementa operaciones para manejar una lista de contactos utilizando un árbol binario de búsqueda. Permite inserción ordenada, eliminación específica y recorridos en el árbol (inorden, preorden, postorden) para obtener contactos ordenados de diferentes formas. También verifica si el árbol está balanceado y calcula su altura.

Contacto: Almacena y gestiona información de un contacto, incluyendo nombre, teléfono, correos y redes sociales. Base para una lista de contactos más funcional.

Nodo: Elemento básico para construir un árbol binario de búsqueda que almacena objetos Contacto. Cada Nodo contiene un Contacto y referencias a nodos hijos, permitiendo organización jerárquica.

Main (Practica_ArbolesBinarios): Interfaz principal para interactuar con un árbol binario de búsqueda de contactos. Permite agregar, buscar, eliminar, modificar, recorrer y obtener estadísticas.

Métodos dentro de la Clase ArbolContacto:

Insertar: Inserción recursiva en un árbol binario de búsqueda, manteniendo orden. Menores a la izquierda, mayores a la derecha.

inOrderRecursivo: Recorrido inorden (izquierda, nodo, derecha).

postOrderRecursivo: Recorrido postorden (izquierda, derecha, nodo).

preOrderRecursivo: Recorrido preorden (nodo, izquierda, derecha).

printTreeNode: Imprime visualmente la estructura del árbol.

getRoot: Devuelve el nodo raíz.

estaBalanceado: Verifica si el árbol está balanceado (diferencia de alturas <= 1).

obtenerAltura: Calcula altura recursivamente.

eliminarContacto: Elimina contacto por nombre, usando eliminación recursiva.

encontrarMinimo: Devuelve el nodo con el valor mínimo en un subárbol.

agregarCorreo: Agrega correo a un contacto.

agregarRedSocial: Agrega red social y URL a un contacto.

buscarContacto: Busca contacto por nombre.

getNumeroContactos: Obtiene el número total de contactos.

getNumeroNiveles: Obtiene el número total de niveles.

imprimirAnchura: Recorre y muestra los contactos por niveles.
