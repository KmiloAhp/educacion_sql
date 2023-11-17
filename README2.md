## Paso1: redirigete a la carpeta del proyecto

## Paso 2:Cree el ambiente virtual
python -m venv myenv

## Paso 3: Avtivar el entorno virtual
myenv\Scripts\activate

### Observacion: si esta en MacOS o Linux debe usar:
source myenv/bin/activate

## Paso 4: Instalar las librerias del archivo requirements
pip install -r requirements.txt

## Paso 5: Luego descargar el csv mas reciente del siguiente url
https://datosabiertos.mineduc.cl/titulados-en-educacion-superior/

## Paso 6: Ejecutar la aplicacion
python get_excel_resumen_es.py