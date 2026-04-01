# 📊 Análisis de Ventas E-Shop Now — Proyecto ABP Módulo 2

![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power_Query-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Power Pivot](https://img.shields.io/badge/Power_Pivot-217346?style=for-the-badge&logo=microsoft&logoColor=white)

---

## 📌 Descripción del proyecto

Proyecto de análisis de ventas desarrollado para **E-Shop Now**, empresa
chilena de retail multicanal (tienda física, web y app móvil) que
comercializa productos en categorías de Tecnología, Electrohogar,
Vestuario, Calzado y Belleza.

El objetivo fue aplicar herramientas avanzadas de Excel para limpiar,
transformar y analizar un dataset de ventas reales simuladas, entregando
insights accionables al equipo comercial.

---

## 📋 Contexto del negocio

E-Shop Now opera en múltiples ciudades de Chile (Santiago, Valparaíso,
Concepción, Temuco, Antofagasta, entre otras) a través de 3 canales de
venta: **Tienda física**, **Web** y **App móvil**.

El dataset contenía problemas típicos de datos reales que debieron ser
identificados y resueltos como parte del análisis.

---

## 🗂️ Descripción del dataset

| Característica | Detalle |
|---|---|
| 📅 Período analizado | Enero — Diciembre 2024 |
| 📝 Registros totales | 1.020 transacciones |
| 📦 Categorías de productos | Tecnología · Electrohogar · Vestuario · Calzado · Belleza |
| 🛒 Canales de venta | Tienda física · Web · App |
| 🌎 Cobertura geográfica | 10 ciudades de Chile |
| 💰 Venta total estimada | $735.149.500 CLP |

**Problemas de calidad detectados en el dataset:**
- `region_cliente`: 395 valores nulos (38,7% del total)
- `categoria_producto`: 389 valores nulos (38,1%)
- `descuento_pct`: 242 valores nulos (23,7%)
- `edad_cliente`: 20 valores nulos

---

## 🔧 Proceso de trabajo

### 1. Limpieza y preparación con Power Query
- Revisión y corrección de tipos de datos por columna
- Identificación y tratamiento de valores nulos en región,
  categoría y descuento
- Eliminación de registros duplicados
- Normalización de categorías textuales inconsistentes
- Estandarización del formato de fechas

### 2. Reglas de negocio implementadas
- **Clasificación de clientes:** Nuevo · Frecuente · Premium
  (según frecuencia de compra y volumen acumulado)
- **Clasificación de vendedores:** Junior · Semi Senior · Senior
  (según antigüedad y desempeño)

### 3. Métricas y columnas calculadas
- Total de venta por registro (precio × cantidad × (1 - descuento))
- Ticket promedio por cliente
- Ventas acumuladas por cliente y por vendedor
- Impacto del descuento en el margen por transacción

### 4. Análisis exploratorio
- Mínimo 2 tablas dinámicas por dimensión de análisis
- Gráficos por categoría, canal, región y vendedor

---

## 📈 Principales hallazgos

- Las categorías **Tecnología** y **Electrohogar** concentran
  el mayor volumen de ventas por monto
- El canal **App** muestra crecimiento sostenido durante el año
- Se identificaron patrones de descuento que impactan el margen
  en ciertos segmentos de productos
- **Santiago** lidera en volumen de transacciones, seguida de
  Valparaíso y Concepción

---

## 🗂️ Estructura del repositorio

```
├── data/
│   └── E-ShopNow_Proyecto_ABP_M2.csv   # Dataset original
├── excel/
│   └── analisis_eshopnow.xlsx           # Archivo de trabajo final
├── docs/
│   └── informe_conclusiones.pdf         # Informe de hallazgos
└── README.md
```

---

## 🛠️ Herramientas utilizadas

| Herramienta | Uso |
|---|---|
| Microsoft Excel | Herramienta principal de análisis |
| Power Query | Limpieza, transformación y preparación de datos |
| Power Pivot | Modelado de datos y medidas calculadas |
| Tablas dinámicas | Análisis exploratorio multidimensional |
| Gráficos Excel | Visualización de hallazgos |

---

## 👤 Autor

**Nicolás Pérez Cerda**  
[LinkedIn](https://www.linkedin.com/in/nicolasperezcerda/) · [GitHub](https://github.com/Recnico)
