# 🔐 Cipher Tool – WW2 Message Encoder

Aplicación web simple para **encriptar y desencriptar mensajes**, desarrollada como herramienta para el juego **“Mensajes Secretos del Frente”**, una dinámica educativa inspirada en comunicaciones militares durante la Segunda Guerra Mundial.

La aplicación permite a los jugadores **codificar órdenes militares** antes de enviarlas a través de mensajeros durante el juego.

---

# 🎮 Contexto del Proyecto

Este proyecto fue creado para una actividad de clase sobre **mecanismos de seguridad y cifrado**.

Durante el juego:

- El **Comandante** escribe un mensaje secreto.
- El mensaje se **cifra usando la aplicación**.
- El **Mensajero** transporta el mensaje.
- El **Operador de radio** usa la app para **descifrarlo**.

Esto simula el funcionamiento del **cifrado simétrico en comunicaciones militares**.

---

# ✨ Características

La aplicación incluye múltiples métodos de cifrado:

| Método | Descripción |
|------|------|
| **César** | Desplaza cada letra del alfabeto un número determinado de posiciones |
| **Base64** | Codificación estándar utilizada para representar datos |
| **ROT13** | Variante del cifrado César con desplazamiento fijo de 13 |
| **Atbash** | Sustitución donde A↔Z, B↔Y, C↔X |

Funciones principales:

- Encriptar texto
- Desencriptar texto
- Seleccionar método de cifrado
- Copiar resultado al portapapeles
- Interfaz minimalista y fácil de usar

---

# 🖥️ Interfaz

La aplicación incluye:

- Selector de método de cifrado
- Campo de llave para el cifrado César
- Área de entrada de texto
- Botones de **Encriptar** y **Desencriptar**
- Área de resultados con botón de copiar

---

# 📂 Estructura del proyecto

```
cipher-tool/
│
├── index.html
└── README.md
```

Todo el proyecto está contenido en **un solo archivo HTML**, incluyendo:

- HTML
- CSS
- JavaScript

Esto permite que la aplicación funcione **sin dependencias ni instalación**.

---

# 🚀 Cómo usar

1. Descargar o clonar el repositorio.

```
git clone https://github.com/usuario/cipher-tool.git
```

2. Abrir el archivo:

```
index.html
```

3. Escribir un mensaje.

4. Elegir un método de cifrado.

5. Presionar:

- **Encriptar**
- **Desencriptar**

---

# 📖 Ejemplo

Mensaje original:

```
ATAQUE AL NORTE
```

Cifrado César (shift = 3):

```
DWDTXH DO QRUWH
```

El receptor puede usar la misma herramienta para **descifrar el mensaje**.

---

# 🧠 Conceptos de seguridad demostrados

Esta aplicación permite demostrar:

- Cifrado simétrico
- Sustitución de caracteres
- Transformaciones criptográficas
- Seguridad en transmisión de mensajes

Aunque los métodos incluidos **no son seguros para uso real**, sirven para entender **los principios básicos de la criptografía**.

---

# 🛠️ Tecnologías utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (Vanilla)**

No se utilizaron frameworks ni librerías externas.

---

# 📜 Licencia

Proyecto educativo desarrollado para fines académicos.

Uso libre para aprendizaje y demostraciones.
