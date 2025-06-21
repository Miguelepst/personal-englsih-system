### 📁 `/prompts/1_captura_espontanea.md`
# Etapa 1 – Captura Espontánea sin Corrección                      v2

🎙️ Etapa 1 – Captura espontánea sin corrección (con opción de guardar en JSON original)

Hola ChatGPT. Estoy en la primera etapa de mi entrenamiento personalizado en inglés. Esta etapa se llama **"Captura espontánea sin corrección"**.

🎯 Voy a hablar o escribir de forma espontánea en inglés. Tal vez mezcle palabras en español, me equivoque, o me bloquee, y está bien.

🛑 **Tu única tarea es transcribir exactamente lo que diga**, sin corregir, sin interpretar y sin mejorar.

Si hay pausas, repeticiones o algo en español, también debes escribirlo (puedes usar puntos suspensivos, o paréntesis para lo dicho en español).

Cuando termine, diré: **"Fin de etapa 1"** y ahí me muestras toda la transcripción.

---

🆕 Después de mostrarme la transcripción, pregúntame:

> “Do you want to save this to your original error database?”

Si digo que **sí**:

1. Pide el link del archivo JSON (si no lo tienes).
   link: https://raw.githubusercontent.com/Miguelepst/personal-englsih-system/main/miguel-en-dialogos-unreviewed.json
2. Verifica que el `error_sentence` no esté repetido.
3. Detecta el último `id` y genera el siguiente.
4. Muestra el bloque JSON con este formato:

```json
[
{
  "id": [autonumérico],
  "date": "[fecha actual]",
  "error_sentence": "[texto capturado]",
  "source": "Spontaneous",
  "status": "Raw"
}
]
```




📌 Descripción breve sugerida (miguel-en-dialogos-unreviewed.json):
link: https://raw.githubusercontent.com/Miguelepst/personal-englsih-system/main/miguel-en-dialogos-unreviewed.json

> "Archivo de registro que contiene las producciones originales en inglés de Miguel Gutiérrez (escritas o habladas), capturadas sin corrección ni análisis. Es utilizado como fuente base para detectar errores reales en etapas posteriores del entrenamiento personalizado."


### 📁 `/prompts/1_captura_espontanea.md`
# Etapa 1 – Captura Espontánea sin Corrección                       v1

> Hola ChatGPT. Estoy en la primera etapa de mi entrenamiento personalizado en inglés. Esta etapa se llama "Captura espontánea sin corrección".

A continuación, voy a hablar de forma espontánea en inglés. Tal vez mezcle palabras en español, me equivoque o me bloquee, y está bien.

Tu única tarea en esta etapa es transcribir exactamente lo que diga, tal como lo diga, sin corregir, sin interpretar, sin mejorar.

🔸 Si hay pausas, errores, dudas o partes en español, también deben registrarse (puedes usar puntos suspensivos, paréntesis, etc.).

⚠️ No hagas correcciones todavía. Solo quiero conservar el registro real de lo que dije.

Cuando yo diga: **“Fin de etapa 1”**, muéstrame la transcripción exacta de todo lo que dije.
