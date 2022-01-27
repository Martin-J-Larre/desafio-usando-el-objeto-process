### Motores de plantillas EJS
* La vistas estas siendo mostradas en la ingenieria EJS.
### Middlewares
* ExpressJs
* socket.io
* Normalizr
* nodemon
* Knex (no implementado)
* Faker
* Passport
* Minimist

### Base de datos
* Mongo-Atlas
* Sqlite3
* Mysql (no implentado)

### Para correr el programa
* npm install
* Crear un .env, agregar lo que esta dentro de .env.exaple y colocar en MONGO_URI la url de la base de datos
* Conectar Sqlite3
![alt text](https://raw.githubusercontent.com/Martin-J-Larre/desafio-login-formulario/main/img-video/sqlStudio.JPG)
* npm run dev
* Ir al localhost:8000
## Preview
![alt text](https://github.com/Martin-J-Larre/desafio-inicio-de-sesion-c/blob/main/assets/Login-Google-Chrome-2022-01-24-18-18-54.gif?raw=true)

### Desafío usando el objeto process
## Consigna 1
* Correr el comando en consola > node index.js server por defecto en el puerto 8080
![alt text](https://raw.githubusercontent.com/Martin-J-Larre/desafio-usando-el-objeto-process/main/assets/por-defecto.JPG)
* Correr el comando en consola > node index.js -p #### / ej. -p 8000 , el puerto es otorgado por argumentos en la linea de comando
![alt text](https://github.com/Martin-J-Larre/desafio-usando-el-objeto-process/blob/main/assets/por-comando.JPG?raw=true)
## Consigna 2
* Agregar una ruta '/info' que presente en una vista sencilla los siguientes datos:
![alt text](https://github.com/Martin-J-Larre/desafio-usando-el-objeto-process/blob/main/assets/info.JPG?raw=true)
## Consigna 3
* Sin parametros ej. -------> `http://localhost:8080/api/randoms`
![alt text](https://github.com/Martin-J-Larre/desafio-usando-el-objeto-process/blob/main/assets/tres-a.JPG?raw=true)
* Con parametros ej. -------> `http://localhost:8080/api/randoms?cant=2000`
![alt text](https://github.com/Martin-J-Larre/desafio-usando-el-objeto-process/blob/main/assets/tres-b.JPG?raw=true)
