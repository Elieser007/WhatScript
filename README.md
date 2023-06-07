
# Paso 1: Entorno de Ejecución

Ingrese a: [Python Download](https://www.python.org/downloads/) y descargar e instalar la versión de Windows.
# Paso 2: Descargar archivos y ejecutar linea de comandos
Ingrese a: [Archivos Zip](https://github.com/Elieser007/WhatScript/archive/refs/heads/master.zip) descargue y descomprima en algun directorio de su PC, luego abra la carpeta y en la parte vacia presiona **Shift + click derecho**, puede seleccionar y abrir con la linea de comandos que guste.
# Paso 3: Instalar Dependencias del Script
Ejecute la siguiente línea de comando para instalar las dependencias.
```cmd
pip install -r requirements.txt
```
# Paso 4: Crear Excel y carpeta de Imagenes.
Para crear el excel y la carpeta debe de ejecutar una vez el archivo WhatScript.py
```cmd
python WhatScript.py
```
 y presionar "y" seguido de "Enter" para aceptar.

- Se creará un archivo **WhatMessages.xlsx** el cual deverá de rellenar con los datos que le pide la planilla. La planilla ya viene con un ejemplo.
- Se creará un carpeta **images** donde podra copiar sus imagenes.
- Se abrirá Whatsapp Web para sincronizar con el dispositivo, despues de sincronizar **no cierre** la pestaña del navegador, ya que ayuda a mantenerlo en la memoria y cargar mas rapido las otras pestañas.
# Paso 5: Enviar mensajes.
Para enviar los mensajes debe de ejecutar una vez más el archivo WhatScript.py
```cmd
python WhatScript.py
```
y empezará a leer el excel y a enviar.
- Importante!.
Si necesita cambiar el Código del Pais puede modificar del archivo WhatScript.py, la variable WHAT_CONTRY_PHONE_CODE.
```python
WHAT_CONTRY_PHONE_CODE = "+595"
```