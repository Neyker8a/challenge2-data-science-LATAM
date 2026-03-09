# Análisis de Evasión de Clientes (Churn Analysis)

## Descripción del proyecto

Este proyecto tiene como objetivo analizar los factores asociados con la evasión de clientes (*churn*) en una empresa de telecomunicaciones. A través de técnicas de análisis exploratorio de datos (EDA), se busca identificar patrones en el comportamiento de los clientes que permitan comprender qué características están relacionadas con una mayor probabilidad de cancelación del servicio.

El análisis se realiza utilizando Python y diversas librerías de ciencia de datos para limpiar, procesar y visualizar la información.

---

## Objetivos

* Analizar la distribución de la variable churn.
* Explorar la relación entre churn y variables categóricas como tipo de contrato, servicio de internet y método de pago.
* Analizar cómo variables numéricas como el tiempo de permanencia del cliente y los cargos mensuales influyen en la evasión.
* Identificar patrones que puedan ayudar a comprender mejor el comportamiento de los clientes.

---

## Tecnologías utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Análisis realizado

Durante el proyecto se realizaron los siguientes pasos:

1. **Importación y limpieza de datos**

   * Revisión de valores faltantes.
   * Conversión de tipos de datos.
   * Eliminación de registros inconsistentes.

2. **Transformación de datos**

   * Conversión de variables categóricas.
   * Creación de la variable `cuentas_diarias`.

3. **Análisis exploratorio de datos (EDA)**

   * Distribución de la variable churn.
   * Análisis de churn según variables categóricas.
   * Análisis de variables numéricas como tenure, cargos mensuales y gasto total.
   * Visualizaciones mediante gráficos.

4. **Análisis adicional**

   * Matriz de correlación entre variables numéricas.
   * Exploración de relaciones entre variables.

---

## Principales insights

* Los clientes con **contratos mensuales** presentan una mayor tasa de cancelación.
* La mayor parte del churn ocurre durante los **primeros meses de relación con la empresa**.
* Los clientes con **cargos mensuales más altos** tienden a presentar mayor probabilidad de cancelar el servicio.
* El **soporte técnico** y el tipo de servicio de internet también parecen influir en la retención de clientes.

---

## Cómo ejecutar el proyecto

1. Clonar el repositorio

```bash
git clone https://github.com/tu_usuario/tu_repositorio.git
```

2. Instalar las dependencias

```bash
pip install pandas numpy matplotlib seaborn
```

3. Abrir el notebook

```bash
jupyter notebook
```

4. Ejecutar el archivo `.ipynb` para reproducir el análisis.

---

## Conclusión

El análisis permitió identificar varios factores asociados con la evasión de clientes, como el tipo de contrato, el tiempo de permanencia y el costo del servicio. Estos hallazgos pueden ayudar a diseñar estrategias de retención y mejorar la experiencia del cliente.

---

## Autor

Proyecto realizado como parte de un desafío de análisis de datos utilizando Python.
