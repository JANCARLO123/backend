Instrucciones
========================================
```sh
Instalar Java 8
Instalar Git
Puerto 8080
```


Clonar repositorio
--------

```sh
git clone https://github.com/JANCARLO123/backend.git
```

Ejecutar
--------

```sh
cd backend
```
Linux
```sh
./gradlew bootRun
```
Windows 
```sh
gradlew.bat bootRun
```

Acceder
--------

### Prueba

```
http://127.0.0.1:8080/libros
```

JSON Response:

```json
[{"id":100,"nombre":"nombre 2","autor":"autor 2","paginas":120,"editorial":"editorial 2","img":"img","activo":true},{"id":101,"nombre":"nombre","autor":"autor","paginas":100,"editorial":"editorial","img":"img","activo":true}]
```


