# despligue_app

Ponemos pwd para ver en que directo nos encontramos
![image](https://user-images.githubusercontent.com/91167870/205785048-c65d7cc4-eb16-4daa-9adb-54acc0a387cf.png)

Ponemos el comando vi docker-compose.yml para verificar el codigo que copiamos (para guardar y salir ponemos ------> wq )
![image](https://user-images.githubusercontent.com/91167870/205785329-0a536d43-2441-440b-b1df-5aa3c84b997e.png)


Ponemos el comando docker ps para ver los contenedores que tenemos ya creados
![image](https://user-images.githubusercontent.com/91167870/205784820-c1f2f4b4-a8dd-4509-b5c5-07e08eb0d164.png)

Colocamos el comando cat docker-compose.yml 
![image](https://user-images.githubusercontent.com/91167870/205785469-778b847d-2596-43eb-ba25-3791235a61a9.png)

Colocamos el comando docker-compose up -d (sirve para descargar las librerias, si ya estan cargadas nos salen que ya estan corriendo)
![image](https://user-images.githubusercontent.com/91167870/205785646-13f34e2d-24b4-479a-826f-1ce0da72fb11.png)

Clonamos el repositorio  con  (git clone https://github.com/maguaman2/tendencias-mar22-security) 
![image](https://user-images.githubusercontent.com/91167870/205785889-d9e0f4eb-aea7-455e-916d-5487a269ee70.png)

Colocamos un ls para ver los directorios que disponemos
![image](https://user-images.githubusercontent.com/91167870/205786008-32263b4d-941a-4a71-9a45-c9d1d0ea63d0.png)

Creamos un documento llamado Dockerfile (vi Dockerfile)
![image](https://user-images.githubusercontent.com/91167870/205786259-d0b58b88-413d-4f43-a8a2-065c84facbca.png)

Colocamos el comando docker build -t myapp .
![image](https://user-images.githubusercontent.com/91167870/205786793-757d90be-0b51-49c9-b25b-fcf4c51bf99e.png)

Colocamos el comando (docker run -d --network db_default -p 8081:8081 myapp) y verificamos en localhost:/users y nos deberia salir la tabla
![image](https://user-images.githubusercontent.com/91167870/205788202-fe4ec087-aa37-4611-9500-3dcf1f2d08d1.png)

                                                         Aplicacion FrontEnd
 Vamos a la carpeta local y colocamos lo siguiente
 Colocamos el comando de (git clone git clone https://github.com/maguaman2/securityfe ) 
 ![image](https://user-images.githubusercontent.com/91167870/205789766-19abef2f-d9dd-4efd-8e01-4c6d643bb96b.png)
 
 Colocamos un ls para ver si se clono el repositorio ( ls )
 ![image](https://user-images.githubusercontent.com/91167870/205789866-8bb7c5a5-e78a-488b-887b-a933c4c54187.png)

 Entramos en el nuevo gitclone y creamos un vi Dockerfile
 ![image](https://user-images.githubusercontent.com/91167870/205789999-bb59af91-5864-4278-be03-6ec7c523806e.png)

 Colocamos el comando (docker build -t myappfe:latest .) para crear una imagen
 ![image](https://user-images.githubusercontent.com/91167870/205790176-41fbfc7a-778a-4504-be2b-dd4c3b456bba.png)

