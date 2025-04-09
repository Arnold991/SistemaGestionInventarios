##  Video de Demostración

Puedes ver el video funcionando en el siguiente enlace:  
[ Ver en YouTube](https://youtu.be/46xgYApWXhk?si=2AZzfnGNqEfHYmTE)


#  Sistema de Gestión de Inventarios

Proyecto final de la clase **Programación Orientada a Objetos** – UTH

##  Desarrollado por:
**Arnold Aguilar**  
Número de cuenta: 202130010449

##  Descripción
Este sistema permite gestionar productos dentro de un inventario, junto con sus categorías y proveedores. Fue desarrollado en Java utilizando los principios fundamentales de la Programación Orientada a Objetos.

##  Características

- Agregar productos con categoría y proveedor
- Mostrar el inventario completo
- Buscar productos por código
- Alertas de stock bajo
- Menú interactivo en consola

##  Tecnologías
- Lenguaje: **Java**
- Entorno: **Apache NetBeans IDE 24**
- Repositorio: **GitHub**

##  Principios de POO aplicados

| Principio       | Aplicación                                                                 |
|----------------|-----------------------------------------------------------------------------|
| Encapsulación   | Atributos privados en clases como `Producto`                              |
| Herencia        | `Categoria` y `Proveedor` heredan de clase abstracta `Entidad`            |
| Polimorfismo    | Uso de interfaz `Buscable` en la clase `Inventario`                       |
| Abstracción     | `Entidad` como clase abstracta general para entidades                     |
| Excepciones     | Manejo de errores con `try-catch` en entrada de datos                     |

## Instrucciones de uso

1. Clona o descarga el repositorio.
2. Abre el proyecto en NetBeans.
3. Ejecuta `Main.java`.
4. Usa el menú interactivo para gestionar tu inventario.
