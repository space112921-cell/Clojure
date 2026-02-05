# Hola Mundo en Clojure

Este repositorio contiene un programa básico en **Clojure** que imprime el mensaje **"Hello, World!"** en la consola.  
El objetivo del proyecto es servir como **primer acercamiento al lenguaje Clojure**, mostrando la estructura mínima de un proyecto y el uso del REPL.


- **deps.edn**: archivo de configuración del proyecto. Define la ruta donde se encuentra el código fuente.
- **src/core.clj**: archivo principal que contiene el código del programa.

---

## 🧠 Contenido del programa

El programa utiliza la función `println` para mostrar un mensaje en pantalla:

```clojure
(ns core)

(println "Hello, World!")
