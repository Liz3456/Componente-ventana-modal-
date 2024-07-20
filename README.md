# Componente Ventana Modal

## Descripción
Este componente permite crear una ventana emergente para mostrar información guardada en un texto. A partir de un botón, la información aparece de forma sistemática. Se utiliza el componente de Java `io` a partir de `JFrame` y `JDialog`. Es una clase principal diseñada a partir de la clase ventana principal, de modo que el botón "Mostrar" genera una ventana emergente con los datos almacenados.

## Usos
- **Mostrar Datos**: Al hacer clic en el botón, puedes mostrar datos de una base de datos o una lista en un cuadro de texto, tabla o área de texto.
- **Actualizar Interfaz**: Utiliza el botón para actualizar la interfaz de usuario, mostrando nuevos elementos gráficos o cambiando el contenido de etiquetas, listas, etc.
- **Mostrar Ventanas Emergentes**: El botón puede abrir ventanas emergentes o diálogos que muestran información adicional o permiten al usuario realizar más acciones.
- **Mostrar Resultados**: Si tu aplicación realiza algún tipo de cálculo o procesamiento, el botón puede ser utilizado para mostrar los resultados de dichas operaciones.
- **Mostrar Imágenes o Gráficos**: Sirve para cargar y mostrar imágenes, gráficos u otros elementos visuales.

## Características
- Botón que muestra, al ser presionado, una ventana emergente.
- Uso de componentes de `io` con `JFrame`.

## Requisitos
- Java versión actualizada.
- NetBeans.

## API
| Nombre         | Tipo de Dato que Retorna | Tipo de Dato que Recibe | Descripción |
|----------------|--------------------------|-------------------------|-------------|
| mostrarDatos   | String                   | int                     | Este método es útil en aplicaciones que necesitan cargar datos desde archivos y mostrarlos dinámicamente en una GUI. Parece estar diseñado para mostrar información personal almacenada en un archivo de texto. |
| editarArchivo  | String                   | String y int            | Este método modifica el archivo directamente. Asegúrate de usarlo con precaución, especialmente en entornos donde el archivo puede ser accedido por otros procesos simultáneamente. |

## Tipos
| Tipo                          | Campo                            | Descripción |
|-------------------------------|----------------------------------|-------------|
| java.io.BufferedReader        |                                  | Esta clase lee texto de un flujo de entrada (como un archivo de texto), almacenando los caracteres en un búfer para proporcionar una lectura más eficiente, especialmente cuando se leen grandes cantidades de datos de manera secuencial. |
| java.io.BufferedWriter        |                                  | Esta clase escribe texto en un flujo de salida, almacenando los caracteres en un búfer para mejorar el rendimiento al escribir grandes cantidades de datos en el archivo de salida. |
| java.io.FileReader            | FileDescriptor fd                private final StreamDecoder sd  | Esta clase se utiliza para leer caracteres de un archivo de texto. Lee los caracteres de forma secuencial, proporcionando métodos para facilitar la lectura de caracteres individuales o bloques de caracteres. |
| java.io.FileWriter            | private final StreamEncoder se   private final FileOutputStream fos| Esta clase se utiliza para escribir caracteres en un archivo de texto. Permite escribir caracteres en el archivo de forma secuencial, proporcionando métodos para escribir caracteres individuales o bloques de caracteres en el archivo. |
| java.io.IOException           | serialVersionUID                 private Throwable caus| Esta clase representa una excepción que puede ocurrir durante la operación de entrada o salida (E/S) en Java. Es una excepción comprobada, lo que significa que el código que realiza operaciones de E/S debe manejar o lanzar esta excepción. |

## Funcionamiento
Desde el siguiente link se puede ver como funciona el codigo https://youtu.be/1w6n_gy0W1M

## Autores
* [Sanjuan Vasquez Liz](https://github.com/Liz3456)
* [Sánchez Pérez Carlos Raúl](https://github.com/Liz3456)

