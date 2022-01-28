Titulo: Transacciones en SQL

  (Ejecutar estas instrucciones en SQL PLUS)
  
  Requerimientos
1. En una nueva base de datos llamada unidad2-oracle, debemos cargar el archivo
unidad2-oracle.sql .

2. El cliente usuario01 ha realizado la siguiente compra:
● Producto: producto9 .
● Cantidad: 5.
● Fecha: fecha del sistema.
Utiliza lo que aprendiste sobre transacciones para almacenar los hechos que ocurrieron en
este punto. Luego, comprueba los resultados mediante otra consulta, enfocando nuestra
atención en el valor del stock, es decir, podremos ver si fue efectivamente descontado.

3. El cliente usuario02 ha realizado la siguiente compra:
● Producto: producto1, producto2, producto8.
● Cantidad: 3 de cada producto.
● Fecha: fecha del sistema.
Mediante el uso de transacciones, realiza las consultas correspondientes para este
requerimiento y luego consulta la tabla producto para validar que si alguno de ellos se queda
sin stock, no se realice la compra.

4. Realizar las siguientes consultas:
A. Deshabilitar el AUTOCOMMIT.
B. Insertar un nuevo cliente.
C. Confirmar que fue agregado en la tabla cliente.
D. Realizar un ROLLBACK.
E. Confirmar que se restauró la información, sin considerar la inserción del punto b.
F. Habilitar de nuevo el AUTOCOMMIT.
