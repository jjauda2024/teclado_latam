# 🎹 Teclado Latinoamericano con Perspectiva en Phaser 🚀

Este proyecto es una implementación de un teclado virtual con la distribución de teclado Latinoamericano, renderizado con el framework de juegos Phaser.js. Incorpora una perspectiva "semirreclinada" para simular la vista de un teclado real de computador, y responde visualmente a las pulsaciones de teclas.

El objetivo principal es crear un componente de teclado modular y configurable que pueda ser integrado en diversos proyectos web basados en Phaser.

## ✨ Características

* **Distribución de Teclado Latinoamericano:** Mapeo preciso de caracteres y teclas especiales (`ñ`, acentos, `Alt Gr`, etc.).
* **Perspectiva Semirreclinada:** Simulación visual de profundidad y ángulo de un teclado físico real (configurable).
* **Modularidad:** Implementado como una clase `KeyboardLayout` independiente para fácil integración y reutilización.
* **Feedback Visual:** Las teclas cambian de color y se animan al ser presionadas.
* **Visualización de Tecla Pulsada:** Muestra la última tecla presionada en la pantalla.
* **Configurable:** Permite ajustar fácilmente parámetros como el tamaño de las teclas, márgenes y la intensidad de la perspectiva.

## 🛠️ Tecnologías Utilizadas

* **JavaScript (ES Modules):** Para la lógica principal y la modularidad del código.
* **Phaser 3:** El framework de juegos para el renderizado gráfico y la gestión de eventos.
* **HTML/CSS:** Para la estructura básica de la página.
