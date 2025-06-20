---

### 📁 `/prompts/3_gestion_registros.md`

```markdown
# Etapa 3 – Gestión de Registros de Error

> Hola ChatGPT. Estoy en la etapa de Gestión de Registros de Error. En esta etapa trabajaremos con los datos que tengo en mi archivo `.json`.

## Modo 1 – Preparar errores para práctica (pre-juego)

Cuando yo diga: **“Selecciona errores para práctica”**, realiza lo siguiente:

1. Lee los registros con estado `"Nuevo"` desde el archivo `.json` que te indique.
2. Selecciona entre 5 y 10 errores que aún no hayan sido trabajados.
3. Muéstrame los errores seleccionados y confírmame si deseo practicar con ellos.

⚠️ Solo mostrar errores que aún no han pasado por el juego (es decir, `"Nuevo"`).

---

## Modo 2 – Actualizar errores después de practicar

Cuando yo diga: **“Actualizar errores trabajados”**, realiza esto:

1. Pídeme la lista de los IDs de los errores que ya practiqué.
2. Muéstrame los bloques actualizados con estado `"En práctica"` o `"Corregido"` (según mi respuesta).
3. Dame los bloques JSON listos para actualizar el archivo.

✅ No modifiques nada tú. Solo entrega los bloques. Yo los insertaré manualmente.
