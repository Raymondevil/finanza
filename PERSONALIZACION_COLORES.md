# 🎨 Guía de Personalización de Colores

## 📖 Cómo Cambiar los Colores de tu Página Web

Tu página web ahora incluye un sistema completo de personalización de colores que te permite cambiar fácilmente toda la apariencia visual.

## 🛠️ Pasos para Personalizar Colores

### 1. Abrir el Archivo de Colores
Navega al archivo: `css/custom-colors.css`

### 2. Encontrar las Variables de Color
En la parte superior del archivo verás una sección que comienza con:
```css
:root {
    /* === COLORES PRINCIPALES === */
    --primary-color: #3B82F6;          /* Azul principal */
    --secondary-color: #8B5CF6;        /* Morado secundario */
    --accent-color: #10B981;           /* Verde de acento */
    /* ... más colores ... */
}
```

### 3. Cambiar los Colores
Simplemente reemplaza los códigos de color hexadecimal (#XXXXXX) por los que prefieras:

```css
/* EJEMPLO: Cambiar a tema rojo */
--primary-color: #DC2626;          /* Rojo principal */
--secondary-color: #7C2D12;        /* Rojo oscuro secundario */
--accent-color: #EF4444;           /* Rojo de acento */
```

## 🎨 Temas Predefinidos

El archivo incluye 4 temas listos para usar. Para activar cualquiera de ellos:

### 🌙 Tema Oscuro
1. Busca la sección "TEMA OSCURO" en el CSS
2. Elimina los `/*` y `*/` de esa sección
3. Comenta (agrega `/*` y `*/`) la sección `:root` original

### 🌿 Tema Verde Naturaleza
1. Busca la sección "TEMA VERDE NATURALEZA"
2. Elimina los `/*` y `*/` de esa sección
3. Comenta la sección `:root` original

### 💼 Tema Azul Profesional
1. Busca la sección "TEMA AZUL PROFESIONAL"
2. Elimina los `/*` y `*/` de esa sección
3. Comenta la sección `:root` original

## 🔧 Variables de Color Disponibles

### Colores Principales
- `--primary-color`: Color principal del sitio
- `--secondary-color`: Color secundario
- `--accent-color`: Color de acento para destacar
- `--warning-color`: Color de advertencia (naranja)
- `--danger-color`: Color de peligro (rojo)

### Colores de Fondo
- `--bg-primary`: Fondo principal de la página
- `--bg-secondary`: Fondo secundario
- `--bg-card`: Fondo de las tarjetas
- `--bg-accent`: Fondo de acento

### Colores de Texto
- `--text-primary`: Texto principal
- `--text-secondary`: Texto secundario
- `--text-muted`: Texto atenuado
- `--text-white`: Texto blanco

### Colores Específicos por Sección
- `--dias-color`: Color para días transcurridos
- `--descanso-color`: Color para días de descanso
- `--abono-color`: Color para abonos
- `--ingresos-color`: Color para ingresos por días

## 🎯 Ejemplos de Personalización

### Ejemplo 1: Tema Morado Elegante
```css
:root {
    --primary-color: #7C3AED;
    --secondary-color: #5B21B6;
    --accent-color: #A855F7;
    --warning-color: #F59E0B;
    
    --bg-primary: #FAF5FF;
    --bg-card: #FFFFFF;
    
    --dias-color: #7C3AED;
    --descanso-color: #5B21B6;
    --abono-color: #A855F7;
    --ingresos-color: #F59E0B;
}
```

### Ejemplo 2: Tema Naranja Vibrante
```css
:root {
    --primary-color: #EA580C;
    --secondary-color: #C2410C;
    --accent-color: #FB923C;
    --warning-color: #FBBF24;
    
    --bg-primary: #FFF7ED;
    --bg-card: #FFFFFF;
    
    --dias-color: #EA580C;
    --descanso-color: #C2410C;
    --abono-color: #FB923C;
    --ingresos-color: #FBBF24;
}
```

### Ejemplo 3: Tema Azul Cielo
```css
:root {
    --primary-color: #0EA5E9;
    --secondary-color: #0284C7;
    --accent-color: #38BDF8;
    --warning-color: #F59E0B;
    
    --bg-primary: #F0F9FF;
    --bg-card: #FFFFFF;
    
    --dias-color: #0EA5E9;
    --descanso-color: #0284C7;
    --abono-color: #38BDF8;
    --ingresos-color: #F59E0B;
}
```

## 🌈 Generadores de Colores Recomendados

Para encontrar códigos de color perfectos:
- **Coolors.co**: Generador de paletas de colores
- **Adobe Color**: Herramienta profesional de colores
- **Color Hunt**: Paletas de colores trending
- **Material Design Colors**: Colores de Google Material Design

## 💡 Consejos para Elegir Colores

1. **Contraste**: Asegúrate de que el texto sea legible sobre los fondos
2. **Coherencia**: Mantén una paleta de 3-5 colores máximo
3. **Accesibilidad**: Verifica que los colores sean accesibles para personas con daltonismo
4. **Propósito**: Usa colores que transmitan la sensación correcta (verde = dinero, rojo = urgente, etc.)

## 🔄 Cómo Probar Cambios

1. Guarda el archivo `css/custom-colors.css` después de hacer cambios
2. Recarga la página web en tu navegador (F5 o Ctrl+R)
3. Los cambios se aplicarán inmediatamente

## 🚨 Solución de Problemas

### Los cambios no se ven
- Asegúrate de guardar el archivo CSS
- Recarga la página con Ctrl+F5 (recarga forzada)
- Verifica que no hay errores de sintaxis en el CSS

### Los colores se ven mal
- Verifica que los códigos de color tengan el formato correcto (#XXXXXX)
- Asegúrate de que solo hay un tema activo (sin comentarios `/* */`)

### Quiero volver al tema original
- Comenta todos los temas alternativos
- Descomenta la sección `:root` original al inicio del archivo

---

¡Diviértete personalizando tu página web! 🎨✨