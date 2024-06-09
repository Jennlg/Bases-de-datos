La base de datos se descarga del siguiente tablero
http://sinaiscap.salud.gob.mx:8080/DGIS/GenerarTabla?titulo=Defunciones%20por%20sexo%20por%20a%F1o&href=/tablero/defunciones/defunciones_sexo_porentidad/1998-2022_defunciones_sexo_porentidad.xlsx&ruta=/tablero/defunciones/defunciones_sexo_porentidad/1998-2022_defunciones_sexo_porentidad.xlsx&hoja=Nacional&adicionalesTitulo=NACIONAL

Primero cargar la tabla de datos a MySQL (OJO: Debe estar en formato .csv, delimitado por punto y coma, y enclose strings=" y únicamente la primera hoja llamada 'Concentrado')

Para poder implementar el código es necesario instalar las siguientes dependencias de python
!pip install mysql-connector-python matplotlib pandas


