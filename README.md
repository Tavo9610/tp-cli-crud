# Entrega Trabajo Practico C.R.U.D MySQL

## Instrucciones
Para iniciar la ejecucion correr/run "npm install mysql2" luego
para ejecutarlo por consola de Git Bash los siguientes comandos

* node index.js get - GET para obtener todos los usuarios
* node index.js add
* node index.js update
* node index.js delete

## Ejemplos / Tests

* node index.js add pepe pepe@gmail.com pepe123
* node index.js update alex alex@gmail.com alex123 id "'385a9ff3-06c9-4c5c-8e15-681e67afdbbf'"
* node index.js delete id "'385a9ff3-06c9-4c5c-8e15-681e67afdbbf'"

## Metodos disponibles

* _Crear Usuario_    > npm run dev add <username> <email> <password>
* _Actualizar usuario_ > npm run dev update <username> <email> <password> <id>
* _Eliminar usuario_ > npm run dev delete <id>

## Notas

* Node.js debe estar instalado
* MySQL debe estar instalado y en ejecución mientras se ejecuta el proyecto
