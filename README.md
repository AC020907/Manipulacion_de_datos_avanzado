# Análisis de Datos de Instacart - "¡Llena ese carrito!"

## 📋 Descripción del Proyecto

Este proyecto realiza un análisis exploratorio de datos (EDA) completo del conjunto de datos de Instacart, una plataforma de entregas de comestibles. El objetivo es identificar patrones de comportamiento de compra de los usuarios y generar insights accionables para la toma de decisiones de negocio.

## 🎯 Objetivos

- Analizar patrones de compra por hora del día y día de la semana
- Identificar productos más populares y frecuentemente reordenados
- Evaluar comportamientos de compra de los clientes
- Calcular tasas de reorden por producto y usuario
- Determinar productos más comúnmente añadidos primero al carrito

## 📊 Conjunto de Datos

El proyecto utiliza 5 tablas principales:

- **instacart_orders.csv**: Información de pedidos (478,967 registros)
- **products.csv**: Catálogo de productos (49,694 productos)
- **order_products.csv**: Productos por pedido (4,545,007 registros)
- **aisles.csv**: Categorías de pasillos (134 pasillos)
- **departments.csv**: Departamentos de la tienda (21 departamentos)

## 🛠️ Tecnologías Utilizadas

- **Python 3.9+**
- **Pandas**: Manipulación y análisis de datos
- **NumPy**: Operaciones numéricas
- **Matplotlib**: Visualización de datos

## 📈 Principales Hallazgos

### Patrones Temporales
- **Horas pico**: 9:00-16:00 horas (horario laboral)
- **Días preferidos**: Domingos y lunes (compras semanales)
- **Frecuencia promedio**: Cada 10.4 días entre pedidos

### Productos Más Populares
1. **Bananas** (66,050 pedidos)
2. **Bolsa de Bananas Orgánicas** (53,297 pedidos)
3. **Fresas Orgánicas** (37,039 pedidos)

### Comportamiento de Compra
- **65% de productos top son orgánicos**
- **Tamaño promedio del carrito**: 5-6 productos
- **Tasa de reorden promedio**: 38.7%

## 📁 Estructura del Proyecto

```
proyecto-instacart/
│
├── notebook.ipynb          # Análisis principal
├── README.md              # Este archivo
└── datasets/              # Datos (no incluidos en repo)
    ├── instacart_orders.csv
    ├── products.csv
    ├── order_products.csv
    ├── aisles.csv
    └── departments.csv
