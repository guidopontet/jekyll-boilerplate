# Webpage

Sitio realizado en [Jekyll](https://jekyllrb.com/) como generador de sitios estáticos.

1.  Clonar el repo localmente: `git clone git@github.com:guidopontet/jekyll-boilerplate.git`
2.  Instalar dependencias de ruby: `bundle install`
3.  Compilar el sitio y correrlo: `bundle exec jekyll server`. El sitio se compila en el directorio `build`

---

## Set-up Windows

  - En Windows, para funcione el [livereload](https://httpain.com/blog/jekyll-live-reload-windows/), es necesario tener instalada la versión [Ruby+Devkit 2.4.4-2 (x64)](https://rubyinstaller.org/downloads/archives/) de Ruby.
  - Y para corregir el `livereload` hay que manualmente instalar la versión correcta de [eventmachine](https://github.com/oneclick/rubyinstaller2/issues/96), realizando los dos siguientes pasos:

    ```
     gem uninstall eventmachine --force
     gem install eventmachine --platform ruby
    ```
---

## Plugins
*  [jekyll-seo-tag](https://help.github.com/articles/search-engine-optimization-for-github-pages/)
*  [jekyll-sitemap](https://github.com/jekyll/jekyll-sitemap)
*  [jekyll-gzip](https://github.com/philnash/jekyll-gzip)
*  [jekyll-webp](https://github.com/sverrirs/jekyll-webp)
*  [jekyll-compress-html](https://github.com/penibelst/jekyll-compress-html)

#### Opcionales
*  [Simple-Jekyll-Search](https://github.com/christian-fei/Simple-Jekyll-Search)
*  [jekyll-paginate](https://github.com/jekyll/jekyll-paginate)
*  [jekyll-manager](https://github.com/ashmaroli/jekyll-manager)
*  [Particles](https://github.com/VincentGarreau/particles.js/)

---

## Estructura básica

Estos son los archivos básicos

```bash
├── _includes           # Includes de componentes Html
├── _layouts            # Layouts Html
├── assets              # Static files
|  ├── js                 # Scripts
|  ├── css                # Styles
|  ├── fonts              # Fuentes
|  └── img                # Images
├── pages               # Páginas
├── _config.yml         # Archivo de configuración de Jekyll
└── index.htm           # Home
```