# Implementando lo aprendido

```java
public class Mascota {
    String nombre;
    int edad;
    boolean durmiendo;

    public Mascota(String nombre, int edad, boolean durmiendo) {
        this.nombre = nombre;
        this.edad = edad;
        this.durmiendo = durmiendo;
    }

    public void dormir() {
        this.durmiendo = true;
        System.out.println("La mascota esta durmiendo.");
    }

    public void despertar() {
        this.durmiendo = false;
        System.out.println("La mascota esta despierta.");
    }

    public void mostrarInfo() {
        System.out.println("Nombre: " + nombre);
        System.out.println("Edad: " + edad);
        System.out.println("Esta durmiendo? " + (durmiendo ? "Si" : "No"));
    }
}
```