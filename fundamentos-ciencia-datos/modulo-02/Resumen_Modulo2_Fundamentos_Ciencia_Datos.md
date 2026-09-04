# Módulo 2 — Obtención e Investigación de Datos
**Curso: Fundamentos de Ciencia de Datos | MICITT**
**Luis Steven Madriz Campos | ATI, TEC Costa Rica**
*Mayo 2026*

---

## 1. Datos y Conjuntos de Datos

Un **conjunto de datos** es una recopilación de datos relacionados. Puede ser privado (acceso restringido a personas autorizadas) o público (disponible para cualquier persona). Ejemplos: los registros de pacientes de un médico son privados; el repositorio de datos abiertos de la OMS es público.

Los conjuntos de datos suelen contener varios archivos en distintos formatos. La información que describe el contenido y estructura de un conjunto de datos se denomina **metadatos** — son la guía que le permite al analista entender los datos antes de trabajar con ellos.

El formato más común para intercambiar datos es **CSV (Comma-Separated Values)**: un archivo de solo texto donde cada dato está separado por comas. Los archivos CSV pueden importarse directamente a herramientas como Excel para su análisis.

---

## 2. Microsoft Excel — Conceptos Fundamentales

### 2.1 Estructura de una hoja de cálculo

| Elemento | Descripción |
|---|---|
| **Celda** | Intersección de una fila y una columna. Identificada por coordenadas como A1, B2. |
| **Fila** | Identificada por números (1, 2, 3...). Excel soporta hasta 1.048.576 filas. |
| **Columna** | Identificada por letras (A, B, C...). Excel soporta hasta 16.384 columnas. |
| **Cuadro de Nombre** | Muestra las coordenadas de la celda activa. Escribir coordenadas aquí navega directamente a esa celda. |
| **Barra de fórmulas** | Muestra el contenido o fórmula de la celda activa. |
| **Hoja de trabajo** | Pestaña individual dentro de un libro. Se puede renombrar, agregar y eliminar. |
| **Libro** | Archivo de Excel (.xlsx) que contiene una o más hojas de trabajo. |

### 2.2 Operaciones básicas de navegación

- **Seleccionar columna completa:** clic en la letra del encabezado.
- **Seleccionar fila completa:** clic en el número del encabezado.
- **Seleccionar múltiples filas/columnas contiguas:** clic y arrastrar sobre encabezados.
- **Seleccionar filas/columnas no contiguas:** Ctrl + clic en cada encabezado.
- **Seleccionar rango de celdas:** escribir el rango en el Cuadro de Nombre (ej. A1:C5) o clic y arrastrar.
- **Seleccionar toda la hoja:** clic en el triángulo superior izquierdo o Ctrl + A.

### 2.3 Atajos de teclado esenciales

| Acción | Atajo |
|---|---|
| Negrita | Ctrl + N (Ctrl + B en inglés) |
| Cursiva | Ctrl + K (Ctrl + I en inglés) |
| Subrayado | Ctrl + S (Ctrl + U en inglés) |
| Copiar | Ctrl + C |
| Pegar | Ctrl + V |
| Seleccionar todo | Ctrl + A |
| Nueva hoja de trabajo | Shift + F11 |

---

## 3. Fórmulas y Funciones en Excel

### 3.1 Fórmulas

Las fórmulas son expresiones que realizan cálculos sobre valores o celdas. **Siempre comienzan con el signo igual (=)**. Sin el signo igual, Excel interpreta la entrada como texto plano.

| Operación | Símbolo | Ejemplo |
|---|---|---|
| Suma | + | =A1+B1 |
| Resta | - | =A1-B1 |
| Multiplicación | * | =A1*B1 |
| División | / | =A1/B1 |

Las fórmulas pueden referenciar celdas directamente, lo que permite que los resultados se actualicen automáticamente cuando cambian los valores de las celdas referenciadas.

### 3.2 Funciones básicas

Las funciones son fórmulas predefinidas integradas en Excel. Las cinco fundamentales:

| Función | Sintaxis | Descripción |
|---|---|---|
| **SUMA** | =SUMA(A1:A5) | Suma todos los valores en el rango |
| **PROMEDIO** | =PROMEDIO(A1:A5) | Calcula el promedio aritmético del rango |
| **CONTAR** | =CONTAR(A1:A5) | Cuenta cuántas celdas del rango contienen números |
| **MAXIMO** | =MAXIMO(A1:A5) | Devuelve el valor más alto del rango |
| **MINIMO** | =MINIMO(A1:A5) | Devuelve el valor más bajo del rango |
| **MEDIANA** | =MEDIANA(A1:A5) | Devuelve el valor central del rango ordenado |

La notación `A1:A5` indica un rango continuo de celdas. Es más eficiente que escribir =A1+A2+A3+A4+A5.

### 3.3 Formato de números

Excel permite aplicar formatos específicos a celdas numéricas:

| Formato | Descripción |
|---|---|
| **General** | Sin formato específico |
| **Número** | Valor numérico con decimales configurables |
| **Moneda** | Agrega símbolo de moneda ($, €, etc.) |
| **Contabilidad** | Similar a moneda, alineada para contabilidad |
| **Fecha** | Formatos de fecha (dd/mm/aaaa, mm/dd/aa, etc.) |
| **Porcentaje** | Multiplica el valor por 100 y agrega el símbolo % |
| **Fracción** | Muestra el número como fracción |
| **Científico** | Notación exponencial |

---

## 4. Importación de Datos en Excel

### 4.1 Archivos CSV y delimitadores

Un **delimitador** es el carácter que separa los datos individuales en un archivo de texto. En los archivos CSV, el delimitador es la coma (`,`).

La primera línea de un archivo CSV generalmente contiene los **encabezados de columna** — los nombres de las variables del conjunto de datos.

**Proceso para importar en la versión gratuita (Office.com):**
1. Guardar el archivo .txt como .csv (Archivo > Guardar Como > cambiar extensión a .csv)
2. Subir el archivo a OneDrive
3. Abrir desde Excel > Archivo > Abrir

**Proceso para importar en la versión completa de Excel:**
Datos > Obtener datos > Desde Archivo > Desde Texto/CSV

### 4.2 Herramientas de análisis de datos mencionadas en el módulo

| Herramienta | Descripción |
|---|---|
| **SQL** | Lenguaje de administración de datos para interactuar con bases de datos relacionales |
| **Tableau** | Plataforma en línea para que profesionales de datos compartan proyectos de análisis de grandes datos |
| **Kaggle** | Comunidad en línea para científicos de datos y entusiastas del aprendizaje automático; permite integración con herramientas como Excel, SQL y Tableau |

---

## 5. Observaciones, Variables y Valores

### 5.1 Conceptos fundamentales

| Concepto | Definición |
|---|---|
| **Variable** | Característica clave que se observa o mide; algo que cambia de una instancia a otra |
| **Observación** | Registro de ocurrencias para un conjunto de variables; equivale a una fila en una hoja de cálculo |
| **Valor** | Dato específico registrado en una observación; algo que ocurrió en una instancia |
| **Punto de datos** | El valor o conjunto de valores de una observación específica |
| **Conjunto de datos** | La colección completa de observaciones |
| **Analítica** | Uso de matemáticas, estadísticas y programación para descubrir patrones relevantes en los datos |

### 5.2 Tipos de variables

Las variables se clasifican en dos categorías principales:

**Variables categóricas (cualitativas)**

| Tipo | Descripción | Ejemplo |
|---|---|---|
| **Nominal** | Valores cualitativos según la identidad del objeto; sin orden inherente | Color de ojos, género, país |
| **Ordinal** | Valores cualitativos en orden de clasificación; las categorías tienen jerarquía | Rango de clases (1°, 2°, 3°), nivel de satisfacción |

**Variables numéricas (cuantitativas)**

| Tipo | Descripción | Ejemplo |
|---|---|---|
| **Discreta** | Conjunto finito de valores enteros contables; no admite fracciones | Cantidad de usuarios, número de pedidos |
| **Continua** | Rango infinito de valores; puede incluir decimales | Volumen de ventas, temperatura, peso |

---

## 6. Resumen de Labs completados

| Lab | Contenido | Entregable |
|---|---|---|
| **Introducción a Microsoft Excel** | Acceso a Office.com, guardar/abrir libros, celdas/filas/columnas, hojas de trabajo, formato básico | Archivo My_Bicycle_Shop_Sales.xlsx |
| **Conceptos Básicos de Excel** | Fórmulas aritméticas, referencias de celda, funciones SUMA/PROMEDIO/CONTAR/MAXIMO/MINIMO, formato de números | Libro "Conceptos Básicos" con 3 hojas |
| **Importando Datos a Excel** | Archivos CSV, delimitadores, importación desde texto y CSV | Archivo bike_sales.csv importado |
| **Práctica de Excel** | Aplicación integrada: encabezados, fórmulas de costo/ingreso/ganancia, función SUMA para totales | Libro Bike_Sales_Data.xlsx |

---

## 7. Preguntas del cuestionario final — respuestas correctas

| # | Pregunta | Respuesta correcta |
|---|---|---|
| 1 | Término que describe características clave observadas o medidas | **Variable** |
| 2 | Emparejar tipos de variable con definición | Nominal → cualitativa por identidad / Continua → cuantitativa rango infinito / Discreta → cuantitativa finita / Ordinal → cualitativa con orden |
| 3 | Categoría que incluye valores nominales y ordinales | **Categórica** |
| 4 | Descripción precisa de variables discretas | Son cuantitativas con un conjunto finito de valores |
| 5 | Emparejar variables con ejemplos | Discreto → cantidad de usuarios / Nominal → color de ojos / Continua → volumen de ventas / Ordinal → rango de clases |
| 6 | Descripción de SQL | Lenguaje de administración de datos para interactuar con bases de datos relacionales |
| 7 | Descripción de Tableau | Plataforma en línea para compartir proyectos de recopilación y análisis de grandes datos |
| 8 | Dos afirmaciones que describen Kaggle | Integración con Excel/SQL/Tableau + comunidad en línea para científicos de datos |
| 9 | Función para encontrar valores enteros mayores de lo esperado | **MAXIMO** (no Sort) |
| 10 | Operación para eliminar formato mixto en Excel | Resaltar rango de datos → pestaña Inicio → Borrar → Borrar Formatos |

---

*Documento generado al completar el Módulo 2 | Mayo 2026*
