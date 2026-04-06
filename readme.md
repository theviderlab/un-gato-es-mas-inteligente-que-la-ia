# Un gato es más inteligente que la IA

¿Es la Inteligencia Artificial que usamos hoy el techo de la tecnología, o simplemente un desvío estadístico en el camino hacia algo mucho más profundo? En esta charla, desarmaremos la arquitectura de los modelos actuales para entender por qué, a pesar de su asombrosa capacidad de lenguaje, carecen de una intuición real sobre el mundo y se enfrentan a limitaciones que los datos masivos no pueden solucionar. Vamos a hablar sobre un cambio de paradigma hacia los "Modelos del Mundo" y cómo una nueva arquitectura inspirada en la biología podría ser la verdadera llave para alcanzar la Inteligencia Artificial General, permitiendo que las máquinas no solo predigan palabras, sino que finalmente comprendan la realidad. 

[Presentación](https://canva.link/vxc80ug0cgt35h4)

## Introducción: El Santo Grial de la Informática
Desde sus inicios, la informática ha perseguido un objetivo máximo: la Inteligencia Artificial General (AGI). Aunque no existe una definición consensuada, una de las más aceptadas describe a la AGI como cualquier inteligencia flexible y general, con recursos y fiabilidad comparables a la inteligencia humana.
Históricamente, el Test de Turing (1950) proponía que si un humano no podía distinguir si hablaba con otra persona o con una máquina, habríamos alcanzado la AGI. Sin embargo, hoy sabemos que imitar el lenguaje no es equivalente a poseer inteligencia.

## Los Niveles de la IA y el Estado Actual
Para medir el progreso, Google DeepMind propuso un marco de seis niveles (del 0 al 5) que cruza la capacidad de realizar tareas específicas frente a tareas generales:
- Nivel 0 (No IA): Una calculadora.
- Nivel 1 (Emergente): Modelos actuales como ChatGPT o Gemini.
- Niveles Intermedios: Algoritmos expertos como Deep Blue (ajedrez) o AlphaGo.
- Nivel 5 (Superhumano): Ejemplos como AlphaFold, que revolucionó la química al predecir estructuras de proteínas.
A pesar del impacto de los modelos de lenguaje, la realidad es que todavía estamos en el Nivel 1 en términos de generalidad.

## Las Limitaciones de los Modelos Autorregresivos (LLM)
Lo que hoy llamamos genéricamente "IA" son, en realidad, LLM autorregresivos. Su funcionamiento se basa en la predicción probabilística del siguiente token. Este diseño conlleva limitaciones intrínsecas que no se solucionan simplemente escalando los modelos o añadiendo más datos:
- Memoria Estática: En cada inferencia, el modelo empieza de cero. No aprende de la interacción en tiempo real; para añadir nuevos conceptos, requiere un reentrenamiento costoso.
- Falta de Razonamiento y Planificación: El modelo no "piensa" la respuesta completa; genera un token tras otro sin una hoja de ruta previa.
- Creatividad Limitada: Por definición, el modelo tiende a dar la respuesta más probable basándose en su entrenamiento, lo cual es opuesto a la verdadera creatividad.
- Error Exponencial (Alucinaciones): Al retroalimentar la entrada con sus propias predicciones, la probabilidad de error crece exponencialmente con la longitud de la salida.
- Falta de Entendimiento del Mundo: Los LLM se alimentan de texto, pero carecen de la intuición física del mundo que posee un ser vivo a través de la experiencia.

## El Cambio de Paradigma: Modelos del Mundo
Ante estas limitaciones, figuras como Yann LeCun (padre de las redes convolucionales y científico jefe en Meta) proponen un camino distinto: los Modelos del Mundo.
A diferencia de la IA generativa, que intenta predecir cada píxel o palabra, los seres humanos operan con representaciones abstractas. Si soltamos un teléfono, sabemos que caerá; no necesitamos renderizar un video mental cuadro por cuadro para predecirlo.

### La Arquitectura JEPA
LeCun propone la Joint Embedding Predictive Architecture (JEPA). Sus componentes principales son:
- Percepción: Un encoder que convierte el mundo real en representaciones abstractas.
- Modelo del Mundo: Predice futuros posibles basados en el pasado y en acciones propuestas.
- Actor y Crítico: El actor propone acciones y el crítico evalúa si ese futuro predicho nos acerca al objetivo.
- Memoria a Corto Plazo: Acumula experiencia para actualizar y entrenar el resto de los módulos de forma natural.

## Evidencia del Éxito: El Caso Minecraft
La eficiencia de este enfoque se demostró con el desafío de minar diamantes en Minecraft.
- Enfoque Tradicional (OpenAI, 2022): Requirió 70,000 horas de video humano, 720 GPUs y 9 días de entrenamiento.
- Modelo del Mundo (DeepMind, 2025 - DreamerV3): Logró el mismo objetivo sin intervención humana, en el mismo tiempo, pero utilizando una sola GPU.

## Conclusión: El Regreso de la Investigación
Como señala Ilya Sutskever, la era de simplemente "escalar modelos" (hacerlos más grandes) está llegando a su fin para dar paso a una nueva era de investigación profunda. Si los modelos del mundo son la llave hacia la AGI, el liderazgo tecnológico podría desplazarse, abriendo nuevas oportunidades para regiones como Europa.

## Referencias

| La fuente | El resumen | La peli | El código |
|-----------|------------|---------|-----------|
| [Position: Levels of AGI for Operationalizing Progress on the Path to AGI](https://arxiv.org/abs/2311.02462) | | | | |
| | [Measuring Progress Toward AGI: A Cognitive Framework](https://blog.google/innovation-and-ai/models-and-research/google-deepmind/measuring-agi-cognitive-framework/) | | |
| [On the Measure of Intelligence](https://arxiv.org/abs/1911.01547v2) | | | |
| [Attention Is All You Need](https://arxiv.org/abs/1706.03762) | | [Atención en los Transformers explicado visualmente](https://www.youtube.com/watch?v=eMlx5fFNoYc), [Breve explicación de los modelos extensos de lenguaje (LLM)](https://www.youtube.com/watch?v=LPZh9BOjkQs), [Pero, ¿qué es un GPT? Introducción visual a los Transformers](https://www.youtube.com/watch?v=wjZofJX0v4M) | |
| [Solving a Million-Step LLM Task with Zero Errors](https://arxiv.org/abs/2511.09030) | | | |
| [The Illusion of Thinking: Understanding the Strengths and Limitations of Reasoning Models via the Lens of Problem Complexity](https://arxiv.org/abs/2506.06941) | | | |
| | [Why Yann LeCun Bet $3.5 Billion on World Models Over LLMs](https://ai.gopubby.com/yann-lecun-ami-labs-world-models-2025-e26eefdd900e), [Contra LeCun on "Autoregressive LLMs are doomed"](https://www.lesswrong.com/posts/zyPaqXgFzqHkQfccq/contra-lecun-on-autoregressive-llms-are-doomed) | [Do LLMs Understand? Yann LeCun Spars with DeepMind's Adam Brown](https://www.youtube.com/watch?v=ykfQD1_WPBQ), [The LLM Revolution Is Over. The Physical AI Revolution Is Coming Fast](https://www.youtube.com/watch?v=MWMe7yjPYpE) | |
| [A Path Towards Autonomous Machine Intelligence](https://openreview.net/pdf?id=BZ5a1r-kVsf) | | [JEPA - A Path Towards Autonomous Machine Intelligence (Paper Explained)](https://www.youtube.com/watch?v=jSdHmImyUjk), [Yann LeCun Self-Supervised Learning, JEPA, World Models, and the future of AI](https://www.youtube.com/watch?v=yUmDRxV0krg), [Yann Lecun: Meta AI, Open Source, Limits of LLMs, AGI & the Future of AI - Lex Fridman](https://www.youtube.com/watch?v=5t1vTLU7s40&t=2s) | |
| [Self-Supervised Learning from Images with a  Joint-Embedding Predictive Architecture](https://arxiv.org/abs/2301.08243) | |  | |
| [Revisiting Feature Prediction for Learning Visual Representations from Video](https://arxiv.org/abs/2404.08471) | | [V-JEPA: Revisiting Feature Prediction for Learning Visual Representations from Video (Explained)](https://www.youtube.com/watch?v=7UkJPwz_N_0) | |
| [Intuitive physics understanding emerges from self-supervised pretraining](https://arxiv.org/abs/2502.11831) | | | [V-JEPA](https://github.com/facebookresearch/jepa), [Intuitive Physics](https://github.com/facebookresearch/jepa-intuitive-physics) |
| [LeWorldModel: Stable End-to-End Joint-Embedding Predictive Architecture from Pixels](https://arxiv.org/abs/2603.19312) | | | |
| [Key-Value Memory Networks for Directly Reading Documents](https://arxiv.org/abs/1606.03126) | | | |
| [Video PreTraining (VPT): Learning to Act by Watching Unlabeled Online Videos](https://arxiv.org/abs/2206.11795v1) | | [Video PreTraining (VPT): Learning to Act by Watching Unlabeled Online Videos (Paper Explained)](https://www.youtube.com/watch?v=oz5yZc9ULAc) | |
| [Mastering diverse control tasks through world models](https://www.nature.com/articles/s41586-025-08744-2) | [World Models: How Dreaming Beats Memorizing in AI](https://blog.delanoe-pirard.com/one-gpu-vs-720-how-dreaming-beats-memorizing-in-ai-d62d837bf4c2) | [Model Based RL Finally Works!](https://www.youtube.com/watch?v=vfpZu0R1s1Y) | |
| | | [Ilya Sutskever – From scaling to the age of research](https://www.youtube.com/watch?v=aR20FWCCjAs) | |

