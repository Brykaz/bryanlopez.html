# Bio-Bryan-Lopez-Macias
Biografia y estudios https://brykaz.github.io/Bio-Bryan-Lopez-Macias/

#
# This file contains configuration flags to customize your site
#

# Name of your site (displayed in the header)
name: Bryan Lopez

# Short bio or description (displayed in the header)
BIOGRAFIA: Me llamo Christian Bryan Lopez Macias, naci el 28 de Julio del año 2000 y actualmente vivo en Guayaquil - Ecuador.
Tengo 20 años y me encuentro bien de salud.

ESTUDIOS: Mis estudios los realice en la escuela "Yanira Maitte" y actualmente se llama "Nela Martinez". Ingrese al colegio en el año 2012 y hace 2 años de mi graduacion que termine el bachiller, he realizado mis estudios con calificaciones excelentes, los realice en la ciudad de Guayaquil en el colegio "Francisco de Orellana". Actualmente me encuentro estudiando mi 1er semestre de la carrera de Software en la Universidad de Guayaquil.

CURSOS ESTUDIADOS: A lo largo de toda mi vida he ingresado a varios cursos los cuales son: 
- Karate
- Futbol
- Ajedrez
- Ingles
De los ya mencionados hay unos cursos los cuales acabo de cursar en los ultimos 5 años y son:
- Natacion
- Curso de nivelacion de materias bachiller

HOBBIES
- Mis hobbies son leer y escuchar musica, auqnue a veces tambien me gusta ver videos sobre temas interesantes tales como "Misterios que no son resueltos hasta el dia de hoy".

# URL of your avatar or profile pic (you could use your GitHub profile pic)
avatar: https://raw.githubusercontent.com/barryclark/jekyll-now/master/images/jekyll-logo.png

#
# Flags below are optional
#

# Includes an icon in the footer for each username you enter
footer-links:
  dribbble:
  email: lbryan370@gmail.com
  facebook: https://www.facebook.com/CbryanlopezM/
  github: barryclark/jekyll-now
  instagram: @brykaz


# Enter your Disqus shortname (not your username) to enable commenting on posts
# You can find your shortname on the Settings page of your Disqus account
disqus:

# Enter your Google Analytics web tracking code (e.g. UA-2110908-2) to activate tracking
google_analytics:

# Your website URL (e.g. http://barryclark.github.io or http://www.barryclark.co)
# Used for Sitemap.xml and your RSS feed
url:

# If you're hosting your site at a Project repository on GitHub pages
# (http://yourusername.github.io/repository-name)
# and NOT your User repository (http://yourusername.github.io)
# then add in the baseurl here, like this: "/repository-name"
baseurl: ""

#
# !! You don't need to change any of the configuration flags below !!
#

markdown: kramdown
highlighter: rouge
permalink: /:title/

# The release of Jekyll Now that you're using
version: v1.2.0

# Jekyll 3 now only supports Kramdown for Markdown
kramdown:
  # Use GitHub flavored markdown, including triple backtick fenced code blocks
  input: GFM
  # Jekyll 3 and GitHub Pages now only support rouge for syntax highlighting
  syntax_highlighter: rouge
  syntax_highlighter_opts:
    # Use existing pygments syntax highlighting css
    css_class: 'highlight'

# Set the Sass partials directory, as we're using @imports
sass:
  style: :expanded # You might prefer to minify using :compressed

# Use the following plug-ins
gems:
  - jekyll-sitemap # Create a sitemap using the official Jekyll sitemap gem
  - jekyll-feed # Create an Atom feed using the official Jekyll feed gem

# Exclude these files from your production _site
exclude:
  - Gemfile
  - Gemfile.lock
  - LICENSE
  - README.md
  - CNAME