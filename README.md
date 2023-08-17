# ¿Qué aprendimos esta semana? (Laboratorio Github)
Leonardo Rodríguez
A01029331

### Lunes 14 de agosto
En este día aprendimos basicamente las definiciones basicas de diferentes terminos que no conociamos antes, aprendimos los basicos de GitHub y trabajamos en Git bash en la terminal de nuestra PC asi como creamos un repositorio nuevo. Github es una plataforma creada para alojar el código de las aplicaciones de cualquier desarrollador web y, que como usuario, da la opción de descargarse la aplicación o acceder a su perfil para leer o colaborar en el desarrollo de los diferentes proyectos. (The Bridge Tech, 2022). Al realizar los traspasos de la terminal a Github tuvimos que solicitar varias llaves privadas para proteger nuestra seguridad. Esto lo hicimos intercambiando llaves en el SSH y el 
Aprendimos comandos basicos como ls, o subcomandos como tal como el list all que es "ls -a". La mayoria de comandos empiezan con "git", como por ejemplo al inicio de todo tuvimos que configurar la Terminal de Git Bash con nuestro usuario y correo y en este caso realizamos el comando "git config --global user.name "dasdo" Para el nombre y "git config --global user.email dasdo1@gmail.com" para el email. Este día mas que nada nos permitio conocer los softwares y darnos una idea de como vamos a trabajar los siguientes días.

![Github logo](/Imagenes/GitHub-logo-2-imagen.jpg)

### Martes 15 de agosto
Trabajamos mas en la terminal y aprendimos a trasladar nuestros cambios o modificaciones desde la terminal hacia el repositorio web en github, ademas de actualizar los cambios directamente en ellos y regresar los cambios del repositorio hacia la terminal. Para realizar todo este proceso de transferir nuestro trabajo hacia el repositorio tuvimos que añadir nuevos comandos a nuestros conocimientos donde se encuentran:
- **Iniciamos GIT en la carpeta donde esta el proyecto**
```
git init
```

- **Clonamos el repositorio de github o bitbucket**
```
git clone <url>
```

- **Añadimos todos los archivos para el commit**
```
git add
```

- **Hacemos el primer commit**
```
git commit -m "Texto que identifique por que se hizo el commit"
```

- **Subimos al repositorio**
```
git push u- origin main
```

Luego una vez aprendido a como subir nuestras cosas al repositorio teniamos que aprender a como editarlo directamente desde ahi pero aun mas importante teniamos que aprender a como traer los nuevos cambios del repositorio a la terminal, así que para ello pusimos en practica este comando:

- **Busca los cambios nuevos y actualiza el repositorio**
```

	git pull origin <nameBranch>
```


![alt text](/Imagenes/git%20push.png)

### Miercoles 16 de agosto
No tuvimos esta clase asi que no asistimos.
### Jueves 17 de agosto
Estamos aprendiendo a trabajar en Visual Studio Code en lugar de la terminal para asi mandarlo al repositorio y a la terminal desde este software. Visual Studio Code es un editor potente y en gran parte por las extensiones. Las extensiones nos permiten personalizar y agregar funcionalidad. En esta clase nos pusimos a dar forma y vida a este archivo "README" con diferentes comando de la extensión de Markdown, aplicamos el estilo, la lista es la

![alt text](/Imagenes/visualstudioimg.png)


## Referencias:
1. [¿Qué es Github?](https://www.thebridge.tech/blog/que-es-git-hub#:~:text=Github%20es%20una%20plataforma%20creada,desarrollo%20de%20los%20diferentes%20proyectos)
2. [¿Qué es Visual Studio Code?](https://openwebinars.net/blog/que-es-visual-studio-code-y-que-ventajas-ofrece/)
3. [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

