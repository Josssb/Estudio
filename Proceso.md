# Proceso de Creación, Compilación y Ejecución del Archivo Java

Este documento describe los pasos necesarios para crear, compilar y ejecutar un programa Java básico desde la línea de comandos.

## Paso 1: Crear el Archivo Java

1. Se abre un editor de texto simple: El seleccionado en este caso fue Bloc de Notas.
2. Se escribe el siguiente código en el editor:

    ```java
    import java.util.Scanner;

    public class Estudio {
      public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Ingrese la marca: ");
        String marca = scanner.nextLine();

        System.out.print("Ingrese el modelo: ");
        String modelo = scanner.nextLine();

        System.out.print("Ingrese la cilindrada: ");
        String cilindrada = scanner.nextLine();

        System.out.print("Ingrese el tipo de combustible: ");
        String tipoCombustible = scanner.nextLine();

        System.out.print("Ingrese la capacidad en pasajeros: ");
        int capacidadPasajeros = scanner.nextInt();

        System.out.println("La marca que ha ingresado es: " + marca);
        System.out.println("El modelo que ha ingresado es: " + modelo);
        System.out.println("La cilindrada que ha ingresado es: " + cilindrada);
        System.out.println("El tipo de combustible es: " + tipoCombustible);
        System.out.println("Tiene una capacidad de " + capacidadPasajeros + " pasajeros.");
      }
    }
    ```

3. Se guarda el archivo con el nombre `Estudio.java`.

## Paso 2: Compilar el Archivo Java

1. Se bre la línea de comandos CMD en Windows.
2. Se navega hasta el directorio donde guardaste `Estudio.java` utilizando el comando `cd`. Por ejemplo:

    ```bash
    cd C:\Users\jossi\Documents\AIEP
    ```

3. Seompila el archivo utilizando el compilador de Java (`javac`):

    ```bash
    javac Estudio.java
    ```

4. La compilación es exitosa, se crea un archivo `Main.class` en el mismo directorio.

## Paso 3: Ejecutar el Archivo Compilado

1. Para ejecutar el programa, usa el comando `java` seguido del nombre de la clase sin la extensión `.class`:

    ```bash
    java Main
    ```

2. El programa solicitará al usuario que ingrese datos y luego mostrará los resultados en la pantalla.
