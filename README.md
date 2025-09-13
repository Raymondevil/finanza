# Control de Trabajo y Finanzas

Una aplicación web para el seguimiento y control de días trabajados, descansos y abonos financieros.

## 🎯 Objetivo del Proyecto

Esta aplicación permite monitorear y calcular automáticamente:
- Días transcurridos desde el inicio del período laboral
- Registro y valor de días de descanso
- Control de abonos recibidos
- Cálculos financieros automáticos

## ✅ Características Implementadas

### 📊 Dashboard Principal
- **Resumen visual** con métricas clave en tarjetas informativas
- **Cálculos automáticos** que se actualizan en tiempo real
- **Diseño responsivo** que funciona en dispositivos móviles y desktop

### 📅 Gestión de Fechas
- **Fecha de inicio**: 17 de marzo de 2025
- **Seguimiento automático** de días transcurridos
- **Cálculo de días trabajados** (días transcurridos - días de descanso)

### 😴 Control de Descansos
- **Contador dinámico** de días de descanso
- **Valor por descanso**: $400 pesos
- **Totales automáticos** que se actualizan al agregar días
- **Panel de control** para agregar nuevos días fácilmente
- **Vista detallada** de todas las fechas de descanso

### 🏖️ Período de Vacaciones
- **23 días de vacaciones** (15 septiembre - 7 octubre 2025)
- **Valor por día de vacaciones**: $600 pesos
- **Total por vacaciones**: $13,800 pesos
- **Vista completa** del período vacacional
- **Botón toggle** para mostrar/ocultar vacaciones
- **Cálculos dinámicos** que se ajustan según visibilidad

### 💰 Registro de Abonos
- **7 abonos registrados** con fechas y montos específicos
- **Suma total**: $19,300 pesos
- **Notas descriptivas** para cada abono
- **Vista cronológica** de todos los pagos

### 🧮 Cálculos Automáticos
- **Días transcurridos × $200**: Ingresos por días trabajados
- **Descansos × $400**: Valor total de días de descanso
- **Vacaciones × $600**: Valor total del período vacacional
- **Suma de abonos**: Total de pagos recibidos
- **Total general**: Descansos + Vacaciones + Ingresos por días - Abonos

## 🚀 Funcionalidades Técnicas

### ⚡ Actualizaciones en Tiempo Real
- Los cálculos se actualizan automáticamente cada minuto
- La fecha actual se muestra siempre actualizada
- Los totales se recalculan dinámicamente

### 🎨 Interfaz de Usuario
- **Tailwind CSS** para estilos modernos y responsivos
- **Font Awesome** para iconografía consistente
- **Animaciones suaves** al cargar la página
- **Sistema de colores personalizable** con variables CSS
- **4 temas predefinidos** (Original, Oscuro, Verde Naturaleza, Azul Profesional)
- **Efectos visuales** como pulso suave en números importantes
- **Panel de control interactivo** para gestionar datos
- **Notificaciones en tiempo real** para acciones del usuario
- **Botón toggle dinámico** para vacaciones

### 🎛️ Funcionalidades Interactivas
- **Toggle de vacaciones**: Mostrar/ocultar período vacacional con un clic
- **Agregar días de descanso**: Panel para añadir nuevas fechas dinámicamente
- **Contadores automáticos**: Títulos que se actualizan con los totales correctos
- **Notificaciones**: Feedback visual para acciones del usuario
- **Validaciones**: Previene duplicados y fechas inválidas

### 📱 Compatibilidad
- **Diseño responsivo** para móviles, tablets y desktop
- **Navegadores modernos** con soporte completo
- **Sin dependencias de servidor** - funciona como sitio estático

## 📋 Datos del Proyecto

### Período de Trabajo
- **Inicio**: 17 de marzo de 2025
- **Fin**: Día en curso (actualización automática)

### Días de Descanso (30 días)
```
20-marzo-2025, 21-marzo-2025, 23-marzo-2025, 24-marzo-2025, 25-marzo-2025,
26-marzo-2025, 06-abril-2025, 13-abril-2025, 21-abril-2025, 22-abril-2025,
27-abril-2025, 01-mayo-2025, 14-mayo-2025, 23-mayo-2025, 01-junio-2025,
08-junio-2025, 15-junio-2025, 22-junio-2025, 29-junio-2025, 05-julio-2025,
13-julio-2025, 19-julio-2025, 20-julio-2025, 27-julio-2025, 03-agosto-2025,
10-agosto-2025, 15-agosto-2025, 16-agosto-2025, 17-agosto-2025, 24-agosto-2025
```

### Período de Vacaciones (23 días)
**Del 15 de septiembre al 7 de octubre de 2025**
```
15-septiembre-2025, 16-septiembre-2025, 17-septiembre-2025, 18-septiembre-2025,
19-septiembre-2025, 20-septiembre-2025, 21-septiembre-2025, 22-septiembre-2025,
23-septiembre-2025, 24-septiembre-2025, 25-septiembre-2025, 26-septiembre-2025,
27-septiembre-2025, 28-septiembre-2025, 29-septiembre-2025, 30-septiembre-2025,
01-octubre-2025, 02-octubre-2025, 03-octubre-2025, 04-octubre-2025,
05-octubre-2025, 06-octubre-2025, 07-octubre-2025
```

### Abonos Registrados
| Fecha | Monto | Nota |
|-------|-------|------|
| 11-mayo-2025 | $1,900 | - |
| 11-mayo-2025 | $1,800 | Día que trabajo me dio 3700 dia de cuenta |
| 16-julio-2025 | $3,600 | lunes en la casa con la pitahaya |
| 30-julio-2025 | $3,600 | lunes que me pidio agua |
| 10-agosto-2025 | $3,600 | domingo en el parque los fresnos |
| 30-agosto-2025 | $1,800 | viernes de ballenas |
| 03-septiembre-2025 | $3,000 | miercoles pago escuela chamuco |

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica de la aplicación
- **CSS3 + Tailwind CSS**: Estilos modernos y responsivos
- **JavaScript ES6+**: Lógica de cálculos y manipulación del DOM
- **Font Awesome**: Iconografía
- **CDN**: Carga rápida de recursos externos

## 📁 Estructura del Proyecto

```
/
├── index.html                    # Página principal
├── css/
│   └── custom-colors.css        # Sistema de colores personalizable
├── js/
│   └── main.js                  # Lógica JavaScript principal
├── README.md                    # Documentación del proyecto
└── PERSONALIZACION_COLORES.md   # Guía completa de personalización
```

## 🚀 Cómo Usar

### Básico
1. **Abrir index.html** en cualquier navegador moderno
2. **Visualizar automáticamente** todos los cálculos actualizados
3. **Los datos se actualizan** cada minuto automáticamente
4. **La página es completamente funcional** sin necesidad de servidor

### Funciones Interactivas
5. **Mostrar/Ocultar Vacaciones**: Usa el botón naranja "Mostrar/Ocultar" en la sección de vacaciones
6. **Agregar Días de Descanso**: 
   - Ve al "Panel de Control"
   - Selecciona una fecha en el calendario
   - Haz clic en el botón "+" verde
   - Los contadores se actualizarán automáticamente
7. **Ver Notificaciones**: Las acciones exitosas mostrarán confirmaciones visuales

## 🎨 Personalización de Colores

### Cambiar Colores Fácilmente
1. **Abre** `css/custom-colors.css`
2. **Modifica** las variables de color en la sección `:root`
3. **Guarda** el archivo y recarga la página

### Temas Predefinidos Disponibles
- **🌟 Original**: Colores azul, morado y verde (activo por defecto)
- **🌙 Oscuro**: Tema oscuro para mejor experiencia nocturna
- **🌿 Verde Naturaleza**: Tonos verdes y naturales
- **💼 Azul Profesional**: Azules corporativos y elegantes

### Guía Completa
Consulta `PERSONALIZACION_COLORES.md` para instrucciones detalladas, ejemplos y consejos de personalización.

## 📈 Características Futuras Sugeridas

- **Exportación a PDF** de reportes
- **Gráficos estadísticos** con Chart.js
- **Edición inline** de días existentes
- **Drag & drop** para reorganizar fechas
- **Búsqueda y filtros** en listas de fechas
- **Modo oscuro** automático según horario
- **Recordatorios** de fechas importantes
- **Histórico mensual** de ingresos y gastos
- **Backup/restauración** de datos
- **Panel admin** para múltiples usuarios

## 🔧 Personalización

### Modificar Datos del Proyecto
1. **Editar js/main.js** para cambiar fechas, montos o valores
2. **Modificar DIAS_DESCANSO** array para agregar/quitar días
3. **Actualizar DIAS_VACACIONES** array para cambiar período vacacional
4. **Actualizar ABONOS** array para nuevos pagos
5. **Cambiar constantes** VALOR_DESCANSO ($400), VALOR_VACACIONES ($600) y VALOR_DIA ($200)

### Personalizar Colores y Apariencia
1. **Editar css/custom-colors.css** para cambiar colores
2. **Usar temas predefinidos** descomentando secciones específicas
3. **Crear tu propio tema** modificando las variables CSS
4. **Consultar PERSONALIZACION_COLORES.md** para guía detallada

## 💡 Notas Importantes

- Los cálculos se basan en la fecha actual del sistema
- Todos los montos están en pesos mexicanos (MXN)
- La aplicación funciona completamente offline
- Compatible con impresión para reportes físicos

---

**Desarrollado con ❤️ para un control financiero eficiente**