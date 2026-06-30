# Bitácora de Trabajo y Documentación del Proceso: "Gatito vs Perrito"

Este documento recopila el proceso de análisis, rediseño y documentación del proyecto educativo "Gatito vs Perrito", trabajado de manera iterativa.

## Fase 1: Análisis y Evaluación Diagnóstica
* **Solicitud Inicial:** Se solicitó analizar el repositorio original de GitHub (`americadiaz906/Juego-Gato`), identificar sus tecnologías (HTML, CSS, JS, Web Audio API) y realizar una evaluación pedagógica centrada en una niña de preescolar con un ritmo de aprendizaje más lento.
* **Resultados de la Evaluación:** Se determinó que el juego era adecuado por su ritmo libre y estética amigable, pero presentaba barreras de autonomía y comprensión debido a su dependencia de instrucciones en texto (ej. "Turno de Gatito" o botones de "Reiniciar partida").

## Fase 2: Implementación de Adecuaciones Pedagógicas en Código
Para eliminar las barreras identificadas, se modificó el archivo `index.html` integrando las siguientes mejoras:
1. **Andamiaje Visual (Pistas):** Implementación de un temporizador de 5 segundos que hace palpitar en verde una casilla recomendada si la estudiante se demora, sirviendo de guía sin resolver el problema por ella.
2. **Retroalimentación Formativa y Multisensorial:** 
   * Ante un error (tocar casilla ocupada): Animación de temblor (`shake`) y voz en off ("¡Oh! El perrito pasó por aquí...").
   * Ante una victoria: Trazado lento de la línea ganadora con estrellas animadas, salto del personaje y voz en off celebratoria.
3. **Autonomía (Iconografía):** Sustitución de textos en botones por íconos universales grandes (🔄, 🧹, 🔊).
4. **Comprensión (Indicador espacial/visual):** Eliminación del texto de turno, sustituido por avatares dinámicos (que crecen y saltan) y cambios sutiles en el color de fondo de la pantalla según el jugador en turno.

## Fase 3: Documentación Educativa (Enfoque NEM)
Se generaron dos documentos clave para respaldar la herramienta:
* **Memoria_Didactica.md:** Documento técnico-pedagógico que fundamenta las adecuaciones tecnológicas bajo los principios de la Nueva Escuela Mexicana (NEM), destacando la inclusión, la equidad, los ajustes razonables y el aprendizaje situado.
* **Manual_Familias.md:** Guía redactada en lenguaje cálido y accesible para orientar a madres, padres y tutores sobre el propósito del juego, habilidades que desarrolla (tolerancia a la frustración, pensamiento espacial) y cómo mediar durante su uso.

## Fase 4: Estrategia de Integración (GitHub Flow)
* **Objetivo:** Definir la ruta tecnológica para devolver estas mejoras al proyecto original de la compañera mediante la dinámica de "Fork" y "Pull Request".
* **Roles:** Se estableció el esquema de trabajo donde la colaboradora (quien hace el Fork) desarrolla y experimenta de forma segura, para posteriormente proponer los cambios a la propietaria original para su revisión e integración oficial.
