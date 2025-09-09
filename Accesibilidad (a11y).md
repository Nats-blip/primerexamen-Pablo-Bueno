# Landing Page MANACO

## Descripción
Landing page de la marca MANACO desarrollada en **HTML5 y CSS** con estructura semántica y principios básicos de accesibilidad.

## Accesibilidad (a11y)
Se implementaron medidas esenciales para garantizar un uso inclusivo de la página:

- **Foco visible**: se configuró un estilo de `outline` azul en enlaces y botones, asegurando que siempre se vea dónde está el foco al navegar con `Tab`.  
- **Textos alternativos (`alt`)**: todas las imágenes de productos tienen descripciones breves y claras, para que usuarios con lectores de pantalla entiendan el contenido visual.  
-**Uso de ARIA**:  
  - `role="banner"`, `role="main"`, `role="contentinfo"` en `header`, `main` y `footer` para reforzar la semántica en navegadores antiguos.  
  - `aria-label="Navegación principal"` en el `<nav>` para describir su función.  
  - `aria-current="page"` en el enlace activo del menú para indicar la página actual.  
  - `aria-labelledby` en secciones y artículos para asociar encabezados con su contenido.  
  - `aria-label` en botones y precios para dar contexto adicional al lector de pantalla. 
- **Pruebas de teclado**: se navegó la página solo con `Tab`, `Enter` y `Espacio`, verificando que todos los elementos interactivos sean alcanzables y usables.  
- **Contraste**: los enlaces del *skip link* y los focos se validaron para tener contraste suficiente frente al fondo, garantizando buena legibilidad.  