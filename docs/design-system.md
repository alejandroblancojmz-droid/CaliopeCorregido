# Design System - Caliope

## Diseño UX/UI

El diseño de la plataforma está enfocado en brindar una experiencia agradable, intuitiva y accesible para lectores y escritores. Se busca una interfaz limpia, moderna y fácil de navegar tanto en dispositivos móviles como en computadoras.

Se toman en cuenta los siguientes principios:
- Usabilidad  
- Accesibilidad  
- Navegación intuitiva  
- Interacción sencilla  
- Diseño responsivo  

---

## Paleta de colores

### Modo claro ☀️

| Uso | Color | HEX |
|-----|------|------|
| Primario | Morado | #633BBC |
| Secundario | Lila suave | #EFE9F9 |
| Fondo general | Fondo app | #F6F5FA |
| Tarjetas / Paneles | Blanco | #FFFFFF |
| Inputs | Fondo inputs | #FBFBFF |
| Títulos | Texto principal | #1C1236 |
| Texto cuerpo | Texto base | #3A2F5A |
| Texto secundario | Subtítulos | #82779A |

---

### Modo oscuro 🌙

| Uso | Color | HEX |
|-----|------|------|
| Fondo general | Fondo app | #130F26 |
| Tarjetas / Paneles | Superficie | #1D183A |
| Inputs | Fondo inputs | #252048 |
| Primario | Morado | #7A52E1 |
| Secundario | Tags fondo | #2D2354 |
| Texto en tags | Lila claro | #A29BFE / #BDB2FF |
| Títulos | Texto principal | #F4F2FA |
| Texto cuerpo | Texto base | #C3BCDB |
| Texto secundario | Subtítulos | #7E7599 |
| Bordes | Separadores | #2F2958 |

---

### Colores de acento (ambos modos)

| Uso | Color | HEX |
|-----|------|------|
| Rating | Amarillo | #F1C40F |
| Éxito | Verde | #2ECC71 |
| Éxito (alternativo) | Verde oscuro | #27AE60 |
| Alerta | Naranja | #FF9F43 |
| Alerta (alternativo) | Naranja oscuro | #E67E22 |

---

### Uso de colores

- **Morado principal:** Botones principales (CTA), navegación activa, enlaces e iconos importantes  
- **Lila suave:** Tags, estados secundarios y acentos  
- **Blanco / Superficies:** Tarjetas y bloques principales  
- **Fondo app:** Base general de la interfaz  
- **Inputs:** Formularios y campos de texto  
- **Textos:** Jerarquía clara entre títulos, cuerpo y secundarios  

---

## Tipografía

### Fuente principal (UI / Interfaz)
**Plus Jakarta Sans**

Uso:
- Botones  
- Navegación (Sidebar)  
- Formularios  
- Etiquetas del sistema  

Pesos:
- 400 (Regular)  
- 500 (Medium)  
- 700 (Bold)  

---

### Fuente secundaria (Lectura / Editorial)
**Lora**  
(Alternativa: *Playfair Display*)

Uso:
- Títulos de obras  
- Capítulos  
- Textos literarios  

Pesos:
- 400 (Regular)  
- 600 (Semi-Bold)  
- 700 (Bold)  

---

## Unidades de medida

- **rem:** tamaños de texto, márgenes, padding  
- **px:** bordes, sombras y detalles precisos  
- **% / vw / vh:** diseño responsivo  

---

## Botones

### Botón primario
- Color claro: #633BBC  
- Color oscuro: #7A52E1  
- Texto: #FFFFFF  
- Bordes: 8px – 12px  

### Botón secundario
- Fondo claro: #EFE9F9  
- Fondo oscuro: #2D2354  
- Texto: morado  

### Interacción
- Hover suave  
- Transición:
```css
transition: background-color 0.3s ease;