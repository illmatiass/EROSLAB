# EROSLAB — Portafolio Interactivo

Sistema creativo con 3 proyectos: EZRA (ropa), SMASH HARD CLUB (burgers), EZRA BOT (trading lab).

---

## 📁 Archivos

| Archivo                  | Qué es                                                  |
| ------------------------ | ------------------------------------------------------- |
| `eroslab.html`           | El lab principal (entrada, transiciones, hubs)          |
| `ezra_manifest.html`     | Brand book de EZRA ropa                                 |
| `ezra_collection.html`   | Web / lookbook de EZRA ropa                             |
| `smash_manifest.html`    | Brand book de SMASH HARD CLUB                           |
| `smash_order.html`       | Web de pedidos de SMASH                                 |
| `ezrabot_manifest.html`  | Brand book de EZRA Bot (opcional, no se usa por ahora)  |

**TODOS los archivos deben estar en la misma carpeta** para que los iframes carguen.

---

## 🚀 Cómo abrirlo

### Opción 1 — Servidor local (recomendado)
1. Abrí PowerShell o terminal en la carpeta del portafolio
2. Corré: `python -m http.server 8000`
3. En el navegador: `http://localhost:8000/eroslab.html`

### Opción 2 — Subir online (Vercel / Netlify)
1. Crear cuenta gratuita en Vercel.com o Netlify.com
2. Drag & drop la carpeta entera
3. Te dan un link tipo `mi-portafolio.vercel.app`
4. Compartilo con clientes / Instagram / donde quieras

---

## 🗺️ Mapa del sistema

```
ENTRY (Enter System)
  └→ TUNNEL (zoom cinemático)
      └→ CORE (los 3 sistemas)
          ├→ EZRA (transición: hilo rojo + letras)
          │   └→ HUB
          │       ├→ ANÁLISIS  → ezra_manifest.html
          │       └→ PÁGINA WEB → ezra_collection.html
          ├→ SMASH HARD CLUB (transición: bars + stamp + neón)
          │   └→ HUB
          │       ├→ ANÁLISIS  → smash_manifest.html
          │       └→ PÁGINA WEB → smash_order.html
          └→ EZRA BOT (transición: terminal boot 3 agents)
              └→ Página de los 3 agentes (sin hub)
```

---

## ⚙️ Para editar contenido

Cualquier archivo se puede editar individualmente:
- Cambiá `ezra_manifest.html` → se actualiza la "ANÁLISIS" de EZRA
- Cambiá `smash_order.html` → se actualiza la web de pedidos
- Etc.

El `eroslab.html` es solo el sistema. Los HTMLs son tu contenido.

---

Built by ErosLAB · v.01
