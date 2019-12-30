---
description: >-
  Conoce el paso a paso para realizar la generación de reportes datos desde
  CKAN.
---

# Reportes con API's en CKAN

{% tabs %}
{% tab title="Instalación API" %}
**CKAN-API:** Librería para copiar en PYTHON desde el entorno de la base de datos de CKAN a formato .CSV:

1. **Copiar la librería CKANAPI**: Copiar en el directorio donde se encuentre el ArcGIS10.5         \fileserver\IDECA\2019\210000Gerencia\3AdministracionIG\2GobiernoDatos\1Insumos\python\ckanapi-3.0.tar.gz a C:\Python27\ArcGIS10.5 

2**. Ejecutar CMD:** Ir al command line del sistema.

3**. Acceder al script:** Pasarse a C:\Python27\ArcGIS10.5\Scripts cd C:\Python27\ArcGIS10.5\Scripts 

4. **Ejecutar PIP**: pip.exe install ..\ckanapi-3.0.tar.gz
{% endtab %}

{% tab title="Ejecutar reporte" %}
1. **Verificar script:** Dejar en ****C:\Python27\ArcGIS10.5\ el script "estadisticas".py

{% file src="../.gitbook/assets/script.txt" %}

{% hint style="success" %}
**Nota:** Por favor cambie la extensión de este archivo a _.py_ y el nombre a "_estadisticas_"
{% endhint %}

**2. Ejecutar .bat:** Cambiar la extensión del siguiente archivo a ".bat", el mismo se puede dejar en cualquier ubicación del explorador de archivos.

{% file src="../.gitbook/assets/bat.txt" %}

{% hint style="success" %}
**Nota:** Por favor cambie la extensión de este archivo a _.bat_  y el nombre a "_reporte_"
{% endhint %}
{% endtab %}

{% tab title="Generar reporte" %}
1. **Ejecutar archivo .bat:** Ingrese al archivo reporte.bat, dando doble clic.
2. **Pongale nombre al archivo:** Se abrirá una ventana "Comando de líneas" y este le pedirá que le asigne un nombre al archivo seguido de la extensión .CSV. _**Ej: ReporteDic.csv**_

![](../.gitbook/assets/image%20%282%29.png)

{% hint style="warning" %}
Tenga en cuenta: El archivo .CSV quedará en el escritorio
{% endhint %}
{% endtab %}
{% endtabs %}



2- Ejecución del programa stats\_datos.py: 2.1- Estando en el command line del sistema. 2.2- Pasarse a C:\Python27\ArcGIS10.5 cd C:\Python27\ArcGIS10.5 2.3- Cambiar el código de páginas de salida del sistema, el cual por defecto está en Mulitlingual Latin I \*\(850\) a West European Latin CHCP 1252 2.4- Verificar código de páginas, con el comando CHCP CHCP 2.5- Copiar el programa stat\_datos.txt o cualquier variante de python en C:\Python27\ArcGIS10.5 como stat\_datos.py 2.6- Ejecutar el programa, con python.exe con parámetros: el programa y el archivo csv de salida, así: python.exe stat\_datos.py &gt; opendata.csv

**Luego los pasos de la reunión del 17 de diciembre con Oscar Ardila**

C:\Python27\ArcGIS10.5

{% file src="../.gitbook/assets/script.txt" %}

{% file src="../.gitbook/assets/bat.txt" %}



