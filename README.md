# API EMITIR BOLETA HONORARIOS

## DESCRIPCIÓN:

La <b>API BBHH Factronica</b> esta diseñada para que el programador pueda realizar una fácil y rápida Integración con Sistema Propio.
<br>El objetivo de esta api es <b>"Emitir Boleta de Honorarios desde Sistema Propio"</b>.
<br>La comunicación entre el Servidor y Cliente se realiza a traves de Datos Json o archivos txt.

## PRECIOS:

La <b>API BBHH Factronica</b>, se encuentra disponible en 2 modalidades; Pago Único y Pago Mensual.
<br>En ambos casos el método de integración es el mismo, lo que cambia solo es la url del endpoint de la api.
<br>Esto quiere decir que si contrata la modalidad pago mensual y posteriormente quiere compra la api, solo deberá cambiar la url a la cual envía el json o archivo txt.
<br>
<br>Precio Modalidad Pago Único: <b>20 UF = $740.000</b>.- aprox. (Descuento)
<br>-Se utiliza en servidores propios del cliente
<br>-Sin limite de boletas emitidas.
<br>-Sin limite de empresas emisoras.
<br>
<br>Precio Modalidad Pago Mensual: <b>1 UF = $37.000</b>.- aprox.
<br>-Se utiliza en servidores de Factronica
<br>-Limite de 12 documentos por minuto.
<br>-Limite de 2 Empresas emisoras.
<br>-
<br>(Descuento) Los clientes que ya han comprado la API factura electrónica o boleta electrónica, tienen un <b>50% de descuento</b> en la modalidad pago único.

## CARACTERÍSTICAS:

![](https://scanapp.org/assets/github_assets/done.png) **Compatibilidad:** Windows, Linux, Mac, Android y Iphone.

![](https://scanapp.org/assets/github_assets/done.png) **Integración:** ApiRest Datos Json o Archivo Txt

![](https://scanapp.org/assets/github_assets/done.png) **Código Abierto:** Al comprar la Api se entrega código fuente.

![](https://scanapp.org/assets/github_assets/done.png) **Acceso SII Chile:** Acceso con Rut y Clave o Certificado Digital.

## PASOS A SEGUIR PARA LA INTEGRACIÓN:

A continuación se detalla el procedimiento a realizar en la integración.

-   [01.-Crear datos json o archivo txt]
-   [02.-Enviar datos Json o archivo txt]
-   [03.-Procesar Respuesta Json o archivo txt] 

## PASO 01:
Crear archivo txt o datos json con el siguiente formato:
````
{
	"Token": "qwerty",
	"RutEmisor": "11111111-1",
	"ClaveSii": "abc123",
	"NombreEmisor": "Juan Perez Pruebas",
	"GiroEmisor": "Servicios Informaticos",
	"DireccionEmisor": "Av. Las Pruebas 3344",
	"ComunaEmisor": "Providencia",
	"FonoEmisor": "56912345678",
	"CorreoEmisor": "correo@emisor.cl",
	"RutReceptor": "22222222-2",
	"NombreReceptor": "Luis Gonzalez pruebas",
	"DomicilioReceptor": "Av Jose Miguel Carrera 2232",
	"ComunaReceptor": "San Miguel",
	"FonoReceptor": "56987654321",
	"CorreoReceptor": "luis@receptor.cl",
	"DescripcionPrestacion_1": "Servicio de Asesoria",
	"ValorPrestacion_1": "100",
	"DescripcionPrestacion_2": "Servicio de Capacitacion",
	"ValorPrestacion_2": "200",
	"DescripcionPrestacion_3": "Instalacion 3 puntos de red",
	"ValorPrestacion_3": "300",
	"DescripcionPrestacion_4": "Upgrade servidor de correos",
	"ValorPrestacion_5": "400",
	"X509Certificate": "-----BEGIN CERTIFICATE-----nnnnnnnnn-----END CERTIFICATE-----",
	"PrivKey": "-----BEGIN PRIVATE KEY-----nnnnnnnnnn-----END PRIVATE KEY-----"
}
````
## PASO 02: ENVIAR PETICIÓN A LA API

Enviar la petición con el txt o datos json a la url del servidor. 
````
curl -k -d "Token=API-KEY-USER&RutEmisor=11111111-1&..." -H "Content-Type: application/x-www-form-urlencoded" -X POST http://www.sitio.cl/api/
````

## PASO 03: RECUPERAR RESPUESTA DE LA API

La respuesta que entrega la api es en formato json. 
````
{"Codigo":"220","Estado":"OK","Mensaje":"Boleta Emitida correctamente","FolioBoleta":"1675","UrlBase64":"nnnnnn"}
````


