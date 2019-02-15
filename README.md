# Laboratorio1-Trading
ITESO, UNIVERSIDAD JESUITA DE GUADALAJARA

INGENIERÍA FINANCIERA
MICROESTRUCTURA Y SISTEMAS DE TRADING
Laboratorio 1

Problema: La idea es replicar un ETF con posiciones en directo. Te han asignado la tarea de hacer un ejercicio simple de replicar la construcción de un portafolio de inversión y un criterio de rebalanceo lo más parecido a un ETF de ishares que tus selecciones. Esto con la finalidad de comparar los resultados de haber rebalanceado periódicamente el portafolio, ó, no haberlo hecho y continuar todo un año con las mismas posiciones. 
Debido a tu formación, te piden que este proceso que construyas sea repetible para cualquier ETF y también incluir 3 medidas de atribución al desempeño, tanto para el caso que el ETF nunca hubiese sido rebalanceado como para los casos donde sí. 
En la mesa de análisis están interesados en conocer el proceso que sigues para adquirir, limpiar, dar formato y utilizar los datos, y a pesar de que el equipo senior de análisis está compuesto por personal altamente calificado en temas de economía y finanzas, ellos no saben programar por lo que te piden que incluyas el código utilizado, y que sea de manera ordenada y explicando el sentido de las funciones y paqueterías que requeriste. 
Solución al problema:
Lo primero que realizamos fue seleccionar un ETF de USA, llamado US Technology, el cual contiene 160 activos aproximadamente, las cuales son acciones que cotizan en las bolsas americanas. Después analizamos si existe una mejor opción, o rendimiento el cual lo realizamos observando si realizando o no modificaciones a los rebalanceos que se hacen de forma mensual, y así poder comparar si alguna de las 12 trayectorias (ya que son 12 meses), obtuvo mejores resultados que como ellos la manejaron.
El plan de trabajo que seguimos fue el siguiente:
•	Elegir un ETF que cotice en EE. UU. en iShare (el cual fue U.S. Technology ETF)
•	Descargar archivos de datos históricos del ETF. – Esto con el objetivo de conocer sus acciones, participaciones, precios, fechas.
•	Replicar el ETF haciendo rebalanceo mensualmente, y como segundo escenario dejar las mismas proporciones de acciones de hace un año para contrastar los rendimientos.
•	Calcular medidas de desempeño: rendimientos, riesgo (desviación estándar), Sharpe Ratio y Alfa Jensen.
•	Hacer un cuadro comparativo entre las medidas mencionadas en el punto anterior y las trayectorias.
Resultados:
U.S. Technology ETF
 

El Sharp Ratio mide la prima de riesgo del ETF por unidad de riesgo (volatilidad), representa la pendiente de la recta que une el rendimiento del activo libre de riesgo y el fondo. Su resultado permite determinar cuáles fondos han logrado batir al índice de referencia o benchmark y cuáles han sido superados por este. Por otro lado, el alfa Jensen se puede entender como el exceso de rendimiento del fondo que un inversionista esperaría recibir en el mismo si el exceso de rendimiento del mercado (sobre el activo libre de riesgo) hubiese sido igual a cero. Por falta de tiempo no se logró calcular esta última medida.
Finalmente, en base al análisis de la tabla mostrada como resultado se puede concluir que el ETF represento mejores rendimientos y medidas de desempeño cuando este se rebalanceo, aunque estos rendimientos no tengan un crecimiento significativo contra el rendimiento de no rebalanceo del portafolio es decir: permanecer con las mismas acciones con ciertos pesos.
