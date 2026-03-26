PASO 1 PARAME EN EL ARCHIVO DONDE ESTA LA LANDING 

cd '/Users/leoneldonatini/Development/01-Sunset Desarrollo'

Luego hago un " ls enter " para ver los archivos que hay ahi adentro deberia ver los index html y esas cosas 

PASO 2 Comitear los cambios que haga aca 

git init
git add .
git commit -m "Primera version landing Sunset"
git branch -M main
git remote add origin https://github.com/leonelprintdustry/desarrolladora.git
git push -u origin main



COMO HAGO PARA PUBLICAR ESTA EXPLICADO MAS ABAJO 

Perfecto. Hacé esto en GitHub y te queda online.

Entrá a tu repositorio desarrolladora y andá a Settings → Pages. En Build and deployment, en Source elegí Deploy from a branch. Después, en el selector de branch, elegí main y en la carpeta elegí /(root). Guardás y GitHub publica el sitio desde esa rama.

Como tu landing es un index.html simple en la raíz del repo, esa configuración es la correcta. GitHub Pages funciona bien para sitios estáticos así, y en cuentas Free el repositorio debe ser público para publicar sin problemas.

La URL esperable de tu sitio, por ser un repositorio de proyecto llamado desarrolladora, debería quedar con este formato:

https://leonelprintdustry.github.io/desarrolladora/

Eso sigue el esquema normal de GitHub Pages para repositorios que no son el sitio principal usuario.github.io.

Si no te aparece enseguida, refrescá la página del repo y mirá la sección Pages o la pestaña Actions. GitHub indica que la publicación corre mediante un workflow de Pages, incluso cuando elegís “Deploy from a branch”, así que ahí vas a ver si terminó bien o si hubo algún error.

Si querés, seguí este mini checklist exacto:

Abrí tu repo en GitHub.
Settings
Pages
Source: Deploy from a branch
Branch: main
Folder: / (root)
Save
Esperá un minuto y abrí: https://leonelprintdustry.github.io/desarrolladora/

Si te tira 404 o blanco, lo más probable es una de estas tres cosas:

el repo está privado,
index.html no quedó en la raíz,
o la publicación todavía no terminó.

Pegame una captura de Settings → Pages o el texto que te aparezca ahí y te digo exactamente qué tocar.

