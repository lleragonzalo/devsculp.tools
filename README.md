# One-Pager Profesional - Leratech

One-pager moderno para vender servicios de Software & Data Engineering con enfoque en sistemas críticos, automatización inteligente y ML.

## 🚀 Ejecución local

```bash
npm install
npm run dev
```

Abre: http://localhost:5173

## ✅ Checklist antes de publicar

### 1. Links de pago (OnePager.jsx)

**✅ MercadoPago**: Configurado con `https://link.mercadopago.com.uy/gllera`

**✅ PayPal**: Configurado con `https://paypal.me/lleragonzalo`

**¡Todos los botones de pago están listos!** Los clientes pueden pagar directamente desde el sitio.

### 2. Contacto (OnePager.jsx)

**⏳ Pendiente - WhatsApp (Línea ~915)**:
```javascript
href="https://wa.me/598XXXXXXXXX?text=..."
```

**✅ LinkedIn**: Ya configurado con `https://www.linkedin.com/in/gonzalollera/`

**✅ Email**: Configurado con `devsculpt10@gmail.com`

### 3. Dominio personalizado (opcional)

Si tenés dominio propio, cambiá el email en:
- Línea 321 (Combo)
- Línea 410 (Contacto)

## 📦 Publicar en GitHub Pages

El deploy es automático via GitHub Actions. Cada `git push origin main` actualiza el sitio en producción automáticamente.

## 📄 Exportar como PDF

1. Abre http://localhost:5173 en Chrome
2. Presiona `Ctrl + P` (Windows) o `Cmd + P` (Mac)
3. Selecciona "Guardar como PDF"
4. Ajusta márgenes a "Ninguno"
5. Guarda

Perfecto para enviar por email a clientes.

## 🎨 Estructura del proyecto

- `OnePager.jsx` - Componente principal (todo en un archivo)
- `index.html` - HTML base con meta tags SEO
- `index.css` - Estilos Tailwind + animaciones
- `vite.config.js` - Configuración de Vite
- `tailwind.config.js` - Configuración de Tailwind

## 📐 Secciones del One-Pager

1. **Hero** - Título impactante + CTAs
2. **Diferenciadores** - 4 pilares clave (MSc+EMBA, velocidad, ML, experiencia internacional)
3. **Sobre mí** - Bio + credenciales + stack tecnológico
4. **Servicios Express** - 3 servicios productizados + Combo
5. **¿Cómo Funciona?** - Proceso de 4 pasos + Garantías/Marketing
6. **Últimos Proyectos** - Casos reales + Logros cuantificables
7. **FAQ** - 3 preguntas con acordeón
8. **Contacto** - Email, WhatsApp, LinkedIn
9. **Footer** - Links y copyright

## 💡 Servicios incluidos

1. **Legacy System Rescue** - USD 650 (desde 48h)
2. **Data Automation Suite** - USD 500 (desde 48h)
3. **Performance Optimization** - USD 400 (desde 48h)
4. **Desarrollo a Medida** - A consultar (según alcance)
5. **Paquete Premium** (3 servicios express) - USD 1.250 (ahorro USD 300)

**Nota**: Los tiempos se estiman después del análisis inicial (1-2h). La mayoría de proyectos se completan en 48-72h según complejidad.

## 📂 Proyectos destacados

La sección "Proyectos Reales" incluye:
- Sistema de Compras Públicas - SOAP Web Services, JBoss, Oracle, Dozer
- Pipeline de Validación (Organismo Gubernamental) - Python, automatización, reglas de negocio, analytics
- Gestor de Convocatorias - JavaScript, MySQL, API REST, reportería Excel/JSON

**Nota**: Los logros cuantificables (100% uptime, 15+ horas ahorradas, 5x optimización) son reales. Cuando tengas testimonios de clientes, simplemente reemplazá el array `achievements` por `testimonials` en el código.

## 🔧 Personalización avanzada

### Cambiar colores
En `tailwind.config.js` o directamente en los componentes (busca `teal-` y `slate-`).

### Agregar servicios
En `OnePager.jsx`, línea 6, agrega objetos al array `services`.

### Modificar precios
Cambia los valores `price` en cada servicio y actualiza el Combo (línea 318).

## 📞 Soporte

Si necesitás ayuda con la personalización, escribí a devsculpt10@gmail.com

---

**Nota**: Este proyecto usa React + Vite + Tailwind CSS. No hay dependencias externas para mantener máxima velocidad de carga.

