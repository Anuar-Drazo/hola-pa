# Actividad: Git y GitHub
 
Curso de Git y Github
 
 
## 1. Que aprendi del video
 
- **Introduccion (#1):** Git es un sistema de control de versiones: guarda el historial de cambios de un proyecto y permite volver a cualquier punto anterior y trabajar en equipo sin pisarse el codigo. GitHub es la plataforma en la nube donde se alojan esos repositorios.
- **Instalacion (#2):** Se instala Git en el equipo y se configura el usuario y el correo que aparecen en cada commit.
- **Primer repositorio y commit (#3):** Con git init se crea un repositorio local. El flujo basico es: modificar archivos, agregarlos al area de preparacion (git add) y guardarlos con un commit (git commit).
- **Stage y logs (#4):** El stage es la zona intermedia donde se eligen los cambios que entraran al siguiente commit. Con git status se ve el estado y con git log se consulta el historial.
- **Git alias (#5):** Los alias son atajos para comandos largos, por ejemplo git st en lugar de git status.
- **Git mv / rm / reset (#6):** Sirven para mover o renombrar archivos, eliminarlos del repositorio y deshacer cambios o commits.
- **.gitignore (#7):** Es un archivo donde se listan los archivos y carpetas que Git debe ignorar (dependencias, archivos temporales, credenciales).
- **Ramas y merge (#8):** Una rama permite trabajar en una funcionalidad aislada sin afectar la rama principal. Luego se unen con git merge.
- **Merge con conflictos (#9):** Cuando dos ramas modifican la misma linea, Git no sabe cual conservar y marca un conflicto. Hay que editar el archivo a mano, elegir el contenido correcto y hacer un nuevo commit.
- **GitHub: subir cambios (push):** Se vincula el repositorio local con uno remoto en GitHub (git remote add origin) y se suben los commits con git push.
- **git clone (#11):** Descarga una copia completa de un repositorio remoto, con todo su historial, a la computadora local.
- **git pull (#12):** Trae los cambios nuevos del repositorio remoto y los integra en el repositorio local.
- **fork (#13):** Crea una copia de un repositorio ajeno en la propia cuenta de GitHub, para poder modificarla libremente.
- **pull request (#14):** Es una solicitud para que el dueno del repositorio original revise e incorpore los cambios hechos en un fork o en una rama.
- **Integracion con IDEs (#15):** Git y GitHub se pueden usar directamente desde NetBeans, Eclipse, IntelliJ y Visual Studio Code, sin depender solo de la terminal.

 
## 2. Dificultades encontradas y como las resolvi
 
- **Dificultad:** No sabia como mergear dos ramas.  
 
- **Dificultad:** Error de autenticacion al hacer git push.  

- **Dificultad:** Git no reconocia mi usuario al hacer el primer commit, tuve que configurar user.name y user.email

- **Dificultad:** La rama principal se llamaba master y en GitHub es main  

## 4. Entrega
 
Se adjunta el archivo PDF de esta actividad.
