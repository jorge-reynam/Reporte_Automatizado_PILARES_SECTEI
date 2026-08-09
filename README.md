# Reporte Automatizado Semanal PILARES

## Descripción del proyecto
Este proyecto surge como una propuesta ante la necesidad de obtener un conteo semanal de atenciones brindadas a usuarias y usuarios de uno de los Puntos de Innovación, Libertad, Artes, Educación y Saberes (PILARES), ubicado en la región sur de la Ciudad de México.
El objetivo del subprograma educativo PILARES, nacido en 2017, es acercar y facilitar la educación media superior, entre otras actividades a las personas que habitan en colonias identificadas con un nivel educativo bajo, población vulnerable, zonas de alta percepción de inseguridad, etc.
El objetivo del presente proyecto es facilitar el conteo de asistencias diarias en el PILARES Cuauhtenco y obtener los principales KPIs (usuarios nuevos, adherencia, recurrencia).

## Objetivos principales
1. Leer información contenida en una base de datos alojada en Google Worspace, misma que se llena de forma diaria con la información de atenciones por usuario, folio y actividad.
2. Calcular el número de usuarios nuevos atendidos por semana.
3. Enviar la información a través de correo electrónico en forma de un dataframe y una gráfica con las atenciones registradas por día.

## Estructura del repositorio
* `reporte_automatico.py`: Script automatizado para generar el reporte

## Tecnologías utilizadas
* **Python:** Lenguaje base.
* **Pandas:** Manipulación y limpieza de estructuras de datos.
* **NumPy:** Manejo de valores nulos y operaciones lógicas.
* **Matplotlib & Seaborn:** Creación de gráficos estadísticos y mapas de calor.
