# Paso 6: Tu póster con Gemini

**Duración:** 20 minutos · [← Paso 5](../05-que-ia/) · Paso 7 →

## Objetivo

Hacer **dos imágenes para tu escuela** con Gemini. Docentes: un cartel para su salón y una infografía de su tema. Secretarias: un aviso de la escuela y un diploma que puedan editar después.

## La idea

Claude no hace imágenes; **Gemini sí**. La receta es la misma, con tres cosas más:

1. **El texto que debe llevar la imagen, exacto y entre comillas.** Si no lo escribes así, lo inventa.
2. **Un estilo concreto y lo que no quieres.** Lo que más delata a una imagen de IA son los degradados, los brillos y el efecto 3D. Pide un estilo con nombre (serigrafía, lámina dibujada a mano, diploma de imprenta), pocos colores y di lo que no quieres.
3. **Una imagen no se edita como un documento.** El texto queda "pintado" en la imagen. Si algo lo vas a cambiar seguido (un diploma con distintos nombres), pide a Gemini **solo el fondo, sin texto**, y a Claude un **PowerPoint con cuadros de texto** encima.

## Qué hacemos

Lo hacemos **todos juntos**, en dos momentos. Cada perfil hace lo suyo.

| Min | Qué pasa |
| --- | --- |
| 0–2 | "Claude no hace imágenes. Gemini sí." |
| 2–4 | **En Gemini, paso a paso:** entra a gemini.google.com con tu Gmail → Crear imagen → adjunta y pide → si no te gustó, un ajuste → descarga |
| 4–10 | **1 de 2 · Un anuncio.** Docentes: un cartel para su salón. Secretarias: un aviso de la escuela, con el logo |
| 10–17 | **2 de 2 · Con tu información.** Docentes: una infografía de su tema. Secretarias: un diploma que puedan editar (el fondo en Gemini y el PowerPoint en Claude) |
| 17–20 | **Revísalo** y descarga |

Los directivos eligen la ruta que les sirva.

## El prompt

Llena lo que está entre corchetes y cambia lo de ejemplo por lo tuyo.

### 1 de 2 · Un anuncio

**Docentes: un cartel para tu salón.**

```
Haz un cartel vertical, tamaño carta, para pegar en mi salón de 1° A. El texto debe decir exactamente: "Acuerdos del grupo", "1. Llegamos a tiempo", "2. Levantamos la mano para hablar", "3. Cuidamos el material", "4. Nos respetamos".
Estilo: cartel dibujado a mano con plumones sobre cartulina, letras de molde grandes y solo tres colores (azul, rojo y negro). Sin degradados, sin brillos, sin efecto 3D y sin personas.
```

**Secretarias: un aviso de la escuela.** Adjunta el **logo de la escuela**.

```
Haz un póster vertical, tamaño carta, para la posada de la Escuela Telesecundaria "Santa Teresa". Te adjunto el logo: ponlo arriba y no lo cambies. El texto debe decir exactamente: "Posada navideña 2026", "Viernes 18 de diciembre, 4:00 p. m.", "Patio de la escuela".
Estilo: cartel de serigrafía mexicana a tres tintas (rojo, verde y crema), con papel picado y faroles en formas planas, textura de papel, como impreso a mano. Sin degradados, sin brillos, sin efecto 3D y sin personas.
```

### 2 de 2 · Con tu información

**Docentes: una infografía de tu tema.** Adjunta **tu tema en `.md`** (el del reto).

```
Te adjunto el tema "Sistemas nervioso y endocrino" de nuestro libro. Hazme una infografía vertical, tamaño carta, para pegar en el salón de 1°, que explique qué hace cada sistema y en qué se parecen.
Usa solo la información del documento. Textos cortos y letra grande.
Estilo: lámina escolar dibujada a mano, con dibujos de línea en tinta y acuarela suave, sobre fondo de papel crema. Títulos como escritos con plumón. Sin degradados, sin brillos, sin efecto 3D y sin fotos.
```

**Secretarias: un diploma que puedas editar.**

*1. En Gemini, el fondo.* Adjunta el **logo de la escuela**.

```
Haz el fondo de un reconocimiento horizontal, tamaño carta. Te adjunto el logo: ponlo arriba al centro y no lo cambies. No escribas ningún texto; deja el centro en blanco. Estilo: diploma clásico de imprenta, fondo blanco, marco de línea fina doble en azul marino. Sin dibujos, sin dorados brillantes y sin degradados.
```

Descarga la imagen.

*2. En Claude, el PowerPoint.* Adjunta **el fondo que te dio Gemini**.

```
Te adjunto el fondo de un reconocimiento. Hazme un PowerPoint de una diapositiva, tamaño carta horizontal, con esta imagen de fondo y cuadros de texto editables encima: "Escuela Telesecundaria 'Santa Teresa'", "Reconocimiento", "a: [nombre del alumno]", "por haber concluido el 1° grado en el ciclo escolar 2026-2027", "Huajuapan de León, Oaxaca, a 9 de julio de 2027" y dos firmas: "Director(a)" y "Docente". Letra con remates, en negro y azul marino.
```

Deja `[nombre del alumno]` así: el nombre lo escribes tú en PowerPoint. Después solo cambias el texto y lo imprimes; el diseño no se mueve.

### Si no te gustó

```
Cambia solo [lo que quieres cambiar]. No cambies nada más.
```

## Cómo debe verse

- **Cartel y aviso:** pocos colores, formas planas, letras grandes y el texto exactamente como lo escribiste.
- **Infografía:** como una lámina dibujada a mano, con la información de tu tema y nada más.
- **Diploma:** un PowerPoint en el que puedes hacer clic en cada texto y cambiarlo.
- La versión gratuita de Gemini descarga en **1K**: alcanza para WhatsApp o una hoja carta, no para una lona.

## Antes de imprimir: revísalo

1. **El texto:** letra por letra. Acentos y palabras inventadas.
2. **Los datos:** ¿la fecha cae en ese día? ¿La infografía dice lo que dice tu libro?
3. **El logo:** compáralo con el original. ¿Lo cambió?
4. **Las personas:** nada de fotos ni nombres de alumnos.

## Si te atoraste

- **No encuentro "Crear imagen":** está en las herramientas, junto a la caja del chat.
- **Me cambió el logo:** pide "deja un espacio en blanco arriba", descarga la imagen y pega el logo real en Word o PowerPoint.
- **No acepta mi `.md`:** adjunta el mismo tema en PDF o Word.
- **Le escribió texto al fondo del diploma:** pide "Quita todo el texto. No cambies nada más."
- **Ya no tengo mensajes de Claude:** abre PowerPoint, ve a Diseño > Formato del fondo > Relleno con imagen, elige el fondo de Gemini y escribe los textos en cuadros de texto.
- **Se acabó el límite de Gemini:** termina en casa con este manual. El límite se recarga.

---

<details>
<summary><strong>Notas para quien imparte</strong></summary>

- **Dos proyectores:** en uno las diapositivas y en el otro tú haciéndolo en vivo, al mismo tiempo que ellos.
- **Dos momentos, un perfil de cada lado** (docentes a la izquierda, secretarias a la derecha), como en el reto. Si no da tiempo, se omite el 2 de 2.
- **El estilo evita el "se ve IA":** pocas tintas, formas planas, textura y una lista de lo que NO queremos (degradados, brillos, 3D).
- **El diploma editable** nace de una queja real: una secretaria batalla para diseñar diplomas. Gemini hace el diseño sin texto y Claude lo vuelve editable; así no hay que generar otra imagen para cada diploma.
- **Muchos diplomas con nombres distintos:** "Combinar correspondencia" de Word con una lista de Excel. No usa IA y los nombres no salen de la escuela.
- **Fechas:** el 18 dic 2026 cae en viernes y es el último día de clases antes de vacaciones; el 9 jul 2027 es el fin del ciclo 2026-2027 (calendario SEP publicado en el DOF). La hora y el lugar de la posada son de ejemplo. Confirma con la dirección si en Oaxaca aplica otro calendario.
- **Datos de la escuela:** del formato de examen de Santa Teresa (Escuela Telesecundaria "Santa Teresa", Huajuapan de León, Oaxaca). La clave del centro de trabajo y la zona no se pusieron porque el formato las trae en blanco.
- **Datos verificados el 21 nov 2026** ([ayuda de Gemini](https://support.google.com/gemini/answer/14286560), [subir archivos](https://support.google.com/gemini/answer/14903178)): se entra con sesión iniciada; Crear imagen usa Nano Banana 2; se pueden subir imágenes para editarlas; hasta 10 archivos por mensaje; la versión gratuita descarga en 1K. Google no publica cuántas imágenes al día da la versión gratuita.
- **Marca de agua:** las imágenes llevan la marca de Gemini en una esquina. Se deja: dice que la hizo una IA. Si preguntan, se quita en Configuración > Marca de agua, pero la marca invisible (SynthID) sigue.
- **Por probar antes del taller:** que Gemini respete el logo; que acepte el `.md` en Crear imagen; que respete "no escribas ningún texto"; que Claude gratuito ponga la imagen como fondo del PowerPoint; que los estilos se vean como se describen; y si las imágenes caben en el límite gratuito. Guarda tus resultados como plan B.
- **Voluntarios para el paso 7:** ubica a un docente con su infografía y una secretaria con su diploma, si se puede.
- **Directivos:** eligen la ruta que les sirva.

</details>
