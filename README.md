# EJERCICIOS CON SQL

Una recopilación de ejercicios con SQL.

# STACK

* MySQL Server
* MySQL Workbench

# QUERYS

* CONSULTAS 01 

1. Obtener los datos completos de los empleados.
   
   SELECT * FROM empleados;

2. Obtener los datos completos de los departamentos
    
    SELECT * FROM departamentos;

3. Obtener los datos de los empleados con cargo 'Secretaria'.
   
   SELECT * FROM empleados WHERE cargoE = 'Secretaria';

    otra rpta puede ser así: SELECT * FROM empleados WHERE lower(cargoE) = 'secretaria'; 

4. Obtener el nombre y salario de los empleados.
   
   SELECT nomEmp, salEmp FROM empleados; 

5. Obtener los datos de los empleados vendedores, ordenado por nombre.
   
   SELECT * FROM empleados WHERE lower(cargoE) = 'vendedor' ORDER BY nomEmp; 

6. Listar el nombre de los departamentos
   
   SELECT distinct nombreDpto FROM departamentos; 

7. Obtener el nombre y cargo de todos los empleados, ordenado por salario
   
   SELECT nomEmp, cargoE, salEmp FROM empleados ORDER BY salEmp;
	
## Screenshot

![](screenshoot/consultas-01.jpg)
