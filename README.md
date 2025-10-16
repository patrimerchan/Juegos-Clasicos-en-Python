# 🎮 Demo de Juegos Clásicos - Proyecto de Entretenimiento Interactivo

## 📌 Descripción General

Este repositorio contiene una **demo de juegos clásicos** desarrollada por nuestro equipo, como parte de un proyecto de entretenimiento interactivo. El objetivo es ofrecer una experiencia divertida y educativa a los usuarios, mediante juegos de lógica, preguntas y estrategia.  

La demo incluye **tres juegos independientes**, desarrollados en Python, cada uno en su propio archivo Jupyter Notebook (`.ipynb`), acompañados de documentación con pseudocódigo, reglas del juego e historias de usuario.

---

## 🕹️ Juegos Incluidos

### 1. Ahorcado
- **Descripción:** Juego de adivinanza de palabras. La usuaria debe descubrir la palabra secreta antes de que se complete el dibujo del ahorcado.  
- **Mecánica:** Cada intento incorrecto acerca al jugador a perder la partida, mientras que los aciertos revelan las letras correctas en el tablero.  
- **Objetivo:** Adivinar la palabra antes de agotar los intentos.  

### 2. Piedra, Papel o Tijeras
- **Descripción:** Juego clásico de elección rápida entre tres opciones: piedra, papel o tijeras.  
- **Mecánica:** La usuaria juega contra la máquina. La primera en alcanzar 3 puntos gana la partida.  
- **Reglas básicas:**
  - Piedra vence a tijeras.  
  - Papel vence a piedra.  
  - Tijeras vence a papel.  

### 3. Preguntas y Respuestas
- **Descripción:** Juego de cuestionario de conocimiento general. Se realizan rondas de 5 preguntas aleatorias de un conjunto de 20.  
- **Mecánica:** La usuaria responde seleccionando la opción correcta. Se otorgan puntos por cada respuesta correcta, con retroalimentación positiva o correctiva.  
- **Objetivo:** Acumular la mayor cantidad de puntos posible y aprender mientras se juega.

---

## ⚙️ Requisitos y Dependencias

- **Lenguaje:** Python 3.x  
- **Entorno recomendado:** Jupyter Notebook  
- **Dependencias:** Ninguna externa, se utilizan solo librerías estándar de Python (`random`, etc.)

---

## 🚀 Instrucciones de Ejecución

1. Clonar el repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
2. Abrir Jupyter Notebook en la carpeta del proyecto:

   jupyter notebook

3. Seleccionar el archivo del juego que deseas ejecutar:

    -  Ahorcado.ipynb

    - Piedra_Papel_Tijeras.ipynb

    - Preguntas_y_Respuestas.ipynb

4. Ejecutar las celdas paso a paso y seguir las instrucciones dentro de cada juego.

## 🗂️ Estructura del Repositorio
```bash
JUEGOS-CLASICOS-EN-PYTHON/
│
├── ahorcado/
│ ├── A_codigo-final.ipynb
│ ├── A_codigo-pruebas.ipynb
│ ├── A_historia_de_usuario.ipynb
│ ├── A_pseudocódigo.ipynb
│ └── A_Reglas.ipynb
│
├── piedra_papel_tijera/
│ ├── PPT_aporte_vio.ipynb
│ ├── PPT_codigo-python_copy.ipynb
│ ├── PPT_codigo-python.ipynb
│ ├── PPT_historia_de_usuario.ipynb
│ ├── PPT_planteamiento.ipynb
│ └── PPT_pseudocódigo.ipynb
│
├── preguntas_respuestas/
│ ├── PR_codigo-final.ipynb
│ ├── PR_Descripción_Técnica.ipynb
│ ├── PR_Historia_de_usuario.ipynb
│ ├── PR_ideas.ipynb
│ └── PR_Reglas.ipynb
│
├── estatutos_Team1.ipynb
├── planificación_Juegos.ipynb
└── README.md

```
## 👥 Equipo de Desarrollo

- Ariana Caldeira
- Elena Pavón
- Gisela Barroso
- Patricia Merchán
- Violeta Pufulete

## 📄 Entrega de Demo al Cliente

Esta demo se entrega como versión de prueba funcional, permitiendo a los usuarios interactuar con los juegos y evaluar la experiencia de usuario.
Se han incluido todas las herramientas necesarias para ejecutar los juegos de manera inmediata y observar la lógica de cada proyecto, incluyendo pseudocódigo y documentación de reglas.

## 🏆 Notas Finales

Todos los juegos están diseñados para ser educativos y entretenidos.

Se pueden ampliar o personalizar fácilmente con más preguntas, palabras o reglas.

Esta demo sirve como prototipo funcional para presentaciones o pruebas de concepto.
