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

3**. Acceder a la API:** Ubicarse en  la carpeta donde esté ArcGIS10.6

C:\Python27\ArcGIS10.6&gt;  

**ejecutando este comando** cd C:\Python27\ArcGIS10.6

Desde el archivo raíz 

4. **Ejecutar PIP**: pip.exe install ..\ckanapi-3.0.tar.gz 

ejecutando este comando 

C:\Python27\ArcGIS10.6&gt;**Scripts\pip.exe install ckanapi-3.0.tar.gz**

{% hint style="success" %}
Este permite ejecutar la API y poder obtener la información de los datos.
{% endhint %}
{% endtab %}

{% tab title="Verificar script" %}
1. **Verificar script:** Dejar en ****C:\Python27\ArcGIS10.5\ el script "estadisticas".py

{% file src="../.gitbook/assets/script.txt" %}

{% hint style="warning" %}
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
**Tenga en cuenta:** El archivo .CSV quedará en el escritorio. Espere hasta que finalice.
{% endhint %}

   3. **Convierte de CSV a XLS:** Abre un nuevo documento en excel, da clic en la pestaña "datos" , luego da clic en el botón "Desde el texto/CSV", selecciona el archivo y da clic en "Abrir".

En el campo "origen de archivo" deja "ninguno", en delimitador "personalizado" y coloca en el campo inferior el pipe "\|". Luego clic en "CARGAR"

![](../.gitbook/assets/image%20%28222%29.png)
{% endtab %}
{% endtabs %}



