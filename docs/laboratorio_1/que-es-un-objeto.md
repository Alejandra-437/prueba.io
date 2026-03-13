# Que es un objeto

![Que es un objeto](../imagenes/Laboratorio_1/7.jpeg)

Un objeto es una instancia concreta de una clase.

## Instanciar una clase

![Instanciacion de una clase](../imagenes/Laboratorio_1/8.png)

Declarar una referencia no crea el objeto; se crea con new.

```java
Mascota perro;
perro = new Mascota("Spike", 3);
```

## Inicializar y usar un objeto

```java
public class Main {
    public static void main(String[] args) {
        Mascota perro = new Mascota("Spike", 3, false);
        perro.mostrarInfo();
    }
}
```

Salida esperada:

```text
Nombre: Spike
Edad: 3
Esta durmiendo? No
```
