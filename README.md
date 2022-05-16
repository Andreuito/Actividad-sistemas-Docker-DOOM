# Actividad-sistemas-Docker-DOOM

## Primero descargamos el doom y luego lo descomprimimos con el comando 'tar -vzxf dockerdoomd.tar.gz'

## Luego con los permisos de root ejecutamos el siguiente comando 'for i in {1..2} ; do docker run -d -t ubuntu:14.04; done' para crear los 2 contenedores
![image](https://user-images.githubusercontent.com/91564971/168660504-d0a463b7-a04c-4fb2-875c-6b0c09eb1055.png)

## Una vez hecho comprobamos que esta todo correcto y en la siguiente imagen podemos ver que si
![image](https://user-images.githubusercontent.com/91564971/168660774-04f25bfd-8b07-40bf-8bff-80c24c4a31e2.png)

## Una vez situados en la carpeta donde se encuentra el doom lo ejecutamos con el siguiente comando './dockerdoomd', veremos que esta disponible en el puerto 5900
![image](https://user-images.githubusercontent.com/91564971/168661005-3f53128a-1203-468e-9544-21b8673bb5a7.png)
 
 ## En este caso he usado Remmina con VNC y poniendo 'localhost:5900' entraremos dentro del juego.
 ![image](https://user-images.githubusercontent.com/91564971/168661247-37c20351-20c7-482f-87fd-aacfd6706398.png)

## Por ultimo paso nos queda jugar al doom
![image](https://user-images.githubusercontent.com/91564971/168661331-01f65bfd-ae1b-420d-841d-620f02ec5c75.png)

