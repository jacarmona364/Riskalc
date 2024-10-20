## Hitos del Proyecto

### Hito 0: Fundamentos del proyecto
- **Descripción:** Investigar las tecnologías que se emplearán en el desarrollo del sistema de evaluación de riesgos financieros, así como determinar las fuentes de datos relevantes para la automatización de cálculos de riesgo.  
- **Entregables:** Informe sobre las tecnologías seleccionadas, requisitos necesarios para el uso y desarrollo de la plataforma, y fuentes de [datos](https://github.com/jacarmona364/Riskalc/blob/Objetivo-1/Documentación%20Adicional/historial_prestamos.xlsx) disponibles, así como el código correspondiente con la estructura de la aplicación.  
- **Viabilidad:** Este hito es crucial para elegir las tecnologías adecuadas y obtener requisitos claros que guiarán el desarrollo del proyecto. Se realizará un análisis de riesgo asociado a la implementación de cada tecnología.
- **Producto:** Generar un prototipo simple o un esquema que represente la arquitectura del sistema, aunque sea en papel o como un diagrama digital, para visualizar la solución.
- **Criterios de viabilidad:** 
  - Identificar y documentar las tecnologías que cumplen con los requisitos de seguridad y escalabilidad.
  - Se evaluará la integración de datos mediante pruebas de conectividad a las fuentes de información.
- **HU asignadas**: [HU1],[HU2]

---

### Hito 1: Cálculo de la Fórmula en Base a Operaciones Pasadas
- **Descripción**: 
  Desarrollar y ajustar la fórmula de cálculo de riesgo utilizando datos históricos de operaciones pasadas. La fórmula deberá considerar [variables](https://github.com/jacarmona364/Riskalc/blob/Objetivo-1/Documentación%20Adicional/scoring.md) como solvencia, renta anual, deudas pendientes y características demográficas de los prestatarios.
- **Entregable**: 
  Módulo de estimación del peso de cada variable, teniendo en cuenta cuánto afecta cada parámetro al pago del préstamo.
- **Viabilidad**: 
  Se utilizarán datos históricos de la empresa para validar la precisión de la fórmula. Se realizará un análisis estadístico para asegurar que la fórmula ofrece resultados consistentes y coherentes.
- **Producto**: 
  Aplicación que genera la fórmula del riesgo ajustada y lista para ser implementada en el sistema automatizado.
- **HU asignadas**: [HU1]

---

### Hito 2: Automatización del Cálculo del Riesgo
- **Descripción**: 
  Implementar la automatización de la fórmula de cálculo de riesgo en la aplicación, permitiendo que los analistas puedan obtener resultados precisos de manera rápida y uniforme, directamente desde el sistema.
- **Entregable**: 
  Versión funcional del módulo con la lógica de cálculo de riesgos integrada, tomará en cuenta las operaciones evaluadas con su resultado real en cada periodo para ajustar la fórmula utilizada. Documentación técnica que detalle la implementación y el uso de la fórmula automatizada.
- **Viabilidad**: 
  La automatización reducirá significativamente el tiempo de evaluación y mejorará la consistencia en las decisiones, cumpliendo con la normativa.
- **Producto**: 
  Aplicación con la capacidad de calcular automáticamente el riesgo de cada operación, utilizando los datos ingresados del prestatario y basada en los pesos de la fórmula extraída con anterioridad.
- **HU asignadas**: [HU1], [HU2]

---

### Hito 3: Modificación de Operaciones Pasadas
- **Descripción**: 
  Desarrollar una funcionalidad que permita a los analistas modificar los datos de operaciones ya evaluadas y recalcular automáticamente el riesgo de acuerdo con la nueva información.
- **Entregable**: 
  Módulo que incluye la posibilidad de modificar operaciones previas y recalcular los resultados de riesgo. Documento de usuario que explica el proceso de modificación y recalculo.
- **Viabilidad**: 
  Esta funcionalidad permitirá ajustar evaluaciones de forma eficiente, reduciendo la carga de trabajo manual y asegurando la precisión de las reevaluaciones.
- **Producto**: 
  Aplicación que permite modificaciones y recalculaciones en tiempo real, adaptándose a cambios en los datos de los prestatarios.
- **HU asignadas**: [HU3]
---

### Hito 4: Filtrado de Operaciones
- **Descripción**: 
  Implementar un sistema de filtrado automático que priorice las operaciones según su nivel de riesgo, permitiendo a los gestores enfocarse en las más urgentes y críticas.
- **Entregable**: 
  Módulo de filtrado integrado en la aplicación, con la capacidad de mostrar automáticamente las operaciones de mayor riesgo. Documento de usuario que detalla cómo usar los filtros y priorizar operaciones.
- **Viabilidad**: 
  El sistema de filtrado permitirá reducir el tiempo de respuesta ante operaciones críticas, mejorando la eficiencia en la gestión del riesgo.
- **Producto**: 
  Aplicación con un sistema de filtrado avanzado que prioriza las solicitudes de acuerdo con los niveles de riesgo definidos.
- **HU asignadas**: [HU4]

