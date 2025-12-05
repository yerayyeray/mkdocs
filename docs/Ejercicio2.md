## Ejercicio 2: Creación de un sitio web en Jekyll con el tema Lagrange
## 1. Conseguir el tema Lagrange:
Para obtener el tema Lagrange y poder usarlo en nuestro repositorio, hay varios metodos, en este caso lo he obtenido haciendo un Fork al repositorio de GitHub del tema, para eso se puede buscar directamente el repositorio o ir desde la pagina [jekyllthemes.org](http://jekyllthemes.org/)

![jtlagrange](img/Ejercicio2/jtlagrange.png)

Cuando estes en la pagina del tema, tienes que ir a homepage

![jtlagrangehp](img/Ejercicio2/jtlagrangehp.png)

Una vez en el repositorio, hay que hacerle un fork para poder clonarlo en local y empezar a modificarlo

![fork](img/Ejercicio2/fork.png)

![fork2](img/Ejercicio2/fork2.png)

Despues de hacer el fork, ya tendremos el repositorio con el tema Lagrange listo para configurarlo, ahora hay que ir a nuestra maquina local y clonar nuestro repositorio a local con el comando:

`git clone https://github.com/yerayyeray/Lagrange.git`

Ahora ya tenemos el repositorio clonado y podemos modificar los archivos para crear el nuevo sitio web

![clonado](img/Ejercicio2/clonado.png)

En mi caso, tuve que actualizar la gema jekyll-sitemap e instalar jekyll-paginate:

![jekyll-sitemap](img/Ejercicio2/jekyll-sitemap.png)

![jekyll-paginate](img/Ejercicio2/jekyll-paginate.png)

## 2. Configuración del sitio:
### Archivo de configuración del sitio:
Ahora tenemos que configurar el archivo de configuración de `_config.yaml` del nuevo sitio

![_config.yaml](img/Ejercicio2/_config.yaml.png)

### Crear los posts del blog:
Crear los post es igual que en el otro sitio, los posts se guardan en `/_posts`

![_posts](img/Ejercicio2/_posts.png)

Y tendran que tener el mismo formato para el nombre de los archivos `año-mes-dia-nombre_del_post` y los post tendran esta estructura:

![post](img/Ejercicio2/post.png)

### Cambial la pagina de "Acerca de":
Para personalizar la sección "Acerca de" hay que ir al archivo `about.md` en la carpeta `menu` y poner la información de nuestro sitio

![about.md](img/Ejercicio2/about.md.png)

### Pagina de contacto:
Este tema tiene una pagina de contacto también en la carpeta `menu` el archivo `contact.md`

![contact.md](img/Ejercicio2/contact.md.png)

## 3. Subir el sitio a GitHub Pages:
Antes de subir el repositorio primero hay que hacer los commits de todos los cambios que se han hecho en el repositorio si aún no se han hecho con los comandos:

```
git add .
git commit -m "comentario"
```

Si se quiere subir directamente a GitHub Pages se puede hacer subiendolo al remoto desde la rama gh-pages, la cual se puede crear así:
> git checkout -b gh-pages

Si no se hace así, se puede hacer desde la interfaz de GitHub desde aquí:

![ghpages](img/Ejercicio1/ghpages.png)

Despues, se hara el push con el comando:

`git push origin gh-pages`

## 4. Sitio web subido en GitHub Pages:
La url de la pagina es esta:

https://yerayyeray.github.io/Lagrange/

Este es el aspecto que tiene el sitio web ya subido en GitHub Pages:

Inicio:

![inicio](img/Ejercicio2/inicio.png)

![autor](img/Ejercicio2/autor.png)

Acerca de:

![acercade](img/Ejercicio2/acercade.png)

Contacto:

![contacto](img/Ejercicio2/contacto.png)

Posts:

![post1](img/Ejercicio2/post1.png)

![post2](img/Ejercicio2/post2.png)

![post3](img/Ejercicio2/post3.png)

![post4](img/Ejercicio2/post4.png)

![post5](img/Ejercicio2/post5.png)

Todo:

![todo](img/Ejercicio2/todo.png)
