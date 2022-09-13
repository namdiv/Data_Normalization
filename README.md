# Data Normalization

Una empresa de ventas de productos al público tomo la decision de ser una empresa Data-driven, concepto en el cual los datos son fundamentales a la hora de tomar decisiones.

En principio, la gerencia decidió crear una base de datos, teniendo en cuenta las principales entidades que son las ventas, compras y gastos. Este proceso deberá ser documentado teniendo en cuenta la estructura de las tablas y un diccionario de datos.
Partiendo del trabajo anterior se deberá analizar su calidad con los datos originales, pudiendo asi encontrar valores faltantes, datos incorrectos y outliers. Antes de proceder con esta limpieza, la genrencia solicito un informe ejecutivo que contenga todas las incongruencias de los datos o la mala calidad de los mismos. Luego, se puede proceder a corregirlos o desestimarlos. Este diagnostico de datos es muy importante y necesario para que el proyecto sea un exito, para ello hay que dedicarle tiempo y analisis para hacerlo bien

Algunos ejemplos de como podrían ser los reportes de calidad del datos son los siguientes.




Si bien el negocio considera primordial entender cuál es la evolucion de las ventas, compras y gastos, desde el area de DATOS se pensó que se podría ofrecer una serie de KPIs utiles para ayudar en la toma de decisiones.

Ademas de todo esto, el area encargada de la apertura de nuevas sucursales necesita encontrar, a partir de la sugerencia del area de DATOS, un lugar para establecer una nueva sucursal.
Se contará con una tabla de localidades de la cual será necesario analizar la calidad de los datos y se deberá normalizar la informacion de dicha tabla. Recuerden que hay un algoritmo para hacer una comparacion de palabras que podria ayudar con esta tarea, ya que esta tarea tiene que ser 100% automatica y sin invervencion de nadie

Se cuenta con los siguientes datasets:

Clientes.csv
Compra.csv
Gasto.csv
Localidades.csv
Proveedores.csv
Sucursales.csv
Venta.csv

Es necesario tener en cuenta que hay otro dataset de clientes (Clientes_2.csv) y no se descarta que puedan aparecer otros. Por eso, se deberá contemplar que el proceso incluya mas dataset de clientes y que no haya duplicados. Esto deberia ser automatico, es fundamental pensar en algo robusto para no tener problemas a futuro.

Por ultimo, recuerden que los reportes que se desarrollarán serán para la toma de decisiones ejecutivas ( Directores, vicepresidente y/o presidente de la empresa, etc), por lo tanto es imperativo evitar errores en los mismos.
