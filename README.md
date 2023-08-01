El proyecto que elaboré se centra en listas de clientes con diversos datos, como ser
nombre, teléfono, email. Cuenta también con la particularidad de tener información 
acerca del género con la funcionalidad de asignar una imagen aleatoria a cada cliente
creado, aprovechando la API de randomUser. En caso de ser un género distinto a 'hombre'o 'mujer' simplemente carga una imagen de usuario sin cara.
Los métodos GET devuelven respuestas html utilizando ejs. La información de genero no se muestra en el html, ya que no me pareció relevante más que para la elección de la foto (puede verse que la linea en main.js está comentada).
También elaboré de manera distinta la función de modificación (a utilizarse en el endpoint PUT)
respecto al ejemplo dado, ya que me pareció más flexible permitir modificar sin necesidad de
cambiar todos los campos a la vez.
A la hora de escribir los id en el archivo, opté por realizarlo en formato string, ya que ví que
los json de ejemplo de randomUser lo trabajan de esta forma. Puede observarse que en el data.json quedaron
algunos valores de id en formato número ya que lo fui creando durante el desarrollo del código, sin embargo esto no afecta ninguna de las operaciones.
Agregué un poco de css por el simple hecho de practicar un poco el front, puede retirarse de ser necesario.