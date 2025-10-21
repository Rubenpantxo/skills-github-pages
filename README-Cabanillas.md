# 🌾 Cultivos de Cabanillas - Mapa Mejorado

## 📋 Cambios Implementados

He transformado tu simulador agrícola en una experiencia inmersiva que recrea fielmente el municipio de Cabanillas (Navarra). Estos son los cambios principales:

### 🗺️ Dimensiones del Mapa
- **Antes**: 3000px × 2000px
- **Ahora**: 5500px × 3850px (83% más grande)
- **Proporción**: Los elementos ahora se ven mucho más pequeños y realistas en relación al territorio

### 🎨 Fondo del Mapa
- **Integración del plano real**: El mapa ahora usa `Fondo.jpg` como imagen de fondo
- **Apariencia de maqueta**: La experiencia visual simula estar desarrollando el juego sobre el plano topográfico real de Cabanillas
- **Overlay sutil**: Capa semi-transparente para mejorar la legibilidad de los elementos interactivos

### 🏘️ Distribución de Zonas

**Pueblo (centro del mapa):**
- 🏪 **Tienda**: Ubicada en el centro del núcleo urbano
- 🏠 **Casa**: Tu hogar en Cabanillas
- 📦 **Almacén**: Zona de almacenamiento municipal

**Áreas de Cultivo (alrededor del pueblo):**
- 🌾 **Campos del Norte**: Zona para cereales
- 🌽 **Campos del Oeste**: Ideal para maíz y hortalizas
- 🥔 **Campos del Este**: Perfecta para cultivos de raíz
- 🍅 **Campos del Sur**: Máxima exposición solar
- 🍓 **Campos del Noroeste**: Cultivos especiales

### 🎮 Mejoras de Navegación
- **Zoom inicial**: Comienza más alejado (0.6x) para apreciar el territorio completo
- **Rango de zoom**: De 0.3x a 2x para explorar desde vista aérea hasta detalle
- **Centrado automático**: La cámara inicia centrada en el pueblo
- **Minimapa mejorado**: Refleja el plano real con todas las zonas marcadas

### 🎨 Mejoras Visuales
- **Título identificativo**: "Cultivos de Cabanillas - Navarra"
- **Zonas más llamativas**: Colores más vivos y efectos de hover mejorados
- **Sombras y profundidad**: Mayor sensación de elementos sobre el mapa
- **Tooltips informativos**: Cada zona tiene nombre y descripción contextual

## 📦 Archivos Incluidos

1. **mapa-cabanillas-mejorado.html** - El juego completo en un solo archivo
2. **Fondo.jpg** - Imagen del plano de Cabanillas

## 🚀 Instalación

### Opción 1: Uso Simple
1. Crea una carpeta llamada `assets` junto al archivo HTML
2. Dentro de `assets`, crea una carpeta llamada `images`
3. Coloca `Fondo.jpg` dentro de `assets/images/`
4. Abre `mapa-cabanillas-mejorado.html` en tu navegador

### Opción 2: Estructura Completa
```
tu-proyecto/
├── mapa-cabanillas-mejorado.html
└── assets/
    └── images/
        └── Fondo.jpg
```

## 🎮 Controles del Juego

### Navegación
- **Arrastrar**: Click izquierdo + mover ratón para desplazar el mapa
- **WASD** o **Flechas**: Movimiento con teclado
- **Rueda del ratón**: Zoom in/out
- **Botones +/-**: Zoom con precisión
- **⊙**: Resetear zoom a vista por defecto
- **🎯**: Centrar mapa en el pueblo

### Interacción
- **Click en zonas**: Abre información detallada
- **Hover sobre zonas**: Muestra tooltip con nombre
- **⊞**: Activar/desactivar grid de coordenadas
- **ℹ️**: Información general del mapa

## 🔮 Próximos Pasos Sugeridos

Para completar tu visión del simulador agrícola de Cabanillas, podrías implementar:

1. **Sistema de Parcelas**
   - Detectar zonas de cultivo específicas (áreas verdes del plano)
   - Permitir colocar cultivos en posiciones específicas del mapa
   - Usar las líneas rojas como guía de expansión

2. **Integración con Sistema de Cultivo**
   - Conectar el archivo `cultivos-cabanillas.html` con este mapa
   - Al hacer click en "Entrar a la Zona", cargar el sistema de cultivo específico
   - Cada zona podría tener diferentes tipos de suelo y capacidades

3. **Sistema de Progresión**
   - Desbloquear zonas progresivamente
   - Cada área de cultivo con características únicas
   - Eventos especiales según la ubicación

4. **Capa de Datos Geográfica**
   - Usar coordenadas reales de Cabanillas
   - Datos meteorológicos de la zona
   - Ciclos de cultivo adaptados al clima navarro

5. **Multijugador Local**
   - Diferentes granjas en diferentes zonas del mapa
   - Cooperación entre jugadores del pueblo
   - Mercado central en el núcleo urbano

## 🎯 Características Técnicas

- **Responsive**: Se adapta a diferentes tamaños de pantalla
- **Performance**: Optimizado con transform CSS para movimientos fluidos
- **Sin dependencias**: Todo el código en un solo archivo HTML
- **Modular**: Fácil de extender con nuevas funcionalidades
- **Personalizable**: Variables de configuración al inicio del JavaScript

## 🐛 Resolución de Problemas

**La imagen de fondo no se carga:**
- Verifica que `Fondo.jpg` esté en `assets/images/`
- Comprueba que el nombre del archivo coincida exactamente (mayúsculas/minúsculas)

**El mapa se ve muy pequeño:**
- Usa los controles de zoom (+/-)
- Ajusta el valor `MIN_ZOOM` en el código si necesitas más acercamiento

**Los elementos están mal posicionados:**
- Puedes ajustar las coordenadas `left` y `top` de cada `.zone` en el HTML
- Activa el grid con el botón ⊞ para ayudarte con el posicionamiento

## 💡 Tips de Uso

1. **Explora desde lejos**: Comienza con zoom alejado para ver el territorio completo
2. **Usa el minimapa**: Te ayuda a orientarte mientras navegas
3. **Prueba el teclado**: WASD es más preciso que arrastrar para movimientos finos
4. **Combina controles**: Arrastra para grandes desplazamientos, teclado para ajustes

## 📞 Soporte

Si necesitas ajustar algo específico:
- Las posiciones de zonas se definen en los elementos `.zone` del HTML
- Los tamaños y colores están en la sección `<style>`
- La lógica del juego está en el `<script>` al final

---

**¡Disfruta cultivando en Cabanillas!** 🌾🚜
