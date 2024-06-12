# Instagram reels optimized

|  field  | value |
|---------|----|
| **Lang** | es |
| **Description** | Versión optimizada del [Instagram reels](instagram_reels.md) |
| **Author** | @umarquez |

## Input fields

- empresa: Nombre de la empresa
- objetivo_campaña: ¿Cuál es el objetivo de esta campaña? ex. hacer crecer mi cuenta y llegar a nuevos seguidores
- objetivo_contenido: ¿Cuál es el objetivo del contenido a crear? ex. ayudar a musico profesionales y principiantes en la producción de música electrónica, dar a conocer nuestra oferta de servicios y soluciones\
- pilar1: Pilar de contenido ex. Educativo y de divulgación, Entretenimiento, Nuevos negocios
- pilar2: Pilar de contenido ex. Educativo y de divulgación, Entretenimiento, Nuevos negocios
- pilar3: Pilar de contenido ex. Educativo y de divulgación, Entretenimiento, Nuevos negocios

## Prompt

```
Actúa como un experto en Instagram, estoy buscando crear Reels de impacto que resuene con mi publico objetivo y que se sienta identificado. Como ${empresa}, quiero ${objetivo_campaña}.

Nuestro objetivo es ${objetivo_contenido}

Haz una lista de contenido en formato tabla para mis pilares de contenido:

PILAR DE CONTENIDO 1:  ${pilar1}
PILAR DE CONTENIDO 2:  ${pilar2}
PILAR DE CONTENIDO 3:  ${pilar3}

Además para cada tema, mínimo identifica 10 ideas de lo siguiente:

Errores que cometen
Mitos en los que creen
Preguntas frecuentes
Creencias limitantes que tienen
Desafíos que viven
Resultados deseados
Temas y contenidos de interes relacionados

Hazme las preguntas que consideres necesarias para obtener toda la información antes de ejecutar la tarea, si después de generar una respuesta hubiera preguntas adicionales que te ayudaran a optimizar la respuesta, hazlas, pues el objetivo es tener eel mejor resultado.
```

## Expected output

```
¡Entendido! Para poder ayudarte a crear Reels de impacto que resuenen con tu público objetivo y alcancen tus objetivos de campaña, necesito obtener más información sobre tu empresa o proyecto. Aquí hay algunas preguntas que me ayudarán a personalizar la estrategia de contenido:

1. **Empresa o Proyecto:**
   - ¿Cuál es el nombre y la naturaleza de tu empresa o proyecto?
   - ¿Cuál es tu propuesta de valor o diferenciador principal en el mercado?

2. **Objetivo de la Campaña:**
   - ¿Cuál es el objetivo específico de la campaña? (Por ejemplo, aumentar seguidores, incrementar la interacción, generar leads, etc.)
   - ¿Cuál es el público objetivo específico de esta campaña? (Edades, intereses, ubicación, etc.)

3. **Objetivo del Contenido:**
   - ¿Qué mensaje principal deseas transmitir con tu contenido?
   - ¿Cómo quieres que tu audiencia se sienta o actúe después de ver tu contenido?

4. **Pilares de Contenido:**
   - Para el Pilar de Contenido 1 (Educativo y de divulgación):
     - ¿Qué temas educativos y de divulgación son más relevantes para tu audiencia?
     - ¿Qué tipo de información crees que tu audiencia está buscando?

   - Para el Pilar de Contenido 2 (Entretenimiento):
     - ¿Qué tipo de contenido de entretenimiento resuena más con tu audiencia?
     - ¿Hay algún formato o estilo particular que prefiera tu audiencia?

   - Para el Pilar de Contenido 3 (Nuevos negocios):
     - ¿Qué aspectos de tu negocio o servicios deseas promover?
     - ¿Qué mensajes clave quieres transmitir para atraer nuevos negocios?

Una vez tenga estas respuestas, podré crear una tabla con ideas de contenido específicas para cada pilar y temática, identificando errores comunes, mitos, preguntas frecuentes, creencias limitantes, desafíos, resultados deseados, y temas de interés relacionados.

¿Qué te parece esta propuesta? ¿Hay alguna otra información adicional que crees que sería útil para desarrollar esta estrategia?
```

## Commands

- `/clear` clean the memory and restart the prompt asking for fields' values again.
- `/fields` ask for a specific field new value and adjust the output according to this change
