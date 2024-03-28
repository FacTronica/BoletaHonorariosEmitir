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

"X509Certificate"=>"-----BEGIN CERTIFICATE-----
MIIH0zCCBbugAwIBAgIKHglG7AABAARheTANBgkqhkiG9w0BAQsFADCBvzELMAkG
A1UEBhMCQ0wxHTAbBgNVBAgTFFJlZ2lvbiBNZXRyb3BvbGl0YW5hMREwDwYDVQQH
EwhTYW50aWFnbzEUMBIGA1UEChMLRS1DRVJUQ0hJTEUxIDAeBgNVBAsTF0F1dG9y
u5IG4NJ3rofCx4Hd88cXsaYWiAvYkwgNdP3Mp3V3q9N+iS+deahAU/ErWH9wIK88
IYYlhnOWn/v8/bYRSX768ABMcuLqJ8xYxKc39dXGkG6eubI+ziVOjprIXqIT1f8N
J6Par5pT5G6AQyx2Pm55cz1NcYVh4kkJes2qL7nEhenS67S+RVXtGmYbULknwGq3
w65YxpsIXC/YyMUoEsAmBekjE20CqjO+CbPfB4QwLr7Rbtu2iyms
-----END CERTIFICATE-----",


"PrivKey"=>"-----BEGIN PRIVATE KEY-----
MIIEvQIBADANBgkqhkiG9w0BAQEFAASCBKcwggSjAgEAAoIBAQDhvn7yI/YXf/Tx
sy5R6vTR0eQ2h4NL4aZLFq8PJ96KX3nNO7o/d8PhqKyIwMT2TxuVfW3GUcnF1N3s
NffGg1YWC2z3bXAbh39Q+3YzsIrPnPz4P3bSENeRMg+ezSRefl7mKSMGNrlo7u6+
0hUpdsrFBcJuanJA74K9+Rzo8eoAh8bwzqcqKC7wMmnd8MEereizxC9za0S0NqbO
leHiz0qife+pLR2QzMrjeBdumm1K4Q9dbCHEChbEdjnUC7YtuCqeT6UY2LX6TztP
C23/u5Zv/2tYyF0O4MDT5w5r9cjpL9ssxjeedAHlg+NDl9JREEJtJ4IlXIJIaZhd
CSqW6kQqKSenC7JvPVM3TrusO4yrcuQyVq5h6gMBAoGAeATzFvIbBggXeF2UTg8O
baKleh84NLDPQY2UzdDHHlEIDAbXA/Sg1BoqNkz8WJKBc0nZkbQUCtVvppRB0xfq
ybQGAr0OO0qJF1fDz5lvlbb7UkAwnsWuPksyC64RZFF+6/9BOsx/lc2nNKYPf2Db
cy0gxQjejh8g1OvHXDgli08=
-----END PRIVATE KEY-----"

);
  
 
?>
````
