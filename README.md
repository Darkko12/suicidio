# 🏺 Pandora: Los Males Desatados

Aventura gráfica interactiva basada en el mito griego de la Caja de Pandora.

**Trabajo Práctico Final - Parte 2**  
Programación Orientada a Objetos - PMIW 2025

---

## 📋 Descripción del Proyecto

Este proyecto es una aventura gráfica interactiva desarrollada con JavaScript y p5.js, implementando Programación Orientada a Objetos. El juego está inspirado en el mito griego de Pandora y desafía al jugador a recapturar los espíritus malignos que escaparon de la famosa caja.

### Características

- ✨ Juego desarrollado con **p5.js** y **POO**
- 🎨 Arte y diseño original inspirado en la mitología griega
- 🌐 Sitio web con **Bootstrap 5** (framework)
- 📱 Diseño responsive (adaptable a móviles)
- 🎯 3 páginas principales: Inicio, Proyecto y Equipo
- 🎮 Acceso directo al juego

---

## 🚀 Publicar en GitHub Pages - PASO A PASO

### **PASO 1: Crear Cuenta en GitHub (si no tienes una)**

1. Ve a [https://github.com](https://github.com)
2. Haz clic en "Sign up"
3. Completa el formulario con tu email, contraseña y nombre de usuario
4. Verifica tu email

---

### **PASO 2: Crear Nuevo Repositorio**

1. Una vez logueado, haz clic en el botón **"+"** (arriba a la derecha) → **"New repository"**
2. Completa los datos:
   - **Repository name**: `pandora-juego` (o el nombre que prefieras)
   - **Description**: "Juego Pandora - TP Final PMIW"
   - Selecciona **"Public"** (para que GitHub Pages funcione gratis)
   - ✅ Marca **"Add a README file"**
3. Haz clic en **"Create repository"**

---

### **PASO 3: Subir los Archivos**

Hay dos formas de subir los archivos:

#### **Opción A: Usando la Interfaz Web (Más Fácil)**

1. En tu repositorio, haz clic en **"Add file"** → **"Upload files"**
2. Arrastra TODOS los archivos y carpetas del proyecto:
   - `index.html`
   - `proyecto.html`
   - `equipo.html`
   - `juego.html`
   - Carpeta `assets/` (con todas las imágenes)
   - Carpeta `game/` (con p5.min.js y tpfinal2.js)
3. Escribe un mensaje como: "Subir proyecto completo"
4. Haz clic en **"Commit changes"**

⚠️ **IMPORTANTE**: Asegúrate de mantener la estructura de carpetas tal cual está:
```
📁 pandora-juego/
├── 📄 index.html
├── 📄 proyecto.html
├── 📄 equipo.html
├── 📄 juego.html
├── 📁 assets/
│   ├── cosobueno.png
│   ├── cosomalo.png
│   ├── fondo.png
│   └── pandoraplayer.png
└── 📁 game/
    ├── p5.min.js
    └── tpfinal2.js
```

#### **Opción B: Usando Git (Para quienes conocen Git)**

```bash
git clone https://github.com/TU-USUARIO/pandora-juego.git
cd pandora-juego
# Copia todos tus archivos aquí
git add .
git commit -m "Agregar proyecto Pandora"
git push origin main
```

---

### **PASO 4: Activar GitHub Pages**

1. En tu repositorio, ve a **"Settings"** (Configuración)
2. En el menú lateral izquierdo, busca y haz clic en **"Pages"**
3. En la sección **"Source"** (Branch):
   - Selecciona **"main"** (o "master" dependiendo de tu repo)
   - Deja la carpeta en **"/ (root)"**
4. Haz clic en **"Save"**
5. Espera 1-2 minutos y refresca la página

---

### **PASO 5: Ver tu Sitio en Línea**

1. En la misma página de "Pages" verás un mensaje que dice:
   > **"Your site is live at https://TU-USUARIO.github.io/pandora-juego/"**

2. Haz clic en ese link o cópialo y pégalo en tu navegador

3. ¡Tu sitio ya está publicado! 🎉

**Tu URL será:**
```
https://TU-USUARIO.github.io/pandora-juego/
```

---

## 🎮 Estructura del Sitio

### **Página Principal (index.html)**
- Hero section con presentación del juego
- Información general y características
- Controles del juego
- Botón para jugar

### **El Proyecto (proyecto.html)**
- Explicación del mito de Pandora
- Proceso de producción del juego
- Tecnologías utilizadas
- Características técnicas

### **Equipo (equipo.html)**
- Información de los integrantes
- Roles y responsabilidades
- Contexto académico
- Herramientas utilizadas

### **Jugar (juego.html)**
- Canvas del juego integrado
- Instrucciones de control
- Juego completamente funcional

---

## 🛠️ Tecnologías Utilizadas

### **Juego**
- JavaScript (ES6+)
- p5.js
- Programación Orientada a Objetos (POO)
- Canvas API

### **Sitio Web**
- HTML5
- CSS3
- **Bootstrap 5** (Framework requerido)
- Font Awesome (Iconos)
- Google Fonts

---

## 👥 Equipo

- **Darkko Nair Jorajuria Etchevarne** - Legajo: 122739/6
  - Programación, arquitectura POO, game design
  
- **Seanna Ursula Sarlangue** - Legajo: 122892/5
  - Diseño visual, arte, programación

---

## 📝 Notas Importantes

### **Requisitos del TP Cumplidos:**
✅ Framework implementado: **Bootstrap 5**  
✅ Tres páginas/secciones: Inicio, Proyecto, Equipo + Juego  
✅ Información sobre temática, proceso y equipo  
✅ Acceso directo a la aventura gráfica  
✅ Tratamiento gráfico acorde a la temática  
✅ Publicado en **GitHub Pages**

### **Si algo no funciona:**

1. **Las imágenes no cargan**: Verifica que las carpetas `assets/` y `game/` estén en la raíz del repositorio
2. **El juego no funciona**: Asegúrate de que los archivos `.js` estén en la carpeta `game/`
3. **GitHub Pages no se activa**: Espera unos minutos, a veces tarda en propagarse

---

## 📞 Contacto

Para cualquier consulta sobre el proyecto:
- Repositorio: [GitHub Link]
- Sitio en vivo: [GitHub Pages URL]

---

## 📄 Licencia

Este proyecto es parte de un trabajo académico para PMIW 2025.

**© 2025 - Programación Orientada a Objetos - PMIW**
