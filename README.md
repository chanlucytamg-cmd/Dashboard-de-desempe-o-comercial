# Dashboard de desempeño comercial Andes Retail Group
La información está dispersa en datos transaccionales y no existe una visión clara que permita responder preguntas estratégicas sobre ventas, rentabilidad y comportamiento de clientes. la misión ES transformar estos datos en información visual, clara y accionable.

💡 **Preguntas del negocio**

¿Cómo ha evolucionado el ingreso total entre 2024 y 2025?
<HEAD></HEAD>

¿Qué segmentos de clientes aportan mayor ingreso y rentabilidad?
<HEAD></HEAD>

¿Qué categorías de producto tienen mayor impacto en el negocio?
<HEAD></HEAD>

¿Existen diferencias relevantes entre países o regiones?
<HEAD></HEAD>

¿Qué patrones temporales se observan a lo largo del año?
<HEAD></HEAD>

¿Dónde podrían existir oportunidades de mejora comercial?


🛠️ **Herramientas del proyecto**

Tableau
<HEAD></HEAD>

Visualizaciones nativas (barras, líneas, mapas, tarjetas KPI)
<HEAD></HEAD>

Modelo de narrativa SQCA


📂 **Dataset del Proyecto**

El archivo Andes_Retail_Group_2024_2025.xlsx contiene transacciones de ventas del negocio retail Andes Retail Group correspondientes a los años 2024–2025.


🔄 **Flujo general del proyecto**

1. Conexión y exploración;	Importar el dataset y revisar tipos de datos, columnas y métricas clave.
  <HEAD></HEAD>
   
2. Preparación de datos	Validar tipos; crear columnas necesarias, revisar consistencia.
   <HEAD></HEAD>
   
3. Aplicar principios de diseño visual;	Definir layout, jerarquía visual, colores y estructura antes de crear visualizaciones.
   <HEAD></HEAD>
   
4. Crear visualizaciones efectivas;	Diseñar dos vistas: Vista General (overview) y Vista Detalle (análisis específico).
   <HEAD></HEAD>
   
5. Filtros e interacciones;	Implementar filtros y configurar interacciones entre gráficos.
    <HEAD></HEAD>
    
6. Narrativa con modelo SQCA;	Construir historia dentro del dashboard y comunicar hallazgos vía Slack.


   **Narrativa con Modelo SCQA**


**S (Situación):**

Durante 2024 y 2025, la empresa generó 5,531,994 en Ingresos Totales y un Margen de 1,941,749. La facturación está concentrada en dos mercados principales: Perú aporta el 39.02% (2,158,578) y Chile el 36.65% (2,027,669), mientras que Colombia representa el 24.33% ($1,345,747).

**C (Complicación):**

Caída Estacional Crítica: En ambos años se produce una caida severa en mitad de año (junio a agosto), alcanzando el punto más bajo en julio con 113,611 en 2024 a cerca de $98,611 en 2025), mostrando una desaceleración en el arranque del ejercicio.

**Q (Pregunta):**

¿Por qué se produce una contracción tan pronunciada a mitad de año y qué mercados/categorías explican la desaceleración interanual?

**A (Respuesta):**

Diagnóstico Macro: Dado que Perú y Chile representan más del 75% del volumen de negocio, las variaciones en la demanda de estos dos países condicionan el resultado global.


**Mensaje asincrónico para Slack (Modelo SCQA)**

Equipo, se observa una Alerta Estacional: Se tiene un patrón recurrente de caída severa a mitad de año

@Lideres_Comerciales Revisar distribución de cuotas y planificar estrategia anti-estacional para Q2/Q3.

@Equipo_Marketing Diseñar paquetes promocionales (bundles) y campañas de reactivación enfocadas en el segmento Económico antes de junio.

@Equipo_Ventas Aprovechar la solidez del margen en Electrónica, Ropa y Deportes (~35%) para ofrecer incentivos comerciales sin comprometer la rentabilidad.


**VISUALIZACIONES DINAMICAS EN TABLEAU**

Puedes consultar en el siguiente link:

https://public.tableau.com/shared/7D74TQHFR?:display_count=n&:origin=viz_share_link


<img width="953" height="810" alt="Captura de pantalla 2026-10-30 a las 12 40 32 p  m" src="https://github.com/user-attachments/assets/d0d12625-f5bd-405a-8273-4ff790e8a1d6" />


<img width="993" height="564" alt="image" src="https://github.com/user-attachments/assets/fdc4391b-ac37-4ff3-9f61-554fa3b92e99" />






