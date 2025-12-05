# Ejercicio 3: Elegir un tema de Jekyll y desplegar el sitio en Netlify
## 1. Buscar un tema de Jekyll:
Para buscar un tema de Jekyll, hay que ir a la pagina [jekyllthemes.org](http://jekyllthemes.org/)

![jt](/img/Ejercicio3/jt.png)

Yo he elegido el tema Yet Another Theme (YAT)

![yat](/img/Ejercicio3/yat.png)

## 2. Obtener el tema:
### Hacer fork del repositorio con el tema
Este es el repositorio al que hacer fork

![repositorio](/img/Ejercicio3/repo.png)

![fork](/img/Ejercicio3/fork.png)

### Clonarlo en local
Clonarlo en la maquina local

![clonar](/img/Ejercicio3/clonar.png)

## 3. Configurar el sitio:
Configurar el archivo `_config.yaml`

![_config.yaml](/img/Ejercicio3/_config.yaml.png)

## 4. Personalizar el sitio:
### Inicio:
Para configurar la pagina de inicio del sitio, modificar el archivo `index.html`; Aquí solo he cambiado la imagen de fondo para la pagina de inicio

![index.html](/img/Ejercicio3/index.html.png)

### Acerca de:
Aqui se personaliza la pagina de "Acerca de" en la que viene la información acerca de la pagina y su autor

![about.html](/img/Ejercicio3/about.html.png)

### Todo:
En esta pagina se muestran todos los posts organizados por la fecha de subida, esto ya viene programado con el tema y no hay que hacerlo a mano

![archives.html](/img/Ejercicio3/archives.html.png)

### Categorías:
En esta pagina se muestran todas las categorias con sus respectivos posts, esto ya viene programado con el tema y no hay que hacerlo a mano

![categories.html](/img/Ejercicio3/categories.html.png)

### Tags:
En esta pagina se muestran todas los tags con sus respectivos posts, esto ya viene programado con el tema y no hay que hacerlo a mano

![tags.html](/img/Ejercicio3/tags.html.png)

### Posts:
Para crear los posts, hay que ir a la carpeta '_posts'

![_posts](/img/Ejercicio3/_posts.png)

Dentro de la carpeta se crearán los post como archivos de markdown con el formato de nombre `año-mes-dia-nombre_del_post` como por ejemplo:

![post](/img/Ejercicio3/post.png)

## 5. Subir el sitio a GitHub:
Antes de subir el repositorio primero hay que hacer los commits de todos los cambios que se han hecho en el repositorio si aún no se han hecho con los comandos:

```
git add .
git commit -m "comentario"
```

Despues, se hara el push con el comando:

`git push origin main`

## 6. Desplegar el sitio en Netlify:
Para subir el sitio a Netlify, hay que dirigirse a la pagina [netlify.com](https://www.netlify.com/) 

![netlify1](/img/Ejercicio3/netlify1.png)

Iniciar sesion en GitHub

![netlify2](/img/Ejercicio3/netlify2.png)

Autorizar el acceso

![netlify3](/img/Ejercicio3/netlify3.png)

Crear el proyecto

![netlify4](/img/Ejercicio3/netlify4.png)

Elegir donde esta el repositorio del sitio web

![netlify5](/img/Ejercicio3/netlify5.png)

Seleccionar el repositorio del sitio

![netlify6](/img/Ejercicio3/netlify6.png)

Desplegar el sitio

![netlify7](/img/Ejercicio3/netlify7.png)

Esperar a que se complete el despliegue

![netlify8](/img/Ejercicio3/netlify8.png)

Cuando el sitio termine de desplegarse, ya se podra acceder a traves de la url

![netlify9](/img/Ejercicio3/netlify9.png)

## 7. Sitio web subido en GitHub Pages:
La url de la pagina es esta:

https://jekyll-theme-yat.netlify.app

Este es el aspecto que tiene el sitio web ya subido en GitHub Pages:

### Inicio:

![inicio](/img/Ejercicio3/inicio.png)

### Acerca de:

![acercade](/img/Ejercicio3/acercade.png)

### Todo:

![todo](/img/Ejercicio3/todo.png)

### Categorías:

![categorias](/img/Ejercicio3/categorias.png)

### Tags:

![tags](/img/Ejercicio3/tags.png)

### Posts:
Post 1

![post1](/img/Ejercicio3/post1.png)

Post 2

![post2](/img/Ejercicio3/post2.png)

Post 3

![post3](/img/Ejercicio3/post3.png)

Post 4

![post4](/img/Ejercicio3/post4.png)

Post 5

![post5](/img/Ejercicio3/post5.png)

Post 6

![post6](/img/Ejercicio3/post6.png)

Post 7

![post7](/img/Ejercicio3/post7.png)
