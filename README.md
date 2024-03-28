# BoletaHonorariosEmitir
Integración para emitir boleta de honorarios con sistema propio

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
