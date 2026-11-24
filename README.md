# Informe de Auditoría de Red Wi-Fi Insegura

## Introducción
Análisis de una petición web desde las herramientas del navegador para ver qué datos se muestran y qué pasa al usar redes Wi-Fi públicas[cite: 2, 3, 5].

## Sitio analizado
* URL: https://shiningwholeyyounglight.neverssl.com/online/[cite: 5]
* Host: shiningwholeyyounglight.neverssl.com[cite: 5]
* Protocolo: HTTP/1.1 (Estado: 200 OK)[cite: 5]

## Evidencia observada
En la pestaña Red y luego headers se ve[cite: 5]:
* Método: GET[cite: 5]
* Host: shiningwholeyyounglight.neverssl.com[cite: 5]
* Referer: http://neverssl.com/[cite: 5]
* User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:160.0) Gecko/20100101 Firefox/160.0[cite: 5]
* Otros headers: Accept-Language, Accept, Accept-Encoding, Connection y datos del servidor[cite: 5].

## Riesgos encontrados
En una red Wi-Fi pública, el tráfico sin cifrar puede ser interceptado por alguien en la misma red usando técnicas como Sniffing, Man-in-the-Middle o Evil Twins[cite: 1, 3]. Así se pueden ver dominios, encabezados como el User-Agent, qué navegás o datos sensibles si van sin cifrar[cite: 1, 3].

## Cómo ayuda una VPN
Una VPN crea un túnel con cifrado y encapsulamiento entre tu equipo y el servidor VPN[cite: 1, 3]. Si alguien intercepta el tráfico en la red pública, lo ve cifrado y no entiende el contenido, lo que protege el tráfico y la privacidad[cite: 1, 3].

## 3 Reglas de Oro
1. Usar VPN en redes Wi-Fi públicas para cifrar y encapsular el tráfico en un túnel[cite: 1, 3].
2. Evitar enviar contraseñas o datos sensibles en conexiones sin cifrar o redes que no conocés[cite: 1, 3].
3. Revisar bien a qué red te conectás y no fiarte solo de que tenga contraseña para evitar redes falsas (Evil Twins) o ataques internos[cite: 1].
