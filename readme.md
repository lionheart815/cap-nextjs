<p align="center">
  <a href="#" target="_blank">
    <img alt="Curso de Next.js" src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/8e/Nextjs-logo.svg/1200px-Nextjs-logo.svg.png" width="60" />
  </a>
</p>
<h1 align="center">
  Proyecto del Curso: Next.js
</h1>
<p align="center">

</p>


* [Cómo trabajar en este proyecto?](#-cómo-trabajar-en-este-proyecto)
* [Guía rápida](#-gu%C3%ADa-rápida)
* [Logros](#-logros)
* [Encontraste un error o mejora?](#-encontraste-un-error-o-mejora)

### 🔎 Cómo trabajar en este proyecto?
El curso es totalmente práctico y progresivo. Este repositorio sólo existe como una guía para cuando lo necesites. Puedes realizar todo el curso en tu propio proyecto y tu propio repositorio.

Avanzamos en el curso a un nuevo tema y no puedes o no quieres completar los cambios anteriores para continuar? 
Empieza desde la etiqueta git correspondiente al módulo del curso.


1.  Actualiza la información de las etiquetas:
    
    > Anteriormente debiste clonar este repositorio tal como lo hicimos en clase.

    ```sh
    git fetch --tags
    ```
    

1.  Lista las etiquetas disponibles:

    ```sh
    git tag
    ```
    
    Deberías ver algo como:

    ```sh
    1-lo-basico
    2-inicio-api
    3-api
    ...
    ```

1.  Inicia un nuevo branch desde el punto que desees:

    ```sh
    git checkout -b el-nombre-de-mi-branch etiqueta-elegida

    # Por ejemplo, para iniciar desde el módulo 4-javascript
    git checkout -b john-javascript 4-javascript
    ```

    Eso es todo, ya puedes iniciar con todos los cambios incluídos hasta ese módulo. 
    

#### Bonus: Cómo subo mis cambios a otro repositorio?
Git permite manejar varios repositorios remotos en una misma copia local. [Aquí encuentras más información](https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes) y te dejaré el cheatsheet a continuación:
```sh
# Crea tu nuevo repositorio en GitHub/GitLab/otro. 
# Asumamos la URL es git@github.com:john/mi-repo-mas-bello.git
# Agrega el nuevo remote

git remote add mi-repo git@github.com:john/mi-repo-mas-bello.git

# Para push
git push mi-repo branch-a-hacer-push


# Para pull
git pull mi-repo branch-a-hacer-push
```

### 🤖 Guía Rápida

1.  **Empieza a desarrollar.**

    Instala dependencias

    ```sh
    yarn
    ```

    Inicia el proyecto

    ```sh
    yarn dev
    ```

    El sitio estará disponible en http://localhost:3000.


### 🚀 Logros

1. Creación del proyecto
1. Agrego una ruta básica
1. Agrego una ruta dinámica
1. Enlazo páginas y creo una SPA
1. Agrega nuestra propia API
1. Páginas usando nuestra propia API
1. Crea components App and Document personalizados
1. Configura path aliases
1. Crea páginas y componentes UI para el sitio.
1. Crea Store simple usando Context


### 🐞 Encontraste un error o mejora?
Ayuda a otros estudiantes con eso que acabas de descubrir que haría este curso y respositorio mucho mejor.


Happy hacking!
