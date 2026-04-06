---
name: ai-image-generator
description: Expert in generating and sourcing copyright-free images for marketing projects, especially landing pages, social media ads, and clinic/aesthetic industry materials. Use when the user asks to generate images with AI, find free stock photos, get images for landing pages, create visuals for ads without copyright issues, or source before/after style photos for aesthetic clinics. Covers AI generation tools (free and paid), stock photo APIs (Pexels, Pixabay, Unsplash), prompt engineering for image generation, and legal licensing knowledge (Creative Commons, public domain, commercial use).
---

# 🎨 Skill Experta: Generación y Obtención de Imágenes Libres de Derechos

## Cuando Activar Esta Skill

Usa esta skill cuando el usuario:
- Pida generar imágenes con IA para su proyecto
- Necesite fotos libres de derechos para landing pages o ads
- Quiera imágenes para campañas de redes sociales sin problemas de copyright
- Solicite fotos de clínicas, tratamientos estéticos, o antes/después
- Necesite prompts para generar imágenes específicas con IA
- Quiera saber qué fuentes de imágenes gratis son seguras legalmente

---

## 📋 Resumen Ejecutivo

Esta skill tiene **2 vías** para obtener imágenes:

| Vía | Cuándo usar | Pros | Contras |
|-----|-------------|------|---------|
| **1. IA Generativa** | Necesitas algo específico que no existe en stock | Personalizado, único, sin límites | Requiere prompt engineering, algunas herramientas tienen límites |
| **2. Stock Photos (APIs)** | Necesitas fotos realistas rápidas de personas/lugares | Gratis, alta calidad, instantáneo | Menos personalizable |

---

## 🤖 VÍA 1: Generación de Imágenes con IA

### Herramientas Gratuitas (2025-2026)

#### Tier 1: Mejor Calidad / Gratis

| Herramienta | Límite gratis | Uso comercial | Watermark | URL |
|-------------|---------------|---------------|-----------|-----|
| **Leonardo.ai** | 150 créditos/día | ✅ Sí | ❌ No | leonardo.ai |
| **Bing Image Creator (DALL-E 3)** | 15 boosts/día, luego más lento | ✅ Sí | ❌ No | bing.com/images/create |
| **Ideogram** | 10-20 prompts/día | ✅ Sí | ❌ No | ideogram.ai |
| **Playground AI** | 500 imágenes/día | ✅ Sí | ❌ No | playgroundai.com |
| **SeaArt.ai** | 100+ créditos/día | ✅ Sí | ❌ No | seaart.ai |

#### Tier 2: APIs Programáticas (para automatizar)

| API | Precio gratis | Modelo | URL |
|-----|---------------|--------|-----|
| **Stability AI API** | 25 créditos iniciales | API REST | stability.ai |
| **OpenAI DALL-E API** | $ de crédito inicial | API REST | platform.openai.com |
| **Together AI** | $25 crédito gratis | API REST | together.ai |
| **Fal.ai** | Créditos iniciales gratis | API REST | fal.ai |

### Prompt Engineering para Imágenes de Clínicas/Estética

#### Fórmula del Prompt Perfecto:

```
[Sujeto] + [Entorno] + [Estilo visual] + [Iluminación] + [Composición] + [Calidad]
```

#### Prompts Listos para NutriHealth / Clínica Estética:

##### 1. Hero — Mujer satisfecha con tratamiento facial
```
A radiant 40-year-old Latina woman with glowing smooth skin, 
gently touching her cheek with a confident smile, 
in a modern bright aesthetic clinic with white and green tones, 
natural window lighting, shot on Canon EOS R5, 85mm lens, 
shallow depth of field, professional commercial photography, 
ultra realistic, 4K quality --ar 16:9 --v 6
```

##### 2. Antes/Después estilo (sin ser médico)
```
Split screen comparison, left side: woman with visible facial 
wrinkles and dull skin looking concerned, right side: same woman 
with refreshed youthful glowing skin smiling confidently, 
clean white background, professional medical aesthetic photography, 
softbox lighting, high detail --ar 16:9
```

##### 3. Tratamiento corporal — Mujer en consulta
```
Professional female doctor in white coat consulting with a 
35-year-old female patient in a modern aesthetic clinic, 
pointing at a digital body analysis screen, warm natural light, 
clean minimalist interior with plants, commercial healthcare 
photography, authentic candid moment --ar 16:9 --v 6
```

##### 4. Lifestyle — Mujer confiada y atractiva
```
Confident 45-year-old Latina woman with voluminous healthy hair 
and radiant skin, wearing elegant casual outfit, walking through 
a bright modern city street, golden hour warm sunlight, 
lifestyle commercial photography, natural authentic expression, 
shallow depth of field --ar 4:5 --v 6
```

##### 5. Consultorio / Clínica
```
Modern aesthetic clinic interior, clean white and green color 
scheme, advanced non-invasive treatment equipment visible, 
soft ambient lighting, plants for natural touch, wide angle 
architectural photography, bright and welcoming atmosphere, 
professional interior photography --ar 16:9
```

##### 6. Procedimiento (genérico, no gráfico)
```
Close-up of aesthetic professional's hands gently applying 
a treatment device to a relaxed patient's face, soft clinical 
lighting, focus on the technology and patient comfort, 
clean modern clinic environment, professional medical 
photography style, reassuring atmosphere --ar 16:9
```

##### 7. Trasplante Capilar — Doctor consultando
```
Professional male hair transplant surgeon in modern clinic, 
consulting with a male patient, examining scalp with digital 
tablet showing hair density analysis, clean bright medical 
office, professional healthcare photography, natural 
window light, trustworthy confident expression --ar 16:9
```

##### 8. Trasplante Capilar — Resultado lifestyle
```
Confident 35-year-old man with full natural-looking hairline, 
smiling at camera in an urban outdoor setting, golden hour 
lighting, lifestyle commercial photography, authentic happy 
expression, shallow depth of field, modern professional look --ar 4:5
```

#### Parámetros Importantes:

| Parámetro | Función | Valores comunes |
|-----------|---------|-----------------|
| `--ar 16:9` | Aspect ratio (landscape) | Para hero de web |
| `--ar 4:5` | Aspect ratio (vertical) | Para Instagram/Facebook ads |
| `--ar 1:1` | Cuadrado | Para posts genéricos |
| `--ar 9:16` | Vertical | Para Stories/Reels/TikTok |
| `--v 6` | Versión del modelo (Midjourney) | Mayor = mejor calidad |
| `--style raw` | Menos estilizado, más realista | Para fotos tipo clínico |

#### Reglas para Prompts de Imágenes de Clínicas:
- ✅ Especificar edad aproximada del sujeto (30-50 para público objetivo)
- ✅ Incluir etnia relevante (Latina para mercado hispano)
- ✅ Pedir iluminación específica (natural, golden hour, softbox)
- ✅ Incluir estilo de fotografía (comercial, lifestyle, profesional)
- ✅ Pedir "authentic" y "natural" para evitar look artificial de IA
- ❌ No pedir primeros planos extremos de procedimientos médicos
- ❌ Evitar "perfect" (genera look irreal)
- ❌ No incluir logos, marcas ni texto en la imagen

---

## 📸 VÍA 2: Stock Photos con APIs (Gratis, Sin Copyright)

### Las 3 Mejores APIs Gratuitas

#### 1. Pexels API

| Detalle | Info |
|---------|------|
| **Licencia** | Pexels License — Gratis para uso comercial |
| **Atribución** | No requerida (opcional) |
| **Rate limit** | 200 requests/hora |
| **API Key** | Gratis en pexels.com/api |
| **Formato** | JSON |

**Endpoint:**
```
GET https://api.pexels.com/v1/search?query={query}&per_page={n}&page={page}
Header: Authorization: {TU_API_KEY}
```

**Ejemplo de búsqueda para clínica estética:**
```
GET https://api.pexels.com/v1/search?query=aesthetic+clinic+interior&per_page=15
GET https://api.pexels.com/v1/search?query=women+skincare+treatment&per_page=15
GET https://api.pexels.com/v1/search?query=beautiful+woman+confident+smile&per_page=15
GET https://api.pexels.com/v1/search?query=doctor+consulting+patient&per_page=15
GET https://api.pexels.com/v1/search?query=hair+restoration+result&per_page=15
```

**Queries recomendados para NutriHealth:**
- `aesthetic clinic modern`
- `woman glowing skin natural`
- `healthcare professional woman`
- `facial treatment spa`
- `nutrition consultation`
- `wellness center interior`
- `happy mature woman portrait`
- `body contouring treatment`

#### 2. Pixabay API

| Detalle | Info |
|---------|------|
| **Licencia** | Pixabay Content License — Uso comercial sin atribución |
| **Rate limit** | 100 requests/minuto |
| **API Key** | Gratis en pixabay.com/api/docs |
| **Requisito** | Cachear respuestas 24 horas |

**Endpoint:**
```
GET https://pixabay.com/api/?key={KEY}&q={query}&image_type=photo&per_page=15
```

**Queries recomendados:**
- `beautiful woman skin care`
- `modern clinic interior`
- `doctor consultation`
- `healthy nutrition food`
- `wellness spa treatment`
- `confident professional woman`

#### 3. Unsplash API

| Detalle | Info |
|---------|------|
| **Licencia** | Unsplash License — Uso comercial sin atribución |
| **Rate limit** | 50 requests/hora (demo) |
| **API Key** | Gratis en unsplash.com/developers |

**Endpoint:**
```
GET https://api.unsplash.com/search/photos?query={query}&per_page=15&client_id={KEY}
```

### Comparación Rápida

| Fuente | Mejor para | Calidad | Cantidad |
|--------|-----------|---------|----------|
| **Pexels** | Fotos de personas y clínicas | ⭐⭐⭐⭐⭐ | +3M |
| **Pixabay** | Variedad general | ⭐⭐⭐⭐ | +4M |
| **Unsplash** | Fotos lifestyle/artísticas | ⭐⭐⭐⭐⭐ | +3M |

---

## ⚖️ Guía de Licencias de Imágenes

### Qué PUEDES hacer sin riesgo legal:

| Fuente | Uso comercial | Modificar | Atribución necesaria |
|--------|---------------|-----------|---------------------|
| IA generativa (Leonardo, DALL-E, etc.) | ✅ Sí | ✅ Sí | ❌ No |
| Pexels | ✅ Sí | ✅ Sí | ❌ No (opcional) |
| Pixabay | ✅ Sí | ✅ Sí | ❌ No |
| Unsplash | ✅ Sí | ✅ Sí | ❌ No (opcional) |
| Wikimedia Commons (CC-BY-SA) | ✅ Sí | ✅ Sí | ✅ Sí |
| Google Images | ❌ NO | ❌ NO | ❌ NO (ilegal) |
| Instagram/Facebook | ❌ NO | ❌ NO | ❌ NO (ilegal) |

### Reglas de Oro:
1. ✅ **NUNCA** usar imágenes de Google Images sin verificar licencia
2. ✅ **NUNCA** usar fotos de redes sociales de otras clínicas
3. ✅ **SIEMPRE** verificar que la licencia permite uso comercial
4. ✅ **SIEMPRE** descargar y alojar en tu servidor (no hotlinking)
5. ✅ **GUARDAR** el archivo de licencia/fuente de cada imagen

### ⚠️ Advertencia sobre Antes/Después:
- Las fotos reales de antes/después **siempre** deben ser de **tus propios pacientes**
- Las fotos generadas por IA de "antes/después" son para **ilustración general**, NO como testimonio real
- Para testimonios reales: usar SOLO fotos documentadas de la clínica

---

## 🛠️ Scripts de Automatización

### Script Python: Descargar imágenes de Pexels

```python
import requests
import os

PEXELS_API_KEY = "TU_API_KEY_AQUI"
HEADERS = {"Authorization": PEXELS_API_KEY}

def download_pexels_images(query, count=10, folder="images"):
    """Download images from Pexels API for a given query."""
    os.makedirs(folder, exist_ok=True)
    
    url = f"https://api.pexels.com/v1/search?query={query}&per_page={count}"
    response = requests.get(url, headers=HEADERS)
    
    if response.status_code == 200:
        photos = response.json().get("photos", [])
        for i, photo in enumerate(photos):
            img_url = photo["src"]["large2x"]  # High res
            img_response = requests.get(img_url)
            
            file_path = os.path.join(folder, f"{query}_{i+1}.jpg")
            with open(file_path, "wb") as f:
                f.write(img_response.content)
            
            print(f"✅ Descargada: {file_path}")
            print(f"   Fotógrafo: {photo['photographer']} (Pexels)")
    else:
        print(f"❌ Error: {response.status_code}")

# Ejemplo de uso:
# download_pexels_images("aesthetic clinic", 10, "clinic")
# download_pexels_images("woman confident smile", 10, "hero")
# download_pexels_images("skincare treatment", 10, "treatment")
```

### Script Python: Descargar imágenes de Pixabay

```python
import requests
import os

PIXABAY_KEY = "TU_API_KEY_AQUI"

def download_pixabay_images(query, count=10, folder="images"):
    """Download images from Pixabay API for a given query."""
    os.makedirs(folder, exist_ok=True)
    
    url = f"https://pixabay.com/api/?key={PIXABAY_KEY}&q={query}&image_type=photo&per_page={count}"
    response = requests.get(url)
    
    if response.status_code == 200:
        hits = response.json().get("hits", [])
        for i, hit in enumerate(hits):
            img_url = hit.get("largeImageURL", hit.get("webformatURL"))
            img_response = requests.get(img_url)
            
            file_path = os.path.join(folder, f"{query}_{i+1}.jpg")
            with open(file_path, "wb") as f:
                f.write(img_response.content)
            
            print(f"✅ Descargada: {file_path}")
    else:
        print(f"❌ Error: {response.status_code}")

# Ejemplo de uso:
# download_pixabay_images("nutrition consultation", 10, "nutrition")
```

---

## 🎯 Guía Rápida: Qué Imagen Para Cada Sección de Landing Page

| Sección de Landing | Tipo de Imagen | Fuente recomendada | Prompt/Query |
|--------------------|----------------|--------------------|--------------|
| **Hero** | Mujer atractable, confianza | Pexels o IA | `confident beautiful woman 40s portrait` |
| **Problema** | Mujer frustrada/mirándose espejo | IA generativa | `woman looking mirror concerned about skin` |
| **Solución** | Doctora con paciente, tecnología | Pexels o IA | `female doctor consulting patient modern clinic` |
| **Prueba social** | ANTES/DESPUÉS reales | **FOTOS REALES de la clínica** | — |
| **Oferta** | Lifestyle, aspiracional | Pexels | `happy woman outdoor golden hour` |
| **FAQ** | Íconos/ilustraciones | IA generativa | `minimalist medical icon, clean design` |
| **CTA Final** | Resultado aspiracional | IA o Pexels | `radiant woman confident smile natural light` |

---

## 📐 Especificaciones de Imagen por Plataforma

### Landing Page (Web)
| Uso | Tamaño recomendado | Formato | Peso máximo |
|-----|-------------------|---------|-------------|
| Hero background | 1920x1080px | WebP/JPG | <300KB |
| Sección imagen | 1200x800px | WebP/JPG | <200KB |
| Testimonio foto | 200x200px | WebP/JPG | <50KB |
| Icono/ícono | 64x64px | SVG/PNG | <10KB |

### Facebook/Instagram Ads
| Formato | Tamaño | Aspect Ratio |
|---------|--------|-------------|
| Feed image | 1080x1080px | 1:1 |
| Feed landscape | 1080x566px | 1.91:1 |
| Story/Reel | 1080x1920px | 9:16 |
| Carousel | 1080x1080px cada una | 1:1 |

### Google Ads
| Formato | Tamaño | Aspect Ratio |
|---------|--------|-------------|
| Landscape | 1200x628px | 1.91:1 |
| Square | 1200x1200px | 1:1 |
| Portrait | 960x1200px | 4:5 |

---

## 🔧 Flujo de Trabajo Recomendado

### Para generar una imagen perfecta para tu landing:

```
Paso 1: Identificar qué necesitas
   ↓ ¿Qué sección de la landing?
   ↓ ¿Qué emoción debe transmitir?
   ↓ ¿Qué formato/tamaño necesitas?

Paso 2: Elegir la vía
   ↓ ¿Existe en stock? → Pexels/Pixabay/Unsplash
   ↓ ¿Necesitas algo específico? → IA Generativa
   ↓ ¿Necesitas ANTES/DESPUÉS real? → Fotos de la clínica

Paso 3: Generar/Descargar
   ↓ Crear prompt (si IA) con la fórmula incluida
   ↓ O buscar con queries optimizados (si stock)
   ↓ Generar 4-8 variantes

Paso 4: Seleccionar y optimizar
   ↓ Elegir la mejor
   ↓ Redimensionar al tamaño correcto
   ↓ Comprimir a WebP
   ↓ Guardar con nombre descriptivo

Paso 5: Documentar
   ↓ Guardar fuente/licencia de la imagen
   ↓ Anotar prompt usado (para replicar)
```

---

## 💡 Tips Pro

### Para que las imágenes de IA parezcan reales:
1. Añadir `"authentic photography"` al prompt
2. Usar `"shot on Canon EOS R5, 85mm"` para look profesional
3. Añadir `"natural lighting"` en vez de "studio lighting"
4. Pedir `"slight imperfections"` para evitar perfección artificial
5. Incluir `"commercial photography style, editorial quality"`

### Para imágenes de clínicas que conviertan:
1. **Personas > Objetos:** Fotos con personas convierten 40%+ más
2. **Mirada a cámara:** Personas mirando al usuario generan confianza
3. **Emoción positiva:** Sonrisas naturales, no forzadas
4. **Diversidad étnica:** Importante para mercado hispano
5. **Colores de marca:** Incluir verde/blanco (colores de NutriHealth) en el prompt

### Para Before/After con IA (ilustración, NO testimonio):
```
Important: These are illustrative only, not real patient results.
Side by side comparison, mature woman with visible signs of 
aging on left — fine lines, dull complexion, sagging skin. 
Same woman on right with refreshed youthful appearance — 
smoother skin, natural glow, lifted contour. Clean white 
background, professional aesthetic photography style, 
realistic not exaggerated --ar 16:9
```

---

## ✅ Checklist: Imagen Lista para Producción

```
✅ Imagen generada/descargada de fuente legal
✅ Licencia verificada para uso comercial
✅ Redimensionada al tamaño correcto
✅ Comprimida (WebP, <300KB para hero)
✅ Nombrada descriptivamente (hero-woman-confident.jpg)
✅ Fuente/licencia documentada en spreadsheet
✅ Se ve bien en móvil (testeada)
✅ No distrae del CTA principal
✅ Colores alineados con marca NutriHealth
✅ Persona relevante al avatar objetivo (30-55, latino)
```

---

## 🚀 Acceso Rápido

### Comandos que puedes dar a esta skill:

| Comando | Qué hace |
|---------|----------|
| "Genera una imagen para el hero de NutriHealth" | Crea prompt + sugiere herramienta + genera |
| "Dame 5 prompts para imágenes de trasplante capilar" | Genera prompts listos para copiar |
| "Busca fotos de clínica estética en Pexels" | Da queries optimizados + URLs de API |
| "¿Puedo usar esta imagen de Google en mi landing?" | Verifica licencias y dice si es legal |
| "Optimiza esta imagen para web" | Da instrucciones de compresión/formato |
| "Dame un script para bajar 50 fotos de stock" | Proporciona script Python personalizado |
| "¿Qué imagen pongo en la sección de testimonios?" | Guía específica por sección de landing |
| "Crea variantes de imagen para testear A/B" | Genera 3-5 prompts alternativos |

---

> **Mantra de esta Skill:** *"La imagen perfecta no es la más bonita — es la que hace que el visitante se diga: 'yo quiero sentirme así' y haga clic en Agendar."*
