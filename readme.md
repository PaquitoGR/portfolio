## Práctica del módulo de HTML y CSS del _XV Bootcamp Desarrollador Web FullStack_ de Keepcoding.
### Elaboración de página personal o portfolio, usando únicamente HTML y CSS.

Se ha iniciado creando la estructura HTML, separada en Header, main con sus scciones, y footer, todo dentro del body. En la medida de lo posible se ha usado etiquedas de HTML semánticas, intentando evitar al máximo la introducción de etiquetas DIV sin función concreta.

Asímismo, se ha copiado dicha página para tomarla como base para la página secundaria, que contendrá un video y una cuadrícula de proyectos consistentes cada uno en un título y una imagen representativa.

Una vez establecida la estructura básica, se ha procedido a implementar diferentes ficheros CSS, agrupando por secciónes coincidentes con las que forman la página HTML
La maquetación con CSS se hizo partiendo de la versión compatible con dispositivos móviles. Ajustando todo segun la filosofía Mobile First.

Una vez terminada la versión para teléfonos moviles y otros dispositivos con resolución horizontal inferior a 768 píxeles, se procedió a adaptar y encuadrar los elementos de la página para hacerla responsive, diferenciando entre dispositivos de mas de 1024 píxeles de ancho, 1440 píxeles y hasta 4k de resolución.

### Assets y recursos externos
Dado que el contenido de la página es ficticio, se han usado algunas imagenes sin copyright obtenidas de la página www.unsplash.com.
Además, para resoluciones móviles, se ha añadido un menú tipo hamburguesa en el footer, tomando como referencia uno de los ejemplos mostrados en la página https://alvarotrigo.com/blog/hamburger-menu-css

### Estructura de carpetas
La estructura usada en la página es la siguiente:
```
├── assets              Carpeta que contiene los recursos
|   ├── img             Carpeta que contiene las imagenes
|   ├── video           Carpeta que contiene los vídeos (uno en este caso)
├── styles              Carpeta que contiene los archivos de estilos CSS
├── index.html          Página principal
├── portfolio.html      Página que contiene la cuadrícula de proyectos
├── favicon.ico         Icono que aparece en la barra de título
├── Readme.md           Fichero de documentación
```

### Github Pages
La página ha sido subida al servidor de Github, cuya URL es https://paquitogr.github.io/portfolio/
