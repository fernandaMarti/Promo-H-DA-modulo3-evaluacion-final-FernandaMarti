# Promo-H-DA-modulo3-evaluacion-final-FernandaMarti
## Proyecto de Análisis de Datos de Clientes de Aerolíneas
## Descripción del Proyecto
Este proyecto tiene como objetivo explorar y analizar datos relacionados con la actividad de vuelo y la lealtad de los clientes de una aerolínea. Se busca identificar patrones, tendencias y relaciones significativas en los datos, así como evaluar diferencias en la cantidad de vuelos reservados según el nivel educativo de los clientes.
## 

## Fases del Proyecto
El proyecto se divide en tres fases principales: Exploración y Limpieza, Visualización y Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo.

## Fase 1: Exploración y Limpieza
1. Exploración Inicial
Importación y Exploración de Datos:
Importar los datos desde los archivos Customer Loyalty History.csv y Customer Flight Activity.csv.
Utilizar funciones de Pandas (.info(), .describe(), .head(), .isnull()) para obtener una visión general de los datos, incluyendo la estructura, valores nulos y estadísticas básicas.
Unión de Conjuntos de Datos:
Identificar una clave común entre los dos conjuntos de datos y realizar una unión de los mismos de manera eficiente utilizando merge de Pandas.

2. Limpieza de Datos
Tratamiento de Valores Nulos:
Identificar columnas con valores nulos y decidir una estrategia de tratamiento (eliminación o imputación) para asegurar la integridad de los datos.

Verificación de Consistencia:
Asegurar que los datos sean coherentes y corregir cualquier inconsistencia detectada.

Ajustes y Conversión de Tipos de Datos:
Realizar cualquier ajuste o conversión necesaria en las columnas para garantizar que los datos estén en un formato adecuado para el análisis.

## Fase 2: Visualización
Utilizando herramientas de visualización (como Matplotlib y Seaborn), se generarán las siguientes gráficas para responder preguntas específicas sobre los datos:

Distribución de Vuelos Reservados por Mes:
¿Cómo se distribuye la cantidad de vuelos reservados por mes durante el año?

Relación entre Distancia de Vuelos y Puntos Acumulados:
¿Existe una relación entre la distancia de los vuelos y los puntos acumulados por los clientes?

Distribución de Clientes por Provincia o Estado:
¿Cuál es la distribución de los clientes por provincia o estado?

Comparación del Salario Promedio entre Niveles Educativos:
¿Cómo se compara el salario promedio entre los diferentes niveles educativos de los clientes?

Proporción de Clientes por Tipo de Tarjeta de Fidelidad:
¿Cuál es la proporción de clientes con diferentes tipos de tarjetas de fidelidad?

Distribución de Clientes según Estado Civil y Género:
¿Cómo se distribuyen los clientes según su estado civil y género?

## Fase 3: Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo
Preparación de Datos
Filtrado de Datos:
Filtrar el conjunto de datos para incluir únicamente las columnas relevantes: 'Flights Booked' y 'Education'.

Análisis Descriptivo
Cálculo de Estadísticas Descriptivas:
Agrupar los datos por nivel educativo y calcular estadísticas descriptivas básicas (como el promedio, la desviación estándar y los percentiles) del número de vuelos reservados para cada grupo.

Prueba Estadística
A/B Testing:
Realizar una prueba estadística (como una ANOVA o t-test) para determinar si existe una diferencia significativa en el número de vuelos reservados entre los diferentes niveles educativos.

### Herramientas Utilizadas
- Python 3
- Pandas
- Matplotlib
- Seaborn
- Scipy/Statsmodels (para pruebas estadísticas)

### Diccionario de Datos

A continuación, se presenta una descripción de las columnas presentes en el conjunto de datos:

| Columna                       | Descripción                                                                                 |
|-------------------------------|---------------------------------------------------------------------------------------------|
| `Loyalty Number`              | Número de fidelidad del cliente                                                            |
| `Year`                        | Año de la transacción o actividad                                                           |
| `Month`                       | Mes de la transacción o actividad                                                           |
| `Flights Booked`              | Número de vuelos reservados                                                                |
| `Flights with Companions`     | Número de vuelos reservados con acompañantes                                               |
| `Total Flights`               | Número total de vuelos reservados                                                          |
| `Distance`                    | Distancia total recorrida en los vuelos                                                    |
| `Points Accumulated`          | Puntos de fidelidad acumulados                                                             |
| `Points Redeemed`             | Puntos de fidelidad canjeados                                                              |
| `Dollar Cost Points Redeemed` | Costo en dólares de los puntos canjeados                                                   |
| `Country`                     | País de residencia del cliente                                                             |
| `Province`                    | Provincia o estado de residencia del cliente                                               |
| `City`                        | Ciudad de residencia del cliente                                                           |
| `Postal Code`                 | Código postal de residencia del cliente                                                    |
| `Gender`                      | Género del cliente                                                                         |
| `Education`                   | Nivel educativo del cliente                                                                |
| `Salary`                      | Salario del cliente                                                                        |
| `Marital Status`              | Estado civil del cliente                                                                   |
| `Loyalty Card`                | Tipo de tarjeta de fidelidad del cliente                                                   |
| `CLV`                         | Valor de vida del cliente (Customer Lifetime Value)                                        |
| `Enrollment Type`             | Tipo de inscripción del cliente                                                            |
| `Enrollment Year`             | Año de inscripción del cliente en el programa de fidelidad                                 |
| `Enrollment Month`            | Mes de inscripción del cliente en el programa de fidelidad                                 |
| `Cancellation Year`           | Año de cancelación del cliente del programa de fidelidad                                   |
| `Cancellation Month`          | Mes de cancelación del cliente del programa de fidelidad                                   |


### Instrucciones para la Ejecución
- Clonar el repositorio:
git clone <URL_DEL_REPOSITORIO>
cd <NOMBRE_DEL_REPOSITORIO>

- Instalar las dependencias necesarias:
pip install -r requirements.txt

### Notas Adicionales
Asegúrate de tener instaladas todas las librerías necesarias listadas en el archivo requirements.txt.

#### Contribución
Si deseas contribuir a este proyecto, por favor crea un fork del repositorio y realiza un pull request con tus mejoras y/o sugerencias.

Licencia
Este proyecto está licenciado bajo la Licencia MIT. Puedes ver más detalles en el archivo LICENSE.

Contacto
Para cualquier consulta, por favor contacta a jaggermarti80@gmail.com.

¡Gracias por tu interés en este proyecto!
