# EJ1_ex2_ED
Javadoc se trata de una utilidad incluida en el JDK, que genera documentación automática en formato HTML, a partir de código fuente Java.
Los comentarios deben ser escritos siguiendo una serie de reglas, donde podrán figurar las propias etiquetas Javadoc junto con etiquetas HTML. Las etiquetas de Javadoc van precedidas por @, estos son los mas usados:
- @author: Autor de la clase. Solo para las clases.
- @version: Versión de la clase. Solo para clases.
- @see: Referencia a otra clase, ya sea del API, del mismo proyecto o de otro. Por ejemplo:
        @see cadena @see paquete.clase#miembro @see enlace.
- @param: Descripción parámetro. Una etiqueta por cada parámetro.
- @return: Descripción de lo que devuelve. Solo si no es void. Podrá describir valores de retorno especiales según las condiciones que se den, dependiendo del            tipo de dato.
- @throws: Descripción de la excepción que puede propagar. Habrá una etiqueta throws por cada tipo de excepción.
- @deprecated: Marca el método como obsoleto. Solo se mantiene por compatibilidad.
- @since: Indica el nº de versión desde la que existe el método.
