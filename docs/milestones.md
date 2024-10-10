## Hitos del Proyecto

### Hito 0: Fundamentos del proyecto
- **Descripción:** Investigar las tecnologías que se emplearán en el desarrollo del sistema de evaluación de riesgos financieros, así como determinar las fuentes de datos relevantes para la automatización de cálculos de riesgo.  
- **Entregables:** Informe sobre las tecnologías seleccionadas, requisitos necesarios para el uso y desarrollo de la plataforma, y fuentes de datos disponibles, así como el código correspondiente con la estructura de la aplicación.  
- **Viabilidad:** Este hito es crucial para elegir las tecnologías adecuadas y obtener requisitos claros que guiarán el desarrollo del proyecto. Se realizará un análisis de riesgo asociado a la implementación de cada tecnología.
- **Producto:** Generar un prototipo simple o un esquema que represente la arquitectura del sistema, aunque sea en papel o como un diagrama digital, para visualizar la solución.
- **Criterios de viabilidad:** 
  - Identificar y documentar las tecnologías que cumplen con los requisitos de seguridad y escalabilidad.
  - Se evaluará la integración de datos mediante pruebas de conectividad a las fuentes de información.
- **HU asignadas**: [HU1],[HU2],[HU3],[HU4]

---

### Hito 1: Cálculo automático del riesgo financiero
- **Descripción:** Desarrollar un módulo que realice el cálculo automático del riesgo de las operaciones financieras, alineado con los criterios establecidos por el Banco de España.  
- **Entregables:** Módulo encargado de la automatización del cálculo de riesgo 
- **Viabilidad:** La creación de un cálculo automático que cumpla con las regulaciones es clave para la funcionalidad del sistema. En esta fase, aún no hay una interfaz de usuario, por lo que el enfoque está en la lógica de negocio y el cálculo en sí.  
- **Producto:** Aplicación básica (Beta). Aunque el producto es funcional en términos de cálculo, no hay una interfaz directa para que el usuario interactúe con él.
- **HU asignadas**: [HU1]

---

### Hito 2: Modificación de los parámetros del cálculo de riesgos
- **Descripción:** Implementar un módulo que permita a los gestores de operaciones financieras modificar las ponderaciones de los parámetros. Además deberá ser manejado mediante una interfaz funcional que permita hacer esto sin tener que acceder al código del sistema. 
- **Entregables:** Módulo de gestión de lógica de riesgos. 
- **Viabilidad:** Poder editar los valores de la función interna con la que trabaja el sistema es crucial, puesto que los ratios de pago de los parámetros van a ser modificados periódicamente. Este hito se centra en asegurar que no sea necesario modificar el código fuente de la aplicación, ofreciendo además una interfaz mucho más intuitiva de cara al usuario.  
- **Producto:** Aplicación con las funcionalidades básicas y mucho más modificable de manera segura, facilitando un uso más intuitivo por medio de una cómoda interfaz de usuario.
- **HU asignadas**: [HU2],[HU3],[HU4]
 

