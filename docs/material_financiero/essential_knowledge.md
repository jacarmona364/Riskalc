# Conocimientos esenciales
Para el desarrollo de este proyecto es esencial manejar una serie de nociones básicas de cara al ámbito económico y de operaciones en finanzas. Por simplicidad, 
nos quedaremos únicamente con la concesión de créditos al cliente, sin diferenciar entre los términos de préstamo y crédito. 
Cuando una empresa de banca ofrece un crédito, lo que hace es prestar una cantidad de capital al cliente que éste tendrá la posibilidad de ir devolviendo a lo largo 
de un tiempo posterior, ateniéndose a un tipo de interés establecido, es decir, pagando una cantidad algo superior al dinero prestado como compensación por el servicio. 
Como es evidente, estas operaciones tienen un riesgo, el riesgo de impago. La empresa no está dispuesta a perder dinero por clientes que no puedan devolverlo, de manera que 
se realiza un estudio de las características y la coyuntura del prestatario. De este modo se puede estimar cuál es la probabilidad de impago en cada caso, para decidir si se 
concede el crédito o no.
En el archivo [scoring.md](https://github.com/jacarmona364/Riskalc/blob/main/Documentación%20Adicional/scoring.md) se recogen una serie de parámetros que se van a tomar en cuenta 
a la hora de realizar ese cálculo. Cada uno de ellos estará ponderado en función de su influencia en el hecho de que se acabe pagando o no, es decir, si el prestatario posee una característica 
que está directamente relacionada con las estadísticas de morosidad (como podrían ser sus ingresos netos o sus deudas pendientes), el riesgo crece y, por lo tanto, sus posibilidades 
para recibir ese préstamo se reducen.

## Algunos términos con los que trabajaremos:
### 1. Préstamo
Un **préstamo** es un acuerdo en el cual una entidad (por ejemplo, un banco o una persona) otorga una cantidad de dinero a otra parte, llamada **prestatario**, bajo la promesa de que será devuelto en un plazo establecido, generalmente con un interés adicional. El monto prestado suele denominarse **capital** y el contrato establece las condiciones, incluyendo el tipo de interés, los plazos de pago y cualquier penalización por incumplimiento.

### 2. Prestamista
El **prestamista** es la persona o entidad que proporciona el dinero o capital en el contrato de préstamo. Este puede ser un banco, una empresa financiera o un individuo. A cambio del dinero prestado, el prestamista espera que el prestatario devuelva el monto junto con un **interés** adicional, que representa el costo del préstamo para el prestatario.

### 3. Prestatario
El **prestatario** es la persona o entidad que recibe el dinero o capital del prestamista bajo las condiciones del contrato de préstamo. Tiene la obligación de devolver el monto recibido más el interés acordado dentro del plazo definido en el acuerdo.

### 4. Interés
El **interés** es la cantidad adicional que el prestatario debe pagar al prestamista, además del capital prestado, como compensación por el uso del dinero durante el tiempo que dure el préstamo. Generalmente, el interés se expresa como un porcentaje del monto prestado (la tasa de interés) y puede calcularse de diversas maneras (interés simple o compuesto).

### 5. Riesgo
En el contexto financiero, el **riesgo** se refiere a la probabilidad de que una inversión o un préstamo no se pague en su totalidad, o que la rentabilidad esperada no se materialice. Para los prestamistas, el riesgo está asociado a la posibilidad de que el prestatario no cumpla con las obligaciones de pago (riesgo de crédito). La evaluación de este riesgo se basa en factores como el historial de crédito del prestatario, sus ingresos, deudas y solvencia.

### 6. Morosidad
La **morosidad** es el incumplimiento en el pago de las cuotas de un préstamo dentro del plazo acordado. Cuando un prestatario no cumple con los pagos, se lo considera **moroso**, y esto puede llevar a sanciones, intereses adicionales, y en algunos casos, la ejecución de garantías asociadas al préstamo.

### 7. Ingresos netos
Los **ingresos netos** son la cantidad de dinero que una persona o entidad recibe después de deducir los impuestos, deudas y otros gastos. En el análisis financiero, los ingresos netos son un factor clave para evaluar la capacidad de un prestatario de cumplir con sus obligaciones de pago, ya que reflejan su solvencia y capacidad de generar flujo de efectivo.

### 8. Deudas
Las **deudas** son obligaciones de pago que una persona o entidad tiene con un tercero. Estas pueden incluir préstamos, tarjetas de crédito, facturas impagas, entre otros compromisos financieros. El nivel de deuda de un prestatario es un indicador importante para evaluar el riesgo de un préstamo, ya que afecta su capacidad de pago.

### 9. Capital
El **capital** es el monto principal que se presta a un prestatario. En términos de préstamo, se refiere a la cantidad de dinero que el prestamista otorga inicialmente al prestatario, sin incluir los intereses. En inversiones, el capital también puede referirse al dinero invertido o comprometido en un proyecto o negocio.

### 10. Compensación
La **compensación** en finanzas puede referirse a diversos mecanismos para equilibrar o ajustar una situación financiera. En el contexto de préstamos, puede implicar el ajuste del saldo de un préstamo en base a devoluciones de productos (en un entorno comercial) o la disminución de una deuda por ciertos factores. También puede referirse a la retribución que un prestatario recibe si realiza pagos anticipados o cumple con ciertas condiciones del préstamo.
