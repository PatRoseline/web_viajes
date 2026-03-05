# 🌍 Viaja con Nosotros - Web de Viajes

Proyecto colaborativo para crear una página web de destinos de viajes con información, consejos y formulario de contacto.

---

## 📋 Tabla de Contenidos

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Instalación](#instalación)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Cómo Trabajar](#cómo-trabajar)
- [Guía de Git](#guía-de-git)
- [Normas de Codificación](#normas-de-codificación)
- [Contacto](#contacto)

---

## 📝 Descripción del Proyecto

Página web interactiva que muestra:
- **Sección Hero**: Portada con imagen de fondo (parallax effect)
- **Destinos Destacados**: 5 destinos principales (Valle del Rhin, Silicon Valley, Tailandia, Japón-Corea, Aurora Boreal)
- **Consejos de Viaje**: Lista de recomendaciones
- **Tabla de Épocas**: Mejores temporadas para viajar
- **Formulario de Contacto**: Para consultas de usuarios
- **Navbar Responsivo**: Menú navegable en todos los dispositivos

---

## 💻 Instalación

### 1. Clonar el Repositorio

```bash
git clone https://github.com/PatRoseline/web_viajes.git
cd web_viajes
```

### 2. Configurar Git (Primera vez)

```bash
git config user.name "Tu Nombre"
git config user.email "tu_email@gmail.com"
```

### 3. Abrir el Proyecto

Simplemente abre `index.html` en tu navegador o usa un servidor local:

```bash
# Con Python 3
python -m http.server 8000

# Con Python 2
python -m SimpleHTTPServer 8000
```

Luego accede a `http://localhost:8000` en tu navegador.

---

## 📁 Estructura del Proyecto

```
ACT_GRUPAL/
├── index.html              # Página principal
├── aurora.html             # Página destino Aurora Boreal
├── silicon.html            # Página destino Silicon Valley
├── tailandia.html          # Página destino Tailandia
├── valle.html              # Página destino Valle del Rhin
├── japon.html              # Página destino Japón-Corea
├── css/
│   └── style.css           # Estilos personalizados
├── imagenes/
│   ├── hero.jpg            # Imagen hero del sitio
│   ├── parallax.jpg        # Imagen parallax
│   ├── boreal.jpg          # Imagen Aurora Boreal
│   ├── silicon.webp        # Imagen Silicon Valley
│   ├── templo.jpg          # Imagen Tailandia
│   ├── japon.webp          # Imagen Japón
│   └── valle.jpeg          # Imagen Valle del Rhin
├── README.md               # Este archivo
└── .git/                   # Repositorio Git
```

---

## 🚀 Cómo Trabajar

### Crear una Rama para tu Tarea

```bash
# Actualizar rama main
git checkout main
git pull origin main

# Crear rama nueva (ej: para modificar formulario)
git checkout -b feature/mejorar-formulario
```

**Nombres de ramas recomendados:**
- `feature/nombre-funcionalidad` - Para nuevas características
- `bugfix/descripcion-bug` - Para correcciones
- `hotfix/descripcion` - Para arreglos urgentes

### Trabajar Localmente

1. **Modifica los archivos** según tu asignación
2. **Prueba en tu navegador** (abre `index.html`)
3. **Guarda los cambios**

### Hacer Commit y Push

```bash
# Ver cambios realizados
git status

# Agregar cambios
git add .

# O agregar archivos específicos
git add css/style.css index.html

# Crear commit con mensaje descriptivo
git commit -m "Feat: Agregar validación al formulario de contacto"

# Enviar cambios a GitHub
git push origin feature/mejorar-formulario
```

### Crear un Pull Request

1. Ve a https://github.com/PatRoseline/web_viajes
2. Haz clic en "Compare & pull request"
3. Añade descripción de los cambios
4. Solicita revisión a tus compañeros
5. Una vez aprobado, merge a `main`

---

## 📚 Guía de Git

### Comandos Básicos

```bash
# Ver estado del proyecto
git status

# Ver historial de commits
git log --oneline

# Ver cambios realizados (antes de agregar)
git diff

# Actualizar rama actual con cambios remotos
git pull

# Traer cambios de main a tu rama
git rebase origin/main

# Deshacer cambios locales
git checkout -- archivo.html

# Eliminar cambios locales (cuidado)
git reset --hard
```

### Conflictos de Fusión

Si hay conflictos al hacer merge:

1. Abre el archivo en conflicto
2. Busca los marcadores: `<<<<<<<`, `=======`, `>>>>>>>`
3. Resuelve manualmente
4. Guarda el archivo
5. Haz commit: `git commit -m "Resolver conflicto en archivo.html"`

---

## 🎯 Normas de Codificación

### HTML
- Usa indentación de **2 espacios**
- Añade `alt` en todas las imágenes
- Usa comentarios: `<!-- SECCION -->`

### CSS
- Usa clases descriptivas: `.btn-primary`, `.hero-section`
- Agrupa propiedades por tema (colores, fuentes, espaciado)

### Commits
- Mensajes en **inglés o español** (que sea consistente)
- Usa prefijos: `Feat:`, `Fix:`, `Docs:`, `Style:`
- Ejemplos:
  - ✅ `Feat: Agregar sección de opiniones`
  - ✅ `Fix: Corregir responsive en tablet`
  - ❌ `cambios` o `actualización`

### Antes de Publicar

1. **Prueba en navegadores**: Chrome, Firefox, Safari
2. **Revisa responsividad**: Abre con F12 → Responsive Design Mode
3. **Valida HTML**: https://validator.w3.org/

---

## 🤝 Colaboración

### Asignaciones de Tareas

Cada usuario debe trabajar en su rama y los cambios deben pasar por revisión antes de entrar a `main`.

**Personas y sus áreas (ejemplo):**
- PatRose: Estructura general y HTML
- Compañero 2: Estilos CSS
- Compañero 3: Formulario y validación
- Compañero 4: Páginas de destinos

### Reuniones de Sincronización

- Revisar progreso
- Resolver conflictos
- Planificar próximas tareas

---

## 📞 Contacto

**Email del proyecto**: viajaconnosotros@gmail.com  
**Teléfono**: +34 666 666 666  
**Ubicación**: Madrid, España

---

## 📄 Licencia

Proyecto académico - Uso exclusivo del grupo.

---

**¡Bienvenido al equipo! Esperamos tu contribución.** ✈️
