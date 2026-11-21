# Prompts del reto

[← Volver al paso 4](README.md)

En cada chat: **1. pídelo en el chat, 2. ajústalo si hace falta y 3. al final pide el archivo**. Así Claude arma el archivo una sola vez y cuidas tus tokens.

Cada paso trae la **plantilla** (llena lo que está entre corchetes y borra los corchetes) y un **ejemplo** lleno. Son una propuesta: cambia el tema, el documento o el formato. Lo importante es darle contexto y sacar un documento.

> **Un chat nuevo no tiene tus documentos.** Adjunta los archivos **en el mismo mensaje** donde dices "te adjunto".

---

## Chat 1 · Hoy: algo nuevo

### Docentes: material para enseñar

**Paso 1 · Pídelo.** Adjunta tu tema en `.md`.

```
Eres profesor de [materia] de secundaria en México.
Contexto: doy [materia] a [grado] de telesecundaria. Te adjunto el tema "[tema]" de nuestro libro.
Tarea: quiero material para enseñar este tema en clase. Muéstramelo aquí en el chat.
Antes de empezar, hazme en un solo mensaje todas las preguntas que necesites. No hagas nada hasta que te responda.
```

*Ejemplo:* "Eres profesor de **ciencias** de secundaria en México. Contexto: doy **Saberes y pensamiento científico** a **1°** de telesecundaria. Te adjunto el tema "**Sistemas nervioso y endocrino**" de nuestro libro…"

Después, **responde sus preguntas** en un solo mensaje, con el mismo número que usó.

**Paso 2 · Ajústalo, si hace falta.**

```
[Lo que quieres cambiar].
```

*Ejemplo:* "Haz más cortas las preguntas para la libreta."

**Paso 3 · Pide el archivo.**

```
Ahora sí, dámelo en Word listo para imprimir.
```

Descarga el Word: lo usas en el chat 2.

### Secretarias: un documento nuevo

**Paso 1 · Pídelo.**

```
Eres secretaria de una escuela secundaria en México y redactas documentos oficiales.
Contexto: trabajo en la telesecundaria [nombre de tu escuela].
Tarea: quiero hacer [un oficio / una circular / un aviso] para [a quién] sobre [qué]. Muéstramelo aquí en el chat.
Antes de empezar, hazme en un solo mensaje todas las preguntas que necesites. No hagas nada hasta que te responda.
```

*Ejemplo:* "…Quiero hacer **un oficio** para **la Supervisión Escolar** sobre **la posada de la escuela**…"

Después, **responde sus preguntas** en un solo mensaje.

**Paso 2 · Ajústalo, si hace falta.**

*Ejemplo:* "Hazlo más corto: que quepa en media hoja."

**Paso 3 · Pide el archivo.** Adjunta tu formato **en este mismo mensaje**.

```
Te adjunto el formato de la escuela. Dámelo en Word, en ese formato y listo para imprimir.
```

---

## Chat 2 · Lo que ya tienes (chat nuevo)

### Docentes: el examen de lo que ya vimos

**Paso 1 · Pídelo.** Adjunta tu Word del chat 1 y un documento de tus clases (tus ejercicios, una lista, un examen viejo).

```
Eres profesor de [materia] de secundaria en México.
Contexto: doy [materia] a [grado] de telesecundaria. Te adjunto material de los temas que hemos visto.
Tarea: hazme un examen con ejercicios parecidos a los de mi material, de [número] reactivos, con su clave de respuestas.
Formato: muéstramelo aquí en el chat.
```

*Ejemplo:* "…de **15** reactivos, con su clave de respuestas."

**Paso 2 · Ajústalo, si hace falta.**

*Ejemplo:* "Los reactivos 3 y 7 están muy fáciles: cámbialos."

**Paso 3 · Pide el archivo.** Si tienes formato de examen, adjúntalo en este mismo mensaje; si no, quita la última frase.

```
Dámelo en Word listo para imprimir, con la clave en hoja aparte. Te adjunto el formato de examen que uso: ponlo ahí.
```

### Secretarias: de PDF a Word

**Paso 1 · Pídelo.** Adjunta tu PDF.

```
Te adjunto un documento que uso seguido, en PDF. Pásalo a un documento de Word con el mismo texto y el mismo orden, listo para editarlo. No cambies ni agregues nada. Si hay algo que no puedes leer, márcalo con [REVISAR].
```

*Ejemplo:* el oficio de comisión que haces cada mes.

**Paso 2 · Cámbialo tú.** Abre el Word y cambia tú la fecha y el destinatario, sin gastar otro mensaje.

---

## Chat 3 · Lo que viene (chat nuevo)

### Docentes: planear el siguiente trimestre

Tú eliges la materia y los temas. La dosificación de la SEP es opcional.

**Paso 1 · Pídelo.**

```
Eres profesor de [materia] de secundaria en México.
Contexto: doy [materia] a [grado] de telesecundaria. El siguiente trimestre vamos a ver estos temas: [tus temas]. (O: te adjunto la dosificación de la SEP.)
Tarea: ayúdame a planear mis clases: cómo dividir los temas por semana y cuántas clases darle a cada uno. Tengo [número] horas a la semana.
Formato: una tabla aquí en el chat.
```

*Ejemplo:* "…Doy **Saberes y pensamiento científico** a **1°**… Tengo **5** horas a la semana."

**Paso 2 · Ajústalo, si hace falta.**

*Ejemplo:* "Junta los dos temas de fracciones y decimales."

**Paso 3 · Pide el archivo.** Elige el que te sirva:

```
Dámelo en Excel.
```

O en Word para imprimirlo, o en `.md` para dárselo a la IA en otro chat como contexto.

### Secretarias: de una lista de Word a Excel

**Paso 1 · Pídelo.** Adjunta tu lista.

```
Te adjunto una lista que tengo en Word. Pásala a un Excel con una columna por cada dato y una fila por cada registro, con los encabezados en la primera fila. No cambies ni agregues nada. Si un dato no está claro, márcalo con [REVISAR].
```

*Ejemplo:* la lista del inventario del aula de medios.

**Paso 2 · Revísalo tú.** Busca los `[REVISAR]` y corrígelos en Excel, sin gastar otro mensaje.

> **"[REVISAR]"** sirve para que la IA no invente donde no puede leer bien: al revisar, sabes dónde fijarte.
