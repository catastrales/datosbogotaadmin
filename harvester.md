---
description: >-
  Te gustaría colectar datos desde plataformas como ArcGIS hub, ckan u otras?.
  Consulta como hacerlo.
---

# Harvester

**1.Verificar configuración en servidor:** asegúrate que los servicios Harvester Gather\_Consumer y Fetch\_Consumer están activos en el servidor del CKAN.

**2.inicia sesión:** digita tu usuario y contraseña de administrador dando clic en la opción _**"Inicio de sesión para entidades"**_

![](.gitbook/assets/image%20%2828%29.png)

**3.Ingresa al harvest de ckan:** digita la URL de la plataforma de datos abiertos abiertos Bogotá, seguido de _**/harvest.**_ Deberá quedar de esta forma.

![](.gitbook/assets/image%20%28131%29.png)

**4.Alista la URL a cosechar:** la URL irá hasta la extensión de dominio Ej: \(.GOV.CO - .COM\), luego digita "/data.json"

![](.gitbook/assets/image%20%2820%29.png)

**5.Agrega una nueva fuente:** Da clic en el botón _"agregar nueva fuente"_

![](.gitbook/assets/image%20%28185%29.png)

**6. Pegar URL:** Copia la "_**URL"**_ que alistaste en el punto 4.

![](.gitbook/assets/image%20%2885%29.png)

**7.Asigna nombre al harvest:** Asigna un nombre a la cosecha de datos que vas a realizar con la entidad. Por favor colocar el nombre de la entidad con la que se va a realizar el harvest.

![](.gitbook/assets/image%20%28157%29.png)

**8.Descripción del harvest:** La descripción debe contener el nombre de la entidad con la entidad que se va a cosechar, plataforma con la que se va conectar. Ej: CKAN, ArcGIS hub.

![](.gitbook/assets/image%20%2841%29.png)

**9. Elige tipo de fuente:** selecciona el tipo de fuente conforme al tipo de plataforma.

![](.gitbook/assets/image%20%28178%29.png)

{% hint style="warning" %}
Tenga en cuenta: Si la plataforma a cosechar es CKAN, selecciona la opción **"CKAN"**. Si la plataforma a cosechar es ArcGIS hub selecciona **"DCAT JSON harvester".**
{% endhint %}

**10. Frecuencia de cosecha:** la cosecha de datos desde otras plataformas se pueden programar con una frecuencia de actualización o hacerla manualmente.

![](.gitbook/assets/image%20%28193%29.png)

**11. Guarda los cambios:** en la opción configuración deja la caja de texto en blanco, luego selecciona la organización con la cual vas a cosechar y da clic en "Guardar".

![](.gitbook/assets/image%20%28127%29.png)

**12. Ejecuta el harvest\(cosecha\):** da clic sobre la opción Reharvest

![](.gitbook/assets/image%20%28159%29.png)

{% hint style="info" %}
Este proceso puede tomar algunos minutos dependiendo del número de datos que se quiera cosechar.
{% endhint %}

**13. Verificar reporte de cargue:** Cuando los datos fueron cargados exitosamente, el estado del reporte muestra el mensaje "Finished" y en la sección _Error Summary_ presenta en mensaje "**No errors for this job**".

![](.gitbook/assets/image%20%2822%29.png)

