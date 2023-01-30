
![Android Logo, symbol, meaning, history, PNG, brand](https://logos-world.net/wp-content/uploads/2021/08/Android-Logo.png)
# Preguntas de entrevista para Android 
Las preguntas se dividen en 3 niveles: Básico, Intermedio y avanzado, se comparte la respuesta claro ;) . Todas estaran en español y si te gusto o sirvio recuerda dejar tu ⭐

**Streams**  

 - https://www.youtube.com/josedlujan1
 - https://www.twitch.tv/josedlujan 
 
**Platiquemos**
 - https://twitter.com/josedlujan
 
 **Discord**
 
 - https://discord.gg/WWpzhV7t

## Índice
-[Índice](#índice)

 - [Básico](#basico)
	 - [¿ Qué es una Activity ?](#que-es-una-activity)
	 - [¿ Qué es un Layout ?](#que-es-uun-layout)
	 - [¿ Para qué se utiliza XML en Android ?](#para-que-se-utiliza-xml-en-android)
	 - [¿ Diferencias entre View y ViewGroup ?](#diferencias-entre-view-y-viewgroup)
	 - [Ejemplos de elementos View y ViewGroup](#ejemplos-de-elementos-view-viewgroup)
	 - [¿ Como indicamos a una Activity cual es su interfaz?](#como-indicamos-a-una-activity-cual-es-su-interfaz)
	 - [¿ Qué lenguajes de programación se utilizan para el desarrollo de aplicaciones Android ?](#que-lenguajes-de-programacion-se-utilizan-para-el-desarrollo-de-aplicaciones-android)
	 - [¿ Qué es el archivo AndroidManifest.xml ?](#que-es-el-archivo-androidmanifest)
	  - [¿ Cuál es la diferencia entre View.INVISIBLE y View.GONE ?](#cual-es-la-diferencia-entre-viewinvisible-viewgone)
	 - [¿ Qué es clase Application ?](#que-es-clase-application)
	- [¿ Qué es el Contexto ?](#que-es-el-contexto)
	- [¿ Qué es el archivo R.java ?](#que-es-el-archivo-r-java)
    - [¿ Qué es el ciclo de vida de una actividad ?](#que-es-el-ciclo-de-vida-de-una-actividad)


 - Intermedio
	 - A
 - Avanzado
	 - B

### ¿ Qué es una Activity?

Una Activity estrictamente es una clase, esta clase se utiliza normalmente para ser el contenedor de una vista y funcionalidades básicas de una pantalla dentro de una aplicación, normalmente viene enlazada a lo que es un XML en donde se tiene definida la vista. Las activities se tienen registradas en un archivo Manifest. Se dice muchas veces para explicar de manera sencilla que una activity es una pantalla, si una aplicación android tiene 5 pantallas podemos decir de manera general que tiene 5 activities, aunque tecnicamente tenemos otras formas de crear vista y no siempre esto es así, pero esa explicación se da muchas veces al inicio a los desarrolladores que estan aprendiendo para facilitar su comprensión.

**[⬆ Volver a índice](#índice)**

### ¿ Qué es un Layout?
Los Layouts son elementos que nos ayudan a definir la estructura de interfaz de una aplicación en Android. Tenemos dos elementos base para los elementos de diseño que son ViewGroup y View. Un View se utiliza para mostrar un elemento, este elemento puede ser solo para mostrar "algo" o puede ser tambien un elemento que tenga interacción con el usuario. Por otro lado ViewGroup es un elemento que puede contener 1 o varios elementos del tipo View o ViewGroup que ayuda a definir la estructura. 

**[⬆ Volver a índice](#índice)**

### ¿ Para qué se utiliza XML en Android?

XML se utiliza normalmente para definir las interfaces utilizando layouts y vistas que nos permiten en combinación crear interfaces de aplicaciones en android. Pero tambien son archivos que se pueden utilizar para definir algunas configuración, valores o reglas, por ejemplo utilizamos un XML para escribir las cadenas de texto de una aplicación en español, ingles u otros idiomas, también podemos utilizar XML para definir los elementos que formaran parte de un menú. Por otro lado el archivo Manifest es un XML en donde se tiene una parte de la configuración de la aplicación y el registro de las activities. Así que podemos utilizarlos con diferentes objetivos aunque el tema de definición de interfaces es el más común.

**[⬆ Volver a índice](#índice)**

### ¿ Diferencias entre View y ViewGroup?

View es una vista que tiene definido un espacio de aparición y acciones a realizar si se le da alguna indicación o sucede alguna interacción. Un ViewGroup es un contenedor invisible que puede contener 1 o más View o ViewGroup. View es una superclase, mientras que ViewGroup es una colección de elementos contenidos. De hecho ViewGroup deriva de View.

**[⬆ Volver a índice](#índice)**

### Ejemplos de elementos View y ViewGroup

Elementos come EditText, TextView, ListView son View.
Elementos como LinearLayour, RelativeLayout, GridLayout, FrameLayout derivan de ViewGroup.

**[⬆ Volver a índice](#índice)**

### ¿ Como indicamos a una Activity cual es su interfaz?

La manera más común es si creamos el clasico "hola mundo" en android sin utilizar JetPackCompose por ejemplo, es dentro del método onCreate() de la Activity tenemos el método setContentView en donde establecemos cual es el layout que vamos a utilizar como recurso para este elemento.

**[⬆ Volver a índice](#índice)**

### ¿ Qué lenguajes de programación se utilizan para el desarrollo de aplicaciones Android ?

Google recomienda hoy en día el lenguaje de programación Kotlin para el desarrollo de aplicaciones android, pero tenemos posibilidades de utilizar otros lenguajes de programación aunque en ocasiones son para funcionalidades muy particulares, se comenzo desarrollando aplicaciones con el lenguaje de programación Java y se sigue utilizando ya que existen muchas aplicaciones aún con este lenguaje de programación y muchos elementos antiguos que solo soportan este lenguaje. Las dos principales opciones actuales son Kotlin y Java, siendo Kotlin el recomendado directamente por el equipo de Android.

**[⬆ Volver a índice](#índice)**

### ¿ Qué es el archivo AndroidManifest.xml ?

Es un archivo que se considera muy importante dentro de una aplicación ya que se configuran elementos cruciales de una aplicación. Encontraremos por ejemplo al configuración de algunos componentes como las Activities, Services y otros. Encontraremos tambien elementos como los iconos, permisos, compatibilidades con algunos dispositivos.

**[⬆ Volver a índice](#índice)**

### ¿ Cuál es la diferencia entre View.INVISIBLE y View.GONE ?

View.INVISIBLE no se en pantalla el elemento, es decir esta invisible pero mantiene el espacio de la vista que le corresponde. View.GONE hace que el elemento tambien sea invisible pero no mantiene el espacio en la vista que le corresponde.

**[⬆ Volver a índice](#índice)**

### ¿ Qué es clase Application ?

La manera corta es decir que es una clase que se puede utilizar como base para mantener el estado de la aplicación. Normalmente se usa para tener elementos disponibles en toda la aplicación o muchas veces se dice de "manera global". Se usa normalmente extendiendo de esta clase una clase propia y colocando los elementos que se van a necesitar, se aprocheca que esta clase se utiliza antes que otras y así lo que este ahí estara disponible antes de la creación de los otros elementos en una aplicación.

**[⬆ Volver a índice](#índice)**

### ¿ Qué es el Contexto ?

De manera tecnica podemos decir es una una clase Abstracta que existe en android y que nos la proporciona el Android. El contexto se utiliza normalmente para tener acceso a elementos dentro de una aplicación y nos ayuda a delimitar como y donde lo hacemos. Una manera fácil de explicarlo es utilizando una aplicación y las actividades. Por ejemplo si estamos en una aplicación y preguntamos por el contexto de la aplicación podemos decir que este nos permite tener acceso a elementos dentro de TODA la aplicación, pero si preguntamos por el contexto de la actividad el contexto solo esta limitado a la actividad en donde estamos cuando preguntamos o usamos el contexto. Así que podemos notar que tenemos diferentes contextos dentro de la misma aplicación y están ligados a diferentes elementos dependiendo de lo que necesitemos tendremos que utilizarlos.

**[⬆ Volver a índice](#índice)**

### ¿ Qué es el archivo R.java?

Es un archivo que se genera automáticamente por AAPT (Android Asset Packaging Tool) Dentro de este archivo podemos ver todos los ID de los recursos que tenemos en el proyecto.

**[⬆ Volver a índice](#índice)**

### ¿ Que es el ciclo de vida de una actividad?

Es un ciclo de procesos/ métodos que se lleva acabo durante el uso de actividades, comienza desde el inicio de la actividad y termina destruyendo una actividad.

**[⬆ Volver a índice](#índice)**