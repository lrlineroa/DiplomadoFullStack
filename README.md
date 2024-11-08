# Bienvenidos al Diplomado Fullstack

## Herramientas a Instalar

 *[Chocolatey](https://chocolatey.org/)
* Visual Studio Code 

```sh
# Para instalar Visual Studio Code usando Chocolatey, ejecuta el siguiente comando:
choco install vscode
```

* GIT 

```sh
# Para instalar Visual Studio Code usando Chocolatey, ejecuta el siguiente comando:
choco install git.install
```

## GIT

### Comandos útiles en git

```sh
# Para instalar Visual Studio Code usando Chocolatey, ejecuta el siguiente comando:
git add . ##Pasa todos los cambios de los archivos del WD al stage
git add <file-name> ## Pasa al stage sólo los cambios del archivo indicado

git commit -m "mensaje para el commit" ## Añade los cambios que esten en el stage al repositorio.

git status ## Nos permite visualizar el estado de git que cambios hay en los árboles mencionados más adelante

git log ## Muestra todos los commits que se llevan hasta ahora

git log --oneline ## Muestra una versión simplificada del registro de los commits

```


En git existen 3 arboles.

![alt text](image.png)

Para crear un repositorio, hacemos una carpeta y en la terminal de esa carpeta ejecutamos el siguiente comando

```sh
# Para instalar Visual Studio Code usando Chocolatey, ejecuta el siguiente comando:
git init
```

Esto nos creara un repositorio vacío en la carpeta .git dentro de nuestra carpeta, de esta manera podremos comenzar a gestionar nuestros archivos con Git

### Ciclo de vida de los cambios de un archivo

![alt text](image-1.png)

### Pasar archivos entre árboles

![alt text](image-2.png)


### Pregunta ¿Qué pasa si yo tengo un cambio de un archivo en el staging y modifico el mismo archivo?

### Ignoremos archivos

### Veamos los commits

* ejecutamos

```sh
# Para instalar Visual Studio Code usando Chocolatey, ejecuta el siguiente comando:
git log
```

miremos la información completa de los commits

* ejecutemos 

```sh
# Para instalar Visual Studio Code usando Chocolatey, ejecuta el siguiente comando:
git log --oneline
```
miramos la versión compacta de los commits


### Desarrollo Quiz

https://www.w3schools.com/quiztest/quiztest.asp?qtest=GIT

### Minitaller

* Crear dos archivos más y comencemos a pasar sus cambios entre los repositorios (tip) usar el git status para ver que está pasando


### Branching