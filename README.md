Instrucciones
========================================
Instalar Java 8
Instalar Git
Puerto 8080



Clonar repositorio
--------

```sh
git clone https://gitlab.com/jan_carlo/backend.git
```

Ejecutar
--------

```sh
cd spring-boot-sample
```
Linux
```sh
./gradlew bootRun
```
Windows 
gradlew.bat bootRun


Acceder
--------

### Select

```
http://127.0.0.1:8080/libros
```

JSON Response:

```json
[{"id":100,"nombre":"nombre 2","autor":"autor 2","paginas":120,"editorial":"editorial 2","img":"img","activo":true},{"id":101,"nombre":"nombre","autor":"autor","paginas":100,"editorial":"editorial","img":"img","activo":true}]
```


