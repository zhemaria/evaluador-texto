# Evaluador de Respuesta Extendida GED (Rúbrica Oficial)

Herramienta interactiva que evalúa ensayos del GED aplicando la rúbrica oficial del GED Testing Service (41 subdimensiones). Desarrollada por José M. Fernández con Gemini Pro 2.5 y Claude Sonnet 4.

## Características

- Evaluación basada en las **3 características oficiales** del GED:
  - Característica 1: Argumentación y Uso de Evidencia (12 subdimensiones)
  - Característica 2: Desarrollo de Ideas y Estructura (15 subdimensiones)
  - Característica 3: Claridad y Dominio del Español (14 subdimensiones)
- Motor de IA: **Groq LLaMA 3.3 70B**
- Evaluación automática de textos menores a 200 palabras
- Modo oscuro / modo claro
- Botón de copia de resultados
- Diseño responsive (móvil y escritorio)

## Requisitos para una respuesta válida

| Criterio | Valor |
|---|---|
| Longitud | 300–500 palabras |
| Párrafos | 4–7 |
| Evidencia | Citas de **ambos** textos fuente |
| Análisis | Comparativo y argumentativo |

## Configuración

1. Abre `index.html` en un navegador.
2. Reemplaza el valor de `GROQ_API_KEY` en el script con tu clave de [Groq](https://console.groq.com):
```js
const GROQ_API_KEY = 'tu_api_key_aquí';
```

## Uso

1. Pega tu respuesta extendida en el área de texto.
2. Haz clic en **Evaluar con Rúbrica Oficial GED**.
3. Revisa la puntuación por característica (escala 0–2) y el total (0–6).

## Tecnologías

- HTML5 / CSS3 / JavaScript (vanilla)
- [Groq API](https://groq.com) — LLaMA 3.3 70B
- [MathJax 3.2](https://www.mathjax.org/)
- [Font Awesome 6.4](https://fontawesome.com/)

## Aviso

Esta herramienta es orientativa. Los resultados pueden diferir de la puntuación oficial del examen GED.
