### 📁 `/prompts/2_analisis_y_registro_json.md`
# Etapa 2 – Análisis y Registro de Errores (Versión JSON)         v4


---
📘 Etapa 2 — Análisis y Registro de Errores (Versión Final con soporte para JSON)

Hola, ChatGPT. Estoy en la Etapa 2 de mi sistema de entrenamiento personalizado en inglés. Esta etapa se llama “Análisis y Registro de Errores”.

Voy a proporcionarte uno de los siguientes tipos de contenido:

- Un texto espontáneo escrito o hablado en inglés.
- Una transcripción de una grabación mía.
- Una descripción escrita de algo que dije.
- O cualquier contenido generado por mí en inglés.

---

🎯 Tu tarea es:

1. Detectar todos los errores posibles en mi comunicación:
   - Gramática
   - Vocabulario
   - Fluidez
   - Entonación (si es deducible)
   - Pronunciación (si aplica)

2. Si detectas una frase en español, trátala como un error y:
   - Márcala como error.
   - Proporcióname **dos formas correctas** de decirlo en inglés.
   - Agrega una explicación breve en inglés simple.

3. Por cada error detectado, genera un bloque JSON (en inglés), con este formato:

{
  "id": [número consecutivo basado en el último ID del archivo JSON],
  "date": "[fecha actual en formato YYYY-MM-DD]",
  "error_sentence": "[frase con error tal como fue dicha]",
  "correction_1": "[primera corrección posible]",
  "correction_2": "[segunda corrección posible]",
  "error_type": "[Grammar, Vocabulary, Pronunciation, Fluency, Tone]",
  "comment": "[explicación breve en inglés simple]",
  "status": "New",
  "source": "[Spontaneous | Transcription | Written]",
  "verified": true
}

---

📂 Antes de comenzar:
Por favor, pídeme el enlace al archivo JSON que contiene mis errores registrados (por ejemplo, desde GitHub). Este archivo debe estar en formato accesible como:
https://raw.githubusercontent.com/Miguelepst/personal-englsih-system/main/miguel-en-errors.json

Tu tarea es:
- Consultar ese archivo para identificar el **último ID existente**.
- Evitar duplicados revisando si la frase con error ya existe.
- Generar nuevos bloques a partir del siguiente ID consecutivo.

---

🧩 Reglas importantes:
- No corrijas el texto completo, solo identifica los errores y crea los bloques de entrada.
- Todos los campos del JSON deben estar en inglés, incluso los comentarios y explicaciones.
- Usa inglés claro y simple en el campo `comment`.
- Mantén el formato limpio para poder copiar y pegar directamente en el archivo `miguel-en-errors.json`.
- Si algún error ya existe en el archivo, indícalo en el campo `comment` como `"duplicate"` o `"already exists"`.

---

Cuando esté listo, dime:  
**"Aquí está el contenido para analizar"** y luego te proporcionaré el texto.

Gracias.






















### 📁 `/prompts/2_analisis_y_registro_json.md`
# Etapa 2 – Análisis y Registro de Errores (Versión JSON)               v2

> Hola ChatGPT. Estoy en la Etapa 2 de mi sistema de entrenamiento personalizado en inglés. Esta etapa se llama “Análisis y Registro de Errores”.

## 📌 PASO 1 – Solicita información

Antes de analizar, por favor pregúntame:

1. El enlace del archivo `.json` donde estoy guardando los errores.
2. La fecha del contenido que te voy a entregar.
3. El estado por defecto que tendrán los errores nuevos: `"Nuevo"`, `"En práctica"`, o `"Corregido"`.

---

## 🔍 PASO 2 – Analiza y clasifica

Ahora analiza el contenido que te entregaré (puede ser texto o transcripción de audio/video). Tu tarea es:

1. Detectar errores de gramática, pronunciación, vocabulario, fluidez o entonación (cuando se pueda).
2. Si hay frases en español, considéralas errores. Muéstrame:
   - La frase en español,
   - Al menos una forma correcta de decirlo en inglés,
   - Una breve explicación.

3. Por cada error, genera un bloque `.json` con esta estructura:

```json
{
  "id": [Número sugerido automáticamente],
  "fecha": "[fecha]",
  "frase_con_error": "...",
  "correccion": "...",
  "tipo": "...",
  "comentario": "...",
  "estado": "[Nuevo / En práctica / Corregido]"
}























### 📁 `/prompts/2_analisis_y_registro_json.md`
# Etapa 2 – Análisis y Registro de Errores (Versión JSON)               v1



Etapa 2 (Versión Básica – Formato tabla)

Prompt: Análisis y Registro de Errores (Etapa 2 – Versión final)

> Hola ChatGPT. Estoy en la segunda etapa de mi sistema de entrenamiento personalizado en inglés. Esta etapa se llama "Análisis y Registro de Errores".

A continuación, te voy a proporcionar un contenido generado por mí. Puede ser uno de estos formatos:

Un texto escrito espontáneamente.

La transcripción de una grabación mía.

Un archivo de audio o video (o el contenido transcrito de ese archivo).


Tu tarea es:

1. Identificar todos los errores posibles en mi comunicación: errores de pronunciación, gramática, vocabulario, fluidez, o entonación (cuando se pueda deducir).


2. Si encuentras una frase en español, considérala un error (ya que estoy tratando de comunicarme en inglés), y:



Indícala como error.

Dame al menos una forma correcta de decir eso mismo en inglés.

Agrega una breve explicación.


3. Clasifica todos los errores por tipo y preséntalos en una tabla clara con los siguientes campos:



Número

Fecha

Frase con error (tal como fue dicha)

Corrección sugerida

Tipo de error

Comentario o ejemplo correcto

Estado: ("Nuevo", "En práctica", o "Corregido")


No corrijas el texto completo, solo quiero la tabla de errores detectados.
Por favor, mantén el orden y claridad de los datos, ya que los usaré para mi base de datos personal.



