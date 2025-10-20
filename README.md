# Mi Granja - Simulador Agrícola

Un simulador de granja interactivo desarrollado con HTML, CSS y JavaScript puro. Cultiva diferentes tipos de plantas, gestiona recursos y mejora tu granja.

## Características

- Sistema de cultivos con diferentes tipos de plantas (trigo, maíz, patata, tomate, fresa, calabaza)
- Sistema de recursos (semillas y monedas)
- Mecánicas de crecimiento en tiempo real
- Sistema de mejoras para acelerar el progreso
- Guardado automático del progreso
- Interfaz responsive y animaciones fluidas

## Versiones del Juego

El proyecto incluye tres versiones diferentes:

1. **index.html** - Versión principal modular
   - Separa HTML, CSS y JavaScript en archivos independientes
   - Mejor para desarrollo y mantenimiento

2. **farm-game-complete.html** - Versión autónoma
   - Todo el código en un solo archivo
   - Fácil de compartir y usar sin dependencias

3. **cultivos-cabanillas.html** - Versión con mapa interactivo
   - Incluye sistema de zonas de cultivo basado en imagen
   - Permite plantar en ubicaciones específicas del mapa

## Estructura del Proyecto

```
skills-github-pages/
├── assets/
│   ├── css/
│   │   └── styles.css          # Estilos del juego
│   ├── js/
│   │   └── script.js           # Lógica del juego
│   └── images/                 # Recursos gráficos
│       ├── Fondo.jpg
│       ├── ZonasCultivo_Azul.png
│       ├── Textura_tierra_*.png
│       └── ...
├── Imagenes/                   # Carpeta adicional de imágenes
├── index.html                  # Página principal
├── farm-game-complete.html     # Versión completa autónoma
├── cultivos-cabanillas.html    # Versión con mapa
└── README.md                   # Este archivo
```

## Cómo Jugar

1. Abre `index.html` en tu navegador web
2. Haz clic en el botón de tienda (esquina superior izquierda)
3. Selecciona un cultivo que puedas permitirte
4. Haz clic en una parcela vacía para plantar
5. Espera a que el cultivo crezca
6. Haz clic en el cultivo maduro para cosechar
7. Usa las monedas para comprar mejoras

## Sistema de Cultivos

| Cultivo | Coste | Tiempo | Recompensa |
|---------|-------|--------|------------|
| Trigo | 1 semilla | 15s | 2 semillas |
| Maíz | 2 semillas, 1 moneda | 20s | 3 semillas, 1 moneda |
| Patata | 2 semillas, 1 moneda | 18s | 3 semillas, 1 moneda |
| Tomate | 3 semillas, 25 monedas | 30s | 5 semillas, 30 monedas |
| Fresa | 3 semillas, 25 monedas | 28s | 5 semillas, 30 monedas |
| Calabaza | 4 semillas, 50 monedas | 40s | 8 semillas, 60 monedas |

## Mejoras Disponibles

- **Hoz** (5 monedas) - Cosecha más rápido
- **Regadera** (10 monedas) - Acelera el crecimiento un 30%
- **Expandir Granja** (10 monedas) - Añade más parcelas
- **Pala** (50 monedas) - Permite plantar múltiples cultivos seguidos

## Tecnologías Utilizadas

- HTML5
- CSS3 (animaciones y diseño responsive)
- JavaScript (ES6+)
- LocalStorage para guardado de partida

## Instalación

No requiere instalación. Simplemente abre cualquiera de los archivos HTML en un navegador web moderno.

Para desarrollo local:

```bash
# Clona el repositorio
git clone https://github.com/Rubenpantxo/skills-github-pages.git

# Abre index.html en tu navegador
open index.html
```

## Compatibilidad

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## Licencia

Este proyecto es de código abierto y está disponible para uso educativo.

## Créditos

Desarrollado como proyecto de demostración de desarrollo web.
