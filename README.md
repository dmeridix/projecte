DAM:
La aplicacion esta dividida en tres usuarios, la cuenta del alumno, la del professor y la del administrador. Cada tipo de cuenta tiene unas limitaciones y unas funciones actividas. El objectivo de la aplicación por parte del alumno es consultar en cualquier momento sus marcages, sus atrasos, su información personal. El objectivo por parte del profesor es consltar su infrmacion personal, sus grupos, pasar lista de los alumnos, crear un horario para el y/o subir un horario mediante archivo excel.

1. Al iniciar sesion en la aplicacion con una cuenta de un alumno lo que primero vera el usuario es un calendario donde se veran reflejados los dias que ha tenido un atraso o una abscencia que estara marcado en rojo, a continaucion vera la inforamcion personal que esta registrda en la base de datos. En el menu de la parte superior de la aplicacion tiene dos botones.
  ![image](https://github.com/user-attachments/assets/28a1886b-1515-4eab-b97d-50e86c9f3875)

  1.1. Marcage
   En este apartado del alumno puede consultar sus margaces donde le muestra la fecha y hora del marcage y el ID del marcage que es la tarjeta RFID o el chip RFID (cada tarjata o chip tiene un id diferente)
   ![image](https://github.com/user-attachments/assets/c6b99d87-2b4b-47ba-ad7d-040d00d71612)

2. Al iniciar sesion en la aplicacion con una cuenta de un profesor lo primero que vera es una tabla de sus grupos donde puede ver su assitencia, en la tabla se muestra el id del grupo, el nombre y la aula que tiene asignada, finalmente s emuestrala información personal del profesor. En el menu de la parte superior contiene dos botones, uno para passar lista y otro para ver sus horarios.
  ![image](https://github.com/user-attachments/assets/4b714e26-9509-4a8a-a61a-61eea5a81c6e)

  2.1. Pasar lista
   En este apartado del professor puede passar lista sobre los alumnos de la clase que tiene selcionada en el desplegable de arriba, esta lista funciona como un scroll dependiendo de la cantodad de alumnos que haya en al clase. Finalmente tiene dos botones en la parte inferior donde uno es para modificar la lista ya pasada y el otro para guardarla
   ![image](https://github.com/user-attachments/assets/323ae17e-3b4c-4692-b300-f4088520df1d)
   
  2.2. Horarios
   En este apartado del profesor puede ver su horario que esta implementado como una tabla que contiene la hora, el nombre del curso y el ID del curso. A parte de visualiar su horario tambien puede subir su horario mediante un archivo de excel que se guardara en el servidor, si no le da al boton de guardar no se guadara el horario.
   ![image](https://github.com/user-attachments/assets/4ff6d7c3-4762-463e-b155-53cfd36c5df0)
   
3. Al iniciar sesion en la aplicaicon con una cuenta de un administrador loprimero que se vera es un tabla con todos los marcages más recientes implementado con una tabla que muestra el id y la fecha del marcage. En el menu de la parte superior de la aplicacion tiene tres botones.
  ![image](https://github.com/user-attachments/assets/335c63d3-7557-4a94-a27b-5063feeac273)

   3.1 Editar marcage o modificar
   En este apartado del administrador puede editar el estado de los marcages si tienen algun algun atraso, abscencia o presencia. A parte de estaas funciones puede notificar al alumno en el caso de exceso de abscencias o atrasos, si no se acciona el boton de guardar no se guardaran las modificaciones o notificaciones.
   ![image](https://github.com/user-attachments/assets/84615e49-46ff-41ea-90e0-437be3f863f3)

   Las demas funcionalidades de los botones son las mismas explicadas anteriormente 
