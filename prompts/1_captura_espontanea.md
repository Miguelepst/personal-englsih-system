
### 📁 `/prompts/1_captura_espontanea.md`
# Etapa 1 – Captura Espontánea sin Corrección                      v3 ✅

                

🎙️ Etapa 1 – Captura espontánea sin corrección (con opción de guardar en JSON estructurado)

Hola ChatGPT. Estoy en la primera etapa de mi entrenamiento personalizado en inglés. Esta etapa se llama "Captura espontánea sin corrección".

🎯 Voy a hablar o escribir de forma espontánea en inglés. Tal vez mezcle palabras en español, me equivoque, o me bloquee, y está bien.

🛑 Tu única tarea es transcribir exactamente lo que diga, sin corregir, sin interpretar y sin mejorar.

Si hay pausas, repeticiones o algo en español, también debes escribirlo (puedes usar puntos suspensivos, o paréntesis para lo dicho en español).

Cuando termine, diré: "Fin de etapa 1" y ahí me muestras toda la transcripción.


---

🆕 Después de mostrarme la transcripción, pregúntame:

> “Do you want to save this to your original dialogue database?”



Si digo que sí:

1. Pide el link del archivo JSON (si no lo tienes).
👉 link recomendado:
https://raw.githubusercontent.com/Miguelepst/personal-englsih-system/main/miguel-en-dialogos-unreviewed.json


2. Verifica que el contenido no esté repetido en el campo "content".


3. Detecta el último "id" y genera el siguiente automáticamente.


4. Pregunta cuál es la fuente (source) del diálogo capturado. Ejemplos:

"Loora"

"PI"

"Duolingo"

"Reading Reflection"

"Spontaneous" (por defecto)



5. Pregunta si desea agregar una breve descripción (description), opcional.


6. Genera un nuevo objeto JSON con la siguiente estructura:



{
  "id": [autonumérico],
  "date": "[fecha actual]",
  "content": "[texto capturado]",
  "source": "[origen seleccionado]",
  "status": "Raw",
  "description": "[opcional: texto descriptivo]",
  "example_record": false
}

> 🔹 Asegúrate de que "example_record": false para todos los registros reales.



> 🔹 El campo "status" siempre será "Raw" en esta etapa, ya que todavía no se ha hecho análisis ni corrección.

















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
