# Instalacion de Moodle con docker con el Equipo6

## Moodle y dependencias
- Instalacion con docker-compose
- Si no esta instalado el docker compose podemos obtenerlo mediante  el siguiente comando:
   
```bash
sudo apt install docker-compose
``` 
# Procedimiento
## Paso 1) Clonar el repositorio

1. Clonar el repositorio al directorio local de instalación
    git clone https://github.com/Davidxdpee/DockerComposeEquipo6

![Moodle-Screen01](fotos/01_Clone.png)

## Paso 2) Correr Moodle

1. Para correr los contenedores

```bash
cd DockerComposeEquipo6
``` 
    
![Moodle-Screen02](fotos/02_Change.png)

    docker-compose up -d

![Moodle-Screen03](fotos/03_Run.png)

  - Para comprobar que los contenedores esten funcionando correctamente podemos usar:
```bash
docker-compose ps
``` 

![Moodle-Screen04](fotos/04_CheckRun.png)

2. Para detener los contenedores
```bash
docker compose down
``` 

![Moodle-Screen05](fotos/05_Stop.png)

# Paso 3)Login en Moodle
1. Credenciales Admin
  - http://localhost/
  - Username: `user`
  - Password: `bitnami`

2.- Damos click en Login e ingresamos las credenciales para entrar al modo administrador

![Moodle-Screen06](fotos/06_Login.png)

3.- Como podemos observar ya estariamos logueados

![Moodle-Screen07](fotos/07_Login2.png)

# Paso 4)Creacion de un curso
1. Habilitamos el modo edicion

![Moodle-Screen08](fotos/08_Edicion.png)

  - De esta forma se veria con el modo de edicion activo

![Moodle-Screen09](fotos/09_EdicionActivo.png)

2. Accedemos al apartado "Mis cursos"

![Moodle-Screen10](fotos/10_Cursos.png)

3. Le damos click a los 3 puntos y despues "Nuevo Curso"

![Moodle-Screen11](fotos/11_NuevoCurso.png)

4. Rellenamos los campos necesarios

![Moodle-Screen12](fotos/12_CreandoCurso.png)

5. Confirmamos los datos y le damos en guardar

![Moodle-Screen13](fotos/13_GuardarCurso.png)

6. Nos mandara dentro del curso donde ahora podemos agregar las actividades y demas propias que pueda contener nuestro curso

![Moodle-Screen14](fotos/14_CursoCreado.png)

7. Si regresamos al apartado de "Mis cursos" podemos observar todos los cursos existentes (Aqui deberiamos visualizar el que acabamod de crear)

![Moodle-Screen15](fotos/15_Cursos.png)
