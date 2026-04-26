# PROYECTO 01 - E-commerce European Fashion

## Base de datos
https://www.kaggle.com/datasets/joycemara/european-fashion-store-multitable-dataset

1) SQL:
- Exploración inicial del dataset.
- Se crean tablas asociadas a cada archivo .csv identificando claves primarias y foráneas.
- Para su correcta lectura, se trabajan los datos de columnas relacionadas a porcentajes.
- Se unen tablas y se procede a realizar consultas generales de negocio.
- Finalmente, se crea una vista, la cual se usará en Python.

2) Python
- Se carga la base de datos desde SQL y se transforman tipos de datos incorrectos a su tipo indicado.
- Debido a la naturaleza del dataset, en la limpieza no se consideró la exploración de outliers.
- En la exploración del dataset, se crean columnas para realizar cálculos considerados necesarios y se definen KPI.
- Se realizan diversos cálculos de negocio cuyos resultados pueden verse tanto en DataFrames como en gráficos.
- Para finalizar, se exporta el DataFrame limpio para su uso en Tableau.

3) Tableau
- Se carga el archivo exportado previamente para realizar diversos gráficos y presentar un dashboard interactivo.
-> https://public.tableau.com/views/01_E-CommerceEuropeanFashion/E-CommerceEuropeanFashion?:language=es-ES&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
