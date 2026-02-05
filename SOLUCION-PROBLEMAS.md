# 🔧 SOLUCIÓN DE PROBLEMAS - Juego no carga

## ❓ ¿Qué hacer si el juego no carga?

### 📋 CHECKLIST RÁPIDO:

#### ✅ 1. Verifica la estructura en GitHub

Tu repositorio debe verse así (NO debe haber carpeta "pandora-github"):

```
tu-repositorio/
├── index.html          ← En la RAÍZ
├── proyecto.html       ← En la RAÍZ
├── equipo.html         ← En la RAÍZ
├── juego.html          ← En la RAÍZ
├── TEST-juego.html     ← NUEVO archivo de prueba
├── assets/             ← Carpeta en la RAÍZ
│   ├── cosobueno.png
│   ├── cosomalo.png
│   ├── fondo.png
│   └── pandoraplayer.png
└── game/               ← Carpeta en la RAÍZ
    ├── p5.min.js
    └── tpfinal2.js
```

#### ✅ 2. Prueba el archivo TEST-juego.html

1. Sube el archivo `TEST-juego.html` a tu repositorio
2. Ve a: `https://TU-USUARIO.github.io/TU-REPO/TEST-juego.html`
3. Lee los mensajes que aparecen:
   - ✅ **Verde**: Todo bien
   - ❌ **Rojo**: Hay un problema

#### ✅ 3. Revisa la Consola del Navegador

1. Presiona **F12** en tu navegador
2. Ve a la pestaña **"Console"**
3. Busca mensajes de error

**Errores comunes y soluciones:**

| Error | Causa | Solución |
|-------|-------|----------|
| `404 - p5.min.js not found` | La carpeta `game/` no está en la raíz | Mueve la carpeta `game/` a la raíz del repo |
| `404 - fondo.png not found` | La carpeta `assets/` no está en la raíz | Mueve la carpeta `assets/` a la raíz del repo |
| `ReferenceError: p5 is not defined` | p5.js no cargó | Usa la versión desde CDN (ver abajo) |
| Canvas en blanco | Los scripts están en el orden incorrecto | Verifica el orden en juego.html |

---

## 🚨 SOLUCIÓN DE EMERGENCIA

Si nada funciona, usa esta versión alternativa que carga p5.js desde internet:

### En `juego.html`, reemplaza estas líneas:

**ANTES (puede fallar):**
```html
<script src="game/p5.min.js"></script>
<script src="game/tpfinal2.js"></script>
```

**DESPUÉS (siempre funciona):**
```html
<script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.7.0/p5.min.js"></script>
<script src="game/tpfinal2.js"></script>
```

---

## 📸 ¿Cómo debe verse tu repositorio en GitHub?

Cuando entres a tu repositorio en GitHub.com debes ver:

```
📁 assets
📁 game
📄 equipo.html
📄 index.html
📄 juego.html
📄 proyecto.html
📄 README.md
📄 TEST-juego.html
```

⚠️ **NO debe decir:**
```
📁 pandora-github    ← ❌ INCORRECTO
```

---

## 🔄 ¿Subiste la carpeta completa por error?

Si ves `pandora-github/` en tu repo, haz esto:

1. Borra TODO en tu repositorio
2. Descomprime el ZIP
3. Entra a la carpeta `pandora-github/`
4. Sube SOLO el contenido (los archivos HTML y las carpetas assets y game)

---

## 💬 Todavía no funciona?

Mándame:
1. La URL de tu GitHub Pages
2. Captura de pantalla de la consola (F12)
3. Captura de tu repositorio en GitHub

Y te ayudo a solucionarlo!
