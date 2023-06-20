# Diccionario de datos

## Base de datos 1

**Los datos del caso están disponibles en formato CSV con 6362620 filas y 10 columnas.

| Variable | Descripción | Tipo de dato | Rango/Valores posibles | Fuente de datos |
| --- | --- | --- | --- | --- |
| step | Unidad de tiempo en el mundo real, en este caso 1 step es 1 hora. | int | 1-743 | CSV |
| type | Tipo de transacción | String | [CASH-IN, CASH-OUT, DEBIT, PAYMENT, TRANSFER] | CSV |
| amount | Cantidad de la transacción en dólares| float | 0-100000000 | CSV |
| nameOrigi | Cliente que inició la transacción | String | Nombre de usuario | CSV |
| oldbalanceOrg | Saldo antes de la transacción | float | 0-60000000 | CSV|
| newbalanceOrig | Nuevo saldo después de la transacción | float | 0-50000000 | CSV |
| nameDest | Nombre del destinatario | String | Nombre usuario | CSV |
| oldbalanceDest | Saldo antes de la transacción del destinatario | float | 0-400000000 | CSV|
| newbalanceDest | Nuevo saldo después de la transacción del destinatario | float | 0-400000000 | CSV |
| isFraud | La transacción es fraudulenta | int | 0-1 | CSV|
| isFlaggedFraud | Intento fraudulento de transacción, en este caso es cuando se quiere transferir más de 200000 en una transacción  | int | 0-1 | CSV |

- **Variable**: nombre de la variable.
- **Descripción**: breve descripción de la variable.
- **Tipo de dato**: tipo de dato que contiene la variable.
- **Rango/Valores posibles**: rango o valores que puede tomar la variable.
- **Fuente de datos**: fuente de los datos de la variable.



