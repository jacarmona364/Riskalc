## User Journeys

### Journey 1: Ana, Analista de Riesgos Financieros
**Contexto**: Una analista de riesgos financieros en una empresa de banca, a menudo, se enfrenta a la dificultad de realizar cálculos de riesgo de manera rápida y precisa, lo que puede retrasar decisiones críticas en la aceptación o denegación de operaciones.

**Recorrido del Usuario:**
1. El usuario accede al sistema y selecciona la opción: "Evaluar operación"
2. Carga la información necesaria de la operación financiera que desea evaluar.
3. El sistema calcula automáticamente el riesgo siguiendo los criterios establecidos por el Banco de España, valorando los [parámetros](https://github.com/jacarmona364/Riskalc/blob/main/Documentación%20Adicional/scoring.md) que se introduzcan en cada caso.
4. El usuario revisa el resultado del cálculo, que se presenta de forma clara y comprensible como un valor discreto.
5. Con la información obtenida, el usuario decide si acepta o deniega la operación.

---

### Journey 2: Luis, Gestor de Operaciones Financieras
**Contexto**: Un gestor de operaciones financieras a menudo se encuentra con discrepancias en los criterios de riesgo aplicados por diferentes empleados, lo que puede llevar a decisiones inconsistentes. Necesita una solución que le elimine estas discrepancias para resolver conflictos rápidamente.

**Recorrido del Usuario:**
1. El usuario accede al sistema.
2. Modifica las ponderaciones manualmente de cada parámetro.
3. El sistema actualiza las operaciones con las que calcula el valor de riesgo final.

---

### Journey 3: Marta, Analista de Riesgos
**Contexto**: Una analista de riesgos necesita modificar los datos de las operaciones en función de factores demográficos como la región y la edad del prestatario. Hacer esto manualmente es tedioso y propenso a errores.

**Recorrido del Usuario:**
1. El usuario accede al sistema y selecciona la opción "Modificar operación"
2. Introduce la información demográfica del prestatario.
3. El sistema ajusta automáticamente los cálculos de riesgo según los datos introducidos pero con los datos de la operación modificados.
4. El usuario revisa el informe final que incluye los cálculos ajustados.

---

### Journey 4: Jorge, Gestor de Riesgos
**Contexto**: Un gestor de riesgos necesita gestionar las operaciones financieras según su nivel de riesgo. Modificar manualmente las ponderaciones de los parámetros de estas operaciones puede ser ineficiente, especialmente con grandes volúmenes de datos.

**Recorrido del Usuario:**
1. El usuario accede el sistema y selecciona la opción "Gestionar evaluación".
2. Define los umbrales de riesgo (alto, medio, bajo) para las operaciones.
3. Modifica los valores de las ponderaciones de los parámetros como estime pertinente.
4. El sistema actualiza automáticamente las operaciones según los umbrales establecidos.
5. El usuario revisa la lista de operaciones que cumplen con el umbral definido.
6. El usuario prioriza las operaciones más riesgosas para su revisión y toma de decisiones rápidas.

