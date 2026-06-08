# Bici Urbana

Plataforma web dedicada a la movilidad sostenible en la ciudad a través de bicicletas urbanas.

## 📋 Descripción

Bici Urbana es un sitio web que proporciona información sobre bicicletas urbanas, incluyendo:
- Tipos de bicicletas disponibles
- Entrevista educativa sobre el ciclismo urbano
- Servicios profesionales de reparación y mantenimiento
- Información de contacto

## 🌐 Características

- Diseño responsive adaptado a dispositivos móviles
- Navegación intuitiva con enlaces a diferentes secciones
- Galería de tipos de bicicletas
- Sección de servicios con 3 opciones principales
- Entrevista con preguntas y respuestas frecuentes

## 📁 Estructura del Proyecto

```
BiciUrbana/
├── index.html       # Página principal (rama main)
└── styles.css       # Estilos CSS (rama styles.css)
```

## 🎨 Tecnologías

- **HTML5**: Estructura semántica
- **CSS3**: Flexbox, Grid, Gradientes, Responsive Design

## 📐 Componentes CSS Principales

### Navegación
- `display: flex` con `justify-content: center` y `gap: 2rem`
- Enlaces horizontales con efectos hover

### Galería de Bicicletas
- Grid responsivo con `repeat(auto-fit, minmax(250px, 1fr))`
- Tarjetas con gradientes y animaciones

### Sección de Servicios
- Grid de 3 columnas: `grid-template-columns: repeat(3, 1fr)`
- Tarjetas interactivas con hover effect
- Responsive: 1 columna en móvil

## 📱 Responsividad

El sitio se adapta automáticamente a diferentes tamaños de pantalla:
- **Desktop**: 3 columnas en servicios, 4 en bicicletas
- **Tablet/Móvil**: 1 columna, navegación comprimida

## 👤 Autor

**Funtimeverde**

## 📄 Licencia

© 2026 BiciUrbana. Todos los derechos reservados.

## 📧 Contacto

Para más información, contacta a: info@biciurbana.com
