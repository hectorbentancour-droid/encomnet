

## 📁 Estructura del Proyecto

```
encomnet/
├── index.html          # Página principal
├── css/
│   └── style.css       # Estilos del sitio
├── js/
│   ├── main.js         # Funcionalidades principales
│   └── particles.js    # Animación de partículas
├── images/
│   ├── autogestion.jpg # Imagen de sección autogestión
│   └── internet-hogar.jpg # Imagen de banner
└── README.md           # Este archivo
```

## 🚀 Características

- ✅ **Diseño Responsive** - Adaptable a móviles, tablets y desktop
- ✅ **Animación de Partículas** - Efecto de red conectada en el hero
- ✅ **Navegación Suave** - Scroll animado entre secciones
- ✅ **Formulario de Contacto** - Listo para integrar con backend
- ✅ **Menú Móvil** - Navegación optimizada para dispositivos móviles
- ✅ **Botón WhatsApp** - Integración directa con WhatsApp
- ✅ **Efectos Hover** - Interacciones visuales en botones y tarjetas

## 📋 Secciones Incluidas

1. **Header** - Logo, navegación y botón de WhatsApp
2. **Hero** - Banner principal con animación de partículas
3. **Características** - 4 ítems destacados
4. **Servicios** - Tarjetas de Internet Residencial, Autogestión y Corporativo
5. **Cobertura** - Zonas de servicio con fondo animado
6. **Contacto** - Formulario de solicitud de servicio
7. **Footer** - Links y datos de contacto

## 🛠️ Tecnologías Utilizadas

- HTML5
- CSS3 (Flexbox, Grid, Animaciones)
- JavaScript (ES6+)
- Canvas API (para partículas)
- Font Awesome (iconos)
- Google Fonts (Inter)

## 📦 Cómo Usar

### Opción 1: Subir a Hosting

1. Comprime todos los archivos en un archivo ZIP
2. Sube el ZIP a tu hosting (cPanel, FTP, etc.)
3. Descomprime en la carpeta `public_html` o equivalente
4. ¡Listo! Tu sitio estará en línea

### Opción 2: Editar Localmente

1. Descarga la carpeta `nortech-clone`
2. Abre `index.html` en tu editor de código (VS Code, Sublime, etc.)
3. Edita el contenido según tus necesidades
4. Guarda y sube los cambios a tu hosting

## ✏️ Personalización

### Cambiar Colores

Edita el archivo `css/style.css` y modifica las variables CSS:

```css
:root {
    --primary-color: #0077b6;    /* Color principal */
    --secondary-color: #00b4d8;  /* Color secundario */
    --whatsapp-color: #25d366;   /* Color WhatsApp */
    --text-dark: #1a1a2e;        /* Texto oscuro */
    --bg-dark: #0d1b2a;          /* Fondo oscuro */
}
```

### Cambiar Textos

Edita el archivo `index.html` y busca las secciones que quieres modificar:

- Título del hero: `<h1 class="hero-title">...</h1>`
- Servicios: `<div class="service-card">...</div>`
- Zonas de cobertura: `<div class="coverage-zones">...</div>`
- Teléfonos: Busca los enlaces `tel:` y `wa.me`

### Cambiar Imágenes

Reemplaza los archivos en la carpeta `images/` manteniendo los mismos nombres:
- `autogestion.jpg` - Imagen de la tarjeta de autogestión
- `internet-hogar.jpg` - Imagen del banner inferior

### Configurar Formulario

El formulario está listo para conectar con tu backend. Busca en `js/main.js`:

```javascript
contactForm.addEventListener('submit', (e) => {
    e.preventDefault();
    // Aquí agrega tu código para enviar los datos
    // Ejemplo: fetch('/api/contact', { method: 'POST', body: formData })
});
```

## 📱 Responsive Breakpoints

- **Desktop**: > 1024px
- **Tablet**: 768px - 1024px
- **Mobile**: < 768px
- **Small Mobile**: < 480px

## 🔧 Funcionalidades JavaScript

- **Partículas animadas** - Efecto de red conectada que responde al mouse
- **Scroll suave** - Navegación animada entre secciones
- **Menú móvil** - Toggle del menú en dispositivos pequeños
- **Botón scroll-to-top** - Aparece al hacer scroll
- **Validación de formulario** - Validación básica de campos
- **Animaciones al scroll** - Elementos que aparecen al hacer scroll

## 🌐 SEO y Meta Tags

El sitio incluye:
- Meta viewport para responsive
- Título optimizado
- Estructura semántica HTML5
- Atributos alt en imágenes
- Enlaces con atributos title

## 📞 Soporte

Si necesitas ayuda para personalizar el sitio, puedes:

1. Revisar los comentarios en el código
2. Modificar los archivos CSS para cambiar estilos
3. Editar el HTML para cambiar contenido
4. Ajustar el JavaScript para modificar comportamientos

