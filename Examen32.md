# Enunciado del ejercicio práctico de EGC para el turno de las 16:30.
***
* Los alumnos que hayan decidido optar por el itinerario de **instensificación colaborativa**, deben realizar únicamente los apartados de cada ejercicio marcados en este itinerario.
* Los alumnos que hayan decidido optar por el itinerario de **balance técnico-organizativo**, deben realizar los apartados de los ejercicios marcados como relativos a los itinerarios intensificación colaborativa y balance técnico-organizativo.
* Los alumnos que hayan decidido optar por el itinerario de **intensificación técnica**, deben realizar todos los ejercicios y todos los apartados de todos los itinerarios.

## IMPORTANTE
* Los ejercicios se realizarán desde los ordenadores del aula de prácticas y se permite la consulta de la wiki de la asignatura y de apuntes en formato físico. En GitHub, sólo se permite el acceso al repositorio del examen. En ningún caso se permitirá acceder a otros recursos externos o repositorios. 

* Realice los cambios en orden secuencial. 

* Se deberá tomar un screenshot después de cada uno de los pasos que estén indicados con el icono :camera:, mostrando la salida de la consola y el comando introducido. En el caso de herramientas gráficas o de herramientas web, se tomarán las capturas de pantallas de las mismas. 

* Una vez terminado el ejercicio:
	* Cree un .zip de la carpeta local del repositorio. Asegúrese de incluir la carpeta .git.
	* Cree una carpeta screenshots donde almacenará las capturas de pantalla que las llamará X.Y siendo X el ejercicio e Y el punto en el que esta, por ejemplo A.03
	* Cree un fichero README.txt donde incluya la url del fork realizado y la url de la aplicación de Render si procede.
	* Comprima todo en un zip con el nombre turno32-uvus.zip

* Posteriormente se subirán las entregas al directorio de [HDVirtual](https://hdvirtual.us.es/discovirt/index.php/s/SFCmgsSLSoY2Zjk) indicado en el hiperenlace.

**La modificación de cualquier contenido del repositorio (wiki, issues o código) una vez entregado el examen implicará el suspenso del alumno. Antes de dejar la sala de la prueba, avisar al profesor para verificar que todo está correctamente enviado.**

## Ejecicio A (GIT)
### Intensificiación colaborativa
1. Realice un fork de este repositorio con el nombre EGC2324-turno32-"uvus".
2. Clone el repositorio del cual ha hecho el fork. :camera:
3. Cree una nueva rama llamada egc_test en el repositorio. 
4. "Salte" a la rama recien creada. :camera:
5. En el código de DECIDE del repositorio existe un error. Identifique el error ejecutando en su máquina el código.
6. Cree una "issue" en el fork del repositorio para reportar el error según lo visto en clase. :camera:
7. Realice las modificaciones necesarias para corregir el error y haga commit de los cambios en la rama egc_test. 
8. Mediante una pull request, fusione en la rama master/main del repositorio los cambios de la rama de egc_test y asocielo a la issue anterior. :camera:
9. Refleje los cambios del repositorio local en el repositorio remoto que creó en el primer paso. 

### Balance técnico-organizativo
10. Cree una rama rv1 y haga tres cambios en el fichero decide/visualizer/templates/visualizer/visualizer.html, de manera que cada cambio sea un commit diferente. :camera:
11. Deshaga los dos últimos cambios de manera soft. :camera:

### Intensificación técnica
12. Realice un cambio en una línea del README.md. Genere un parche con este cambio. :camera:
13. Cambie a una rama diferente y aplique el parche en esa rama. :camera:
14. Haga commit de los cambios realizados. :camera:

## Ejercicio B (GITHUB ACTIONS)
### Intensificiación colaborativa
1. Modifique el workflow django.yml para que utilice la versión de postgres 15. :camera:
2. Prepare el workflow para que en lugar de ejecutarse sobre la última versión de ubuntu, lo haga explícitamente sobre la versión 22.04. :camera:
3. Haga commit y push de los cambios realizados. :camera:
4. Verifique el correcto funcionamiento del workflow. :camera:

### Balance técnico-organizativo
5. Configure el workflow django.yml para lanzar las pruebas con dos versiones de python diferentes (3.10.12 y 3.11). :camera:
6. Haga commit y push de los cambios realizados. :camera:
7. Verifique el correcto funcionamiento del workflow. :camera:

### Intensificación técnica
8. Configure DECIDE para generar releases automáticas mediante el uso de workflows. :camera:
9. Haga commit y push de los cambios realizados.
10. Verifique que se ha creado una release. :camera:

## EJERCICIO C (DOCKER)
### Intensificiación colaborativa
1. Realice los cambios necesarios en los archivos de docker para que despliegue este repositorio. :camera:
2. Haga commit de los cambios realizados. :camera:

### Balance técnico-organizativo
3. Realice los cambios necesarios en la configuración de docker para que el servicio web lanzado mediante docker compose utilice 4 workers de gunicorn. :camera:
4. Haga commit y push de los cambios realizados. :camera:

### Intensificación técnica
No hay nuevos apartados.

## EJERCICIO D (VAGRANT)
### Intensificiación colaborativa
1. Realice los cambios necesarios en los archivos de Vagrant para que despliegue este repositorio. :camera:
2. Haga commit de los cambios realizados. :camera:

### Balance técnico-organizativo
3. Realice los cambios necesarios para que DECIDE se despliegue con Vagrant y sea accesible desde el sistema host en el puerto 8081. 📷
4. Haga commit y push de los cambios realizados. 📷

### Intensificación técnica
No hay nuevos apartados.

## EJERCICIO E (RENDER)
### Intensificiación colaborativa
No hay nuevos apartados.

### Balance técnico-organizativo
No hay nuevos apartados.

### Intensificación técnica
1. Realice los cambios necesarios para desplegar DECIDE en Render mediante el ciclo de integración y despliegue continuos. :camera:
2. Haga commit y push de los cambios realizados. :camera:


