# 🎮 Juego de Memoria (Memory Game)

Juego de cartas clásico para encontrar parejas, desarrollado con HTML, CSS moderno (usando Tailwind CSS) y JavaScript puro. Un proyecto simple pero divertido para practicar lógica de programación y manipulación del DOM.

## 🌟 Características

  * **16 Cartas** (8 pares de emojis de comida).
  * **Mecánica de volteo y emparejamiento** con bloqueo de tablero temporizado.
  * Diseño **responsive** con cuadrícula.
  * Efecto de **giro 3D** para las cartas.
  * Implementación de lógica de **barajado** (Fisher-Yates).

## 🛠️ Tecnologías Utilizadas

  * **HTML5:** Estructura del juego.
  * **CSS:** Estilos personalizados para el efecto *flip* de las cartas.
  * **Tailwind CSS:** Framework de CSS utilitario para un diseño rápido y moderno (cargado vía CDN).
  * **JavaScript (ES6+):** Lógica del juego, manejo de clics, comparación de parejas y reinicio del juego.

## 🚀 Cómo Jugar

Simplemente abre el archivo `[index.html](/index.html)` en cualquier navegador web moderno (Chrome, Firefox, Edge, etc.) para comenzar a jugar.

Si lo estás viendo en **[GitHub Pages](https://elbuho89.github.io/juego-memoria-html/)**:

1.  Haz clic en cualquier carta para voltearla y revelar su emoji.
2.  Haz clic en una segunda carta.
3.  **Si coinciden:** Las cartas se quedan volteadas y se marcan con un color diferente.
4.  **Si no coinciden:** Las cartas se voltearán de nuevo después de 1 segundo.
5.  Encuentra todas las parejas para ganar y el juego se reiniciará automáticamente.

## 📁 Estructura del Proyecto

El proyecto está autocontenido en un solo archivo para máxima simplicidad:

```
├── index.html    <-- Contiene todo el HTML, CSS (<style>) y JavaScript (<script>)
└── README.md     <-- Este archivo
```

## 📜 Licencia

Este proyecto está bajo la Licencia MIT. Eres libre de usar, modificar y distribuir el código. Para más detalles, consulta el archivo [LICENSE](/LICENSE) 
