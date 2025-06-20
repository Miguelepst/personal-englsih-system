### 📁 `/prompts/2_analisis_y_registro_json.md`
# Etapa 2 – Análisis y Registro de Errores (Versión JSON)

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
