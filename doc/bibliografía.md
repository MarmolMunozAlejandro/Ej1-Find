Todas las instrucciones usadas provienen de la Biblioteca de MongoDB :  https://docs.mongodb.com/manual/reference/operator/query/#query-selectors

--Apuntes personales--

Mongo es un sistema de base de datos que no guarda la información en Tablas (como libreoffice) sino en formato JSON (texto)

Servidor > Bases > colección > Documento            -Colección: análogo a las tablas    -Documento: análogo a los registros

- Documentos: descripción de un objeto de la vida real:
 {
 "nombre":"Leonardo",            O en lineal
 "apellido":"Kuffo",             -----------> {"nombre":"Leonardo","apellido":"Kuffo","edad":21}
 "edad": 21
 }