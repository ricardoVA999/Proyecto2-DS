# Proyecto2-DS
# Incumplimiento de pago de tarjeta de crédito
En los años de la pandemia, en los Estados Unidos de América, el comportamiento del uso de tarjetas de crédito ha variado bastante.  El promedio de la deuda de tarjeta de crédito creció en 52% entre el 2020 y el 2019, sin embargo, este porcentaje ha caído significativamente en el 2020(ValuePenguin) (Household Debt and Credit Report, NewYorkFed). El objetivo de este proyecto es crear modelos de aprendizaje automático que permita predecirqué tipo de clientes podrán caer en impago, o no.

Para esto se cuenta con un conjunto de datosque contiene información sobre pagos predeterminados, factores demográficos, datos crediticios, historial de pagos y extractos de cuentas de clientes de tarjetas de crédito en Taiwán desde abril de 2005 hasta septiembre de 2005.
Descripción del Conjunto de datos:
El conjunto de datos tiene la siguiente información:

Hay 25 variables:  
-ID:  ID de cada cliente  
-LIMIT_BAL:   cantidad del crédito otorgado en dólares NT (incluye crédito individual y familiar / suplementario  
-SEX:  Género (1 = masculino, 2 = femenino)  
-EDUCATION:  (1 = estudios de posgrado, 2 = universidad, 3 = bachillerato, 4 = otros, 5 =desconocidos, 6 = desconocidos)  
-MARRIAGE:  Estado civil (1 = casado, 2 = soltero, 3 = otros)  
-AGE:  Edad en años  
-PAY_0:  Estado de reembolso en septiembre de 2005 (-1 = pago debidamente, 1 = retrasoen el pago durante un mes, 2 = retraso en el pago durante dos meses,... 8 = retraso en elpago durante ocho meses, 9 = retraso en el pago durante nueve meses o más)  
-PAY_2:  Estado de reembolso en agosto de 2005 (escala igual a la anterior)  
-PAY_3:  Estado de reembolso en julio de 2005 (escala igual a la anterior)  
-PAY_4:  Estado de reembolso en junio de 2005 (escala igual a la anterior)  
-PAY_5:  Estado de reembolso en mayo de 2005 (escala igual a la anterior)  
-PAY_6:  Estado de reembolso en abril de 2005 (escala igual a la anterior)  
-BILL_AMT1:  Monto de la factura en septiembre de 2005 (dólar NT)  
-BILL_AMT2:  Monto de la factura en agosto de 2005 (dólar NT)  
-BILL_AMT3:  Monto de la factura en julio de 2005 (dólar NT)  
-BILL_AMT4:  Monto de la factura en junio de 2005 (dólar NT)  
-BILL_AMT5:  Monto de la factura en mayo de 2005 (dólar NT)  
-BILL_AMT6:  Monto de la factura en abril de 2005 (dólar NT)  
-PAY_AMT1:  Monto del pago anterior en septiembre de 2005 (dólar NT)  
-PAY_AMT2:  Monto del pago anterior en agosto de 2005 (dólar NT)  
-PAY_AMT3:  Monto del pago anterior en julio de 2005 (dólar NT)  
-PAY_AMT4:  Monto del pago anterior en junio de 2005 (dólar NT)  
-PAY_AMT5:  Monto del pago anterior en mayo de 2005 (dólar NT)  
-PAY_AMT6:  Monto del pago anterior en abril de 2005 (dólar NT)  
-default.payment.next.month:  incumplimiento de pago al mes siguiente (1 = sí, 0 = no)
