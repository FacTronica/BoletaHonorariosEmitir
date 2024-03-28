# Emitir Boleta de Honorarios desde Sistema Propio

API Diseñada para que el programador pueda realizar una rápida Integración de Sistema Propio.
El objetivo de esta api es "Emitir boleta de honorarios desde sistema propio".
La comunicación entre el Servidor y Cliente se realiza a traves de Datos Json.

## PRECIOS:
---
---

## CARACTERÍSTICAS:

![](https://scanapp.org/assets/github_assets/done.png) **Compatibilidad:** Windows, Linux, Mac, Android y Iphone.

![](https://scanapp.org/assets/github_assets/done.png) **Integración:** ApiRest Datos Json o Archivo Txt

![](https://scanapp.org/assets/github_assets/done.png) **Código Abierto:** Al comprar la Api se entrega código fuente.

## Documentación

A continuación se detalla el procedimiento a realizar en la integración.

-   [01.-Crear datos json o archivo txt]
-   [02.-Enviar datos Json o archivo txt]
-   [03.-Procesar Respuesta Json o archivo txt] 

## Ejemplo php arrat json:
````
<?php

$arregloJson = array(

"Token" => "qwerty",

"RutEmisor"=>"11111111-1",
"ClaveSii"=>"abc123",

"NombreEmisor"=>"Juan Perez Pruebas",
"GiroEmisor"=>"Servicios Informaticos",
"DireccionEmisor"=>"Av. Las Pruebas 3344",
"ComunaEmisor"=>"Providencia",
"FonoEmisor"=>"56912345678",
"CorreoEmisor"=>"correo@emisor.cl",
        
"RutReceptor" => "22222222-2",
"NombreReceptor" => "Luis Gonzalez pruebas",
"DomicilioReceptor" => "Av Jose Miguel Carrera 2232",
"ComunaReceptor" => "San Miguel",
"FonoReceptor" => "56987654321",
"CorreoReceptor" => "luis@receptor.cl",

"DescripcionPrestacion_1" => "Servicio de Asesoria",        
"ValorPrestacion_1" => "100",
"DescripcionPrestacion_2" => "Servicio de Capacitacion",        
"ValorPrestacion_2" => "200",
"DescripcionPrestacion_3" => "Instalacion 3 puntos de red",        
"ValorPrestacion_3" => "300",
"DescripcionPrestacion_4" => "Upgrade servidor de correos",        
"ValorPrestacion_5" => "400",

"X509Certificate"=>"-----BEGIN CERTIFICATE-----nnnnnnn-----END CERTIFICATE-----",
"PrivKey"=>"-----BEGIN PRIVATE KEY----nnnnnnn-----END PRIVATE KEY-----"
);
 
?>
````


## Ejemplo Json
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
