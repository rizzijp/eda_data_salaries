Propósito del Análisis

En el dinámico y cambiante panorama de las carreras relacionadas con los datos, comprender los roles laborales y las tendencias salariales es fundamental para quienes buscan orientar su desarrollo profesional.
A través del análisis de aspectos clave como los diferentes puestos, la ubicación de las empresas, el nivel de experiencia y los salarios promedio, este estudio busca ofrecer una visión clara del mercado y servir como guía para quienes se inician en profesiones vinculadas al análisis y la ciencia de datos.

El documento se estructura de la siguiente manera:

Definición del objetivo de negocio y su propósito.

Descripción detallada de las fuentes de datos.

Documentación de los pasos de limpieza y transformación.

Análisis acompañado de visualizaciones y hallazgos clave.

Conclusiones e ideas para futuras exploraciones.

Objetivo de Negocio

El objetivo es realizar un Análisis Exploratorio de Datos (EDA) que proporcione una visión significativa de los salarios en carreras relacionadas con datos a nivel global, junto con perspectivas, tendencias y conclusiones que orienten a los nuevos profesionales del sector.

Preguntas guía del análisis:

¿Cómo están organizados los datos?

¿Existen problemas de sesgo o credibilidad en la fuente?

¿Qué pasos se siguieron para limpiar los datos?

¿Qué herramientas se utilizaron en el análisis?

¿Cómo influyen factores como el país, el puesto, el tamaño de la empresa, la modalidad de trabajo y el nivel de experiencia en el salario?

¿Qué tendencias o relaciones se detectaron?

¿Cómo pueden estos hallazgos ayudar al público objetivo a tomar mejores decisiones?

Fuente y Descripción de los Datos

Fuente:
https://github.com/foorilla/ai-jobs-net-salaries

Descripción:
El dataset contiene información global sobre salarios en los campos de Inteligencia Artificial, Machine Learning y Big Data, recopilada de forma anónima a través de la encuesta de ai-jobs.net/salaries
.
Su objetivo es ofrecer una referencia transparente sobre la remuneración en diferentes roles del sector, ayudando a profesionales, reclutadores y empresas a tomar decisiones mejor informadas.

Los datos se actualizan semanalmente e incluyen información anónima de profesionales y empleadores de todo el mundo. El dataset consta de una única tabla con las siguientes columnas principales:

Columna	Descripción
work_year	Año en que se registró el dato.
experience_level	Nivel de experiencia profesional (Entry-level, Mid-level, Senior, Executive).
employment_type	Tipo de empleo (Full-time, Part-time, Contract).
job_title	Título específico del puesto (Data Scientist, Data Engineer, Data Analyst, etc.).
salary	Salario bruto anual en la moneda local.
salary_currency	Moneda en la que se paga el salario (USD, EUR, etc.).
salary_in_usd	Salario bruto anual convertido a dólares estadounidenses (USD) para facilitar comparaciones.
employee_residence	País de residencia del empleado.
remote_ratio	Porcentaje de trabajo remoto.
company_location	País donde se encuentra la empresa.
company_size	Tamaño de la empresa (S: pequeña, M: mediana, L: grande).
job_category	Clasificación general del rol en categorías amplias.