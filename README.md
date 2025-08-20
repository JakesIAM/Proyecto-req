🩺 Calculadora de Nivel de Alcohol en Sangre (BAC)
Este proyecto es una aplicación web de una sola página (OnePage) diseñada para calcular el nivel de alcohol en sangre (BAC) de una persona, utilizando la fórmula de Widmark. El objetivo es proporcionar una herramienta técnica y visualmente clara que muestre el proceso de cálculo de manera interactiva y sencilla.

💡 Intenciones del Proyecto
Mostrar el flujo del cálculo paso a paso, usando diagramas generados dinámicamente.

Permitir al usuario ingresar sus datos para obtener un cálculo personalizado de BAC.

Incluir fórmulas matemáticas presentadas de forma profesional.

Ofrecer advertencias y recomendaciones personalizadas basadas en el resultado.

💻 Requisitos Técnicos
El proyecto está estructurado para ser robusto y escalable, utilizando tecnologías modernas de desarrollo web.

Frontend
El frontend se encarga de la interfaz de usuario, la lógica de cálculo y la visualización de datos.

Lenguajes y Librerías:

TypeScript (TS): Para un código más limpio y con menos errores.

HTML5 y CSS3: Para la estructura y el diseño de la interfaz.

Mermaid.js: Para generar diagramas de flujo a partir de texto.

KaTeX o MathJax: Para renderizar las fórmulas matemáticas de forma clara.

Herramientas de Desarrollo:

Vite o Webpack: Empaquetadores para compilar y optimizar el código.

npm o yarn: Gestores de paquetes para manejar las dependencias del proyecto.

Backend (Opcional)
El backend es opcional para la funcionalidad básica, pero es necesario para futuras expansiones como autenticación de usuarios o almacenamiento de datos.

Lenguaje y Entorno:

Node.js: Entorno de ejecución del lado del servidor.

TypeScript (TS): Para mantener la coherencia en el código del servidor.

Frameworks y Librerías:

Express.js: Framework para crear la API REST.

Base de Datos (Opcional)
La base de datos es útil si se planea almacenar historiales de cálculo o perfiles de usuario.

Tipo de Base de Datos:

MongoDB (NoSQL): Recomendada por su flexibilidad.

PostgreSQL (SQL): Opción robusta si se necesita una estructura de datos más rígida.

Herramientas y Librerías:

Mongoose: Para interactuar con MongoDB.

Sequelize: Para interactuar con PostgreSQL.










Tengo el siguiente one page



✅ Alternativas Más Eficientes a Mermaid para un Onepage Técnico

Aquí te presento opciones más robustas y eficientes que Mermaid para tu caso:

Opción ¿Qué es? Ventajas HTML + CSS + JS Página estática hecha a mano Control total sobre visual, interacción, fórmulas, diseño responsive Notion + FigJam/Figma Documento estructurado + diagrama externo Ideal para presentaciones o compartir online LaTeX (con TikZ o PGF) Sistema de documentación científica Profesional, preciso, excelente para fórmulas Docusaurus / MkDocs Generadores de documentación técnica Soporte para diagramas, Markdown, HTML y temas Canva / Whimsical / Figma Herramientas visuales de diagramación Muy visual, rápido, exportable como PNG o PDF Jupyter Notebook / Observable Documentos interactivos con código Si deseas cálculos reales y visualización dinámica 💡 Recomendación: OnePage en HTML + CSS + JS

Si quieres eficiencia, visual atractivo, y posibilidad de incluir fórmulas técnicas bien presentadas, una página HTML estática es probablemente lo mejor.

Te permitiría:

Mostrar el flujo del cálculo paso a paso

Incluir fórmulas matemáticas con MathJax o KaTeX

Permitir inputs para que el usuario calcule su BAC

Mostrar tablas, advertencias, y resultados dinámicos

🧱 Estructura del OnePage (HTML)

Aquí va una estructura base que podrías usar:

<title>Cálculo de Nivel de Alcohol en Sangre</title> <script src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js" async></script>

Cálculo Técnico del Nivel de Alcohol en Sangre (BAC)



Basado en la fórmula de Widmark

Fórmula General



BAC=Ar⋅P⋅100−β⋅h

A: gramos de alcohol puro

r: coeficiente de difusión (0.68 hombre, 0.55 mujer)

P: peso corporal en kg

β: tasa de eliminación (~0.015%/h)

h: horas desde la última bebida

Proceso de Cálculo



Determinar volumen y tipo de bebida

Calcular gramos de alcohol: \( Volumen \times \% \text{ de alcohol} \times 0.8 \)

Aplicar fórmula con peso y coeficiente según sexo

Restar eliminación según tiempo

Intenciones del onepage



Mostrar cuánto puedes beber antes de exceder el límite legal (0.08% en muchos países).<li>Puede estar en una app móvil o sitio web como calculadora BAC.</li>



<li>Útil para mostrar en tiempo real cómo disminuye el BAC con el paso de las horas.</li>



<li> Podría incorporar advertencias personalizadas (ej. "No deberías conducir").</li>

</ol>



OnePage BAC Calculator © 2025

Puedes expandir esto con CSS para el diseño, o JavaScript si quieres que sea interactivo (inputs para ingresar datos, botones, cálculo en vivo, etc.).





necesito que me entregues los requisitos tecnicos, que se use typescript, node.js, mermaid
