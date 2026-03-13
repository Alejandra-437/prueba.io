# Encapsulamiento

![Encapsulamiento](../imagenes/Laboratorio_1/5.jpeg)

Encapsular protege los atributos y controla el acceso mediante metodos.

```java
public class Mascota {
    private String nombre;
    private int edad;
    private boolean durmiendo;

    public Mascota(String nombre, int edad, boolean durmiendo) {
        this.nombre = nombre;
        this.edad = edad;
        this.durmiendo = durmiendo;
    }

    public String getNombre() {
        return nombre;
    }

    public void setNombre(String nombre) {
        this.nombre = nombre;
    }

    public int getEdad() {
        return edad;
    }

    public void setEdad(int edad) {
        this.edad = edad;
    }

    public boolean isDurmiendo() {
        return durmiendo;
    }

    public void setDurmiendo(boolean durmiendo) {
        this.durmiendo = durmiendo;
    }
}
```