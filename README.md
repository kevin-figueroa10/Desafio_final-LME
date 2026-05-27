# AguaTech - Sistema de Monitoreo Responsivo en la Nube

Dashboard responsivo de monitoreo de calidad del agua para sistemas de acuicultura AguaTech. 

## 🎯 Características

- ✅ **Mobile-First**: Diseñado para dispositivos móviles primero
- ✅ **Responsivo**: 3 breakpoints (Móvil, Tablet, Desktop)
- ✅ **CSS Grid & Flexbox**: Layouts avanzados sin dependencias
- ✅ **Navegación Híbrida**: Menú responsivo sin JavaScript (CSS Checkbox Hack)
- ✅ **Sprites CSS**: 6 iconos optimizados en CSS puro
- ✅ **Accesible**: Semántica HTML5 y etiquetas ARIA
- ✅ **Despliegue en la nube**: Optimizado para Vercel

## 📱 Breakpoints

| Dispositivo | Ancho | Columnas Grid |
|-------------|-------|---------------|
| Móvil | < 600px | 1 |
| Tablet | 600px - 1023px | 2-4 |
| Desktop | ≥ 1024px | 3-4 |

## 📊 Métricas IoT

El dashboard monitorea 6 parámetros de calidad del agua:

1. **pH** - Acidez/Alcalinidad
2. **Oxígeno Disuelto** - Mg/L
3. **Temperatura** - °C
4. **Conductividad** - µS/cm
5. **Turbiedad** - NTU
6. **Potencial Redox** - mV

## 🚀 Despliegue en Vercel

### Opción 1: Desde GitHub (Recomendado)
1. Sube el código a GitHub
2. Ve a [vercel.com](https://vercel.com)
3. Conecta tu repositorio GitHub
4. Vercel desplegará automáticamente

### Opción 2: Vercel CLI
```bash
npm i -g vercel
vercel
```

## 📁 Estructura del Proyecto

```
LME_DESAFIO/
├── index.html
├── Css/
│   └── styles.css
├── vercel.json
├── .gitignore
└── README.md
```

## 🔧 Requisitos

- Navegador moderno (Chrome, Firefox, Safari, Edge)
- No requiere Node.js ni dependencias

## 📝 Licencia

© 2026 AguaTech - Todos los derechos reservados.

## 👨‍💻 Autor

Kevin Figueroa - Desafío LME Final

---

**Despliegue en tiempo real:** 🔗 [Ver en Vercel](https://desafio-final-lme.vercel.app)
