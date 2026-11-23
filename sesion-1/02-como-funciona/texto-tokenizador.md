# Texto para el tokenizador

[← Volver al paso 2](README.md)

Copia el texto del recuadro y pégalo en el [tokenizador de OpenAI](https://platform.openai.com/tokenizer), en la pestaña **GPT-5.x & O1/3**. Fíjate en los colores: cada color es un pedazo (token).

```
Cómo hierve el agua

Cuando calientas agua, sus moléculas se mueven cada vez más rápido y algunas escapan como vapor. Ese vapor empuja hacia afuera con cierta fuerza, que se llama presión de vapor, y esa fuerza crece con la temperatura. El agua hierve cuando su presión de vapor iguala la presión del aire que tiene encima. A partir de ahí se forman burbujas de vapor dentro del líquido, no solo en la superficie, y suben sin que la presión del aire las aplaste.

Mientras hierve, la temperatura deja de subir aunque sigas calentando. La energía extra se usa en convertir el líquido en vapor.

Por qué cambia con la altura

Mientras más alto estás, menos aire tienes encima y más baja es la presión atmosférica. Con menos presión, al agua le basta una temperatura menor para que su vapor la iguale, así que hierve antes.

Nivel del mar: unos 100 °C
Alrededor de 1,600 m (como Huajuapan): unos 94–95 °C
Ciudad de México (~2,240 m): unos 92–93 °C
Cima del Everest: unos 70 °C
```

## Qué buscar

- **Palabras comunes, un solo pedazo:** *agua*, *vapor*, *presión*.
- **Palabras menos comunes, varios pedazos:** *Huajuapan*, *calientas*, *escapan*, *burbujas*.
- **Los números también se cortan:** *1,600* y *94–95* salen en varios pedazos.

Así se ve: [tokenizador.png](tokenizador.png).
