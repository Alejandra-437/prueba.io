# Que es una clase

![Que es una clase](../imagenes/Laboratorio_1/1.png)

Una clase define:

- Atributos (caracteristicas)
- Metodos (acciones)
- Constructores
- Modificadores de acceso

```java
public class Mascota {
    String nombre;
    int edad;
    boolean comiendo;

    public void comer() {
        this.comiendo = true;
        System.out.println("Nam Nam Nam");
    }

    public void hacerSonido() {
        System.out.println("Woof!");
    }
}
```

## Abstraccion

![Abstraccion](../imagenes/Laboratorio_1/2.jpeg)

Abstraer es modelar solo lo necesario del problema.
