# 🎸 Práctica Diapasón – App interactiva para guitarra

Aplicación web **autocontenida** (un solo archivo `.html`), diseñada para ayudarte a memorizar las **notas del diapasón** de la guitarra. Funciona sin conexión, sin necesidad de instalar nada ni lanzar servidores. Compatible con móviles y ordenadores.

---

## 🚀 ¿Qué puedes practicar?

Al iniciar, se te pregunta:

> **¿Qué quieres practicar?**

Tienes dos opciones:

### 🟦 Modo 1: Ubicar trastes según nota y cuerda

* Se muestra una nota aleatoria (ej. `B de cuerda 5`).
* Tú debes mentalmente ubicarla en el diapasón.
* Puedes comprobar la respuesta pulsando el botón **“Trastes”**, que indica los trastes correctos.
* Opción de control por voz: decir **“otra”**, **“siguiente”** o **“nota nueva”** genera una nueva pregunta.

### 🟩 Modo 2: Averiguar nota según traste y cuerda

* Se muestra una combinación aleatoria (ej. `Traste 7 de cuerda 2`).
* Tú debes adivinar qué nota es.
* Puedes comprobar la respuesta con el botón **“Mostrar 🎵”** (no reproduce sonido).
* Al generar la combinación, se reproduce el sonido de la nota si el sonido está activado.
* También soporta control por voz (mismas palabras clave).

---

## ⚙️ Configuración antes de practicar

* Selecciona las **notas a practicar** (ej: A, B, C…).
* Puedes incluir **sostenidos (#)** y/o **bemoles (b)** si lo deseas.
* El sistema generará solo combinaciones válidas según tu selección.

---

## 🔈 Controles de sonido

* Puedes **activar/desactivar el sonido** desde la interfaz (modo configuración o práctica).
* Puedes **ajustar el volumen** con un deslizador.
* El sonido reproduce un tono con frecuencia correspondiente a la nota mostrada.

---

## 🎤 Control por voz (opcional)

* Una vez iniciada la práctica, puedes **activar el control por voz**.
* Funciona diciendo: `"siguiente"`, `"otra"`, `"nota nueva"` (en español).
* Se muestra un **indicador rojo** cuando el micro está escuchando.
* Compatible con navegadores que soporten `webkitSpeechRecognition` o `SpeechRecognition`.

---

## 📱 Optimizado para móviles

* Diseño vertical y adaptado a pantalla completa.
* Todos los controles son táctiles (sin necesidad de teclado).

---

## 🔁 Funcionalidades extra

* Nunca se repite la **misma nota consecutivamente** (modo 1).
* Puedes volver al menú principal con el botón **“Volver al inicio”**.
* Tu selección de notas se guarda entre sesiones.
* El fondo cambia de color en cada nueva pregunta para hacerlo más dinámico.
* Iconos visuales decorativos como SVG de trastes y 🎵 para una experiencia más agradable.

---

## 🧩 Cómo usar la app

1. Abre el archivo `.html` en cualquier navegador moderno.
2. Selecciona el modo de práctica.
3. Configura las notas que quieres trabajar.
4. ¡Empieza a practicar!
