# Aprendiendo Mark
Mis primeros *pasos*en **Mark**, que es un formato de mercado de ***archivos de texto***.

A continuacion una _lista_:

* Item 1 
* Item 2 
        * Item2.1
        * Item 2.2
* Item 3 

A continuacion una _tabla_

|Codigo| Nombre | Precio |
|-|-|-|
| 1 | TV | 555.99
| 2 | Computador | 1687.23 |
| 3 | Celular | 791.51 |


A continuacion un _enlace_ o *link*:

[DIARIO EL PAIS DE ESPAÑA] (https://www.elmundo.es/)

A continuacion una _imagen_:

![Logo tipo de JAVA](https://1000marcas.net/wp-content/uploads/2020/11/Java-logo.jpg)


# Titulo nivel 1
 ## Titulo nivel 2
 ### Titulo nivel 3 

A continuacion el **codigo del programa**
    import java.util.Scanner;

    public class Saludo2 {
	public static void main(String[] args){
	    Scanner sc = new Scanner(System.in);
		 String nombre;
		 System.out.print("Dime tu nombre: ");
		 nombre = sc.nextLine();
		 System.out.print("Hola " + nombre);
		 System.out.println(", encantado de conocerte!");
	    }
    }

End
