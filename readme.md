# Principales comandos de GIT
![logo GIT](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Git-logo.svg/768px-Git-logo.svg.png)


***
Estos son los principales comandos de GIT con los que hemos trabajado💻📚  
    
Se dividen en los grupos:
- Generales para consola bash
- Por fases:
  - Crear repositorio local i vincular a repositorio remoto
  - Trabajar con el control de versiones
*** 


## Comandos bàsicos para Git Bash
| **Comando** | **Descripción**                        |
|-------------|----------------------------------------|
| clear       |             limpiar consola            |
| pwd         | imprimir ruta local                    |
| ls          | listar contenido del directorio actual |
| cd          | cambiar directorio                     |
| mkdir       | crear directorio                       |
| code ..     | abrir ubicación actual en VS Code      |        

![Imagen consola git bash](https://res.cloudinary.com/vishnupadmanabhan/image/upload/v1491753329/git/original.jpg)
*** 


## Por fases    
### Crear repositorio local i vincular con repositorio remoto
| **Comando**                | **Descripción**                                  |
|:--------------------------:|:------------------------------------------------:|
| _Crear desde el ordenador_ | ----------------------                           |
| git init                   | asociar directorio a repositorio                 |
| git init nombreRepositorio | crear directamente un repositorio                |
| _Crear desde GitHub_       | ----------------------                           |
| get clone "url"            | Clonar un repositorio remoto a nuestro ordenador |
***

### Trabajar con el control de versiones    


🔵 **Mandar cambios del working directory al staging area**          
- git add nombreArchivo ➡ *mandar un archivo al staging area*  
- git add . ➡ *mandar todos los archivos al staging area*  
- git rm --cached archivo ➡ *quitar una archivo del staging area*

🟢 **Mandar cambios del staging area al repositorio local**   
- git commit -m "mensaje" ➡ *mandar un archivo al repositorio local*   

⚠ Este paso no se puede deshacer de forma sencilla     
⚠ El mensaje debe ser descriptivo  

🟠 **Trabajar con el repositorio remoto**  
- git push ➡ mandar cambios del repositorio local al repositorio remoto    
- git pull ➡ recuperar cambios del repositorio remoto hacia el repositorio local   

![Esquema](https://miro.medium.com/max/1204/1*zpvd5fjZAFGsVAEsvMGKxA.png) 