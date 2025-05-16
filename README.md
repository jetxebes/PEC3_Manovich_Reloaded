


# **Manovich Reloaded: TouchDesigner y ComfyUI como metamedios contemporáneos.**

Este ensayo se propone analizar dos ejemplos recientes de hibridación de medios que, a mi juicio, merecerían un lugar en una reedición de El software toma el mando de Lev Manovich, TouchDesigner y ComfyUI. El análisis parte de cuatro ejes conceptuales del autor, softwarización, técnicas independientes del medio, modularidad cultural y remezcla algorítmica. Estas son las claves para comprender cómo el software transforma las prácticas creativas y reorganiza el ecosistema audiovisual.

Con softwarización Manovich define el giro decisivo por el cual las operaciones propias de un medio se desprenden de su soporte físico y se reescriben como algoritmos genéricos. Simular un libro, por ejemplo, implica reproducir funciones como copiar, pasar página o buscar, antes que su apariencia material. Una vez codificadas, esas operaciones se emancipan del medio originario, así, la acción de “copiar y pegar” sirve indistintamente para texto, imagen o audio, mientras que un filtro gráfico puede aplicarse tanto a una fotografía como a un objeto 3D, facilitando así la hibridación entre formatos.

Visto lo anterior, podemos abordar el concepto de técnicas independientes del medio. Estos son conjuntos de algoritmos que realizan tareas conceptualmente equivalentes sobre estructuras de datos distintas, como cortar y pegar o aplicar transformaciones de forma. Al abstraerse del soporte, estas técnicas circulan libremente por la cultura digital como herramientas aplicables a diferentes dominios y disciplinas.

La modularidad cultural describe un ecosistema donde operaciones como copiar, filtrar o superponer capas se encapsulan en módulos reutilizables agrupados como presets, nodos, APIs o plantillas, que cualquier creador puede ensamblar como si se tratase de piezas de LEGO. La innovación ya no depende de crear procedimientos inéditos, sino de recombinar bibliotecas y recursos compartidos.

Finalmente, la remezcla algorítmica constituye el pilar de la cultura del software. Los algoritmos extraen fragmentos de obras ajenas y los recombinan. Esto se realiza sin alterar la lógica de la operación original, tan solo sus parámetros al pasar, por ejemplo, de texto a imagen o sonido. La creatividad se concentra, pues, en seleccionar, transformar y ensamblar funciones preexistentes, permitiendo así la hibridación contemporánea de medios.

Sobre este marco, TouchDesigner y ComfyUI se estudian como entornos metamediales donde convergen estas cuatro dinámicas, extendiendo el legado de After Effects, analizado por Lev Manovich en “El software toma el mando”, hacia la generación gráfica en tiempo real y la síntesis multimodal asistida por inteligencia artificial.


## **Caso 1: TouchDesigner - El metamedio escénico y performativo**


TouchDesigner, desarrollado por Derivative desde finales de los años noventa, es hoy un entorno visual de programación en el que confluyen gráficos 2D/3D, sonido, datos en red y sensores físicos, todo ello procesado en tiempo real y gestionado mediante una estructura de nodos u “operadores”. Esta arquitectura procedural ha convertido al software en el estándar de facto para instalaciones inmersivas, espectáculos de música electrónica y prototipado interactivo, razón por la cual resulta un caso paradigmático de la hibridación que describe Lev Manovich.  
  
La interfaz gráfica de TouchDesigner distribuye las operaciones clásicas del audiovisual como pueden ser, mezclar fuentes, aplicar efectos o definir el timeline, en familias de algoritmos genéricos. Estos se agrupan por familias definidas como TOPs para píxeles, CHOPs para señales, SOPs para geometría, DATs para tablas y scripts. Cada operador funciona como una caja negra que expone parámetros y admite cualquier flujo de datos compatible, es decir, la lógica de “ajustar niveles” o “mezclar canales” se hace independiente del soporte concreto. Esto cumple con la tesis de Manovich según la cual las funciones del medio se vuelven funciones abstractas invocables desde cualquier tipo de dato. La actualización oficial de 2023 reforzó esa tendencia al incorporar tracking por IA y procesado de profundidades ZED bajo la misma interfaz nodal, sin que el usuario deba cambiar de paradigma  
  
En TouchDesigner, un nodo Blur suaviza tanto un vídeo en 8K como la textura de un objeto 3D; un LFO oscila valores que pueden modular la intensidad de la luz o la velocidad de reproducción; un Feedback crea ecos visuales o retardo sonoro. La equivalencia funcional entre imágenes, vectores, audio y datos numéricos ilustra la abstracción de técnicas: el mismo algoritmo opera sobre dominios heterogéneos sin perder eficiencia, habilitando flujos transmediales fluidos.  
  
La comunidad ha producido miles de tox  files, paletas y componentes listos para arrastrar y soltar, desde sintetizadores granulados hasta sistemas de realidad aumentada. Estos módulos encapsulan conocimiento experto y pueden encadenarse como piezas LEGO para resolver problemas complejos en minutos. Plataformas educativas como The NODE Institute mantienen repositorios y cursos que socializan dichos paquetes, acelerando la innovación colectiva y desplazando el mérito creativo hacia la curaduría y combinación de bloques existentes.  
  
El motor de scripting en Python permite manipular en caliente cualquier parámetro, clonar redes enteras o generar variaciones estocásticas, un patch puede alimentarse de tweets, traducirlos a text-to-speech y, simultáneamente, mapear su análisis de sentimiento en la intensidad de un láser. Cada ejecución es una remezcla parametrizada en tiempo real, los algoritmos recombinan fragmentos de audio, geometría y datos procedentes de fuentes externas (OSC, MIDI, WebSocket) generando resultados irrepetibles. Herramientas comunitarias de 2024 como Craft Kontrol introducen shaders procedentes de motores de juego que se injertan en la red nodal para producir paisajes generativos ultra detallados, ampliando aún más el repertorio disponible.  
  
TouchDesigner funciona simultáneamente como instrumento de directo, laboratorio pedagógico y middleware para grandes eventos. Su licencia gratuita fomenta la experimentación amateur, mientras que la edición comercial escala hasta videowalls 16K o instalaciones multisensoriales en museos. Al condensar en una misma interfaz la captura de datos, la síntesis audiovisual y la lógica de control, el programa se erige en un auténtico metamedio, materializa la softwarización, propicia técnicas independientes, se sostiene en una modularidad abierta y empuja la remezcla algorítmica como método creativo central. Así, prolonga el legado que Manovich rastreó en After Effects y lo proyecta hacia un escenario donde la computación en vivo redefine la estética y la autoría digital contemporáneas.

Recursos visuales:

- Showcase oficial: [https://derivative.ca/showcase](https://derivative.ca/showcase)
    
- Vídeo demostrativo: [https://www.youtube.com/watch?v=Y0xZzuYS2YI](https://www.youtube.com/watch?v=Y0xZzuYS2YI)

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXcrqE_cLRLLATGS5-NxTTiwhbDCWiJ4JDtNwytd91OEpHi_5-r16byRAmrD7uqxJKTW4W6IlzYSnosakxctZbfRtwlh1s7z12qy3f6hGkPqk-i5Vt40iirku70o44m3A5grI-AQLQ?key=0q3dibSTk2o3WQDl9krjZQ)**


## **Caso 2: ComfyUI — La estética de la remezcla algorítmica**

ComfyUI, proyecto abierto alojado en GitHub desde diciembre de 2022, es un motor visual que permite diseñar y ejecutar pipelines de Stable Diffusion mediante un diagrama de nodos. Cada bloque representa una operación específica (cargar modelo, codificar texto, muestrear, decodificar, post-procesar) y las conexiones hacen explícito el flujo de datos, de modo que el proceso acostumbrado a permanecer oculto en la “caja negra” del prompt se vuelve transparente y editable. Disponible para Windows, Linux y macOS, la interfaz se ha convertido en referencia para creadores que necesitan control granular sobre IA generativa sin abandonar la agilidad del prototipado gráfico.  
  
Las funciones que antes exigían línea de comandos como cambiar de sampler, ajustar pasos o fusionar checkpoints, aparecen aquí como algoritmos genéricos invocables sobre cualquier tipo de dato. Un mismo nodo Sampler admite latentes procedentes de texto o de imagen. Un nodo KSampler ejecuta la integración numérica que define el proceso de difusión sin importar el modelo en memoria. Cuando en 2024 se incorporaron IP-Adapter, LCM y Turbo, bastó añadir nuevos operadores al flujo sin alterar la lógica global, confirmando la idea de Manovich de que el medio (imagen, vídeo, 3D) se reescribe como función abstracta lista para combinarse a voluntad.  
  
ComfyUI extiende la misma operación sobre dominios distintos, un sampler  Euler pasa de texto-a-imagen a image-to-image variando solo el origen de los latentes. ControlNet aplica idénticas convoluciones para pose, profundidad o bordes. El nodo CLIP  Encode codifica frases, bocetos vectoriales o fotogramas, demostrando que la “técnica” vive separada del soporte. Así, la equivalencia funcional que Manovich señalaba entre copiar-pegar en texto e imagen encuentra una actualización en la conversión indiferente entre modalidades por IA.  
  
El ecosistema se organiza en paquetes de nodos que el usuario instala con un clic vía ComfyUI-Manager. Repositorios como Awesome ComfyUI  Custom Nodes o Comfyroll ofrecen centenares de operadores, LoRA Switchers, Multi-ControlNet, fusionadores de modelos, generadores de vídeo y scripts de automatización. Compartir una “red” es tan simple como copiar el JSON del flujo, otros pueden abrirlo, cambiar modelos o parámetros y producir variaciones, de modo que la innovación cultural se acelera al ritmo en que circulan estos módulos intercambiables.  
  
La lógica de “seleccionar-variar-ensamblar” se intensifica en los workflows que combinan IP-Adapter para rostro consistente, dos ControlNet simultáneos y un merger de checkpoints SDXL + DreamShaper. El mismo nodo puede clonar su estado, duplicarse en paralelo y recibir seeds pseudoaleatorios, generando series infinitas donde cada imagen remixa la anterior mediante leves perturbaciones. Scripts en Python permiten bucles que leen carpetas, cambian prompts y guardan GIFs, creando un estudio algorítmico que mezcla otras obras, modelos y datos con mínima fricción.  
  
Para artistas digitales ofrece la posibilidad de reproducir exactamente un resultado, algo difícil en interfaces de prompt tradicionales, y, al mismo tiempo, explorar variaciones en tiempo real. Además, se puede pausar tras cada paso y visualizar los latentes. En la industria, la exportación de gráficos de flujo a documentación agilita auditorías y reproducibilidad. ComfyUI se alinea así con la visión de Manovich, un metamedio donde convergen operaciones abstractas, módulos distribuibles y remezcla constante, configurando estéticas computacionales que trascienden el soporte original.

Recursos visuales:

- Repositorio de ejemplos: [https://github.com/comfyanonymous/ComfyUI_examples](https://github.com/comfyanonymous/ComfyUI_examples)
    
- Colección visual: [https://comfyworkflows.com/](https://comfyworkflows.com/)
    
- Vídeo explicativo: [https://www.youtube.com/watch?v=0fFxtJwT-vw](https://www.youtube.com/watch?v=a7KtirwLoyo)

**![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfhQoVx_4zWusNuGsqihwWTlw6yup2DIAT5dPj5ij_89GdRV5pGQ2TMnhCk-4ZPJyLMxMKYpT77XmyuYgexCUE1Seth7RpjKbFJc22ZMJs8oXUChEKvut6-1dC-T2Gn0bXUl_Y9vg?key=0q3dibSTk2o3WQDl9krjZQ)**


## **Conclusiones**

TouchDesigner y ComfyUI confirman que la “softwarización” señalada por Lev Manovich no es un episodio histórico cerrado, sino un proceso en curso que convierte las operaciones propias de todos los medios en algoritmos que circulan libremente por todo el ecosistema digital. Sus interfaces nodales muestran cómo esas operaciones, convertidas en técnicas independientes del medio, pueden aplicarse a píxeles, vectores, señales o latentes con la misma naturalidad con que se copia y pega un párrafo de texto. Al encapsularse en bloques reutilizables, dichas técnicas alimentan una modularidad cultural que acelera la innovación. Basta ensamblar nodos, presets o scripts para obtener resultados inéditos.

La remezcla algorítmica emerge entonces como lógica creativa dominante. Ambos entornos permiten clonar, perturbar y recombinar flujos de datos en tiempo real, de modo que cada ejecución reescribe el material precedente.

<*No se trata de una yuxtaposición superficial, sino de una integración funcional que reorganiza el ecosistema digital contemporáneo*>. “*Fundamentos y evolución de la multimedia*” Adell Español (2024, p. 4)

Así, el software deja de ser mera herramienta para convertirse en metamedio expresivo, un espacio donde convergen técnicas algorítmicas, cultura participativa y estética computacional. Si Manovich actualizara hoy El software toma el mando (2013), TouchDesigner y ComfyUI ocuparían un lugar central como ejemplos paradigmáticos de la hibridación presente, demostrando que la cultura digital se forja en la selección, variación y ensamblaje continuo de módulos de código antes que en la invención desde la nada.

## **Glosario**

-   **Softwarización**: proceso continuo por el que las operaciones propias de cualquier medio ,filtrar, mezclar, transformar,... se reescriben como funciones de software reutilizables y paramétricas.
    
-   **Técnica independiente del medio**: algoritmo capaz de ejecutar la misma tarea conceptual sobre datos heterogéneos (píxeles, vectores, audio, latentes) sin depender del soporte físico que los originó.
    
-   **Metamedio**: entorno computacional que no solo imita medios preexistentes, sino que los hospeda, los hibrida y los trasciende al permitir nuevas combinaciones imposibles fuera del software.
    
-   **Modularidad cultural**: principio según el cual prácticas y objetos culturales se diseñan como módulos intercambiables que pueden ensamblarse en cadenas productivas cada vez más complejas.
    
-   **Remezcla algorítmica**: lógica creativa basada en la selección, variación y ensamblaje automatizado de fragmentos de datos o procesos, generando series potencialmente infinitas.
    
-   **Entorno nodal**: interfaz visual donde las operaciones se representan como nodos conectados, de modo que el flujo de datos y la lógica del programa resultan transparentes y reconfigurables.
    
-   **Operador**: unidad funcional elemental en TouchDesigner y otros entornos nodales; recibe entradas, ejecuta una operación específica y produce salidas, pudiendo encadenarse con otros operadores para construir flujos complejos.
    
-   **Ingeniería de prompts**: arte y técnica de formular instrucciones textuales de alta precisión para orientar a los modelos generativos hacia resultados estilísticos y semánticos deseados.
    
-   **Espacio latente**: representación vectorial continua donde un modelo de aprendizaje automático codifica rasgos abstractos de los datos, permitiendo interpolaciones y transformaciones topológicas.
    
-   **Difusión estable** (Stable Diffusion): arquitectura generativa que modela la síntesis de imágenes como un proceso de difusión inversa, partiendo de ruido gaussiano y guiado por condicionamiento textual.
    
-   **SDXL**: versión de gran escala de Stable Diffusion (aprox. 3.5 B parámetros) entrenada con un conjunto de datos ampliado; mejora la coherencia compositiva, la definición de detalles y la gama cromática frente a iteraciones previas.
    
-   **Pipeline de aprendizaje automático**: cadena de etapas automatizadas, recolección, preprocesado, inferencia, posprocesado,... que garantizan reproducibilidad y escalabilidad en un proyecto de IA.
    
-   **IP-Adapter**: módulo que inyecta mapas de características de visión por computadora en la etapa de atención de un modelo generativo, reforzando el control visual sobre la síntesis.
    
-   **CraftKontrol**: framework de TouchDesigner que abstrae la lógica de interacción mediante componentes reutilizables, acelerando la construcción de prototipos audiovisuales complejos.
    
-   **Hibridación de medios**: integración funcional de elementos provenientes de diferentes medios en un único flujo computacional, engendrando artefactos mixtos y lenguajes emergentes.
    
-   **Modelo de difusión**: red neuronal entrenada para invertir un proceso progresivo de adición de ruido y generar datos sintéticos (imágenes, audio, vídeo) a partir de condicionamientos textuales o visuales.
    
-   **ControlNet**: extensión arquitectónica que incorpora mapas de características externas (pose, profundidad, contornos) en las capas de atención de un modelo de difusión, brindando control estructural preciso sobre el resultado.
    
-   **LoRA**: técnica de adaptación de baja densidad que ajusta un modelo grande mediante matrices de rango reducido, permitiendo especializarlo con pocos parámetros y sin reentrenar la red completa.
    
-   **Checkpoints**: archivos binarios que almacenan los pesos de un modelo entrenado o afinado en un estado concreto; en el ecosistema Stable Diffusion designan los modelos base o personalizados que pueden cargarse, mezclarse o continuar su entrenamiento.
    
-   **Dreamshaper**: checkpoint finamente ajustado que fusiona Stable Diffusion con estilos ilustrativos y fotorrealistas, entrenado mediante DreamBooth y técnicas LoRA para obtener imágenes versátiles y de alta estética.
    
-   **Semilla** (seed): valor numérico que inicializa el generador de pseudoaleatoriedad y garantiza la reproducibilidad de los resultados; alterar la semilla introduce variaciones manteniendo idénticos parámetros.
    
-   **Sampler** (muestreador): algoritmo que soluciona la ecuación de difusión inversa, Euler, Heun, DPM,… determinando la trayectoria de actualización de los latentes y la textura estética final. 

## **Uso de herramientas de inteligencia artificial**

Durante la elaboración de este trabajo se ha empleado **ChatGPT** de **OpenAI** como apoyo para la organización del contenido, revisión de redacción y sugerencias de mejora estilística, siguiendo los principios de uso responsable según la «Guía para citar el uso de IA» de la UOC (2023).


## **Referencias**

 - Adell Español, F. (2024). Fundamentos y evolución de la multimedia. Universitat Oberta de Catalunya.

 - Comfyanonymous. (2025). ComfyUI (Version 1.0) [Computer software]. GitHub. [https://github.com/comfyanonymous/ComfyUI](https://github.com/comfyanonymous/ComfyUI)

 - Comfyanonymous. (n.d.). ComfyUI Wiki. GitHub. [https://github.com/comfyanonymous/ComfyUI/wiki](https://github.com/comfyanonymous/ComfyUI/wiki)

 - Derivative. (n.d.). TouchDesigner (Version 2023) [Computer software]. Derivative. [https://derivative.ca](https://derivative.ca)

 - Ferguson, K. (2014). Everything is a Remix [Film]. [http://www.everythingisaremix.info/](http://www.everythingisaremix.info/)

 - Manovich, L. (2013). Software Takes Command. Bloomsbury Academic.

 - StackEdit. (n.d.). StackEdit [Web‑based Markdown editor]. [https://stackedit.io](https://stackedit.io)
