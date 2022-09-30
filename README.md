# EjerciciosBaseDatos
cambio cosas y todo lo que quiera y no hay problema

SELECT provincias.nombre FROM provincias 
  LEFT JOIN clientes 
  ON clientes.codigoProvincia=provincias.codigo
  WHERE clientes.codigoprovincia IS null;