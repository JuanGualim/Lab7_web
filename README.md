# 🐍 Snake Game con React (sin herramientas de build)

## 📌 Descripción

Este proyecto es una implementación del clásico juego **Snake** desarrollada utilizando **React vía CDN** y **Babel**, sin el uso de herramientas de build como Vite o Create React App.

El objetivo principal fue aplicar conceptos fundamentales de React como:

* Componentes
* Props
* Estado (`useState`)
* Efectos (`useEffect`)

---

## 🚀 Características

### 🎮 Funcionalidad principal

* Movimiento de la serpiente con el teclado
* Crecimiento al comer comida
* Generación aleatoria de comida
* Detección de colisiones:

  * Con paredes
  * Con el propio cuerpo
* Sistema de puntaje
* Game Over

---

### ⭐ Extras implementados

* Pantalla de inicio
* Botón de reinicio del juego
* Velocidad progresiva (aumenta la dificultad)
* Interfaz mejorada

---

## 🧱 Estructura del proyecto

El proyecto está organizado en componentes:

* **Game** → Contenedor principal y lógica del juego
* **Board** → Tablero donde se renderiza el juego
* **Snake** → Representación conceptual de la serpiente
* **Food** → Representación conceptual de la comida
* **Score** → Muestra el puntaje y velocidad

---

## 🕹️ Cómo jugar

1. Abrir el archivo `index.html` en navegador
2. Presionar el botón **"Iniciar Juego"**
3. Usa las flechas del teclado:

   * ⬆️ Arriba
   * ⬇️ Abajo
   * ⬅️ Izquierda
   * ➡️ Derecha
4. Come la comida para crecer y ganar puntos
5. Evita chocar contra las paredes o contra ti mismo

---

## 🛠️ Tecnologías utilizadas

* React (CDN)
* ReactDOM (CDN)
* Babel (CDN)
* HTML5
* CSS3
* JavaScript (ES6)

---

## 📂 Estructura de archivos

```bash
📁 proyecto-snake/
│── index.html
│── README.md
```

---

## ▶️ Ejecución

No se requiere instalación.

Simplemente abrir el archivo:

```bash
index.html
```

en cualquier navegador moderno.

---

## 👨‍💻 Autor

**Juan Gualim**

---
