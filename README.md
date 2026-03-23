# 🗣️ AI Language Coach (Experimental)

Este es un proyecto experimental desarrollado para explorar las capacidades de la **API de Groq** y el procesamiento de voz nativo en navegadores modernos (**Web Speech API**).

## 💡 ¿Por qué este experimento?

En el mercado actual existen muchísimas aplicaciones para practicar idiomas con IA (como Speak, ELSA o Loora), pero casi todas funcionan bajo modelos de suscripción bastante costosos. 

Este proyecto nace de la curiosidad: **¿Hasta dónde podemos llegar utilizando únicamente herramientas gratuitas y nativas?**
- **Cero costes de servidores:** El procesamiento de voz (STT y TTS) se delega totalmente al navegador del usuario.
- **Inferencia de alto nivel:** Las respuestas las genera **Groq**, aprovechando su generosa capa gratuita para desarrolladores.

## 🚀 Prueba la App

Puedes acceder a la versión funcional directamente desde tu navegador (móvil o PC) aquí:

👉 **[https://tvorog-228.github.io/mi_tutor/](https://tvorog-228.github.io/mi_tutor/)**

> **Nota importante:** Para que el tutor funcione, deberás introducir tu propia **API Key de Groq** al iniciar. La clave se guarda de forma segura y local en tu navegador (`localStorage`) y nunca sale de tu dispositivo hacia otros servidores que no sean los oficiales de Groq.

## 🌟 Funcionalidades clave

- **Procesamiento de Voz (STT):** Uso de `SpeechRecognition` nativo para convertir el habla del usuario en texto sin necesidad de APIs externas de pago.
- **Síntesis de Voz (TTS):** Implementación de `SpeechSynthesis` con selector de voces del sistema y control de velocidad en tiempo real.
- **Cerebro con Groq:** Respuestas inteligentes y ultrarrápidas utilizando el modelo `llama-3.3-70b-versatile`.
- **Estructura de Aprendizaje:** El sistema ofrece correcciones gramaticales sutiles y mantiene el flujo de la conversación de forma natural.
- **Escenarios Dinámicos:** Modos configurables (Entrevista, Amigo, Viajes) que adaptan la personalidad y el vocabulario de la IA.

## 🛠️ Tecnologías utilizadas

- **HTML5 / JavaScript (Vanilla):** Sin frameworks pesados (React/Vue) para garantizar la máxima velocidad de carga.
- **Tailwind CSS:** Interfaz moderna, minimalista y adaptada a dispositivos móviles.
- **Web Speech API:** Tecnología nativa del navegador para el reconocimiento y la síntesis de voz gratuita.
- **Groq Cloud API:** Inferencia de IA de bajísima latencia para una conversación fluida.

## 🧪 Notas del Experimento

Este proyecto demuestra que no siempre es necesario pagar una suscripción mensual para tener un tutor de idiomas de alta calidad. Al combinar el hardware del propio usuario (su navegador) con APIs de inferencia eficientes como Groq, podemos democratizar el acceso a herramientas de aprendizaje potentes.

---
Desarrollado con curiosidad, **Neovim** y código limpio.
