# Mensaje Interactivo 💌

Una web interactiva, moderna y mobile-first pensada para acompañar una carta personal, romper el hielo con humor y dar una respuesta sin presión.

---

## 🚀 ¿Cómo clonar y usar este proyecto para ti?

### 1. Clonar el repositorio
Si usas Git, ejecuta en tu terminal:
```bash
git clone https://github.com/DevMauricio03/mensaje.git
cd mensaje
```

*(O puedes darle al botón **Fork** arriba a la derecha en GitHub, o descargar el archivo **ZIP** directo desde el botón verde "Code").*

---

## 🛠️ ¿Qué debes modificar para personalizarlo?

Todo el contenido se encuentra en el archivo `index.html`. Solo necesitas cambiar estos puntos:

### 1. Tu número de WhatsApp
Busca en `index.html` el enlace de WhatsApp:
```html
<a href="https://wa.me/529518826439" ...>
```
Reemplaza `529518826439` por tu número con código de país (ejemplo México: `52` + tus 10 dígitos).

### 2. Tus imágenes y referencias
En la carpeta `img/` puedes reemplazar los archivos por tus propias fotos o memes:
* `img/duolingo.jpg`
* `img/yoshinegro.webp`
* `img/blackops.jpg`
* `img/donramon_clean.jpg`

### 3. Tus textos y anécdotas
En `index.html` puedes cambiar:
* Los textos de bienvenida (Paso 1).
* Las tarjetas con tus propios chistes / anécdotas (Paso 2).
* La propuesta o meme (Paso 3).
* Las frases del botón que esquiva (`noPhrases` en el `<script>`).
* El mensaje final y la disculpa sincera tras los 10 intentos.

---

## 🌐 ¿Cómo publicarlo en internet (Gratis)?

Para que la otra persona pueda abrirlo escaneando un código QR desde su celular:

1. Sube tu proyecto modificado a tu propia cuenta de GitHub (como repositorio **Público**).
2. En tu repositorio, ve a: **Settings** > **Pages** (en el menú izquierdo).
3. En **Branch**, selecciona `main` y la carpeta `/(root)`.
4. Haz clic en **Save**.
5. ¡Listo! En 1 minuto tendrás tu enlace activo:
   `https://TU_USUARIO.github.io/NOMBRE_DEL_REPO/`

---

## 📱 Generar el Código QR
Una vez tengas tu enlace activo, puedes generar la imagen del código QR con este comando en tu terminal (cambiando el link):
```bash
curl -s "https://api.qrserver.com/v1/create-qr-code/?size=600x600&margin=15&format=png&data=TU_ENLACE_AQUI" -o codigo_qr.png
```
O usando cualquier generador de QR en línea. ¡Imprímelo o pégalo al final de tu carta!
