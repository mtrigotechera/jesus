# Portafolio personal | Maria Isabel Trigo Techero.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Responsive Design](https://img.shields.io/badge/Responsive_Design-6366F1?style=for-the-badge)

## Descripción personal

Portafolio web personal orientado a presentar mi perfil como desarrollador web, mis habilidades técnicas y mis proyectos. Cuenta con una interfaz de temática oscura, diseño adaptable y elementos interactivos desarrollados con tecnologías web nativas.

El proyecto no requiere frameworks, gestor de paquetes, base de datos ni proceso de compilación.

## Características

- Diseño responsive para ordenadores, tabletas y dispositivos móviles.
- Menú de navegación adaptable y desplazamiento suave entre secciones.
- Presentación personal con texto rotatorio animado y fotografía de perfil.
- Indicadores animados de habilidades técnicas.
- Tarjetas de proyectos con etiquetas de tecnologías y espacios para enlaces.
- Formulario de contacto con validación HTML y simulación de envío.
- Botón para volver al inicio y actualización automática del año en el pie de página.

## Tecnologías utilizadas

| Tecnología | Finalidad |
| --- | --- |
| HTML5 | Estructura semántica y contenido. |
| CSS3 | Estilos, variables CSS, Flexbox, Grid, diseño responsive y transiciones. |
| JavaScript (Vanilla JS) | Interacción con el DOM, eventos y animaciones. |
| Google Fonts | Tipografía Poppins, con fuentes alternativas del sistema. |
| Git y GitHub | Control de versiones y alojamiento del código. |

## Estructura del proyecto

```text
jesus/
├── index.html    # Estructura y contenido del portafolio
├── styles.css    # Estilos y diseño adaptable
├── script.js     # Interactividad y animaciones
├── imagen.jpg    # Fotografía de perfil
└── README.md     # Documentación del proyecto
```

## Ejecución en local

### Requisitos

- Un navegador web moderno.
- Git, si se desea clonar el repositorio.

### Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/JesusArcis/jesus.git
   ```

2. Accede al directorio:

   ```bash
   cd jesus
   ```

3. Abre `index.html` en el navegador.

Opcionalmente, puedes utilizar Live Server en Visual Studio Code o iniciar un servidor local si tienes Python 3 instalado:

```bash
python -m http.server 8000
```

Accede a `http://localhost:8000` desde el navegador.

## Secciones del portafolio

| Sección | Contenido |
| --- | --- |
| Inicio | Presentación personal y accesos a proyectos y contacto. |
| Sobre mí | Perfil profesional e indicadores de habilidades. |
| Proyectos | Tarjetas del portafolio, aplicación de tareas y landing page de producto. |
| Contacto | Formulario y espacios para datos de contacto y redes profesionales. |

## Personalización

- `index.html`: modifica la presentación, los proyectos, los datos de contacto y los atributos `data-value` de las habilidades.
- `styles.css`: ajusta la paleta cromática mediante las variables de `:root`, la tipografía y la distribución visual.
- `script.js`: configura los textos rotatorios, las animaciones y el comportamiento del formulario.
- `imagen.jpg`: sustituye la fotografía manteniendo el nombre del archivo o actualizando su referencia en el HTML.

## Despliegue con GitHub Pages

El proyecto es compatible con alojamiento web estático. Para publicarlo en GitHub Pages:

1. Accede a **Settings → Pages** en el repositorio.
2. En **Build and deployment**, selecciona **Deploy from a branch**.
3. Selecciona la rama `main` y el directorio `/ (root)`.
4. Guarda la configuración.

Una vez publicado correctamente, la URL prevista es:

https://jesusarcis.github.io/jesus/

## Estado y mejoras pendientes

- [x] Estructura y diseño del portafolio.
- [x] Navegación móvil y animaciones.
- [x] Indicadores de habilidades y tarjetas de proyectos.
- [x] Formulario de contacto con simulación de envío.
- [ ] Integrar un servicio real de envío de mensajes, como Formspree o EmailJS.
- [ ] Sustituir los enlaces de ejemplo por enlaces reales a proyectos y perfiles.
- [ ] Actualizar los datos de contacto de ejemplo.
- [ ] Revisar accesibilidad, rendimiento y posicionamiento SEO.

> El formulario actual no envía ni almacena mensajes. Los enlaces de demostración y código de las tarjetas de proyectos son marcadores pendientes de configurar.

## Autor

**Jesús A.** — Desarrollador web

- GitHub: [@JesusArcis](https://github.com/JesusArcis)
- Ubicación: Rota, Cádiz, España.

## Licencia

Actualmente, el repositorio no incluye un archivo de licencia explícita. Consulta con el autor antes de reutilizar o redistribuir el código fuera de los permisos aplicables de GitHub.

---

Desarrollado en Rota, España.
