## **English**
![cover](images/project_cover.jpg)
---
This project is responsible for transforming and modeling a dataset using dbt (Data Build Tool) and Snowflake.

# How It Works ⚙️

1. **Data Loading:**  
   The original dataset is loaded into Snowflake, generating a base table (for example, I named it DATASET_SUPERSTORE).

2. **Data Transformation with dbt:**  
   I used dbt to transform, clean, and model the data. Each model is located in the `models/` folder, and the results appear in Snowflake as views or tables, depending on what is defined in `dbt_project.yml`. In my case, the *sales* view contains the transformed data ready for analysis.

3. **Validation and Data Quality:**  
   Automated tests are run to ensure data quality and consistency.

5. **Data Consumption:**  
   The transformed data is available for use by data analysis and visualization tools (such as Power BI, Tableau, or directly through queries in Snowflake) to derive insights.

# Data Source 📊  
The dataset used in this project comes from Kaggle, a leading platform for data analysis and machine learning. You can find it at the following link: [Super Store](https://www.kaggle.com/datasets/itssuru/super-store?resource=download)

# Services, Tools, etc. ☁️💾

- **dbt Core:** To define and execute SQL transformations.  
- **Snowflake:** As a data warehouse to store transformed data.  
- **Python & Virtual Environment:** To manage dbt and its dependencies without system conflicts.

# Screenshots 🖼️

## Data visualization in Snowflake
![Snowflake](images/screenshots/snowflake_screenshot.png)

## **Español**
![cover](images/project_cover.jpg)
---
Este proyecto se encarga de transformar y modelar un DataSet utilizando dbt (Data Build Tool) y Snowflake.

# Cómo Funciona ⚙️

1. *Carga de Datos:*  
   Se carga el dataset original en Snowflake, lo que genera una tabla base (por ejemplo, yo lo nombré DATASET_SUPERSTORE).


2. *Transformación de los datos con dbt:*  
   Usé dbt para transformar, limpiar y modelar los datos. Cada modelo se encuentra en la carpeta models/ y los resultados se muestran en Snowflake como views o tablas, según lo que definas en dbt_project.yml. En mi caso, la view *sales* contiene los datos transformados listos para el análisis.

3. *Validación y Calidad de Datos:*  
   Se ejecutan tests automatizados para asegurar la calidad y consistencia de los datos.
   
5. *Consumo de Datos:*  
   Los datos transformados están disponibles para ser consumidos por herramientas de análisis y visualizacion de datos (como Power BI, Tableau, o directamente mediante consultas en Snowflake) para obtener insights de los mismos.

# Fuente de datos📊 
El conjunto de datos utilizado en este proyecto proviene de Kaggle, una plataforma líder en análisis de datos y aprendizaje automático. Puedes encontrarlo en el siguiente enlace: [Super Store](https://www.kaggle.com/datasets/itssuru/super-store?resource=download)

# Servicios, Herramientas, etc ☁️💾

- *dbt Core:* Para definir y ejecutar transformaciones en SQL.  
- *Snowflake:* Como data warehouse para almacenar los datos transformados.  
- *Python & Entorno Virtual:* Para administrar dbt y sus dependencias sin conflictos en el sistema.

# Capturas 🖼️

## Visualización de los datos en Snowflake
![Snowflake](images/screenshots/snowflake_screenshot.png)

