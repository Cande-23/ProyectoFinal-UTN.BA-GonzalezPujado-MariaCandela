# ProyectoFinal-UTN.BA-GonzalezPujado-MariaCandela

El proyecto consiste en un local de hamburguesas, que tiene las mejores variedades para tu familia. En internet está todo el mundo. ¿Qué queremos decir con esto? Que tus potenciales clientes pasan cierto tiempo al día en internet. lo que puede aumentar las ventas, es realizando una página web, lo que sirve para estar mas conectados con el cliente.

Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas.

Visual Studio Code

Para la instalación de Visual Studio Code, es: 

Paso 1: Ve a la página de Microsoft Visual Studio Code en Academic Software y haz clic en el botón 'Descargar Visual Studio Code' para descargar el archivo de instalación.
Paso 2: Abre el archivo de instalación .exe en tu carpeta de descargas para iniciar la instalación.
Paso 3: Lee y acepta el acuerdo de licencia. Haz clic en Next para continuar.
Paso 4: Puedes cambiar la ubicación de la carpeta de instalación o mantener la configuración predeterminada. Haz clic en Next para continuar.
Paso 5: Elige si deseas cambiar el nombre de la carpeta de accesos directos en el menú Inicio o si no deseas instalar accesos directos en absoluto. Haz clic en Next.
Paso 6: Selecciona las tareas adicionales, por ej. crear un icono en el escritorio o añadir opciones al menú contextual de Windows Explorer. Haz clic en Next.
Paso 7: Haz clic en Install para iniciar la instalación.
Paso 8: El programa está instalado y listo para usar. Haz clic en Finish para finalizar la instalación y lanzar el programa.

Puede escribir código de alta calidad con herramientas de prueba completas en Visual Studio. Las pruebas unitarias proporcionan a los desarrolladores y evaluadores una forma rápida de buscar errores en la lógica del código. Puede analizar la cantidad de código que prueba y ver los resultados instantáneos en un conjunto de pruebas, o conocer el efecto de cada cambio que realice con características avanzadas que prueben el código mientras lo escribe.

Por ejemplo:
Empezaremos creando un archivo y agregándole código.
1-Abra Visual Studio. Seleccione la tecla Esc o elija Continuar sin código en la ventana de inicio para abrir el entorno de desarrollo.
2-En el menú Archivo de la barra de menús, elija Nuevo>Archivo o seleccione las teclas CTRL+N.
3- En el cuadro de diálogo Nuevo archivo, en la categoría General, elija Clase de Visual y, después, elija Abrir.
4-Se abre un archivo nuevo en el editor con el esqueleto de una clase.

Para finalizar, como obtener datos del sistema o como usarlos para una pequeña demo.

En .NET, tiene tres opciones para modelar y manipular datos en la memoria después de recuperarlos de un origen de datos:
Entity Framework. Puede usarla para programar con datos relacionales como objetos .NET de primera clase. Para las nuevas aplicaciones, debe ser la primera opción predeterminada cuando se requiere un modelo. Requiere compatibilidad personalizada con el proveedor de ADO.NET subyacente.
LINQ to SQL. Un asignador relacional de objetos de generación anterior. Funciona bien para escenarios menos complejos, pero ya no está en desarrollo activo.
Conjuntos de datos. La más antigua de las tres tecnologías de modelado. Está diseñada principalmente para el desarrollo rápido de aplicaciones de "formularios sobre datos" en las que no procesa grandes cantidades de datos ni realiza consultas o transformaciones complejas. 

No es necesario usar ninguna de estas tecnologías. En algunos escenarios, especialmente cuando el rendimiento es crítico, simplemente puede usar un objeto DataReader para leer de la base de datos y copiar los valores que necesita en un objeto de colección, como List<T>.

Las pruebas automatizadas de IU (CUIT) controlan la aplicación a través de su interfaz de usuario. Estas pruebas incluyen unas pruebas funcionales de los controles de la interfaz de usuario. Permiten comprobar si toda la aplicación, incluida la interfaz de usuario, funciona correctamente. Las pruebas automatizadas de IU son útiles donde haya validación u otra lógica en la interfaz de usuario, por ejemplo, en una página web. También se suelen usar para automatizar una prueba manual existente.
La creación de una prueba automatizada de IU en Visual Studio es sencilla. Basta con efectuar la prueba manualmente mientras el generador de pruebas automatizadas de IU se ejecuta en segundo plano. También puede especificar qué valores deben aparecer en campos concretos. El generador de pruebas automatizadas de IU registra las acciones y genera código a partir de estas. Después de crear la prueba, puede editarla en un editor especializado que permita modificar la secuencia de acciones.
El editor y el Generador de pruebas automatizadas de IU especializados facilitan la creación y la edición de pruebas automatizadas de IU, aunque sus principales habilidades se centren en las pruebas en lugar de en la codificación. Pero si es un desarrollador y desea extender la prueba de forma más avanzada, el código se estructura para que sea fácil de copiar y adaptar. 
Por ejemplo, puede registrar una prueba para comprar algo en un sitio web y, a continuación, editar el código generado para agregar un bucle que compre muchos elementos.

Cuando la aplicación se compila con Visual Studio, se puede ejecutar desde cualquier ventana de comandos. Aquí se muestra cómo buscar y ejecutar la aplicación nueva en una ventana del símbolo del sistema.
En la ventana del Explorador de archivos, abra la carpeta Depuración.

Las pruebas de estilo de codificación 

El texto que se copia de otras aplicaciones mantiene la codificación original y los caracteres de salto de línea. Por ejemplo, cuando copia texto desde el Bloc de notas y lo pega en un archivo de texto en Visual Studio, el texto tiene la misma configuración que tenía en el Bloc de notas.
Cuando abre un archivo que tiene caracteres de salto de línea diferentes, puede que vea un cuadro de diálogo que le pregunta si los caracteres de salto de línea incoherentes deben normalizarse y qué tipo de salto de línea quiere.
  
Agrega notas adicionales sobre como hacer deploy
 
El proceso para realizar deploy se puede realizar de tres formas diferenciadas, un proceso manual, un proceso automatizado con algunas acciones manuales y un proceso totalmente automatizado. 

Deploy manual, se produce cuando el proceso necesario para realizar deploy requiere de acciones manuales. 
Dos ejemplos de tipo de deploy manual los encontramos en: uando se hace deploy de un sitio web utilizando una herramienta FTP que requiere conectarse a un servidor, seleccionar el directorio donde se subirán los archivos de la web y otras acciones manuales.
Cuando se necesita realizar algún pequeño cambio en la web, como modificar un pequeño archivo para corregir un error o activar una función.

Deploy mixto, se produce cuando el deploy se encuentra automatizado, pero aun así requiere de alguna pequeña acción manual para que se produzca (como ejecutar un código o dar un permiso de acceso). 

Deploy continuo, se trata del deploy que más se utiliza en la actualidad y se realiza de forma totalmente automatizada. Este concepto está íntimamente relacionado con nuevas metodologías de desarrollo de software como DevOps y entrega continua.
El deploy continuo permite pasar a producción los cambios realizados por varios programadores, sin que se produzcan problemas o errores en el proceso.

Construido con herramientas que utilicé para crear mi proyecto

Visual Studio Code

Autor 
  
María Candela Gonzalez Pujado
  
Expresiones de Gratitud 
 
Gracias a todos por leer y ver este proyecto en el que he pasado por todos los estados emocionales. Gracias también al profesor Gerson que estuvo para nosotros en este cursado.
