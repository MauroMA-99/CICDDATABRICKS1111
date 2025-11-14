# ⭐ MovieRatings Analytics Pipeline
### Arquitectura Medallion en Azure Databricks

[![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)](https://databricks.com/)
[![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoft-azure&logoColor=white)](https://azure.microsoft.com/)
[![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apache-spark&logoColor=white)](https://spark.apache.org/)
[![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD8?style=for-the-badge&logo=delta&logoColor=white)](https://delta.io/)
[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)](https://powerbi.microsoft.com/)
[![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)](https://github.com/features/actions)

*Pipeline automatizado de datos para análisis de peliculas por rating con arquitectura de tres capas y despliegue continuo*

</div>

## 🎯 Descripción

📄 MovieRatings Analytics Pipeline es un proyecto de ingeniería de datos que implementa un flujo ETL completo en Databricks para procesar la información de películas y calificaciones de usuarios.
Los archivos movies.csv y ratings.csv se ingieren en el nivel Bronze, se limpian y transforman en Silver, y luego se modelan en tablas Golden listas para análisis avanzado.

El proyecto incluye deduplicación de columnas, enriquecimiento de datos (años, géneros, complejidad), categorización de ratings y creación de métricas agregadas, permitiendo habilitar dashboards en Power BI y análisis de machine learning basados en preferencias de usuarios y características de películas.

### ✨ Características Principales

- 🔄 **ETL Automatizado** - Pipeline completo con despliegue automático via GitHub Actions
- 🏗️ **Arquitectura Medallion** - Separación clara de capas Bronze → Silver → Gold
- 📊 **Modelo Dimensional** - Star Schema optimizado para análisis de negocio
- 🚀 **CI/CD Integrado** - Deploy automático en cada push a master
- 📈 **Power BI Ready** - Conexión directa con SQL Warehouse
- ⚡ **Delta Lake** - ACID transactions y time travel capabilities









