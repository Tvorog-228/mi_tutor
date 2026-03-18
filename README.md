# 🗣️ AI Language Coach (Experimental)

Este es un proyecto experimental desarrollado para explorar las capacidades de la **API de Groq** y el procesamiento de voz nativo en navegadores modernos (**Web Speech API**).

El objetivo principal fue probar la integración de un modelo de lenguaje de alto rendimiento (Llama 3.3) con herramientas de accesibilidad web para crear un tutor de idiomas interactivo.

## 🚀 Prueba la App

Puedes acceder a la versión funcional directamente desde tu navegador (móvil o PC) aquí:

👉 **https://tvorog-228.github.io/mi_tutor/**

> **Nota importante:** Para que el tutor funcione, deberás introducir tu propia **API Key de Groq** al iniciar. La clave se guarda de forma segura y local en tu navegador (`localStorage`) y nunca se envía a ningún servidor externo que no sea el de Groq.

## 🌟 Funcionalidades clave

- **Procesamiento de Voz (STT):** Uso de `SpeechRecognition` para convertir el habla del usuario en texto sin servidores intermedios.
- **Síntesis de Voz (TTS):** Implementación de `SpeechSynthesis` con selector de voces nativas y control de velocidad en tiempo real.
- **Cerebro con Groq:** Respuestas inteligentes y ultrarrápidas utilizando el modelo `llama-3.3-70b-versatile`.
- **Estructura de Aprendizaje:** El sistema primero ofrece una corrección gramatical y luego continúa el flujo de la conversación de forma concisa.
- **Escenarios Dinámicos:** Modos configurables (Entrevista, Amigo, Viajes) que adaptan la personalidad y el vocabulario de la IA.

## 🛠️ Tecnologías utilizadas

- **HTML5 / JavaScript (Vanilla):** Sin frameworks pesados para garantizar la máxima velocidad.
- **Tailwind CSS:** Interfaz moderna y adaptada a dispositivos móviles.
- **Web Speech API:** Utilizada para el reconocimiento y la síntesis de voz nativa.
- **Groq Cloud API:** Inferencia de IA de baja latencia.

## 🧪 Notas del Experimento

Este proyecto nació como una prueba de concepto para demostrar que es posible crear herramientas de aprendizaje potentes utilizando únicamente tecnologías nativas del navegador. Al eliminar el backend, se reduce la latencia y se mejora la privacidad del usuario.

---
Desarrollado con curiosidad, Neovim y código limpio. 
