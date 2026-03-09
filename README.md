# 🎨 Canvas 2D con Programación Orientada a Objetos

Aplicación web desarrollada con **HTML, CSS, JavaScript y Bootstrap** que demuestra el uso de la **API Canvas 2D** utilizando **Programación Orientada a Objetos (OOP)** para crear y renderizar círculos dentro de distintos canvas.

---

## 📌 Descripción

Este proyecto muestra cómo utilizar **Canvas 2D en JavaScript** para dibujar figuras geométricas mediante una **clase llamada `Circle`**.

La aplicación contiene tres ejemplos principales:

1. **Objeto 2D**  
   Un círculo generado con valores fijos en el centro del canvas.

2. **Objeto con Random**  
   Un círculo generado con **posición y tamaño aleatorios**.

3. **Múltiples Objetos**  
   Se generan varios círculos dentro del canvas utilizando un **ciclo `for`**.

Cada círculo tiene:

- Color de contorno  
- Color de relleno  
- Texto centrado  
- Posición dentro del canvas  

Además, el sistema evita que los círculos **se salgan del área del canvas**.

---

## 🛠️ Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript
- Bootstrap 5
- Canvas API

---

## 📂 Estructura del proyecto
proyecto-canvas2D
│
├── index.html
│
├── assets
│ │
│ ├── css
│ │ └── style.css
│ │
│ ├── js
│ │ └── main.js
│ │
│ └── Img
│ └── conejo.png
│
└── README.md


## ⚙️ Funcionamiento

El proyecto utiliza una **clase `Circle`** para crear objetos gráficos.

### Constructor

```javascript
constructor(x, y, radius, color, text, backcolor, textcolor)