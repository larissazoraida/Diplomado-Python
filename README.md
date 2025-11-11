## Diplomado Python para Ingenieros - FIUNA

# Ajuste y Extension de Curvas de Ejecucion

> Este repositorio contiene el trabajo final en el marco del Bootcamp de Data Analytics organizado por [Escuela de Datos Vivos].

## 🔍 Overview

Las obras civiles se enmarcan en un cronograma para su ejecucion, el mismo cronograma se expresa como porcentajes de ejecucion sobre el monto total estimado. De esta
manera podemos proyectar los montos que se esperan desembolsar en obras por año.
Si bien estas curvas programaticas sirven de referencia, siempre existe un desfase (positivo o negativo) entre la ejecucion real y la esperada segun el cromograma.
El objetivo de este proyecto es desarrollar una metodología de re-proyección. Primero, se ajustará la Curva programática restante, partiendo del avance real ejecutado a la fecha. En segundo lugar, se simulará un escenario de contingencia donde se implementa una extensión del plazo del 50% sobre la duración original de la obra, con el fin de proyectar su nuevo perfil de desembolsos anuales.

---

## 📊 Descripción del Proyecto

Este proyecto se centra en [el avance de las obras en etapa de ejecucion del Ministerio de obras publicas] a partir de [los datos de curvas y de contratos disponibles en el SICOE]. Para proveer una visión clara y en tiempo real de cómo estas se están desempeñando. 

Se utilizo BigQuery para analisis exploratorio y calculo avanzado de valores relevantes para la tabla de hechos, asi como para crear organizar todo el datamart. Desde PowerQuery se realizaron otras transformaciones y calculos menores para obtener la visualizacion final el PowerBI.

---
