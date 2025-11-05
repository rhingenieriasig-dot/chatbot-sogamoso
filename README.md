# Chatbot del Municipio de Sogamoso

Este proyecto contiene un **prototipo web del chatbot** conectado con **Dialogflow ES (Google Cloud)**.

---

## 🚀 Cómo usar este proyecto

### 1️⃣ Reemplaza el enlace del iframe
Abre el archivo `chatbot.html` y busca la línea:

```html
<iframe src="https://console.dialogflow.com/api-client/demo/embedded/tu-agente-id" allow="microphone;"></iframe>
```

Sustituye `"tu-agente-id"` por el enlace generado desde **Dialogflow → Integrations → Web Demo → Enable**.

---

## 🌐 OPCIÓN 1: Publicar con GitHub Pages

1. Crea una cuenta gratuita en [https://github.com](https://github.com)
2. Crea un repositorio público (por ejemplo: `chatbot-sogamoso`)
3. Sube el archivo `chatbot.html`
4. Entra a **Settings → Pages**
5. En “Source” elige `main / (root)`
6. Guarda los cambios

GitHub generará una URL pública como:

```
https://tuusuario.github.io/chatbot-sogamoso/
```

---

## ☁️ OPCIÓN 2: Publicar en Google Cloud Storage (GCS)

1. Entra a [https://console.cloud.google.com/storage](https://console.cloud.google.com/storage)
2. Crea un **bucket público**
3. Sube `chatbot.html`
4. Asigna permiso de lectura a `allUsers`
5. Usa la URL pública generada (por ejemplo):
```
https://storage.googleapis.com/chatbot-sogamoso-demo/chatbot.html
```

---

## 🧠 Créditos

- Asistente Virtual del Municipio de Sogamoso
- Desarrollado con **Dialogflow ES + Google Cloud**
- Interfaz HTML con botón flotante 💬

