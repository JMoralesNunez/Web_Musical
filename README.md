# Web Musical Accesible

Este proyecto es una aplicación web educativa e inclusiva que funciona como una **biblioteca musical multimedia**, diseñada especialmente para facilitar el acceso a contenido musical por parte de personas con discapacidad visual. Se estructura mediante HTML5, CSS3 y buenas prácticas de accesibilidad.

---

## Estructura del Proyecto

```
📁 index.html                # Página principal con la lista de álbumes
📁 Html/
    ├── album1.html         # Página del álbum "Divide" - Ed Sheeran
    └── album2.html         # Página del álbum "What Is Love?" - Clean Bandit
📁 Css/
    ├── style1.css          # Estilo principal compartido
    ├── style2.css          # Estilo personalizado para album1.html
    └── style3.css          # Estilo personalizado para album2.html
📁 audio/                    # Archivos de audio por canción
📁 video/                    # Archivos de video musicales
📁 img/
    ├── Divide.png          # Portada del álbum "Divide"
    ├── What_is_love.jpeg   # Portada del álbum "What Is Love?"
    └── github.svg          # Icono de GitHub
```

---

## Funcionalidades

- Navegación simple con encabezado y barra accesible
- Reproductores integrados de **audio** y **video**
- Álbumes organizados semánticamente usando `article`, `figure`, `figcaption`, etc.
- **Accesibilidad visual mejorada**: colores de alto contraste, enfoque visible, uso de `aria-label` y etiquetas descriptivas
- Contacto de los desarrolladores con íconos de GitHub en línea

---

## Desarrolladores

| Nombre           | GitHub                                                  |
|------------------|----------------------------------------------------------|
| Jhonatan Morales     | [@JMoralesNunez](https://github.com/JMoralesNunez)       |
| Brahian Montoya  | [@BrahianMS](https://github.com/BrahianMS)               |
| Diego Zuluaga    | [@alejo11102001](https://github.com/alejo11102001)       |

---

## Accesibilidad

El proyecto está diseñado con base en criterios de accesibilidad:

- Navegación con teclado
- Enlaces y controles multimedia con `focus visible`
- Uso correcto de encabezados, etiquetas semánticas y descripciones `alt`

---

## Cómo ejecutar el proyecto

1. Clona o descarga este repositorio
2. Abre `index.html` en un navegador moderno
3. Para mejor compatibilidad (especialmente con los iframes de YouTube), ejecuta un servidor local:

---

## Notas

- Los archivos de audio y video deben estar presentes en sus respectivas carpetas para que los reproductores funcionen correctamente.
- Puedes expandir este proyecto fácilmente con más álbumes, artistas o secciones educativas.
