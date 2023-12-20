Documentación de la API de Buda.com

La API de Buda.com proporciona acceso a información sobre los mercados y operaciones relacionadas con criptomonedas.
Puedes realizar llamadas públicas y privadas, dependiendo de las necesidades. 

Base URL
El URL base para acceder a la API de Buda.com es el siguiente:

https://www.buda.com/api/[version]/[path].[format]

Version: v2.
Format: Json.

Las llamadas públicas no requieren decir quién eres para usarlas, son datos públicos. 
De hecho, las puedes probar directamente en tu browser (agregando .json al final del path). 
Por ejemplo, prueba ingresando la siguiente URL: https://www.buda.com/api/v2/markets/eth-btc/ticker.json


Las llamadas privadas necesitan autenticación, así que para usarlas necesitas obtener un par API-KEY / API-SECRET desde tu cuenta. 
Para esto debes iniciar sesión en buda.com e ir a la sección de Configuración donde encontrarás la pestaña API Keys en la cual podrás 
crear llaves con diferentes niveles de permisos y fechas de expiración.
