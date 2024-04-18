# flinkcommerce_apacheflink_ecommerce_datastreaming

# Data E-commerce Flink Project

## Descripción
Este proyecto implementa un sistema de procesamiento de datos en streaming utilizando Apache Kafka para la ingestión de datos, Apache Flink para el procesamiento en tiempo real, GraphQL para el almacenamiento de datos estructurados y Elasticsearch con Kibana para el análisis y visualización de datos.

## Estructura de Carpetas

### Flink
- src: Contiene el código fuente.
  - java/flinkcommerce: Código principal para procesamiento de datos con Flink.
    - Deserializer: Clases para deserialización de datos JSON.
    - Dto: Objetos de Transferencia de Datos (Data Transfer Objects).
    - utils: Utilidades generales del proyecto.
  - resources: Configuraciones para el proyecto como log4j2.properties.

### flink-1.18.1
- Versión de Apache Flink utilizada.

![image](https://github.com/Yawwwe/flinkcommerce_apacheflink_ecommerce_datastreaming/assets/124920713/c666ef33-f4fd-4317-8d12-db4263c54b3b)


### SalesTransactionGenerator
- main.py: Script de Python para generar transacciones y enviarlas a Kafka.

### docker-compose.yml
- Configuración para levantar los servicios con Docker Compose.

## Docker Containers

- broker: Contenedor de Apache Kafka broker.
- zookeeper: Contenedor de Apache Zookeeper para gestionar el estado de Kafka.
- postgres: Contenedor de la base de datos PostgreSQL.
- es-container: Contenedor de Elasticsearch.
- kb-container: Contenedor de Kibana para la visualización de datos.

- ![image](https://github.com/Yawwwe/flinkcommerce_apacheflink_ecommerce_datastreaming/assets/124920713/d013b20d-c4f7-4f11-b8d8-accff9b1ceb7)
