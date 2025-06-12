# Análisis Superstore - Dashboard de Rentabilidad

Un proyecto completo de **Business Intelligence** que analiza datos de ventas de Superstore, con procesamiento en Python y visualización interactiva en Power BI.

## Descripción del Proyecto

Este proyecto presenta un análisis integral de los datos de Superstore, enfocándose en métricas clave de rentabilidad, tendencias de ventas y rendimiento empresarial. Combina técnicas de análisis de datos con visualización moderna para proporcionar insights accionables para la toma de decisiones.

## Demo en Vivo

**[Ver Proyecto Completo](index.html)** - Página web con dashboard interactivo

**[Dashboard Power BI](https://app.powerbi.com/reportEmbed?reportId=a69b85bf-7d38-46ba-afa3-9180402bd62c&autoAuth=true&ctid=430f2559-efe1-453d-b47a-db7388705331&actionBarEnabled=true)** - Análisis interactivo completo

## Contenido del Proyecto

### Archivos Principales

```
BI-analyst/
├── index.html                       # Página web del proyecto
├── bi_superstore_analisis.ipynb     # Análisis en Jupyter Notebook
├── Superstore.csv                   # Dataset original
├── Superstore_limpio.csv            # Dataset procesado
└── README.md                        # Documentación del proyecto
```

### Componentes del Análisis

#### 1. **Preprocesamiento de Datos** (`bi_superstore_analisis.ipynb`)
- Limpieza y normalización de datos
- Estandarización de nombres de columnas
- Conversión de tipos de datos (fechas)
- Validación de calidad de datos

#### 2. **Dashboard Interactivo** (Power BI)
- **Análisis de Ventas**: Métricas de rendimiento por período
- **Datos por Región**: Distribución geográfica de ventas
- **Tendencias Temporales**: Patrones estacionales y evolutivos
- **Segmentación de Clientes**: Análisis por categorías de cliente

#### 3. **Interfaz Web** (`index.html`)
- Diseño profesional y responsive
- Integración con dashboard de Power BI
- Optimizado para móviles y tablets
- Carga rápida y experiencia fluida

## Tecnologías Utilizadas

### Análisis de Datos
- **Python** - Lenguaje principal de análisis
- **Pandas** - Manipulación y análisis de datos
- **Jupyter Notebook** - Entorno de desarrollo interactivo

### Visualización
- **Power BI** - Dashboard interactivo y reportes
- **HTML5/CSS3** - Interfaz web moderna
- **JavaScript** - Interactividad y animaciones

### Diseño
- **CSS Grid & Flexbox** - Layout responsive
- **Font Awesome** - Iconografía profesional
- **Google Fonts (Inter)** - Tipografía moderna

## Métricas y KPIs Analizados

### Rentabilidad
- Margen de beneficio por producto
- ROI por categoría
- Análisis de costos vs ingresos

### Ventas
- Volumen de ventas por período
- Crecimiento year-over-year
- Productos más vendidos

### Geográfico
- Performance por región
- Mapas de calor de ventas
- Oportunidades de expansión

### Segmentación
- Análisis por tipo de cliente
- Patrones de compra
- Valor de vida del cliente (CLV)

## Cómo Ejecutar el Proyecto

### Prerrequisitos
```bash
# Python 3.7+
pip install pandas numpy jupyter
```

### Pasos para ejecutar

1. **Clonar el repositorio**
```bash
git clone [tu-repositorio]
cd BI-analyst
```

2. **Abrir el análisis en Jupyter**
```bash
jupyter notebook bi_superstore_analisis.ipynb
```

3. **Ver la página web**
- Abrir `index.html` en tu navegador
- O usar un servidor local:
```bash
# Con Python
python -m http.server 8000

# Con Node.js (si tienes instalado)
npx serve
```

## Insights Clave Descubiertos

### Principales Hallazgos
- **Producto más rentable**: [Pendiente de análisis]
- **Región con mejor performance**: [Pendiente de análisis]
- **Tendencia estacional**: [Pendiente de análisis]
- **Segmento de cliente más valioso**: [Pendiente de análisis]

### Recomendaciones Estratégicas
1. **Optimización de inventario** basada en tendencias estacionales
2. **Expansión geográfica** en regiones sub-exploradas
3. **Estrategias de retención** para segmentos de alto valor
4. **Mejora de márgenes** en productos de bajo rendimiento

## Características de la Interfaz Web

### Experiencia de Usuario
- **Diseño Profesional**: Paleta corporativa azul/dorado
- **Responsive Design**: Funciona en móviles, tablets y desktop
- **Carga Rápida**: Optimizado para performance
- **Navegación Intuitiva**: Acceso directo al dashboard

### Componentes Interactivos
- **Preview del Dashboard**: Vista previa con gráficos animados
- **Botones CTA**: Acceso directo a Power BI
- **Información del Proyecto**: Scroll suave entre secciones
- **Descarga de Dataset**: Acceso al archivo procesado

## Estructura de Datos

### Dataset Original (`Superstore.csv`)
- **Filas**: ~10,000 registros de ventas
- **Columnas**: 21 campos incluyendo fechas, productos, clientes, etc.
- **Período**: Datos históricos de ventas

### Dataset Procesado (`Superstore_limpio.csv`)
- Nombres de columnas normalizados
- Tipos de datos corregidos
- Fechas en formato estándar
- Valores nulos tratados

## Próximas Mejoras

### Análisis Avanzado
- [ ] Análisis predictivo con Machine Learning
- [ ] Modelos de forecasting de ventas
- [ ] Clustering de clientes
- [ ] Análisis de market basket

### Interfaz
- [ ] Modo oscuro para la web
- [ ] Más gráficos interactivos
- [ ] Sistema de filtros avanzados
- [ ] Exportación de reportes PDF

## Autor

**Diego** - Analista de Business Intelligence

- Especializado en análisis de datos y visualización
- Python, Power BI, SQL, Excel avanzado
- Enfoque en insights accionables para negocio

## Contacto

¿Interesado en colaborar o contratar servicios de análisis de datos?

- Email: [tu-email]
- LinkedIn: [tu-linkedin]
- Portfolio: [tu-portfolio]

## Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo `LICENSE` para más detalles.

---

**¿Te gustó el proyecto?** ¡No olvides darle una estrella!

**¿Necesitas análisis de datos para tu empresa?** ¡Contáctame!
