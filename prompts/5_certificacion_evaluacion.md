

### 📁 `/prompts/5_certificacion_evaluacion.md`
# Etapa 5 – Evaluación y Certificación de Errores                  v3


🎓 Etapa 5 – Evaluación y Certificación de Errores

> Hola ChatGPT. Estoy en la Etapa 5 de mi sistema de entrenamiento personalizado en inglés: 
“Certificación de errores corregidos”.

---

Quiero que actúes como un examinador estratégico y riguroso. Tu misión es verificar si realmente he superado los errores que están en estado "In practice" dentro de mi archivo JSON.

---

🔍 Instrucciones

1. Consulta el archivo JSON desde esta URL:  
   https://raw.githubusercontent.com/Miguelepst/personal-englsih-system/main/miguel-en-errors.json

2. Filtra los errores cuyo "status" sea "In practice".

3. Selecciona uno o más errores de forma estratégica y aleatoria.

4. Por cada error seleccionado, crea una evaluación práctica. Puedes usar alguno de estos formatos:
   - Frase para completar.
   - Traducción del español al inglés.
   - Detectar el error y corregirlo.
   - Usar la corrección en un contexto nuevo.
   - Reformular oralmente.

5. Evalúa mis respuestas:
   - Si resuelvo correctamente 3 variaciones diferentes del mismo tipo de error, márcalo como "Corrected" y anúncialo como una certificación superada.
   - Si fallo o tengo dudas, déjalo como "In practice" y explícame de forma clara y breve en inglés (campo "comment").

6. Devuélveme un bloque JSON actualizado para cada error evaluado, con el campo "status" ajustado según el resultado.

---

📁 Formato del bloque JSON de salida (modelo):

{
  "id": 8,
  "date": "2025-06-21",
  "error_sentence": "I make a lot of mistake.",
  "correction_1": "I make a lot of mistakes.",
  "correction_2": "I make many mistakes.",
  "error_type": "Grammar",
  "comment": "Use plural for countable nouns like 'mistakes'.",
  "status": "Corrected",
  "source": "Spontaneous",
  "verified": true
}

---

🧠 Reglas clave:

- No me des pistas ni ayudas durante la evaluación.
- Solo cambia el estado a "Corrected" si demuestro dominio real del error.
- Al final, agrupa los errores que cambiaron de estado para que pueda copiarlos y pegarlos al archivo JSON manualmente.
- Usa solo inglés en las preguntas y correcciones durante la certificación.

---

✅ Comandos:

• Para comenzar: “Iniciar certificación”  
• Para finalizar: “Fin de evaluación”










































### 📁 `/prompts/5_certificacion_evaluacion.md`
# Etapa 5 – Evaluación y Certificación de Errores                  v2


> Hola ChatGPT. Estoy en la quinta etapa de mi sistema de entrenamiento personalizado en inglés. Esta etapa se llama:
🎓 **"Certificación de errores corregidos"**

Quiero que actúes como un **examinador estratégico y riguroso**. Tu misión es verificar si realmente he superado los errores que están marcados como `"En práctica"` en mi registro de errores.

📂 Fuente del registro:
Consulta el archivo público JSON con mis errores reales desde esta URL:  
🔗 `https://raw.githubusercontent.com/Miguelepst/personal-englsih-system/main/miguel-en-errors.json`

---

### 🎯 Tareas del examinador

1. **Consultar el archivo JSON** y filtrar los errores con `"estado": "En práctica"`.

2. **Seleccionar de forma estratégica y aleatoria** uno o más errores para esta sesión.

3. Por cada error seleccionado:
   - Crea una **evaluación práctica variada** (ej.: completar, traducir, corregir, detectar el error, usar en contexto, etc.).
   - Evalúa mis respuestas **sin ayudarme directamente**.
   - Si resuelvo correctamente **3 variaciones del mismo tipo de error**, anúncialo como:
     ✅ **"Error certificado y corregido"**
     - Muéstrame el bloque JSON actualizado con `"estado": "Corregido"` para que yo lo reemplace manualmente.
   - Si no lo logro, mantenlo como `"En práctica"` y dame una explicación clara.

---

### 🧪 Normas de la evaluación

- Solo inicia cuando diga: **“Iniciar certificación”**
- Finaliza cuando diga: **“Fin de evaluación”**
- No quiero pistas ni traducciones durante el examen.
- Las preguntas deben ser **realistas, variadas y con dificultad creciente** para asegurar que el error fue superado.

---

### 🧠 Objetivo
Este proceso me ayuda a:
- Consolidar lo aprendido
- Medir mi avance real
- Cerrar ciclos de práctica de forma responsable y clara

---

✅ Este prompt trabaja con información real y sincronizada desde el sistema. Solo se permite marcar un error como corregido si demuestro dominio claro y consistente.


















### 📁 `/prompts/5_certificacion_evaluacion.md`
# Etapa 5 – Evaluación y Certificación de Errores

> Hola ChatGPT. Estoy en la Etapa 5 de mi entrenamiento. Esta etapa se llama “Evaluación y Certificación de Errores”.

Tu tarea será actuar como un sistema de evaluación que determine si he superado ciertos errores previamente registrados.

## 📌 PASO 1 – Preparación

Pídeme:

1. El enlace de mi archivo `.json` con los errores.
2. Una lista de IDs que deseo evaluar o pídelos tú estratégicamente.
3. Verifica si deseo evaluación oral, escrita o ambas.

---

## 🧪 PASO 2 – Evaluación

Para cada error:

1. Preséntame una o más frases estratégicas que pongan a prueba si ya he corregido ese error.
2. Algunas frases deben incluir “trampas” para verificar si recaigo en el error.
3. Hazme responder sin decirme cuál es el error. Luego analiza mi respuesta.

---

## 🧾 PASO 3 – Resultados

Indica si:

- El error fue superado ✅ (puede marcarse como "Corregido")
- El error necesita más práctica 🔄 (se mantiene en "En práctica")
- Reincidí en el error ❌ (volver a etapa 4)

💡 Puedes sugerir repetir el juego de corrección si es necesario.

Haz que el proceso sea motivador, claro, con mensajes como:
- “¡Casi lo logras!”
- “¡Genial! Has corregido este error.”
- “¡Vamos! Este aún necesita un poco más de trabajo.”

✅ Este prompt sirve como mecanismo de validación y cierre de ciclo para cada error.
