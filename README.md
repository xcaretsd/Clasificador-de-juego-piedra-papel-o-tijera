# Clasificador de Gestos: Piedra, Papel o Tijera con IA

## Descripción del Proyecto
Este proyecto consiste en un modelo de visión por computadora capaz de reconocer en tiempo real los gestos del clásico juego "Piedra, Papel o Tijera" utilizando la cámara web del usuario.

El modelo fue entrenado mediante aprendizaje supervisado utilizando la herramienta **Teachable Machine** de Google, procesando las imágenes directamente en el navegador con **TensorFlow.js** para ofrecer una experiencia interactiva y sin necesidad de instalar software adicional.

## Demo en vivo
Puedes probar el modelo funcionando directamente en tu navegador aquí:
**[Haz clic aquí para jugar con la IA](https://xcaretsd.github.io/Clasificador-de-juego-piedra-papel-o-tijera/)**
*(Nota: Requiere dar permisos de acceso a la cámara web).*

## Tecnologías Utilizadas
* **HTML5 y CSS3:** Para la estructura y el diseño responsivo de la página.
* **JavaScript:** Para la lógica de interacción.
* **TensorFlow.js:** Para ejecutar el modelo de IA en el navegador.
* **Teachable Machine (Google):** Para el entrenamiento del modelo de clasificación de imágenes.
* **Git y GitHub:** Para el control de versiones.
* **GitHub Pages:** Para el despliegue y alojamiento de la página web.

## ¿Cómo funciona?
1. Se recopilaron imágenes de los tres gestos (Piedra, Papel y Tijera) usando la cámara web, variando la iluminación, el fondo y los ángulos.
2. Se entrenó un modelo de red neuronal directamente en Teachable Machine.
3. El modelo se exportó en formato TensorFlow.js.
4. La página web captura el video de la cámara en tiempo real, lo envía al modelo y muestra la predicción con su nivel de confianza (en porcentaje).

## Datos de Entrenamiento y Limitaciones
* **Clases:** 3 (Piedra, Papel, Tijera).
* **Muestras:** Aproximadamente [PON AQUÍ EL NÚMERO, ej. 150] imágenes en total.
* **Limitaciones:** Al ser un modelo entrenado con un dataset pequeño, su precisión puede disminuir en condiciones de baja iluminación o si la mano se encuentra muy cerca de la cámara. 

## Autora
**Xcaret Sanchez Delgado**
Estudiante de Ingeniería en Inteligencia Artificial
