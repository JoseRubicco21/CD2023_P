# Hello world con Java

## Instalación de JAVA
Primero que nada debemos de asegurarnos de instalar JAVA, para ello podemos utilizar el comando:

```
java
```

Si no tenemos JAVA instalado nos mostrará comando para poder instalarlo.

En este caso el comando que queremos utilizar es:

```
sudo apt install default-jre
```
*Nota:* Es importante notar que esta es la versión default, si queremos utilizar una versión más reciente debemos especificarla o utilizar otro comando.

Para verificar que se instaló correctamente y que versión utilizamos:

```
java -version
```

## Creación, compilación y ejecución del programa

Ahora deberiamos de tener una salida de todas las opciones de ejecución de Java.

Una vez hecho eso creamos nuestra clase "Hola mundo" con el código correspondiente.

```java
public class Hello_World {
    public static void main(String[] args){

        System.out.println("Hello world!");

    }
}
```
Para compilar debemos utilizar *javac*, que es el compilador de java.

```
javac Hello_world.java
```

Deberiamos de tener un nuevo archivo con la extension **.class**, este archivo es el que se puede ejecutar, basta con lanzar el siguiente comando:

```
java Hello_world
```

**Nota:** Si el programa solo consiste de una clase principal basta con utilizar el comando:

```
java Hello_world.java
```

A partir del JDK 11, si es solo una clase el se llama de forma inferida javac y luego java.