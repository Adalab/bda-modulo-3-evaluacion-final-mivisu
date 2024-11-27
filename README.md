# Examen Final - Análisis de Datos del Comportamiento de Clientes en un Programa de Lealtad de Aerolínea

Este README tiene como objetivo proporcionar una descripción detallada de los pasos y las metodologías utilizadas para analizar los datos proporcionados en los archivos "Customer Flight Analysis.csv" y "Customer Loyalty History.csv". El análisis de estos datos busca entender el comportamiento de los clientes dentro del programa de lealtad de una aerolínea.

## Descripción de los Archivos

### 1. **Customer Flight Analysis.csv**
Este archivo contiene información sobre la actividad de vuelo de los clientes, incluyendo detalles sobre los vuelos reservados, la distancia volada, puntos acumulados y redimidos, y los costos asociados a los puntos redimidos. Los atributos clave de este archivo son:

- **Loyalty Number**: Identificador único para cada cliente dentro del programa de lealtad.
- **Year**: Año de registro de las actividades de vuelo.
- **Month**: Mes del año en que ocurrieron las actividades.
- **Flights Booked**: Número de vuelos reservados por el cliente durante el mes.
- **Flights with Companions**: Vuelos reservados en los que el cliente viajó con acompañantes.
- **Total Flights**: Total de vuelos realizados por el cliente.
- **Distance**: Distancia total volada durante el mes.
- **Points Accumulated**: Puntos acumulados por el cliente durante el mes.
- **Points Redeemed**: Puntos redimidos por el cliente.
- **Dollar Cost Points Redeemed**: Valor en dólares de los puntos redimidos.

### 2. **Customer Loyalty History.csv**
Este archivo proporciona un perfil detallado de los clientes, incluyendo su ubicación, nivel educativo, ingresos, estado civil, y detalles sobre su membresía en el programa de lealtad. Los atributos clave incluyen:

- **Loyalty Number**: Identificador único del cliente, utilizado para unir los dos archivos.
- **Country**: País de residencia del cliente.
- **Province**: Provincia o estado de residencia.
- **City**: Ciudad de residencia.
- **Postal Code**: Código postal.
- **Gender**: Género del cliente.
- **Education**: Nivel educativo del cliente.
- **Salary**: Ingreso anual estimado del cliente.
- **Marital Status**: Estado civil del cliente.
- **Loyalty Card**: Tipo de tarjeta de lealtad.
- **CLV**: Valor total estimado del cliente durante su relación con la aerolínea.
- **Enrollment Type**: Tipo de inscripción al programa de lealtad.
- **Enrollment Year/Month**: Año y mes de inscripción.
- **Cancellation Year/Month**: Año y mes de cancelación (si aplica).

## Fase 1: Exploración y Limpieza

### Exploración Inicial
En esta fase, se realiza una exploración básica de los datos para comprender su estructura y contenido. Utilizamos las siguientes acciones:

1. **Carga de los Datos**: Importamos los archivos CSV y revisamos su estructura.
2. **Revisión de Valores Nulos**: Identificamos la presencia de valores nulos en columnas clave.
3. **Estadísticas Descriptivas**: Generamos estadísticas básicas como el número de filas, columnas, y los tipos de datos.
4. **Unión de los Archivos**: Combinamos ambos archivos utilizando la columna `Loyalty Number` para asociar la información de vuelos con el perfil de los clientes.

### Limpieza de Datos
Para asegurar la calidad de los datos, se realizan las siguientes tareas:

1. **Manejo de Valores Nulos**: Se imputan o eliminan los valores faltantes en columnas esenciales.
2. **Corrección **: Revisamos y corregimos valores atípicos.
3. **Conversión de Tipos de Datos**: Nos aseguramos de que las columnas tengan los tipos de datos adecuados.

## Fase 2: Visualización de Datos

En esta fase, realizamos diversas visualizaciones para responder a preguntas clave sobre el comportamiento de los clientes. Utilizamos herramientas como **matplotlib** y **seaborn** para generar los gráficos necesarios.

1. **Distribución de Vuelos Reservados por Mes Durante el Año**:  
   Se utiliza un gráfico de barras (barplot) se utiliza cuando deseas representar la media, suma, conteo u otra función agregada de una variable en función de categorías.
   para visualizar cómo se distribuye la cantidad de vuelos reservados mes a mes a lo largo del año.

2. **Relación entre Distancia de los Vuelos y los Puntos Acumulados**:  
   Utilizamos un gráfico de dispersión (scatter plot) para mostrar si existe alguna relación entre la distancia volada y los puntos acumulados por los clientes.

3. **Distribución de los Clientes por Provincia o Estado**:  
   Utilizo un gráfico de barras (countplot) Este tipo de gráfico es ideal para visualizar la frecuencia de valores en una variable categórica.
   Muestra cómo se distribuyen los clientes según su provincia o estado de residencia.

4. **Comparación del Salario Promedio entre Niveles Educativos**:  
   Utilizo un gráfico de barras (barplot) se utiliza cuando deseas representar la media, suma, conteo u otra función agregada de una variable en función de categorías
   Nos permite comparar el salario promedio de los clientes según su nivel educativo.

5. **Proporción de Clientes con Diferentes Tipos de Tarjetas de Lealtad**:  
   Un gráfico de pastel (pie chart) es adecuado para mostrar la proporción de clientes que poseen diferentes tipos de tarjetas de fidelidad.

6. **Distribución de Clientes Según Estado Civil y Género**:  
   Utilizo un  gráfico de barras (countplot) Este tipo de gráfico es ideal para visualizar la frecuencia de valores en una variable categórica.
   Apiladas puede ser útil para mostrar cómo se distribuyen los clientes según su estado civil y género.

 MATERIAL UTILIZADO :

- Material de estudio proporcionado por Adalab "Módulo 3: Transformando Datos"

- Código de Visual Studio

- Material de estudio: ejercicios intermedios

- Archivos CSV

- Chat GPT

 TECNOLOGIA UTILIZADA:

- Python : lenguaje de programación principal.

- Bibliotecas :

- pandaspara manipulación de datos.

- numpypara operaciones numéricas.

- scipypara análisis estadístico.

- matplotliby seabornpara visualización de datos.

- sklearnpara imputación de datos y análisis adicional.

- scikit_posthocspara pruebas estadísticas post-hoc.


## Conclusiones

En base al análisis realizado, se proporcionan recomendaciones sobre cómo la aerolínea podría optimizar su programa de lealtad. Los resultados obtenidos a través de las visualizaciones y los análisis estadísticos pueden ofrecer información valiosa sobre los comportamientos de los clientes y cómo estos se pueden correlacionar con variables como ingresos, educación y tipo de tarjeta de lealtad.

- CONTRIBUCIONES :

- Todas las sugerencias y contribuciones que me ayuden a mejorar seran bienvenidas, cualquier duda que te surja contactar conmigo a - mire0609@gmail.com

- AUTORA : Mirella Vissetti Suárez
---
