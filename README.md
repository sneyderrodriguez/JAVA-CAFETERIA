# ☕ Sistema de Cafetería — Java

> Proyecto de consola desarrollado en **Java** para practicar los fundamentos de programación mediante la simulación del procesamiento de pedidos de una cafetería.

![Java](https://img.shields.io/badge/Java-Programación-orange?logo=openjdk)
![Estado](https://img.shields.io/badge/Estado-Proyecto%20académico-blue)

---

## 📌 Sobre el proyecto

**Sistema de Cafetería** reúne ejercicios de introducción a Java y una clase principal (`Cafeteria.java`) que integra variables, arreglos, operadores, condicionales y ciclos. Los pedidos y productos están definidos directamente en el código; la aplicación muestra sus resultados en la consola.

## ✨ Características principales

- Catálogo de cinco productos con nombre, precio y categoría.
- Clasificación de productos mediante `switch`: bebida caliente (`B`), bebida fría (`F`), comida (`C`) y postre (`P`).
- Procesamiento de pedidos con arreglos y un ciclo `for`.
- Comprobación del inventario de brownies antes de procesar su venta.
- Descuento del **10 %** cuando el subtotal de un pedido supera **$12.000**.
- Validación del monto de apertura mediante `do-while` (con valor establecido en el código).
- Resumen de pedidos procesados, total recaudado y pedido de mayor valor.

> **Nota:** es una simulación con datos precargados, no un sistema con interfaz gráfica, base de datos ni captura interactiva de pedidos.

## 🧰 Tecnologías y conceptos

- **Lenguaje:** Java.
- **Ejecución:** consola.
- **Conceptos:** tipos de datos, constantes, operadores, `if/else`, `switch`, `while`, `do-while`, `for`, arreglos y depuración.
- **Entorno:** el proyecto incluye archivos de configuración de IntelliJ IDEA (`.idea/` y `.iml`), aunque puede compilarse desde la terminal con un JDK compatible.

## 📁 Estructura del proyecto

```text
JAVA-CAFETERIA/
├── README.md
├── .gitignore
├── Sistema_Cafeteria.iml
└── src/
    ├── Cafeteria.java
    ├── variablestipodatos.java
    ├── operadores.java
    ├── suitch.java
    ├── ciclowhile.java
    ├── ciclodowhile.java
    ├── foryarrays.java
    └── debugging.java
```

### ¿Qué hace cada clase?

| Archivo | Contenido |
|---|---|
| `Cafeteria.java` | Integra catálogo, pedidos, inventario, descuentos y resumen de ventas. |
| `variablestipodatos.java` | Declara e imprime distintos tipos de datos. |
| `operadores.java` | Calcula un descuento condicional del 15 % en un ejercicio independiente. |
| `suitch.java` | Clasifica categorías de productos y muestra porcentajes de IVA como ejemplo. |
| `ciclowhile.java` | Simula la disminución de inventario con `while`. |
| `ciclodowhile.java` | Ejemplifica la validación de un monto de apertura. |
| `foryarrays.java` | Recorre productos y calcula el precio promedio. |
| `debugging.java` | Contiene un ejemplo de corrección de errores y cálculo de descuento. |

## 🖥️ Ejecutar el proyecto localmente

**Requisito:** tener instalado un JDK compatible con el método `main` sin modificador de acceso usado en estas clases (por ejemplo, JDK 25).

### 1. Obtener el proyecto

Descarga o descomprime el proyecto y abre una terminal en su carpeta raíz (`JAVA-CAFETERIA`).

### 2. Compilar la clase principal

```bash
javac -d out src/Cafeteria.java
```

Este comando genera el archivo compilado dentro de la carpeta `out`.

### 3. Ejecutar la simulación

```bash
java -cp out Cafeteria
```

Para ejecutar otro ejercicio, sustituye `Cafeteria` por el nombre exacto de su clase y compila antes el archivo correspondiente. También puedes abrir el proyecto en IntelliJ IDEA, configurar el JDK y ejecutar la clase deseada.

## 🔎 Funcionamiento de la simulación

La clase principal define un catálogo y seis registros de pedido en dos arreglos paralelos: uno indica el producto y el otro su cantidad. Para cada registro, el programa muestra la categoría, comprueba las existencias si se trata de brownies, calcula el subtotal y aplica el descuento cuando corresponde. Finalmente imprime el total de pedidos atendidos, la recaudación y el número del pedido de mayor valor.

**Datos configurables:** puedes cambiar los productos, precios, categorías, pedidos, cantidades, inventario inicial y monto de apertura directamente en `src/Cafeteria.java`. Si modificas los pedidos, mantén alineados los arreglos `pedidoProducto` y `pedidoCantidad` y utiliza índices válidos del catálogo.

## 🚀 Posibles mejoras

- Permitir ingresar pedidos desde el teclado.
- Validar los índices de productos y las cantidades solicitadas.
- Administrar el inventario de todos los productos.
- Separar la lógica en métodos o clases para facilitar su mantenimiento.
- Incorporar pruebas automáticas.

## 👨‍💻 Autor

**Sneyder Rodríguez** — Desarrollo Full-Stack Java.

- [GitHub](https://github.com/SneyderRodriguez)
- [LinkedIn](https://www.linkedin.com/in/sneyder-rodriguez-ingeniero-de-sistemas/)
- [Portafolio](https://sneyderrodriguez.netlify.app/)

---

## 📄 Licencia

Este proyecto está disponible bajo la licencia **MIT**.

Puedes utilizar, modificar y distribuir el código respetando los términos establecidos en dicha licencia.
