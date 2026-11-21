# Paso 3: Los archivos

**Duración:** 18 minutos · [← Paso 2](../02-kahoot/) · Paso 4 →

## Objetivo

Saber **qué es cada tipo de archivo y cuándo pedirlo**: Word, PDF, PowerPoint, Excel y uno que casi nadie conoce, **Markdown**.

## La idea

En el gancho viste el mismo trabajo en varias formas: la lista en Word, la clase en PowerPoint, la misma clase en PDF para el iPad, el examen en Word, las calificaciones en Excel y el libro en un archivo `.md`. **El formato lo decides tú**, y se elige con una pregunta:

| Formato | Pídelo cuando… | En el gancho |
| --- | --- | --- |
| **Word** (`.docx`) | lo vas a **cambiar** antes de usarlo | La lista de ejercicios y el examen |
| **PDF** (`.pdf`) | quieres que **nadie lo cambie** y que se vea igual en todos lados | La presentación para el iPad |
| **PowerPoint** (`.pptx`) | lo vas a **proyectar** | Los 3 ejercicios resueltos |
| **Excel** (`.xlsx`) | tiene **números que hay que calcular** | Las calificaciones |
| **Markdown** (`.md`) | se lo vas a **dar a la IA para que lo lea** | El libro |

Y una regla: **si no le dices el formato, te lo da en el chat.**

### Markdown, el que no conocías

**¿Qué es?** Una forma de escribir texto con formato usando solo el teclado: unos símbolos dicen qué es título, qué va en negritas y qué es lista.

| Escribes | Se ve |
| --- | --- |
| `# Sistemas de ecuaciones` | un título |
| `**incógnita**` | **incógnita** |
| `- Método de reducción` | • Método de reducción |

- Los archivos terminan en **`.md`**.
- Se abren con **cualquier programa**, hasta el Bloc de notas.
- Así escriben **Claude y ChatGPT** sus respuestas, y así está escrito **este manual**. Si alguna vez copiaste del chat a Word y te salieron `**` o `#`, eso era Markdown.

**¿Por qué dárselo a la IA en `.md`?**

| | PDF | Word | `.md` |
| --- | --- | --- | --- |
| **Se hizo para** | Verse igual e imprimirse | Editar e imprimir | Leerse como texto |
| **Qué guarda** | Cómo se ve cada página | El texto + letra, márgenes y diseño | Solo el texto y sus títulos |

De un tema en PDF, la IA recibe el texto **y además una imagen de cada página**. En `.md` recibe solo el texto: gasta varias veces menos de tu límite gratuito, y te queda más para trabajar. Además, el libro del taller trae marcado el número de página (`<!-- p. 33 -->`), así que la IA puede decirte de qué página sacó algo.

**No tienes que escribirlo:** los libros ya te los dimos en `.md`, y cualquier otro documento se lo puedes pedir a Claude ("pásame este documento a Markdown").

**Su límite:** no tiene imágenes. En los libros del taller, los exponentes quedaron "aplanados" (`ax2` quiere decir a·x²). Si tu tema depende de una figura o una gráfica, súbela aparte.

## Qué hacemos

| Min | Qué pasa |
| --- | --- |
| 0–1 | **Puente:** "Ya los vieron funcionar. Ahora: ¿qué es cada uno y cuándo lo pido?" |
| 1–6 | **Los cuatro conocidos:** Word, PDF, PowerPoint y Excel, con las respuestas de las preguntas 14 a 17 del Kahoot |
| 6–15 | **Markdown:** qué es, por qué dárselo a la IA en `.md` en lugar de PDF o Word, y cómo conseguir uno |
| 15–18 | **¿Qué le pido?** Los cinco en una tabla y la regla del formato |

## El prompt

En este paso no hay prompt: es explicación. Para practicar en casa:

```
Te adjunto un documento. Pásamelo a Markdown, con el mismo texto y el mismo orden, y dámelo en un archivo .md.
```

## Cómo debe verse

- Un archivo `.md` abierto con el Bloc de notas se ve como **texto con algunos `#` y `**`**. Abierto en Claude o en un programa que lo entienda, se ve con títulos y negritas.
- El libro de 2° en `.md` empieza con unas instrucciones para la IA y luego el texto del tema, con marcas como `<!-- p. 33 -->` donde empieza cada página.

## Si te atoraste

En este paso no hay nada que hacer en tu equipo: solo escucha y pregunta.

---

<details>
<summary><strong>Notas para quien imparte</strong></summary>

- **Este paso es teórico.** La práctica con los archivos (las secretarias pasan su PDF a Word; los docentes abren los archivos del gancho) va en el paso 4.
- **Las respuestas del Kahoot van aquí.** Durante el Kahoot anota cómo les fue en la 14 (Word), 15 (PDF), 16 (PowerPoint) y 17 (pasar un PDF a Word). Dedica más tiempo a las que acertó menos de la mitad del grupo; si las acertaron todas, pasa rápido y dale esos minutos a Markdown.
- **La 17 es el puente a la práctica:** un oficio en PDF que usas cada mes se pasa a Word **una vez** y luego lo cambias tú. Dilo así: "es lo que van a hacer las secretarias en el reto".
- **PDF a Word con IA:** la IA no convierte el archivo, **lo vuelve a escribir**. Logos, firmas y sellos no pasan, y el texto hay que revisarlo.
- **Markdown es el centro del paso:** casi nadie lo conoce. No se trata de que lo escriban, sino de que entiendan por qué el libro va así y que no se asusten al ver `#` y `**`.
- **"Varias veces menos" y no una cifra:** la comparación de tokens es una estimación, no una medición (un tema de 5 páginas: unos 1,500 tokens en `.md` contra 10,000 a 12,000 en PDF). En la presentación se dice "varias veces menos".
- **De Word no se compara cuánto gasta:** no hay una fuente que lo mida; la tabla solo dice qué guarda cada formato.
- **Si preguntan por los PDF largos:** según la ayuda de Claude (consultada el 20 nov 2026), en PDF de hasta 100 páginas analiza texto e imágenes; en PDF de 101 a 1000 páginas, solo el texto. Por eso en la diapositiva se habla de "un tema".
- **Conecta con la sesión 1:** "todo cuesta" (los tokens). El `.md` es la forma de que el libro completo quepa en la cuenta gratuita.
- **Si preguntan por qué no viene con dibujos:** los libros salieron del formato accesible de la SEP, que es solo texto. Por eso tampoco tienen imágenes.

</details>
