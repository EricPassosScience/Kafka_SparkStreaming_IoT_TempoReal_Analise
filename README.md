# Análise de Dados de Sensores IoT em Tempo Real com Apache Spark Streaming e Apache Kafka
Vamos implementar uma solução completa de análise de dados em tempo real usando o Apache Spark e o Apache Kafka. Coletaremos dados de sensores IoT(Internet of Things) e, em tempo real (à medida que os dados são gerados e coletados), realizar o trabalho de análise e entregar respostas para um determinado problema de negócio.

## Definição do Problema
Uma determinada industria de materiais esportivos tem diversos equipamentos no parque industrial da empresa usados para produção e que funcionam 24/7.

Cada equipamento tem um sensor que mede a temperatura em intervalos regulares. Os equipamentos que excedem uma determinada temperatura média por muito tempo, podem ter a vida útil reduzida, gerando custos adicionais de manuntenção ou troca de equipamento.

O departamento de operações gostaria de ter uma solução de análise de dados em tempo real que calculasse a média de temperatura de cada equipamento a partir da leitura dos dados emitidos pelos sensores IoT em intervalos regulares.

Isso ajudaria no monitoramento da operação e ainda permitiria criar um histórico de uso dos equipamento.

O nosso trabalho será entregar essa solução.

## Arquitetura da Solução
### Fontes de dados de Sensores IoT:
Dados de medição de temperatura de máquinas industriais em tempo real. Criaremos um simulador em Python para gerar os dados;

### Apache Kafka (Processamento de Streaming de Dados):
Extração, organização, processamento, segurança e persistência dos dados gerados em tempo real. Os dados devem ficar disponíveis independente da solução de Analytics.

Link para dowload e documentação -> https://kafka.apache.org

### Spark Streaming (Analise de Dados em Tempo Real - Leitura do Streaming de Dados e Anáise com PySpark):
Converter o streaming de dados para calcular a média de temperatura por sensor, em tempo real.

Link da documentação do Conector com o Kafka -> https://spark.apache.org/docs/latest/structured-streaming-kafka-integration.html

ESPAÑOL: 

# Análisis de datos de sensores IoT en tiempo real con Apache Spark Streaming y Apache Spark
Implementaremos una solución completa de análisis de datos en tiempo real utilizando Apache Spark y Apache Kafka. Recopilaremos datos de sensores IoT (Internet of Things) y, en tiempo real (a medida que se generan y recopilan datos), realizaremos trabajos de análisis y entregaremos respuestas a un problema comercial determinado.

## Definición del problema
Cierta industria de artículos deportivos tiene varios equipos en el parque industrial de la empresa que se utilizan para la producción y funcionan las 24 horas del día, los 7 días de la semana.

Cada equipo tiene un sensor que mide la temperatura a intervalos regulares. Los equipos que superan cierta temperatura promedio por mucho tiempo pueden tener una vida útil reducida, generando costos adicionales de mantenimiento o reemplazo de equipos.

Al departamento de operaciones le gustaría contar con una solución de análisis de datos en tiempo real que calcule la temperatura promedio de cada equipo a partir de la lectura de datos emitidos por sensores IoT a intervalos regulares.

Esto ayudaría a monitorear la operación y también permitiría crear un historial de uso del equipo.

Nuestro trabajo será entregar esa solución.

## Arquitectura de soluciones
### Fuentes de datos de sensores IoT:
Datos de medición de temperatura en tiempo real de máquinas industriales. Crearemos un simulador en Python para generar los datos;

### Apache Kafka (procesamiento de transmisión de datos):
Extracción, organización, procesamiento, seguridad y persistencia de los datos generados en tiempo real. Los datos deben estar disponibles independientemente de la solución de Analytics.

Enlace de descarga y documentación -> https://kafka.apache.org

### Spark Streaming (Análisis de datos en tiempo real - Lectura y análisis de transmisión de datos con PySpark):
Convierta el flujo de datos a la temperatura promedio por sensor, en tiempo real.

Enlace de documentación del conector con Kafka -> https://spark.apache.org/docs/latest/structured-streaming-kafka-integration.html
