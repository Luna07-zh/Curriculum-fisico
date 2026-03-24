## Cómo conectar la foto (sin errores)

Tu HTML ya está programado para buscar esta ruta:

```html
photo: "./foto-cv.png"
```

Eso significa **una sola cosa**:

👉 La imagen debe estar en la **misma carpeta** que el archivo HTML
👉 Y debe llamarse exactamente: `foto-cv.png`

### Estructura correcta de carpeta

```
/CV/
 ├── index-ventas.html
 ├── index-operativo.html
 ├── index-documento-impreso.html
 └── foto-cv.png
```

### Errores típicos (evítalos)

* ❌ `foto.png` → no carga
* ❌ `Foto-CV.png` → mayúsculas importan
* ❌ `foto-cv.jpg` → formato distinto
* ❌ Imagen en otra carpeta → no la encuentra

Si quieres usar `.jpg`, cambia esto en el HTML:

```js
photo: "./foto-cv.jpg"
```

---

## Cómo abrirlos (no te compliques)

### Método 1 (el correcto y suficiente)

1. Ve a la carpeta
2. Doble clic en:

   * `index-ventas.html` (por ejemplo)

👉 Se abre en tu navegador (Chrome, Edge, etc.)

---

### Método 2 (si no abre bien)

1. Click derecho
2. “Abrir con”
3. Elige Chrome o Edge

---

## Cómo exportarlo a PDF (importante)

Dentro del archivo verás un botón:

👉 **“Imprimir / guardar como PDF”**

O haz:

* `Ctrl + P`

Luego:

* Destino → **Guardar como PDF**
* Activar: ✅ *Gráficos de fondo* (clave para el diseño)

---

## Cómo usar esto estratégicamente (aquí te corrijo)

No hiciste todo esto para “tener archivos bonitos”.

Debes usarlo así:

### 1. Subirlos a GitHub

Ahí se vuelven accesibles con link

### 2. Convertir ese link en QR

👉 Lo pones en tu CV físico

### 3. Usar uno distinto por puesto

* ventas → `index-ventas`
* operativo → `index-operativo`
* administrativo → `index-documento`

Eso te vuelve **10x más precisa que el promedio**

---

## Si la foto NO carga

Haz esto:

1. Abre el HTML
2. Click derecho → inspeccionar
3. Busca `foto-cv.png`
4. Si sale error → el nombre está mal (siempre es eso)

---

Si quieres, en el siguiente paso te armo:

* el GitHub listo (estructura exacta)
* el link público
* y el QR directo para tu CV

Ahí pasas de “tener archivos” a “tener presencia profesional real”.
