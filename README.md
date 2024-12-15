# API

https://cors-anywhere.herokuapp.com/corsdemo


Pasos para configurar un proxy local con local-cors-proxy

1. Instalar Node.js y npm

Si aún no tienes Node.js instalado:
	1.	Descarga e instala Node.js desde nodejs.org.
	2.	Durante la instalación, asegúrate de incluir npm (Node Package Manager).

Para verificar la instalación:
node -v
npm -v

2. Instalar local-cors-proxy

local-cors-proxy es una herramienta que facilita el despliegue rápido de un proxy CORS.

Ejecuta este comando en tu terminal para instalarlo globalmente

npm install -g local-cors-proxy

3. Configurar el Proxy

Inicia el proxy apuntando al servidor de la API de SEACE. En tu terminal, ejecuta:

lcp --proxyUrl https://contratacionesabiertas.osce.gob.pe

Esto iniciará un servidor proxy local. Por defecto:
	•	La URL del proxy será: http://localhost:8010/proxy
	•	Las solicitudes enviadas a esta URL serán redirigidas al servidor de SEACE.
