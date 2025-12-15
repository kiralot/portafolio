# 🚀 Mi Portafolio Profesional - Data Science

Portafolio profesional diseñado para mostrar mis habilidades, proyectos y formación en Data Science, Machine Learning e Inteligencia Artificial.

## 📋 Características

- **Diseño Responsivo**: Adaptado a todos los dispositivos (móvil, tablet, desktop)
- **Animaciones Suaves**: Transiciones y efectos visuales profesionales
- **Secciones Completas**:
  - 👤 Sobre Mí
  - 💪 Habilidades Técnicas (6 categorías)
  - 💼 Proyectos Destacados
  - 🎓 Educación y Certificaciones
  - 📧 Formulario de Contacto

## 🛠️ Tecnologías Utilizadas

- HTML5
- CSS3 (con variables CSS y Grid/Flexbox)
- JavaScript Vanilla
- Font Awesome Icons

## 📂 Estructura del Proyecto

```
portafolio/
│
├── index.html          # Página principal
├── styles.css          # Estilos completos
├── script.js           # Interactividad y animaciones
└── README.md          # Este archivo
```

## 🚀 Cómo Usar

1. **Abrir localmente**:
   - Abre `index.html` en tu navegador favorito

2. **Personalizar**:
   - Edita `index.html` para actualizar tu información personal
   - Modifica los proyectos en la sección de Proyectos
   - Actualiza los enlaces de redes sociales
   - Cambia el email y datos de contacto

3. **Desplegar en línea**:
   - **GitHub Pages**: Sube el proyecto a un repositorio de GitHub y activa GitHub Pages
   - **Netlify**: Arrastra la carpeta en netlify.com
   - **Vercel**: Conecta tu repositorio en vercel.com

## 📝 Personalización

### Cambiar Colores
En `styles.css`, modifica las variables CSS:
```css
:root {
    --primary-color: #3b82f6;
    --secondary-color: #8b5cf6;
    /* ... más colores */
}
```

### Agregar Proyectos
En `index.html`, duplica y modifica el bloque `.project-card`:
```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-icon-name"></i>
    </div>
    <div class="project-content">
        <h3>Nombre del Proyecto</h3>
        <p>Descripción...</p>
        <!-- ... -->
    </div>
</div>
```

### Actualizar Habilidades
Modifica los porcentajes en `style="width: XX%"` dentro de `.skill-progress`

## 🎨 Personalización del Formulario de Contacto

El formulario actual muestra una alerta. Para hacerlo funcional:

1. **Con EmailJS** (Recomendado):
   ```javascript
   // Regístrate en emailjs.com
   emailjs.send("service_id", "template_id", {
       from_name: name,
       from_email: email,
       message: message
   });
   ```

2. **Con Formspree**:
   - Crea cuenta en formspree.io
   - Cambia el action del form: `<form action="https://formspree.io/f/tu-id">`

3. **Con Backend Propio**:
   - Crea un endpoint en Node.js/Python/PHP
   - Usa `fetch()` para enviar los datos

## 📱 Redes Sociales

Actualiza los enlaces en el archivo HTML:
```html
<a href="https://github.com/tuusuario" target="_blank">
<a href="https://linkedin.com/in/tuusuario" target="_blank">
<a href="mailto:tu@email.com">
```

## 🎯 Próximos Pasos

- [ ] Añadir tus proyectos reales
- [ ] Incluir capturas de pantalla de proyectos
- [ ] Añadir tu foto de perfil
- [ ] Conectar formulario de contacto
- [ ] Optimizar imágenes para web
- [ ] Agregar meta tags para SEO
- [ ] Configurar dominio personalizado

## 📄 Licencia

Este proyecto es de uso personal. Siéntete libre de usarlo como base para tu propio portafolio.

---

**Hecho con ❤️ y mucho ☕**
