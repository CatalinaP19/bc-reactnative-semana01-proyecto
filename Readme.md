Mi App Personal - React Native
Una aplicación móvil personal desarrollada con React Native y Expo, que presenta un perfil profesional con diseño moderno y componentes reutilizables.
📋 Características

Perfil Personal: Sección con información de contacto y descripción profesional
Tarjetas de Proyectos: Componente reutilizable para mostrar proyectos con etiquetas
Tarjetas de Habilidades: Visualización de skills con indicadores de nivel
Diseño Moderno: Interfaz limpia con una paleta de colores personalizada
Componentes Reutilizables: Arquitectura modular y mantenible

🎨 Paleta de Colores

Amarillo Principal: #E0D976
Azul: #3971B8
Fondo Claro: #FBF7E6
Texto: #000000 / #4a5568

🚀 Tecnologías

React Native: 0.81.4
React: 19.1.0
Expo: ~54.0.13
NativeWind: ^4.2.1
TypeScript: ~5.9.2

📦 Instalación
bash# Clonar el repositorio
git clone [URL_DEL_REPO]

# Instalar dependencias
pnpm install

# Iniciar la aplicación
pnpm start
```

## 🏗️ Estructura del Proyecto
```
mi-primera-app/
├── components/
│   ├── Profilesection.tsx   # Sección de perfil principal
│   ├── ProjectCard.tsx       # Tarjeta de proyecto
│   └── Skillcard.tsx         # Tarjeta de habilidad
├── img/
│   └── cata.jpg             # Imagen de perfil
└── package.json
📱 Componentes
ProfileSection
Componente principal que incluye:

Header con título de la app
Avatar circular con borde
Nombre y profesión
Información de contacto (email, ubicación, GitHub)
Sección "Sobre Mí" con biografía

ProjectCard
Tarjeta reutilizable para proyectos:
typescript<ProjectCard
  emoji="🎨"
  titulo="Nombre del Proyecto"
  descripcion="Descripción breve"
  tags={["React", "TypeScript"]}
/>
SkillCard
Tarjeta para mostrar habilidades:
typescript<SkillCard
  emoji="⚛️"
  nombre="React Native"
  nivel="Avanzado"
/>
🎯 Scripts Disponibles
bashpnpm start      # Inicia Expo
pnpm android    # Ejecuta en Android
pnpm ios        # Ejecuta en iOS
pnpm web        # Ejecuta en navegador
👩‍💻 Desarrolladora
Catalina Perez

📧 Email: cp131537@gmail.com
📍 Ubicación: Bogotá, Colombia
🔗 GitHub: CatalinaP19