# Reportes de Ventas y Finanzas

Proyecto con dos páginas HTML para visualización de datos de ventas y reportes financieros mensuales.

## Páginas

1. **ventas.html** - Tabla de transacciones de ventas granulares
   - 30 transacciones con datos detallados
   - Estadísticas en tiempo real (total transacciones, ingresos, promedio, mejor vendedor)
   - Diseño minimalista con colores fríos

2. **reporte-mensual.html** - Resumen financiero mensual
   - 12 meses de datos agregados
   - Tarjetas de resumen con estadísticas anuales
   - Gráfico de barras interactivo de ingresos mensuales
   - Diseño minimalista con colores fríos

## Características del Diseño

- **Paleta de colores fríos**: Tonos azules, morados y grises
- **Diseño minimalista**: Limpio, moderno y profesional
- **Responsive**: Adaptable a dispositivos móviles
- **Interactivo**: Efectos hover y animaciones sutiles
- **Tipografía moderna**: Fuente Inter para mejor legibilidad

## Despliegue en Vercel

### Opción 1: GitHub Integration (Recomendado)

1. **Subir a GitHub**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin <tu-repo-url>
   git push -u origin main
   ```

2. **Desplegar en Vercel**:
   - Ve a [vercel.com](https://vercel.com)
   - Conecta tu cuenta de GitHub
   - Importa el repositorio
   - Vercel detectará automáticamente que es un sitio estático
   - Haz clic en "Deploy"

### Opción 2: Vercel CLI

1. **Instalar Vercel CLI**:
   ```bash
   npm i -g vercel
   ```

2. **Desplegar**:
   ```bash
   vercel --prod
   ```

### URLs después del despliegue

Una vez desplegado, tendrás acceso a tus páginas en:

- `https://tu-proyecto.vercel.app/ventas.html`
- `https://tu-proyecto.vercel.app/reporte-mensual.html`

O usando las rutas amigables configuradas:

- `https://tu-proyecto.vercel.app/ventas`
- `https://tu-proyecto.vercel.app/reporte-mensual`

## Desarrollo Local

Para probar localmente:

```bash
npm install
npm run dev
```

Luego abre `http://localhost:3000` en tu navegador.

## Estructura del Proyecto

```
crw_pages_test/
├── ventas.html              # Página de transacciones
├── reporte-mensual.html     # Página de reporte mensual
├── vercel.json             # Configuración de Vercel
├── package.json            # Dependencias del proyecto
└── README.md               # Este archivo
```
