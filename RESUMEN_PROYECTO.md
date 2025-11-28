# 📋 Resumen del Proyecto - Contexto para ChatGPT

## 🎯 Descripción del Proyecto

Este es un **template base reutilizable** para crear landing pages profesionales y modernas. El proyecto actual es una aplicación web de **colorización inteligente de bocetos/dibujos** que permite a los usuarios subir imágenes en blanco y negro y aplicar colores de forma automática usando IA.

### Funcionalidad Principal
- **Colorización de imágenes**: Los usuarios suben bocetos/dibujos y la aplicación los colorea automáticamente usando IA
- **Sistema de créditos**: Sistema de pago único con créditos (2000 créditos por $10)
- **Galería de ejemplos**: Muestra transformaciones antes/después
- **Landing page completa**: Hero section, ejemplos, precios, contacto

### Características del Template
- Diseño minimalista con paleta de colores relajante (predominantemente blanco)
- Animaciones fluidas con Framer Motion
- Completamente responsive
- Optimizado para performance
- SEO friendly

## 🛠️ Stack Tecnológico

### Framework y Lenguaje
- **Next.js 15.5.2** (con App Router)
- **TypeScript 5**
- **React 19.1.0**
- **React DOM 19.1.0**

### Estilos y UI
- **Tailwind CSS 4** (sistema de diseño)
- **Framer Motion 12.23.12** (animaciones)
- **Lucide React 0.542.0** (iconos)

### Backend y APIs
- **API Routes de Next.js** (endpoints personalizados)
- **Svix 1.76.0** (webhooks)
- **Zod 4.1.5** (validación de esquemas)

### Pagos
- **@polar-sh/nextjs 0.4.4** (integración de pagos)

### Herramientas de Desarrollo
- **ESLint 9** (linting)
- **Turbopack** (compilación rápida)
- **PostCSS** (procesamiento CSS)

## 📁 Estructura del Proyecto

```
my-app/
├── app/
│   ├── api/                    # API Routes
│   │   ├── colorize/          # Endpoint de colorización
│   │   ├── credits/           # Gestión de créditos
│   │   ├── polar/             # Integración de pagos
│   │   └── webhooks/          # Webhooks de pagos
│   ├── components/            # Componentes React
│   │   ├── Button.tsx
│   │   ├── ColorizationApp.tsx  # App principal de colorización
│   │   ├── ExamplesGallery.tsx
│   │   ├── Header.tsx
│   │   ├── HeroTransformation.tsx
│   │   ├── PricingCard.tsx
│   │   └── SmoothScroll.tsx
│   ├── utils/                 # Utilidades
│   │   └── analytics.ts      # Google Analytics
│   ├── globals.css           # Estilos globales y variables CSS
│   ├── layout.tsx            # Layout principal
│   └── page.tsx              # Página principal
├── public/                    # Assets estáticos
│   └── IMG/                  # Imágenes del proyecto
├── types/                     # Tipos TypeScript
│   └── api.ts
└── package.json              # Dependencias
```

## 🎨 Sistema de Diseño

### Paleta de Colores
- **Primario**: Naranja (#ff6b35) - Botones principales y acentos
- **Secundario**: Verde (#4ade80) - Elementos de éxito
- **Acento**: Azul (#3b82f6) - Información y enlaces
- **Fondo**: Blanco puro (#ffffff) - Diseño minimalista
- **Texto**: Grises (#171717, #6b7280)

### Características de Diseño
- Diseño minimalista y limpio
- Paleta predominantemente blanca (relajante para la vista)
- Animaciones suaves en entrada, hover y scroll
- Responsive: Mobile (320px+), Tablet (768px+), Desktop (1024px+)

## 🔧 Funcionalidades Técnicas

### API Routes
- `/api/colorize` - Procesa imágenes y aplica colorización con IA
- `/api/credits` - Gestiona créditos de usuarios
- `/api/polar/checkout` - Maneja pagos
- `/api/webhooks/polar` - Recibe webhooks de pagos
- `/api/poll-result` - Polling de resultados de procesamiento

### Componentes Principales
- **ColorizationApp**: Componente principal que maneja la subida de archivos, procesamiento y visualización de resultados
- **HeroTransformation**: Muestra transformaciones antes/después en el hero
- **ExamplesGallery**: Galería de ejemplos de colorización
- **PricingCard**: Tarjeta de precios con sistema de créditos
- **Header**: Navegación fija con efectos de scroll

### Sistema de Créditos
- Plan gratuito: 1 crédito de prueba
- Plan de pago: 2000 créditos por $10 (pago único)
- Los créditos nunca expiran
- Sistema de tracking de usuarios basado en fingerprint del navegador

## 📝 Configuración y Personalización

El proyecto está diseñado como **template base** que se puede copiar y personalizar fácilmente:
- Cambio de colores mediante variables CSS
- Personalización de textos en componentes
- Reemplazo de imágenes en `/public/IMG/`
- Adaptación de funcionalidad según necesidad

## 🚀 Scripts Disponibles

- `npm run dev` - Servidor de desarrollo con Turbopack
- `npm run build` - Construcción para producción
- `npm run start` - Servidor de producción
- `npm run lint` - Verificación de código

## 📚 Documentación Incluida

- `COMO_EMPEZAR.md` - Guía paso a paso para crear un proyecto nuevo
- `CUSTOMIZATION_CHECKLIST.md` - Checklist de personalización
- `PROJECT_CONFIG.md` - Documentación completa de configuración
- `README.md` - Documentación general del proyecto

---

**Nota**: Este proyecto está orientado al sector salud (estética/dentista/clínica) según las preferencias del usuario, aunque actualmente el ejemplo es de colorización de bocetos. El template es completamente adaptable a cualquier tipo de negocio o servicio.





