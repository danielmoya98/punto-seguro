# Punto Seguro - Landing Page

Landing page moderna y optimizada para "Punto Seguro", un servicio de traslados privados y seguros al aeropuerto.

![Punto Seguro Preview](https://via.placeholder.com/800x400?text=Punto+Seguro+Preview)

## 📋 Descripción

Este proyecto es una web estática diseñada para ofrecer una experiencia de usuario rápida y fluida. Muestra servicios de transporte, testimonios de clientes, preguntas frecuentes y opciones de contacto, todo con un diseño visual atractivo y animaciones suaves.

## 🚀 Características

- **Diseño Responsivo**: Adaptado a móviles, tablets y escritorio.
- **Animaciones Reveal**: Efectos de aparición al hacer scroll.
- **Scroll Infinito**: Banner animado en la sección de seguridad.
- **Componentes UI**:
  - Hero Section con video/imagen de fondo.
  - Tarjetas de servicios y testimonios.
  - Acordeón de preguntas frecuentes (diseño estático).
  - Botón de WhatsApp flotante o en CTA.

## 🛠️ Tecnologías

- **HTML5**: Estructura semántica.
- **CSS3**: Estilos personalizados en `assets/css/style.css`.
- **Tailwind CSS**: Framework de utilidad (vía CDN) para estilizado rápido.
- **JavaScript**: Lógica de animaciones e interacciones en `assets/js/script.js`.
- **Iconify**: Iconos vectoriales ligeros.

## 📂 Estructura del Proyecto

```
/
├── index.html              # Archivo principal
└── assets/
    ├── css/
    │   └── style.css       # Estilos personalizados y animaciones
    └── js/
        └── script.js       # Lógica del frontend (IntersectionObserver, etc.)
```

## 🔧 Instalación y Uso

1.  **Clonar el repositorio**:
    ```bash
    git clone https://usuario/punto-seguro.git
    cd punto-seguro
    ```

2.  **Ejecutar localmente**:
    No se requiere instalación de dependencias (Node.js, etc.) si solo se desea visualizar.
    - Opción A: Abrir `index.html` en tu navegador.
    - Opción B (Recomendada): Usar una extensión como "Live Server" en VS Code o correr un servidor simple con Python:
      ```bash
      python3 -m http.server 8080
      ```
      Luego visita `http://localhost:8080`.

## 🌐 Despliegue

Este proyecto está listo para desplegarse en cualquier servicio de hosting estático como **Render**, **Netlify** o **Vercel**.

### Pasos para Render:
1. Sube tu código a GitHub/GitLab.
2. Crea un nuevo "Static Site" en Render.
3. Conecta tu repositorio.
4. Render detectará automáticamente `index.html`.
5. ¡Listo!

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para más detalles.

---
Desarrollado para **Punto Seguro**.
