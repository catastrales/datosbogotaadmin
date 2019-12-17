---
description: >-
  Conoce el paso a paso para realizar la generación de reportes datos desde
  CKAN.
---

# Reportes con API's en CKAN

**Poner las instrucciones que envío Jose Ignacio**

1- Instalación de ckanapi que es una librería que sirve para copiar en python desde el entorno de la BD de CKAN a un archivo tipo csv: 1.1- Copiar la librería ckanapi que está en: \fileserver\IDECA\2019\210000Gerencia\3AdministracionIG\2GobiernoDatos\1Insumos\python\ckanapi-3.0.tar.gz a C:\Python27\ArcGIS10.5 1.2- Salir al command line del sistema. 1.3- Pasarse a C:\Python27\ArcGIS10.5\Scripts cd C:\Python27\ArcGIS10.5\Scripts 1.4- Ejecutar pip así: pip.exe install ..\ckanapi-3.0.tar.gz

2- Ejecución del programa stats\_datos.py: 2.1- Estando en el command line del sistema. 2.2- Pasarse a C:\Python27\ArcGIS10.5 cd C:\Python27\ArcGIS10.5 2.3- Cambiar el código de páginas de salida del sistema, el cual por defecto está en Mulitlingual Latin I \*\(850\) a West European Latin CHCP 1252 2.4- Verificar código de páginas, con el comando CHCP CHCP 2.5- Copiar el programa stat\_datos.txt o cualquier variante de python en C:\Python27\ArcGIS10.5 como stat\_datos.py 2.6- Ejecutar el programa, con python.exe con parámetros: el programa y el archivo csv de salida, así: python.exe stat\_datos.py &gt; opendata.csv

**Luego los pasos de la reunión del 17 de diciembre con Oscar Ardila**

C:\Python27\ArcGIS10.5

{% file src="../.gitbook/assets/script.txt" %}

{% file src="../.gitbook/assets/bat.txt" %}



