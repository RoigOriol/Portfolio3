Portfolio React – Tailwind + i18next + Framer Motion
ES 🇪🇸 · EN 🇬🇧

🇪🇸 Español
🚀 Portfolio React (Tailwind + i18next + Framer Motion)
Sitio portfolio responsivo con diseño no convencional, animaciones suaves, modo claro/oscuro y contenido en Catalán, Español e Inglés.

✨ Características
Layout creativo.

Animaciones modernas con Framer Motion.

Dark/Light mode con transición animada.

i18next para internacionalización (CA/ES/EN) + selector de idioma.

Secciones: Hero, Sobre mí, Proyectos, CV/Resume, Contacto.

Iconos sociales visibles (LinkedIn, GitHub, email).

Código modular y limpio, fácil de mantener.

🧰 Stack
React 18, Vite

Tailwind CSS (+ plugins forms y container-queries)

react-router-dom

i18next / react-i18next

Framer Motion

📁 Estructura
txt
Copiar
Editar
my-portfolio/
├─ public/
│  └─ locales/
│     ├─ ca/common.json
│     ├─ es/common.json
│     └─ en/common.json
└─ src/
   ├─ components/   # UI modular (panels, toggles, etc.)
   ├─ context/      # ThemeContext
   ├─ data/         # Datos de proyectos
   ├─ hooks/        # Hooks custom (tema, prefersDark)
   ├─ pages/        # Pantallas/maquetación principal
   ├─ i18n.js       # Init i18next
   ├─ routes.jsx    # Rutas
   ├─ App.jsx
   ├─ main.jsx
   └─ index.css
🔧 Instalación y uso
bash
Copiar
Editar
# 1. Crear proyecto (si aún no lo hiciste)
npm create vite@latest my-portfolio -- --template react
cd my-portfolio

# 2. Copia los archivos provistos en esta estructura

# 3. Instala dependencias
npm install

# 4. Ejecuta en desarrollo
npm run dev

# 5. Build de producción
npm run build
npm run preview
🌐 Internacionalización
Archivos en public/locales/{lang}/common.json.

Cambia o añade claves para más textos.

El selector de idioma guarda la preferencia en localStorage.

🌓 Tema claro/oscuro
Hook useTheme + ThemeContext.

Respeta prefers-color-scheme del SO si no hay elección previa.

Clases dark: de Tailwind.

🖼️ Personalización
Cambia imágenes de fondo en HeroPanel.jsx.

Añade proyectos en src/data/projects.js.

Ajusta rotaciones/diseño inusual en SectionShell.jsx.

🚢 Deploy
Netlify/Vercel: build npm run build y publica la carpeta dist/.

GitHub Pages: usa Vite + acción de CI o gh-pages.

📄 Licencia
Libre uso y adaptación para proyectos personales. Añade tu propia licencia si lo publicas.

🇬🇧 English
🚀 React Portfolio (Tailwind + i18next + Framer Motion)
Responsive portfolio with an unconventional layout, smooth animations, dark/light mode, and content in Catalan, Spanish, and English.

✨ Features
Creative, non-standard layout.

Modern transitions via Framer Motion.

Dark/Light mode with animated toggle.

i18next for i18n (CA/ES/EN) + language switcher.

Sections: Hero, About Me, Projects, CV/Resume, Contact.

Visible social icons (LinkedIn, GitHub, email).

Clean, modular, maintainable code.

🧰 Tech Stack
React 18, Vite

Tailwind CSS (+ forms & container-queries plugins)

react-router-dom

i18next / react-i18next

Framer Motion

📁 Structure
txt
Copiar
Editar
my-portfolio/
├─ public/
│  └─ locales/
│     ├─ ca/common.json
│     ├─ es/common.json
│     └─ en/common.json
└─ src/
   ├─ components/   # Modular UI (panels, toggles, etc.)
   ├─ context/      # ThemeContext
   ├─ data/         # Projects data
   ├─ hooks/        # Custom hooks (theme, prefersDark)
   ├─ pages/        # Main layout/screens
   ├─ i18n.js       # Init i18next
   ├─ routes.jsx    # Routes
   ├─ App.jsx
   ├─ main.jsx
   └─ index.css
🔧 Setup & Run
bash
Copiar
Editar
# 1. Create project (if you haven't)
npm create vite@latest my-portfolio -- --template react
cd my-portfolio

# 2. Copy the provided files into this structure

# 3. Install deps
npm install

# 4. Dev server
npm run dev

# 5. Production build
npm run build
npm run preview
🌐 Internationalization
JSON files in public/locales/{lang}/common.json.

Add/change keys to extend texts.

Language choice stored in localStorage.

🌓 Dark/Light Theme
useTheme hook + ThemeContext.

Respects system prefers-color-scheme if no saved choice.

Tailwind dark: classes.

🖼️ Customization
Update hero background in HeroPanel.jsx.

Add projects in src/data/projects.js.

Tweak rotations/unconventional layout in SectionShell.jsx.

🚢 Deployment
Netlify/Vercel: build with npm run build, serve dist/.

GitHub Pages: use Vite + CI action or gh-pages.

📄 License
Free to use/modify for personal projects. Add your own license if distributing.
