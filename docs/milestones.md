## Hitos del Proyecto

### Hito 0: Fundamentos del proyecto
- **Descripción:** Investigar las tecnologías que se emplearán en el desarrollo del sistema de evaluación de riesgos financieros, así como determinar las fuentes de datos relevantes para la automatización de cálculos de riesgo.  
- **Entregables:** Informe sobre las tecnologías seleccionadas, requisitos necesarios para el uso y desarrollo de la plataforma, y fuentes de [datos](https://github.com/jacarmona364/Riskalc/blob/main/docs/material_financiero/historial_prestamos.csv) disponibles, así como el código correspondiente con la estructura de la aplicación.  
- **Viabilidad:** Este hito es crucial para elegir las tecnologías adecuadas y obtener requisitos claros que guiarán el desarrollo del proyecto. Se realizará un modelo asociado a la implementación de cada tecnología. Se considerará completado cuando dicho modelo ofrezca una imagen clara de la resolución del problema, lenguaje a utilizar y presente una lógica de negocio consistente.
- **Producto:** Generar un prototipo simple que represente la arquitectura del sistema para visualizar la solución, así como los requisitos necesarios para el uso y desarrollo de la plataforma.

---

### Hito 1: Cálculo de la Fórmula en Base a Operaciones Pasadas
- **Descripción**: 
  Desarrollar y ajustar la fórmula de cálculo de riesgo utilizando datos históricos de operaciones pasadas. La fórmula deberá considerar [variables](https://github.com/jacarmona364/Riskalc/blob/main/docs/material_financiero/scoring.md) como solvencia, renta anual, deudas pendientes y características demográficas de los prestatarios.
- **Entregable**: 
  Módulo de estimación del peso de cada variable, teniendo en cuenta cuánto afecta cada parámetro al pago o no del préstamo.
- **Viabilidad**: 
  Se utilizarán datos históricos de la empresa para validar la precisión de la fórmula. Se realizará un análisis estadístico mediante test para asegurar que la fórmula ofrece resultados consistentes y coherentes.
- **Producto**: 
  Código que genera la fórmula del riesgo ajustada y lista para ser implementada en el sistema automatizado.

---

### Hito 2: Automatización del Cálculo del Riesgo
- **Descripción**: 
  Implementar la automatización de la fórmula de cálculo de riesgo en la aplicación, permitiendo que los analistas puedan obtener resultados precisos de manera rápida y uniforme, directamente desde el sistema.
- **Entregable**: 
  Versión funcional del módulo con la lógica de cálculo de riesgos integrada, tomará en cuenta las operaciones evaluadas con su resultado real en cada periodo para ajustar la fórmula utilizada. Documentación técnica que detalle la implementación y el uso de la fórmula automatizada.
- **Viabilidad**: 
  La automatización reducirá significativamente el tiempo de evaluación y mejorará la consistencia en las decisiones, cumpliendo con la normativa.
- **Producto**: 
  Código con la capacidad de calcular automáticamente el riesgo de cada operación, utilizando los datos ingresados del prestatario y basada en los pesos de la fórmula extraída con anterioridad.

---

### Hito 3: Modificación de Operaciones Pasadas
- **Descripción**: 
  Desarrollar una funcionalidad que permita a los analistas modificar los datos de operaciones ya evaluadas y recalcular automáticamente el riesgo de acuerdo con la nueva información.
- **Entregable**: 
  Módulo que incluye la posibilidad de modificar operaciones previas y recalcular los resultados de riesgo. Documento de usuario que explica el proceso de modificación y recalculo.
- **Viabilidad**: 
  Esta funcionalidad permitirá ajustar evaluaciones de forma eficiente, reduciendo la carga de trabajo manual y asegurando la precisión de las reevaluaciones.
- **Producto**: 
  Código que permite modificaciones y reevaluaciones en tiempo real, adaptándose a cambios en los datos de los prestatarios.

---

### Hito 4: Filtrado de Operaciones
- **Descripción**: 
  Implementar un sistema de filtrado automático que priorice las operaciones según su nivel de riesgo, permitiendo a los gestores enfocarse en las más urgentes y críticas.
- **Entregable**: 
  Módulo de filtrado integrado en la aplicación, con la capacidad de mostrar automáticamente las operaciones de mayor riesgo. Documento de usuario que detalla cómo usar los filtros y priorizar operaciones.
- **Viabilidad**: 
  El sistema de filtrado permitirá reducir el tiempo de respuesta ante operaciones críticas, mejorando la eficiencia en la gestión del riesgo.
- **Producto**: 
  Código con un sistema de filtrado avanzado que prioriza las solicitudes de acuerdo con los niveles de riesgo definidos.

