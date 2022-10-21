# Casptone_project_Titanic

Análisis del Dataset de los sobrevivientes del Titanic.

Integrantes: José Zamora Cifras

Este dataset importado de una competición de Kaggle, muestra una base de sobrevivientes y fallecidos durante el accidente del titanic.
Dentro de este encontraremos variables como:

- PassengerId: Valor unico que identifica a la persona representada en la fila del dataset.
- Survived: Nos muesta si la persona sobrevivió o no al accidente (falleció = 0, sobrevivió = 1).
- PcClass: A que clase pertenecía la persona (1 = primera clase, 2 = segunda clase, 3 = tercerca clase).
- Name: Nombre de la persona
- Sex: El sexo de la persona
- Age: Edad de la persona.

Dentro de la carpeta Notebooks encontraás 3 notebooks para correr en el siguiente orden:

1. Data Cleaning: En este notebook podrás ver como hice la limpieza del dataset, eliminando columnas con muy pocos valores y cambiando strings por valores, ejemplo sex female = 0, male = 1.
2. Data Analisys: Encontrarás una revisión del dataset, donde vemos la cantidad de fallecidos por sexo o clase.
3. Report: Notebook completo de trabajo donde utilizamos una regresión lineal para predecir quienes podrian sobrevivir al incidente.

Por otra parte, en Data podrás encontrar los datasets para trabajar los notebooks, en el hay dos carpetas:
1. Raw: Donde se encuentran las bases de manera bruta:
  - Train: Base para entrenar el modelo de regresión.
  - Test: Para testear el modelo
  - Submmission: Para comparar el resultado del testeo.
2. Proccesed: Base de Datos procesada.
