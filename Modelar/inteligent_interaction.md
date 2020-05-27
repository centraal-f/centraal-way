# Explorar/Construir Modelos para interacciones cognitivas

Dentro del [PAL](link) a la hora de explorar la factibilidad o construir un modelo de ML/IA que aopoye la interacciones humanas-software-congnitive o software-congnitive [CENTRAAL](www.centraal.com) cree en las buenas praticas de repodctubilidad de los experimentos de ciencia de datos y la trazabilidad de los experimentos ejecutados. Para ello sugiere y apoya utilizar herramientas como:
1.[Kedro](Kedro)
2. [MLflow](Mlflow).

Este documento describe como realizar  la inicializacion del repo basado en las herramientas mencionadas.

1. Crear un virtual enviorment del proyecto

Para controlar las dependencias del proyecto es necesario crear un virtual env. Para ello:
  - Linux/Unix systems:
  
     `virtualenv ~/venv/project_name`
     
  - Windows:
  
      `python -m ~/venv/project_name`
      
2. Activar el virtual env
  - Linux/ Unix Systems
      
      `source  ~/venv/project_name/bin/activate`

3. Instalar Kedro
  `pip install kedro`
  
4. Instalar requerimientos
  `kedro build-reqs`
  `kedro install`
  
5. crear los keys adecuados en `conf/local/credentials.yml`


 
      
