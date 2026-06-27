# 🤍 Sitio para Vanessa

Página web hecha con amor para Vanessa.

## Estructura de archivos

```
/
├── index.html        ← Página principal
├── card.html         ← Tarjeta interactiva (se carga dentro de index.html)
├── README.md         ← Este archivo
└── imagenes/         ← CARPETA CON TODAS LAS FOTOS
    ├── 2026-06-26_19-44-43_475.jpg
    ├── 2026-06-26_19-44-43_517.jpg
    ├── ... (todas las fotos)
    └── 2026-06-26_19-44-44_777.jpg
```

## Cómo subir a GitHub Pages

1. Crea un repositorio en GitHub (puede ser público o privado con GitHub Pro)
2. Sube todos estos archivos al repositorio
3. Ve a **Settings → Pages → Source: main branch / root**
4. Tu sitio estará en: `https://tuusuario.github.io/nombre-del-repo/`

## Personalizar los seguidores

En `index.html`, busca la sección `// ─── FOLLOWERS ───` y reemplaza el array `followers` con los datos reales del archivo Excel (nombres de usuario de Instagram).

Ejemplo:
```js
var followers = [
  { name: "nombre_usuario_real", emoji: "🌸" },
  { name: "otro_usuario", emoji: "✨" },
  // ...
];
```

## Notas

- La carpeta `imagenes/` debe contener exactamente los archivos con los nombres originales
- La foto principal de la tarjeta usa `imagenes/2026-06-26_19-44-44_729.jpg`
- El sitio funciona sin servidor — es 100% HTML/CSS/JS estático
