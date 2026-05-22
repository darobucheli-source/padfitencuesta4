# PADFIT — App de Encuestas

Complejo deportivo de Loja, Ecuador: pádel, squash, CrossFit, fisioterapia, nutrición, rooftop bar.

## 🚀 Deploy en Vercel (3 pasos)

### Opción A — Vercel CLI
```bash
npm install -g vercel
cd padfit
npm install
vercel --prod
```

### Opción B — GitHub + Vercel Dashboard
1. Sube este directorio a un repositorio GitHub
2. Ve a https://vercel.com/new → "Import Git Repository"
3. Elige el repo → Framework: **Vite** → Deploy

Vercel detecta Vite automáticamente. No necesitas configurar nada.

---

## 🏃 Desarrollo local
```bash
npm install
npm run dev
# Abre http://localhost:5173
```

## 📁 Estructura
```
padfit/
├── index.html          # Entry HTML
├── vite.config.js      # Vite config
├── vercel.json         # SPA routing
├── package.json
└── src/
    ├── main.jsx        # React entry
    └── App.jsx         # Toda la app
```

## 🔐 Panel Admin
- URL: click en "Panel Administrador" en la home
- Contraseña: `padfit2025`  ← cambia en `src/App.jsx` línea `const ADMIN_PASSWORD`

## 📊 Características
- ✅ Pantalla home con dos botones
- ✅ Encuesta por secciones (7 servicios)
- ✅ Preguntas: estrellas, opción única, opción múltiple, comentario abierto, NPS 0-10
- ✅ Panel admin protegido
- ✅ Editor de preguntas completo
- ✅ Análisis IA (tab "Análisis IA" en el panel)
- ✅ Datos guardados en localStorage
- ✅ Diseño oscuro con verde neón PADFIT
