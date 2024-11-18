# EAT Demo IA Predictiva

Adélie Celier y Mathilde Naudin

## Marketing Político - Persuasión del Votante

### Caso elegido de los "182 Examples of Predictive Analytics"

[Ver documento completo aquí](https://1drv.ms/b/s!AtNNGt4B6rm7gtZHJJy5f4p1Il9OjQ?e=v1bmu3)

Table 7 - Voter Persuasion

---

## Revisión de lo que existe

<details>
<summary>Campaña Obama 2012</summary>

Para identificar a los votantes indecisos o propensos a no movilizarse, la campaña de Obama analizó datos de participación en elecciones anteriores, enfocándose en los votantes registrados que no habían votado en elecciones previas. Estos votantes eran considerados prioritarios para acciones de persuasión y movilización destinadas a aumentar su participación.

La campaña de Obama también utilizó pruebas A/B de manera intensiva para probar diversas versiones de mensajes (correos electrónicos, anuncios, eslóganes) y medir su eficacia en términos de compromiso y persuasión. Por ejemplo, grupos de prueba recibían correos electrónicos con distintos temas e imágenes, lo que permitía al equipo medir las tasas de apertura y clics para seleccionar la versión más atractiva.

**Ventajas:**  
- Esta campaña destacó el aspecto movilizador de la segmentación, buscando fomentar el compromiso democrático.  
- Estableció un modelo ético y participativo en el uso de datos.  

**Desventajas:**  
- Aunque menos controvertido, el uso de datos ya planteaba cuestiones de privacidad, aunque estaba limitado a interacciones con la campaña.

</details>

<details>
<summary>Campaña Trump 2016 y escándalo Cambridge Analytica</summary>

La campaña de Trump buscó influir en los comportamientos electorales de manera más intensiva, aprovechando las divisiones y emociones dentro del electorado.

**Estrategia:**  
En colaboración con Cambridge Analytica, el equipo usó modelos psicométricos basados en el modelo OCEAN (Apertura, Conciencia, Extraversión, Amabilidad, Neuroticismo) para desarrollar perfiles psicológicos precisos. Esta segmentación permitió la difusión de mensajes personalizados adaptados a las vulnerabilidades emocionales de cada grupo.

**Técnicas:**  
- Se utilizaron datos de millones de usuarios de Facebook para personalizar los mensajes en plataformas como Facebook e Instagram.  
- En los estados clave, también se difundieron anuncios destinados a desalentar el voto de los demócratas indecisos.

**Ventajas:**  
- Este enfoque demostró la eficacia del marketing político predictivo, permitiendo dirigirse con precisión a los votantes indecisos y a los estados estratégicos.  
- El uso de datos psicológicos permitió una segmentación extremadamente precisa.

**Desventajas:**  
- El escándalo de Cambridge Analytica reveló fallos éticos, ya que los datos se usaban a menudo sin consentimiento explícito, generando preocupaciones sobre manipulación y privacidad.  
- Esta campaña resaltó los riesgos de polarización y desinformación a través de mensajes dirigidos.

</details>

<details>
<summary>Paralelismo con un proyecto de marketing político predictivo</summary>

En un proyecto de análisis predictivo político, sería esencial:

- **Definir una visión ética y un marco de consentimiento para el uso de datos.**
- **Identificar variables clave** para los modelos predictivos basados en datos de comportamiento electoral, tendencias demográficas y sentimientos sociales, asegurando una recolección legítima.
- **Crear mensajes de campaña adaptados** a los grupos objetivo, manteniendo la transparencia sobre el uso de datos y los objetivos de influencia.

Con la campaña de Trump y el escándalo de Cambridge Analytica, es posible identificar los puntos críticos en los que el targeting predictivo puede mejorar la eficacia de las campañas, siendo consciente de las implicaciones éticas para la privacidad y la democracia.

### Conclusión de la comparación de estas dos campañas

La campaña de Obama marcó el inicio del uso de datos para el targeting político, mientras que la campaña de Trump mostró hasta dónde podían llegar la personalización y el perfilado psicológico, especialmente gracias a la inteligencia artificial y los algoritmos de predicción.

**Implicaciones éticas:** La campaña de Obama estableció las bases de un targeting ético centrado en la movilización, mientras que la de Trump reveló riesgos de manipulación, especialmente cuando los datos personales se explotan sin transparencia.

**Impacto en el compromiso y la democracia:** Aunque ambas campañas demostraron que el análisis predictivo podía aumentar la eficacia de los mensajes, también mostraron que el uso irresponsable de estas técnicas puede minar la confianza de los ciudadanos en las instituciones democráticas.

En conclusión, la comparación entre las campañas de Obama 2012 y Trump 2016 pone de relieve la evolución de las técnicas de marketing político hacia una personalización cada vez más precisa. Aunque el targeting predictivo puede mejorar el compromiso, plantea cuestiones éticas fundamentales sobre la privacidad y la necesidad de un marco de transparencia y consentimiento en el uso de datos en política.

</details>

---

## Formulación breve

### Visión

El objetivo del proyecto es desarrollar un modelo de IA predictivo que identifique a los votantes franceses susceptibles de cambiar su voto y que puedan ser convencidos de apoyar a nuestro candidato, Edouard Philippe, en las elecciones de 2027. Nuestra visión es adaptar y aplicar en Francia las técnicas exitosas de microsegmentación y marketing político utilizadas en las campañas de Obama y Hillary Clinton para crear estrategias personalizadas que movilicen eficazmente a estos electores.

### Plan de acción 

1. Definir los criterios de segmentación de votantes.

2. Recopilar datos demográficos, de comportamiento y de redes sociales relevantes para los segmentos identificados.

3. Limpiar y preparar los datos para el análisis.

4. Fusionar y analizar los datos para identificar patrones dentro de cada segmento.

5. Desarrollar modelos predictivos utilizando algoritmos de IA específicos para cada segmento.

6. Generar perfiles detallados de votantes y personalizar mensajes de campaña basados en los resultados del modelo.

   - Analizar las salidas del modelo para identificar las características clave de cada votante o segmento.
   - Diseñar mensajes de campaña personalizados que aborden las preocupaciones y motivaciones específicas de cada segmento.
   - Seleccionar los canales de comunicación más efectivos para llegar a cada grupo (por ejemplo, redes sociales, correo electrónico, eventos locales).

7. Implementar estrategias de marketing dirigidas a cada segmento.

8. Monitorear y evaluar la efectividad de las campañas y ajustar según sea necesario.

### Mapa de Riesgos

<details>
<summary> 1. Riesgo de Percepción de Manipulación </summary>

- Descripción: Los votantes podrían sentirse manipulados si perciben una personalización excesiva en los mensajes.

- Mitigación:
    - Mantener transparencia sobre las prácticas de recolección y uso de datos.
    - Evitar mensajes demasiado intrusivos o que revelen un conocimiento excesivo sobre las preferencias personales.
    - Enfatizar mensajes centrados en valores y propuestas más que en tácticas persuasivas.

</details>

<details>
<summary> 2. Riesgo Ético y Legal en el Uso de Datos </summary>

- Descripción: El uso de datos personales puede violar regulaciones y comprometer la privacidad.

- Mitigación:
    - Asegurar el cumplimiento legal con todas las regulaciones de protección de datos (ej. RGPD).
    - Anonimizar y pseudonimizar los datos utilizados para proteger la identidad de los individuos.
    - Obtener consentimiento explícito cuando sea necesario y comunicar claramente cómo se usarán los datos.
    - Implementar políticas internas de manejo y seguridad de datos.

</details>

<details>
<summary> 3. Riesgo de Sesgo en la Segmentación </summary>

- Descripción: Los modelos pueden contener sesgos que discriminen a ciertos grupos.

- Mitigación:
    - Utilizar conjuntos de datos diversos y representativos para minimizar sesgos.
    - Aplicar técnicas de auditoría de sesgos en los modelos predictivos.
    - Incluir a expertos en ética y diversidad en el equipo de análisis.
    - Revisar y ajustar continuamente los modelos y estrategias basadas en los hallazgos.
 
</details>
      
<details>
<summary> 4. Riesgo de Saturación y Fatiga de Canales </summary>
- Descripción: La sobreexposición a mensajes puede causar rechazo en los votantes.

- Mitigación:
    - Diversificar los canales de comunicación, incluyendo medios tradicionales y digitales.
    - Optimizar la frecuencia de los mensajes para evitar la sobrecarga.
    - Segmentar la audiencia para enviar contenido relevante y evitar mensajes redundantes.
    - Monitorear las métricas de interacción para ajustar las estrategias en tiempo real.

</details>
 
<details>
<summary> 5. Riesgo de Seguridad de la Información </summary>
- Descripción: Brechas de seguridad podrían comprometer datos sensibles.

- Mitigación:
    - Implementar medidas robustas de seguridad informática, incluyendo encriptación y controles de acceso.
    - Realizar auditorías de seguridad periódicas.
    - Desarrollar planes de respuesta ante incidentes de seguridad.

</details>

<details>
<summary> 6. Riesgo de Interpretación Incorrecta de los Datos </summary>
- Descripción: Malinterpretar datos puede llevar a decisiones estratégicas erróneas.

- Mitigación:
    - Contar con analistas de datos experimentados y capacitados.
    - Validar los modelos predictivos con datos históricos y pruebas piloto.
    - Utilizar técnicas de validación cruzada y otras metodologías estadísticas para asegurar la fiabilidad.
 
</details>
      
<details>
<summary> 7. Riesgo de Reacción Negativa del Público </summary>
- Descripción: Prácticas percibidas como poco éticas pueden dañar la imagen del candidato.

- Mitigación:
    - Mantener prácticas éticas en todas las actividades de la campaña.
    - Comunicar de manera proactiva las políticas de privacidad y el compromiso con la ética.
    - Estar preparados para gestionar crisis de comunicación si es necesario.

</details>

<details>
<summary> 8. Riesgo de Dependencia Tecnológica </summary>
- Descripción: Excesiva dependencia de la tecnología puede limitar la adaptabilidad.

- Mitigación:
    - Combinar el análisis tecnológico con la intuición y experiencia humana.
    - Desarrollar estrategias alternativas que no dependan exclusivamente de la tecnología.
    - Capacitar al equipo en el uso de herramientas, pero también en habilidades analíticas y estratégicas.

</details>
     
<details>
<summary> 9. Riesgo de No Cumplir con las Expectativas </summary>
- Descripción: Predicciones inexactas pueden llevar a pérdida de recursos y eficacia.

- Mitigación:
    - Establecer métricas claras de desempeño y criterios de éxito.
    - Realizar pruebas A/B y ajustes continuos basados en resultados reales.
    - Mantener expectativas realistas sobre lo que la IA puede lograr.

</details>
      
<details>
<summary> 10. Riesgo de Competencia Tecnológica </summary>
- Descripción: Otros pueden utilizar tecnologías similares, reduciendo nuestra ventaja.

- Mitigación:
    - Innovar constantemente en estrategias y tecnologías utilizadas.
    - Monitorear las tendencias y avances en marketing político.
    - Invertir en capacitación y desarrollo del equipo.

</details>

### Niveles de Aceptación

<details>
<summary>1. Eficacia del Modelo Predictivo</summary>

- **Precisión Adecuada:**
    - El modelo debe alcanzar métricas aceptables en precisión, recall, F1-score, etc.
- **Generalización:**
    - Debe demostrar buen rendimiento con datos nuevos y no vistos.

</details>

<details>
<summary>2. Impacto en los Objetivos de la Campaña</summary>

- **Mejora en Indicadores Clave:**
    - Incremento en el compromiso de los votantes, tasas de conversión u otros KPIs definidos.
- **Cumplimiento de Metas Establecidas:**
    - Logro de los objetivos específicos fijados para el piloto.

</details>

<details>
<summary>3. Viabilidad Operativa</summary>

- **Escalabilidad Técnica:**
    - La infraestructura puede manejar el aumento en volumen de datos y usuarios.
- **Capacidad del Equipo:**
    - El personal está preparado para operar y mantener el sistema a gran escala.

</details>

<details>
<summary>4. Cumplimiento Legal y Ético</summary>

- **Conformidad Regulatoria:**
    - El proyecto cumple con el RGPD y otras leyes pertinentes.
- **Aceptación Pública:**
    - No hay reacciones negativas significativas por parte del público o autoridades.

</details>

<details>
<summary>5. Rentabilidad y ROI Positivo</summary>

- **Beneficios Superan Costos:**
    - El análisis costo-beneficio indica que es financieramente viable.
- **Eficiencia de Recursos:**
    - Ahorro en tiempo y recursos comparado con métodos tradicionales.

</details>

<details>
<summary>6. Aprobación de Stakeholders</summary>

- **Apoyo Interno:**
    - La dirección y partes interesadas están de acuerdo en escalar el proyecto.
- **Feedback Positivo:**
    - Usuarios y equipos involucrados valoran positivamente los resultados del piloto.

</details>

--- 

## Breve inventario de recursos actuales y necesarios

### Datos

<strong> 🔴 Ver el proyecto en el repositorio con los métodos de recuperación de datos.</strong>

Basándonos en la literatura, los repositorios y los casos revisados, incluyendo las campañas de Obama 2012 y Trump 2016, hemos identificado una serie de **variables de interés** cruciales para proyectos de marketing político predictivo. A continuación, presentamos un listado detallado de estas variables, incorporando los elementos discutidos, y detallamos las posibles fuentes de datos desde diversos sistemas de información gerencial especializados, como **CRM**, **ERP**, **MES**, **MRP**, entre otros.


#### Variables de Interés Encontradas en los Casos Revisados


<details>
<summary> 1. Variables Demográficas</summary>

- **Edad**: Grupos de edad (18-24, 25-34, etc.), con objetivos específicos para jóvenes y jubilados.
- **Sexo**: Diferencias en las preferencias políticas y prioridades según el género.
- **Lugar de Residencia**: Zonas rurales, urbanas, periurbanas; distinción entre grandes ciudades y zonas rurales.
- **Nivel de Educación**: Nivel educativo más alto alcanzado (secundaria, universitaria, posgrado).
- **Situación Socioeconómica**: Ingresos, ocupación (sectores de actividad), estatus profesional (empleado, autónomo, desempleado).
- **Origen Étnico y Religioso**: Grupos etnoculturales o comunitarios con prioridades específicas (si está disponible y es relevante en el contexto legal y ético).

</details>

<details>
<summary> 2. Variables Comportamentales</summary>

- **Historial de Voto**: Participación en elecciones previas, afiliación política anterior, frecuencia de participación (frecuente, ocasional, nunca).
- **Engagement en Redes Sociales**: Número de "me gusta", compartidos, comentarios en publicaciones políticas, interacciones con cuentas de candidatos.
- **Participación en Eventos de Campaña**: Frecuencia y tipo de eventos (mitines, reuniones, discusiones en línea).
- **Preferencia de Canal de Comunicación**: Correo electrónico, SMS, redes sociales (Facebook, Twitter, Instagram, TikTok), llamadas telefónicas, anuncios digitales.
- **Reacciones Pasadas a Mensajes de Campaña**: Historial de reacciones a correos electrónicos, SMS, anuncios en línea (medido por tasas de clics y aperturas).

</details>

<details>
<summary> 3. Variables Psicográficas</summary>

- **Rasgos de Personalidad (Modelo OCEAN)**: Puntuaciones de personalidad medidas por pruebas o inferidas, como Apertura, Conciencia, Extraversión, Amabilidad y Neuroticismo.
- **Valores y Creencias**: Actitudes sobre temas como el clima, seguridad nacional, economía, derechos de las minorías.
- **Intereses y Pasiones**: Temas prioritarios identificados, como salud pública, poder adquisitivo, educación, empleo, tecnología o temas sociales.
- **Reactividad Emocional**: Nivel de emoción en las reacciones a publicaciones, como respuestas intensas a anuncios políticos o crisis (por ejemplo, inmigración, seguridad).

</details>

<details>
<summary> 4. Variables de Campaña</summary>

- **Puntuación de Persuasión**: Medida de la probabilidad de persuasión de un votante en función de interacciones e intereses.
- **Mensajes Personalizados**: Temas de mensajes que resuenan con cada segmento (por ejemplo, seguridad para personas mayores, cambio climático para jóvenes urbanos).
- **Impacto de Anuncios en Redes Sociales**: Medido por tasas de clics y compartidos para cada tipo de mensaje (mensajes positivos vs. mensajes alarmistas).
- **Frecuencia de Contacto y Tipo de Mensaje**: Frecuencia de contacto semanal y tipo de mensaje (informativo, persuasivo, movilizador).
- **Impacto de Eventos de Campaña**: Participación en línea después de reuniones, reacciones en línea a discursos.

</details>

<details>
<summary> 5. Variables Sociales y Contextuales</summary>

- **Eventos de Actualidad**: Crisis sociales o económicas, eventos geopolíticos o pandemias, medidos por el número de menciones en redes sociales.
- **Tendencias de la Opinión Pública**: Opiniones mayoritarias sobre temas actuales en tiempo real, mediante encuestas o análisis de sentimientos en Twitter.
- **Influencia de Líderes de Opinión**: Seguimiento de figuras influyentes, celebridades o influencers que apoyan la campaña y su impacto en el engagement.
- **Contexto Regional y Nacional**: Desempleo regional, desarrollo económico, tasa de criminalidad, contaminación local.

</details>

#### Posibles Fuentes de Datos desde Sistemas de Información Gerencial

<details>
<summary> 1. CRM (Customer Relationship Management)</summary>

- **Descripción**: Sistemas CRM esenciales para gestionar y analizar las interacciones con votantes y simpatizantes.
- **Datos Disponibles**:
  - Información de contacto y demográfica.
  - Historial de comunicaciones y respuestas.
  - Preferencias y comportamientos registrados.
  - Historial de donaciones y participación en eventos.
- **Fuentes**:
  - **Sistemas CRM propios de la campaña** (ej. NationBuilder, NGP VAN).
  - **Bases de datos de votantes** obtenidas legalmente y con consentimiento.

</details>

<details>
<summary> 2. ERP (Enterprise Resource Planning)</summary>

- **Descripción**: Sistemas ERP que aportan datos internos útiles para planificación y asignación de recursos.
- **Datos Disponibles**:
  - Recursos asignados a regiones o segmentos.
  - Logística de eventos y actividades de campaña.
- **Fuentes**:
  - **Sistemas ERP internos** si la campaña requiere gestión compleja de recursos.

</details>

<details>
<summary> 3. MES (Manufacturing Execution Systems) y MRP (Material Requirements Planning)</summary>

- **Aplicabilidad Limitada**: Más relevantes en fabricación, útiles para logística de materiales de campaña.
- **Datos Disponibles**:
  - Inventario de materiales promocionales.
  - Programación de producción y distribución de folletos, carteles, etc.
- **Fuentes**:
  - **Sistemas MES/MRP** si se producen y distribuyen materiales físicos a gran escala.

</details>

<details>
<summary> 4. Plataformas de Redes Sociales y Herramientas Analíticas</summary>

- **Descripción**: APIs y herramientas para extraer y analizar datos de redes sociales.
- **Datos Disponibles**:
  - Actividad e interacción de usuarios.
  - Tendencias y temas populares.
  - Sentimiento del público hacia ciertos temas o candidatos.
- **Fuentes**:
  - **APIs oficiales** de Twitter, Facebook, Instagram.
  - **Herramientas de terceros** como Hootsuite, Brandwatch.

</details>

<details>
<summary> 5. Sistemas de Información Públicos y Open Data</summary>

- **Descripción**: Datos disponibles públicamente que enriquecen el análisis.
- **Datos Disponibles**:
  - Estadísticas demográficas y socioeconómicas.
  - Resultados electorales históricos.
  - Información geográfica y censal.
- **Fuentes**:
  - **Institutos nacionales de estadística** (ej. INSEE en Francia).
  - **Portales gubernamentales de datos abiertos**.

</details>

#### Conclusión

Estas variables permitirán construir un modelo predictivo sólido para segmentar a los votantes en un contexto de campaña presidencial. Al integrar datos demográficos, comportamentales, psicográficos, de campaña y contextuales, podemos:

- **Segmentar y perfilar** a los votantes de manera precisa.
- **Personalizar mensajes** y estrategias de campaña adaptadas a cada segmento o individuo.
- **Predecir comportamientos electorales** y ajustar tácticas en consecuencia.

**Importante**: Al recopilar y utilizar estos datos, es esencial garantizar el **cumplimiento legal y ético**, respetando regulaciones como el **RGPD** y obteniendo el **consentimiento explícito** cuando sea necesario. La **Anonimización** y **Pseudonimización** de datos personales son prácticas recomendadas para proteger la privacidad de los individuos.

--- 

### Capital Humano

#### Tipos de Profesionales Fundamentales para el Proyecto

<details>
<summary>1. Científicos de Datos</summary>

- **Rol:** Desarrollan modelos predictivos y algoritmos de aprendizaje automático para analizar y extraer información de los datos recopilados.
- **Responsabilidades:**
  - Construir y entrenar modelos de machine learning.
  - Realizar análisis estadísticos y predictivos.
  - Validar y optimizar modelos para mejorar su precisión.

</details>

<details>
<summary>2. Analistas de Datos</summary>

- **Rol:** Interpretan y visualizan los datos para extraer insights accionables que apoyen la toma de decisiones estratégicas.
- **Responsabilidades:**
  - Limpieza y preparación de datos.
  - Análisis exploratorio de datos.
  - Creación de informes y visualizaciones.

</details>

<details>
<summary>3. Arquitectos de Datos</summary>

- **Rol:** Diseñan y supervisan la arquitectura de datos, asegurando que los sistemas de almacenamiento y procesamiento sean eficientes y escalables.
- **Responsabilidades:**
  - Definir la infraestructura de datos.
  - Seleccionar tecnologías adecuadas para el almacenamiento y procesamiento.
  - Garantizar la integridad y calidad de los datos.

</details>

<details>
<summary>4. Ingenieros de Datos</summary>

- **Rol:** Construyen y mantienen pipelines de datos, asegurando que los datos fluyan correctamente desde las fuentes hasta los sistemas de análisis.
- **Responsabilidades:**
  - Desarrollar procesos ETL (Extracción, Transformación y Carga).
  - Integrar diversas fuentes de datos.
  - Optimizar el rendimiento de los sistemas de datos.

</details>

<details>
<summary>5. Especialistas en Aprendizaje Automático</summary>

- **Rol:** Implementan y ajustan algoritmos avanzados de machine learning y deep learning para mejorar la capacidad predictiva del modelo.
- **Responsabilidades:**
  - Implementar técnicas avanzadas como redes neuronales.
  - Experimentar con diferentes algoritmos y enfoques.
  - Mantenerse actualizado con las últimas tendencias en IA.

</details>

<details>
<summary>6. Expertos en Ética y Cumplimiento Legal</summary>

- **Rol:** Aseguran que el proyecto cumpla con todas las regulaciones legales y éticas, especialmente en cuanto al uso y protección de datos personales.
- **Responsabilidades:**
  - Garantizar el cumplimiento del RGPD y otras leyes relevantes.
  - Establecer políticas internas de manejo de datos.
  - Realizar evaluaciones de impacto y riesgos legales.

</details>

<details>
<summary>7. Especialistas en Marketing Digital y Político</summary>

- **Rol:** Traducen los insights de datos en estrategias de marketing efectivas y alineadas con los objetivos de la campaña.
- **Responsabilidades:**
  - Diseñar mensajes y contenidos personalizados.
  - Planificar y ejecutar campañas en diversos canales.
  - Monitorear y optimizar el rendimiento de las campañas.

</details>

<details>
<summary>8. Gerentes de Proyecto</summary>

- **Rol:** Coordinan el equipo y las actividades del proyecto, asegurando que se cumplan los plazos y objetivos establecidos.
- **Responsabilidades:**
  - Planificar y supervisar el progreso del proyecto.
  - Gestionar recursos y presupuestos.
  - Facilitar la comunicación entre equipos.

</details>

<details>
<summary>9. Analistas de Negocio</summary>

- **Rol:** Actúan como puente entre los equipos técnicos y los objetivos estratégicos de la campaña, asegurando que las soluciones técnicas satisfagan las necesidades del negocio.
- **Responsabilidades:**
  - Identificar requisitos y objetivos clave.
  - Evaluar el impacto comercial de las soluciones propuestas.
  - Recomendar mejoras basadas en análisis de datos.

</details>

<details>
<summary>10. Diseñadores de Experiencia de Usuario (UX)</summary>

- **Rol:** Mejoran la interacción con los votantes en plataformas digitales, asegurando una experiencia intuitiva y atractiva.
- **Responsabilidades:**
  - Diseñar interfaces de usuario efectivas.
  - Realizar pruebas de usabilidad.
  - Optimizar el recorrido del usuario en aplicaciones y sitios web.

</details>

<details>
<summary>11. Especialistas en Seguridad de la Información</summary>

- **Rol:** Protegen los sistemas y datos contra amenazas y vulnerabilidades, garantizando la confidencialidad y la integridad de la información.
- **Responsabilidades:**
  - Implementar medidas de ciberseguridad.
  - Monitorear y responder a incidentes de seguridad.
  - Realizar auditorías y evaluaciones de riesgo.

</details>

---

#### Habilidades Necesarias para Ejecutar el Plan

<details>
<summary>1. Alfabetización en Datos (Data Literacy)</summary>

- **Capacidad para Comprender y Trabajar con Datos:**
  - Interpretación de conjuntos de datos y resultados analíticos.
  - Comprensión de conceptos estadísticos básicos y avanzados.
  - Habilidad para comunicar hallazgos de manera clara y efectiva.

</details>

<details>
<summary>2. Habilidades Técnicas</summary>

- **Programación y Desarrollo:**
  - Dominio de lenguajes como **Python** o **R**.
  - Experiencia con bibliotecas y frameworks de análisis de datos (pandas, NumPy).
  - Conocimientos en **SQL** para consultas de bases de datos.

- **Aprendizaje Automático y Modelado Predictivo:**
  - Familiaridad con algoritmos de machine learning (regresión, clasificación, clustering).
  - Uso de herramientas como **scikit-learn**, **TensorFlow**, **Keras**.
  - Comprensión de técnicas de validación y evaluación de modelos.

- **Manipulación y Procesamiento de Datos:**
  - Experiencia en procesos **ETL**.
  - Conocimientos de **Big Data** y herramientas como **Hadoop**, **Spark**.
  - Habilidad para manejar datos estructurados y no estructurados.

- **Visualización de Datos:**
  - Uso de herramientas como **Tableau**, **Power BI**, **Matplotlib**, **Seaborn**.
  - Capacidad para crear dashboards y reportes interactivos.

</details>

<details>
<summary>3. Habilidades Analíticas</summary>

- **Análisis Estadístico:**
  - Conocimientos en estadística descriptiva e inferencial.
  - Capacidad para realizar pruebas de hipótesis y análisis multivariante.

- **Pensamiento Crítico y Resolución de Problemas:**
  - Habilidad para identificar patrones y tendencias significativas.
  - Enfoque estratégico para traducir insights en acciones.

</details>

<details>
<summary>4. Habilidades de Comunicación</summary>

- **Comunicación Efectiva:**
  - Capacidad para explicar conceptos técnicos a audiencias no técnicas.
  - Presentación clara de hallazgos y recomendaciones.

- **Colaboración Interdisciplinaria:**
  - Trabajo en equipo con profesionales de diversas áreas.
  - Adaptabilidad para ajustar enfoques según feedback y necesidades.

</details>

<details>
<summary>5. Conocimientos en Ética y Cumplimiento</summary>

- **Regulaciones y Normativas:**
  - Familiaridad con el **RGPD** y leyes de protección de datos.
  - Comprensión de principios éticos en el manejo de información.

- **Responsabilidad Social y Transparencia:**
  - Compromiso con prácticas éticas en el uso de datos.
  - Promoción de la transparencia en las actividades del proyecto.

</details>

<details>
<summary>6. Habilidades en Marketing y Estrategia</summary>

- **Conocimiento del Marketing Político:**
  - Comprensión de tácticas y estrategias de campaña.
  - Experiencia en segmentación de audiencias y personalización de mensajes.

- **Análisis del Comportamiento del Votante:**
  - Estudio de tendencias electorales y motivaciones de los votantes.
  - Capacidad para adaptar estrategias según insights obtenidos.

</details>

<details>
<summary>7. Habilidades en Seguridad de la Información</summary>

- **Ciberseguridad:**
  - Conocimientos en protección de datos y prevención de amenazas.
  - Implementación de protocolos de seguridad y mejores prácticas.

</details>

<details>
<summary>8. Gestión de Proyectos</summary>

- **Planificación y Organización:**
  - Definición de objetivos, plazos y entregables.
  - Gestión eficiente de recursos y seguimiento del progreso.

- **Riesgos y Contingencias:**
  - Identificación y mitigación de riesgos potenciales.
  - Desarrollo de planes de contingencia.

</details>

### Métodos 

#### Segmentación de los votantes francéces - Votantes influenciables

<details>
<summary>Jóvenes urbanos ecologistas</summary>

**Por qué podrían cambiar de voto:**

Este segmento, aunque potencialmente favorable a los temas ecológicos, puede verse influido si En Marche refuerza sus compromisos ambientales con promesas concretas. Macron podría haber perdido popularidad entre ellos debido a políticas consideradas insuficientes para responder a la emergencia climática.

**Estrategia de influencia:**

Difundir mensajes enfocados en acciones ambientales reforzadas (reducción de emisiones de carbono, inversiones en energías renovables, transición verde). Usar influencers ecologistas para convencer de que En Marche es el partido mejor posicionado para avanzar la ecología en el poder.

</details>

<details>
<summary>Jóvenes profesionales en busca de seguridad económica</summary>

**Por qué podrían cambiar de voto:**

Estos votantes buscan principalmente estabilidad económica y seguridad laboral. La pandemia ha trastornado el mercado laboral, y muchos podrían verse atraídos por medidas de apoyo económico y empleo propuestas por partidos competidores.

**Estrategia de influencia:**

Destacar las políticas económicas de En Marche, como las iniciativas de apoyo a startups, ayuda a jóvenes emprendedores y medidas de reactivación. Valorar las reformas que facilitan la creación de empleos, mostrando que el partido se preocupa por el futuro de los jóvenes profesionales.

</details>

<details>
<summary>Clases medias y trabajadoras en áreas rurales</summary>

**Por qué podrían cambiar de voto:**

Esta población es sensible a los temas de poder adquisitivo y acceso a servicios públicos, y podría sentir que En Marche no ha respondido lo suficiente a sus necesidades. Pueden verse atraídos por discursos populistas o más cercanos a sus preocupaciones diarias.

**Estrategia de influencia:**

Difundir mensajes tranquilizadores sobre medidas de apoyo a las familias, reducción de impuestos para la clase media e inversiones en infraestructuras rurales. Mostrar que En Marche entiende sus necesidades en términos de poder adquisitivo y desarrollo de áreas rurales.

</details>

<details>
<summary>Jubilados y prejubilados preocupados por la seguridad social</summary>

**Por qué podrían cambiar de voto:**

Las reformas de pensiones propuestas por Macron en su primer mandato fueron percibidas como una amenaza para la estabilidad de las pensiones. Los partidos opositores podrían atraerlos jugando con esta inseguridad.

**Estrategia de influencia:**

Reforzar los mensajes sobre la protección de las pensiones, asegurando que la reforma de las pensiones está pensada para preservar el futuro manteniendo la estabilidad. Usar cifras y ejemplos concretos para disipar temores sobre las reformas y garantizar una seguridad social reforzada.

</details>

<details>
<summary>Jóvenes votantes sensibles a cuestiones de justicia social e igualdad</summary>

**Por qué podrían cambiar de voto:**

Estos votantes pueden estar decepcionados por una falta percibida de iniciativas en favor de la justicia social y derechos de las minorías. Otros partidos más comprometidos en estos temas pueden atraerlos.

**Estrategia de influencia:**

Comunicar acciones contundentes en justicia social e inclusión, como reformas para la igualdad de oportunidades, lucha contra la discriminación y acceso equitativo a la educación. Mostrar que En Marche está comprometido con la promoción de la igualdad y justicia social, con iniciativas específicas para las minorías.

</details>

<details>
<summary>Votantes en zonas periurbanas preocupados por la seguridad</summary>

**Por qué podrían cambiar de voto:**

Este segmento podría verse atraído por partidos más estrictos en temas de seguridad, especialmente si incidentes recientes han incrementado sus preocupaciones sobre seguridad local.

**Estrategia de influencia:**

Acentuar las medidas de seguridad pública, como el refuerzo de las fuerzas del orden y la inversión en programas de seguridad de proximidad. Mostrar que Macron es sensible a los problemas de seguridad y que implementa acciones concretas para las zonas periurbanas.

</details>

<details>
<summary>Pequeñas empresas y autónomos</summary>

**Por qué podrían cambiar de voto:**

Buscan a menudo reformas fiscales y administrativas simplificadas. Otros partidos podrían captar su atención con promesas de reducción de cargas.

**Estrategia de influencia:**

Destacar las acciones de En Marche para apoyar a las pequeñas empresas, como alivios fiscales, simplificación administrativa y acceso facilitado a financiación para PYMEs. Mostrar que En Marche apoya a los emprendedores y se compromete a facilitar sus actividades.

</details>

#### Conclusión

Al dirigirse a estos segmentos con mensajes personalizados y adaptados a sus preocupaciones, la campaña de En Marche podría atraer a votantes indecisos o que buscan un partido alineado con sus valores y necesidades actuales. Aprovechando los logros del primer mandato y reconociendo las preocupaciones actuales, es posible influir positivamente en estos perfiles de votantes para apoyar a Macron en su campaña de reelección.

Cada segmento debe recibir mensajes a través de los canales más pertinentes para ellos (redes sociales, correos electrónicos, influencers, anuncios locales), maximizando así el alcance de la campaña.


### Desarrollo de Modelos de IA Específicos para Cada Perfil

<details>
<summary><b>1. Identificación de Votantes Persuadibles</b></summary>

<p>Utilizamos modelos predictivos para identificar a votantes persuadibles basándonos en variables clave derivadas de campañas exitosas como las de Obama y Cambridge Analytica.</p>

#### Variables clave utilizadas:

- **Demográficas**:
  - Edad
  - Género
  - Nivel educativo
  - Ingresos estimados
  - Lugar de residencia (rural, urbano)

- **Psicográficas**:
  - Rasgos de personalidad (Modelo OCEAN)
  - Valores e intereses personales
  - Opiniones y creencias sobre temas clave

- **Comportamentales**:
  - Historial de votación
  - Interacción en redes sociales (likes, compartidos, comentarios)
  - Respuestas previas a mensajes de campaña (apertura de correos, clics)

#### Variables ya presente en los codigos existantes 
   - DEM: Candidato apoyado por el anuncio (1 para el candidato principal, 0 para el oponente).
   - ATT: Tipo de mensaje (1 para un ataque, 0 para un mensaje neutro o positivo).
   - AD_POSITION: Posición del anuncio en una pausa publicitaria (1 para primera posición, 5 para la última).
   - AD_LENGTH_IND: Duración del anuncio (1 para más de 30 segundos, 0 para 30 segundos o menos).
   - slant: Inclinación del anuncio (apoyo u oposición al candidato).
   - consistency: Coherencia del mensaje (entre 0 y 1, donde 1 indica una alta coherencia).
   - WEEK, Day, TIME_WINDOW: Variables temporales que representan la semana, el día y la franja horaria de difusión.
   - PROG_GENRE: Género del programa durante el cual se emite el anuncio (por ejemplo, "News", "Sports").
   - NETWORK: Cadena de difusión del anuncio (por ejemplo, CNN, MSNBC).
   - LOG_CAN_WOM_5_PRE y LOG_CAN_WOM_5_POST: Engagement antes y después del anuncio, medido en términos de "Word of Mouth" (boca a boca).

#### Varaiables ficticias añadidas por la integración de redes sociales y la personalización de mensajes
   - Platform: Tipo de red social donde se difunde el mensaje (Facebook, Instagram, Twitter, TikTok).
   - Engagement_Rate: Tasa de engagement en redes sociales (porcentaje de interacciones respecto al número de vistas).
   - Influencer_Boost: Indicador de compartición por un influencer o líder de opinión (1 = sí, 0 = no).
   - Video_Length: Longitud del video o anuncio en segundos, especialmente para formatos cortos en redes sociales.
   - Timing_Post: Hora de publicación del mensaje en la red social (por ejemplo, "Mañana", "Tarde", "Noche").
   - Segment: Categoría de electores objetivo (por ejemplo, "Jóvenes Urbanos Ecologistas", "Clases Medias Rurales").
   - Platform_Preference: Plataforma favorita de cada segmento de electores (por ejemplo, TikTok para los jóvenes, LinkedIn para los profesionales).
   - Content_Preference: Tipo de contenido que interesa a cada segmento (por ejemplo, "Ecología", "Justicia Social").
   - Engagement_Sensitivity: Nivel de sensibilidad de cada segmento al engagement (valores de 1 a 5, donde 5 indica una alta receptividad).

#### Algoritmos empleados:

- **Regresión Logística**: Ideal para predecir la probabilidad de persuasión.
- **Random Forest**: Captura relaciones complejas entre variables.
- **Gradient Boosting Machines (XGBoost, LightGBM)**: Modelos de alta precisión.

#### Proceso paso a paso:

1. **Preparación de datos**: Se limpian y codifican las variables relevantes.
2. **Entrenamiento del modelo**: Los datos se dividen en conjuntos de entrenamiento y prueba.
3. **Evaluación del modelo**: Se usan métricas como precisión, AUC-ROC, y F1-score.

</details>

<details>
<summary> <b>2. Asignación de Puntuaciones a los Votantes (Scoring)</b> </summary>

<strong> 🔴 Ver los ejemplos en el espacio de codigos (codespace).</strong>

<p>Asignamos a cada votante una puntuación basada en la probabilidad de que sea persuadido, utilizando las salidas del modelo predictivo.</p>

#### Fórmula de puntuación:

```math
Score\ del\ Votante = (0.30 \times Historial\ de\ Votación) + (0.25 \times Interacción\ con\ la\ Campaña) +
(0.20 \times Actividad\ en\ Redes\ Sociales) + (0.15 \times Variables\ Psicográficas) + (0.10 \times Variables\ Demográficas)

</details>

