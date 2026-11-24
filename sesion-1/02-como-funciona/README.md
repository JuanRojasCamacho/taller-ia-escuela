# Paso 2: Cómo funciona

**Duración:** 15 minutos · [← Paso 1](../01-gancho/) · [Paso 3 →](../03-pedir-bien/)

## Objetivo

Entender **cómo escribe la IA**: predice la palabra siguiente, lee en pedazos (tokens) y de ahí salen tres reglas para usarla bien.

## La idea

La IA no busca la respuesta en un libro: **escribe la palabra más probable, una tras otra**, según todo lo que leyó. Casi siempre lo probable coincide con lo verdadero, y por eso parece que "sabe". Pero **probable no es verdadero**: cuando no sabe algo, igual escribe lo que suena bien.

Eso tiene nombre: es un **modelo de lenguaje** (en inglés, *LLM*). La IA es un campo grande (el GPS que calcula tu ruta, el celular que reconoce tu cara); la que usamos en este taller es un modelo de lenguaje: leyó muchísimo texto y aprendió qué palabra suele seguir a otra. No busca en un libro, no conoce tu escuela y no sabe cuándo no sabe. Claude, ChatGPT y Gemini son modelos de lenguaje; por eso, en lo básico, hacen lo mismo.

Además, la IA no lee letras ni palabras completas: lee **tokens**, pedazos de palabras. Todo lo que escribes y todo lo que te responde se cuenta en tokens.

De ahí salen tres reglas:

| Cómo funciona | Qué significa para ti |
| --- | --- |
| Predice, no sabe | **Revisa** siempre lo que te da |
| Todo se cuenta en tokens | **Piensa antes de enviar:** la versión gratuita tiene un límite |
| En cada mensaje vuelve a leer toda la conversación | **Mismo tema, mismo chat; tema nuevo, chat nuevo** |

## Qué hacemos

| Min | Qué pasa |
| --- | --- |
| 0–1 | Formamos equipos por mesa y cada uno recibe su hoja |
| 1–5 | **Escribe como una IA:** a partir de *"El agua hierve a…"*, cada quien agrega una palabra. La hoja da tres vueltas |
| 5–7 | Cada equipo lee su frase. Comparamos, le ponemos nombre (**modelo de lenguaje**) y viene **el giro**: ¿a cuántos grados hierve el agua aquí, en Huajuapan? |
| 7–10 | **Por dentro:** una animación muestra qué pasa con tu mensaje: se corta en tokens, viaja a un servidor, la IA predice palabra por palabra y la respuesta regresa |
| 10–15 | **Tres reglas** que salen de todo esto |

### Las reglas del juego

1. Escribe **una sola palabra** y pasa la hoja.
2. Lee **todo lo que ya está escrito**, sin hablar.
3. La hoja da **tres vueltas** al equipo.

La hoja para imprimir está en [hoja-juego.pdf](hoja-juego.pdf) (tamaño carta horizontal, una por equipo).

## El prompt

En este paso no hay prompt: solo observa y participa en voz alta.

**Para practicar en casa:** abre el [tokenizador de OpenAI](https://platform.openai.com/tokenizer) y pega el [texto del taller](texto-tokenizador.md), o escribe tu nombre, el de tu escuela y una frase en español y en inglés. Fíjate en cuántos pedazos salen. Es la herramienta de otra IA (la de ChatGPT); Claude corta distinto, pero la idea es la misma.

## Cómo debe verse

- **Al principio todos coinciden:** casi todos los equipos escriben "cien grados", porque es lo más probable.
- **Después cada equipo se va por su lado:** con el mismo inicio salen frases distintas. La IA hace lo mismo: no responde igual dos veces.
- **En la animación** las palabras comunes son un solo pedazo y las raras se parten en varios; con cada mensaje viaja toda la conversación.

La animación está en [como-funciona-la-ia.html](como-funciona-la-ia.html): descárgala y ábrela con doble clic. También es un archivo HTML hecho con Claude, igual que el que harás en el paso 6.

## Si te atoraste

En este paso no hay nada que hacer en tu equipo. Si te quedaste atrás en los pasos anteriores, aprovecha para dejar tu sesión de Claude abierta.

---

<details>
<summary><strong>Notas para quien imparte</strong></summary>

- **Imprime una hoja por equipo** ([hoja-juego.pdf](hoja-juego.pdf)) y lleva unas de sobra. Equipos por mesa, del tamaño que salga; la hoja trae 20 líneas, una por palabra, y alcanza para tres vueltas en equipos de hasta 6. Solo es para este juego: el resto del taller es individual.
- **La hoja va abierta:** cada quien lee toda la frase antes de escribir, igual que la IA lee todo lo anterior antes de escribir la palabra siguiente.
- **Mientras escriben,** deja proyectada la diapositiva "Todos empiezan igual" y recorre las mesas. Si a los 4 minutos no terminan, di **alto**: con lo que lleven basta para comparar. Si un equipo se atora, que escriba la primera palabra que se le ocurra: de eso se trata.
- **Al comparar,** retoma el gancho: "por eso su animación puede verse distinta a la mía". Si algún equipo NO escribió "cien", úsalo en el giro.
- **El juego es con el grupo, no con Claude:** lo que importa es que vivan cómo escribe la IA, palabra por palabra.
- **"Esto es un modelo de lenguaje":** un minuto, justo después de "Así escribe la IA". Es ponerle nombre a lo que acaban de vivir, no una clase de teoría. Menciona "LLM" una vez, para que lo reconozcan si lo leen en otro lado, y sigue.
- **El giro de Huajuapan:** a unos 1,600 m sobre el nivel del mar, el agua hierve a unos 95 °C, no a 100. "Cien" era lo más probable, pero no lo verdadero **aquí**. Deja la idea sembrada: en la sesión 2 vemos que lo local es justo donde la IA más inventa.
- **La animación "¿Cómo funciona la IA?"** ([como-funciona-la-ia.html](como-funciona-la-ia.html)) sustituye al tokenizador en vivo. En la presentación se abre a pantalla completa; avanza con sus botones **Atrás** y **Siguiente**, y las flechas o el control cambian de diapositiva. En el paso 8 da clic en **+ Chat nuevo** y luego en **Enviar**. El guion de cada paso está en las notas de la diapositiva (tecla S; ábrelas antes de llegar aquí).
- **Los cortes de la animación son reales** (salen de la captura del tokenizador de OpenAI, [tokenizador.png](tokenizador.png)): *agua*, un pedazo; *hier·ve*, dos; *cal·ient·as*, tres. Repite la aclaración que aparece en pantalla: así corta ChatGPT; Claude corta distinto, pero la idea es la misma. Las barras de probabilidad y los conteos dicen "ejemplo": no son números reales.
- **Remátala con la diapositiva siguiente:** las tres reglas salen de lo que acaban de ver (predice; todo cuesta; viaja toda la conversación).
- **Los tokens preparan la sesión 2:** ahí la IA falla al contar letras, porque ve pedazos y no letras.
- **La regla 3 no contradice al gancho:** el aviso se pidió en el mismo chat porque era el mismo tema. Retómalo así: "¿se acuerdan de que no le repetimos el tema? Por eso".
- **No te extiendas en la regla 2.** El paso 3 explica cómo cuidar la versión gratuita.

</details>
