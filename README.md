# ☕ El Arcón de Java: Mi Pieza de Colección

[![Java Version](https://img.shields.io/badge/Java-8%2B-orange?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.oracle.com/java/)
[![Project Type](https://img.shields.io/badge/Proyecto-Educativo%20%2F%20Portafolio-blue?style=for-the-badge)](https://github.com/)
[![Status](https://img.shields.io/badge/Estado-Restaurado%20y%20Exhibido-brightgreen?style=for-the-badge)](https://github.com/)

> *"Como una figura de colección clásica encontrada en el ático: llena de nostalgia, construida con los cimientos más puros y ahora limpia, pulida y lista para brillar en la repisa principal."*

¡Bienvenido a este repositorio! Este es mi proyecto más antiguo en **Java**, el lugar donde se esculpieron mis primeras líneas de código, donde peleé contra el compilador y donde aprendí a domar la lógica estructurada, la orientación a objetos y las estructuras dinámicas desde cero.

Hoy, este repositorio ha sido "limpiado y restaurado" con esta documentación premium para lucir como la joya de la corona de mis inicios como desarrollador.

---

## 🗺️ Mapa de la Vitrina (Estructura del Proyecto)

El repositorio está dividido de forma cronológica e incremental. Cada módulo representa un nivel de dificultad superior, mostrando mi evolución en el dominio del lenguaje:

```
JAVA/
├── 🌱 PRIMEROS PASOS EN JAVA          # Sintaxis básica, Scanner y bucles clásicos
├── 🧱 POO(PROGRAMACION ORIENTADA...)  # Clases, Herencia y el poder de los Arreglos
├── 🎨 01_INTERFACES VISUALES          # GUI de escritorio con javax.swing (Coordenadas y Eventos)
└── ⚡ 02_ESTRUTURAS DINAMICAS         # Estructuras de datos (Pilas/Colas) hechas a mano
```

---

## 🔍 Detalle de las Piezas (Módulos)

### 🌱 1. Primeros Pasos en Java (El Cincelado Básico)
La base de todo. Aquí aprendí cómo interactuar con el sistema de forma imperativa y a resolver lógica matemática directa en consola.
*   **Contenido:** 12 proyectos desde secuenciales simples hasta bucles anidados.
*   **Enfoque:**
    *   Lectura de datos por consola (`java.util.Scanner`).
    *   Estructuras de decisión (`if`, `else if`, `else`) con condiciones lógicas simples y compuestas.
    *   Bucles iterativos controladores por centinelas y contadores (`while`, `for`, `do-while`).
*   **Pieza Destacada:** `Proyecto2_SueldoOperario`, el clásico cálculo de horas de trabajo multiplicadas por costo de hora que todo programador escribe en su primer día.

### 🧱 2. POO y Arreglos Lineales (La Estructuración del Taller)
El salto al paradigma de objetos y la manipulación de datos en memoria indexada.
*   **Contenido:** 16 subcarpetas explorando algoritmos y relaciones de clases.
*   **Enfoque:**
    *   **Orientación a Objetos:** Instanciación de clases, constructores parametrizados y herencia para reutilización de código.
    *   **Relaciones:** Colaboración directa entre objetos (ej. `Banco` y `Cliente`).
    *   **Algoritmia:** Ordenación de vectores (Método Burbuja), búsqueda de mayor/menor, matrices rectangulares e irregulares, y vectores paralelos.

### 🎨 3. Interfaces Visuales (El Pulido Gráfico)
El momento en que el código cobró vida en la pantalla mediante ventanas interactivas nativas.
*   **Contenido:** 9 proyectos enfocados en componentes del framework clásico **Swing**.
*   **Enfoque:**
    *   Uso de componentes visuales: `JButton`, `JTextField`, `JTextArea`, `JComboBox`, `JMenuBar`, `JRadioButton`.
    *   Diseño mediante coordenadas absolutas (`setLayout(null)` y `setBounds`).
    *   Captura de eventos del usuario mediante `ActionListener` y `actionPerformed`.

### ⚡ 4. Estructuras Dinámicas (La Ingeniería de Precisión)
La sección más avanzada del portafolio. En lugar de usar la biblioteca estándar de Java, diseñé e implementé estructuras de datos clásicas mediante **punteros a nodos enlazados**.
*   **Contenido:** Implementación y demostración de Pilas (`LIFO`) y Colas (`FIFO`).
*   **Enfoque:**
    *   Creación de nodos (`Nodo` con `info` y puntero `sig`).
    *   Operaciones nativas de inserción (push/enqueue) y extracción (pop/dequeue).
    *   **Casos de uso visuales:**
        *   Una interfaz Swing para agregar y quitar elementos de una pila en vivo.
        *   Un analizador que valida si los símbolos algebraicos `()`, `[]`, `{}` de una expresión están **correctamente balanceados** usando una pila interna.

---

## 🛠️ Cómo Exhibir este Proyecto (Ejecución)

Esta figura de colección está diseñada para ser importada en cualquier entorno de desarrollo moderno:

1.  **Requisitos:** Tener instalado el **JDK 8** o superior en tu sistema.
2.  **Importación:**
    *   **Eclipse / IntelliJ IDEA:** Abre el IDE y selecciona *Importar Proyecto existente*. Las carpetas conservan los archivos de metadatos originales de Eclipse (`.project`, `.classpath`).
    *   **VS Code:** Abre la carpeta raíz del proyecto y asegúrate de tener instalada la extensión *Extension Pack for Java*.
3.  **Ejecutar:** Abre cualquier clase que contenga un método `public static void main(String[] args)` (como `Pila.java` en estructuras dinámicas o `SueldoOperario.java` en primeros pasos) y presiona **Run**.

---

## ✨ Mantenimiento de la Figura (Propuestas de Mejora)

Para mantener esta figura libre de polvo y con los estándares modernos de desarrollo, aquí hay algunas tareas de mantenimiento interesantes que se le podrían aplicar:
*   **Ajuste de Convenciones (Clean Code):** Renombrar las clases escritas en minúsculas (como `pila.java` a `Pila.java`) e implementar nombres de variables en `camelCase` en lugar de `PascalCase`.
*   **Layout Managers:** Migrar del posicionamiento absoluto (`setBounds`) de las GUIs a administradores responsivos (`BorderLayout`, `GridLayout`) para que las ventanas se vean perfectas en cualquier resolución.
*   **Pruebas Automatizadas:** Incorporar **JUnit** para verificar de forma unitaria y automática la lógica de balanceo de fórmulas de `Formula.java`.

---

> ✨ *¡Gracias por visitar este rincón del pasado! Es un recordatorio de que cada gran desarrollador comenzó con un simple `System.out.println("Hola Mundo");`.*
