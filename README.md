# prueba-infolaft

1. Generar el jar mvn clean install

2. Ejecutar docker-compose up 

3. Ejecutar para llenar los estados 
   INSERT INTO public.estado (estado_id,nombre_estado) VALUES
      (1,'COMPLETADA'),
      (2,'PENDIENTE');

4. http://localhost:9000/swagger-ui/index.html swagger 
5. http://localhost:9000/ el front 
6. la collecion de postman para que pruebe los end point
7. se crearon pruebas unitarias de la capa servicio en backend
