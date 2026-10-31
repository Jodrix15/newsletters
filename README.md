# Newsletters

Archivo web de mis newsletters, publicado con GitHub Pages.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=githubpages&logoColor=white)

🌐 **Web:** https://jodrix15.github.io/newsletters/

## Newsletters

| Newsletter | Qué es | Archivo |
|---|---|---|
| Al Día | Actualidad, moda, tendencias, deporte, comunicación y curiosidades, los martes y jueves | [al-dia/](https://jodrix15.github.io/newsletters/al-dia/) |
| Hobby Fiction | Edición semanal | [hobby-fiction/](https://jodrix15.github.io/newsletters/hobby-fiction/) |

## Estructura

```
├── index.html             Portada con todas las newsletters
├── al-dia/
│   ├── index.html         Archivo de ediciones
│   ├── 00/index.html      Una carpeta por edición
│   └── 01/index.html
└── hobby-fiction/
    ├── index.html         Archivo de ediciones
    └── test.html          Página de prueba de la publicación
```

## Publicar una edición nueva

1. Crea la carpeta con el número de la edición (por ejemplo, `al-dia/02/`) y su `index.html`.
2. Añade el enlace en el `index.html` del archivo de esa newsletter.
3. Haz commit y push a `main`: GitHub Pages la publica en un par de minutos.
