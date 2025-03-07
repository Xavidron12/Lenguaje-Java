# Programación Orientada a Objetos (POO) en Java

La **Programación Orientada a Objetos (POO)** es un paradigma de programación basado en el uso de **clases** y **objetos**. Java es un lenguaje diseñado específicamente para este enfoque.

## 🏗️ **Conceptos clave de la POO**
1️⃣ **Clases:** Plantillas para crear objetos.  
2️⃣ **Objetos:** Instancias de una clase.  
3️⃣ **Encapsulación:** Protección de datos mediante modificadores de acceso.  
4️⃣ **Herencia:** Capacidad de una clase de heredar atributos y métodos de otra.  
5️⃣ **Polimorfismo:** Uso de una misma interfaz para distintos tipos de datos.

##  **Ejemplo de una Clase en Java**
```java
class Persona {
    String nombre;
    
    Persona(String nombre) {
        this.nombre = nombre;
    }

    void mostrarNombre() {
        System.out.println("Mi nombre es " + nombre);
    }
}

public class Main {
    public static void main(String[] args) {
        Persona p = new Persona("Javier");
        p.mostrarNombre();
    }
}
