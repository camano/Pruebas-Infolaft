# Prueba-infolaft

1. Generar el jar con el siguiente comando  mvn clean install

2. Ejecutar docker-compose up se configuro las imagenes de base de datos y el java que se esta utilizando solo es ejecutar el comando y el proyecto quedaria arriba 

3. Ejecutar para llenar los estados solo faltaria llenar los estados a la tabla 
   INSERT INTO public.estado (estado_id,nombre_estado) VALUES
      (1,'COMPLETADA'),
      (2,'PENDIENTE');

4. http://localhost:9000/swagger-ui/index.html swagger con los end point a consumir
5. http://localhost:9000/  hice build al front y lo añadi al proyecto backend en esa ruta se encontraria las vistas
6. la collecion de postman para que pruebe los end point se encuentra en la raiz del proyecto
7. se crearon pruebas unitarias de la capa servicio en backend me falto crear las pruebas de front pero si he realizado pruebas con angular
