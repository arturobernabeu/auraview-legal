---
layout: default
title: Política de privacidad
permalink: /privacidad/
---

# Política de privacidad de AuraView IPTV

**Última actualización:** 7 de octubre de 2026

AuraView IPTV es un reproductor de listas IPTV. Esta política explica qué datos
maneja la aplicación, dónde se guardan y con quién se comparten.

El resumen es corto: **AuraView no tiene servidores propios y no recibe ningún
dato tuyo.** Todo lo que introduces se queda en tu dispositivo.

---

## 1. Quién es el responsable

Arturo Bernabeu, desarrollador independiente de AuraView IPTV.

Contacto: arturobernabeu.dev@gmail.com

## 2. Qué datos guarda la aplicación

Todo lo siguiente se almacena **únicamente en tu dispositivo**:

| Dato | Para qué | Cómo se guarda |
| :--- | :--- | :--- |
| Direcciones de tus listas (URL M3U, portal Xtream o fichero local) | Descargar y sincronizar tus canales | Base de datos local de la aplicación |
| Usuario y contraseña de tu portal Xtream | Conectarse a tu proveedor | **Cifrados** con una clave del almacén seguro de Android (`Keystore`), no en texto legible |
| Canales, categorías y guía de programación | Enseñarte la lista y qué están dando | Base de datos local |
| Tus favoritos y tus preferencias (tema, opciones de reproducción) | Recordar cómo quieres usar la aplicación | Base de datos local y preferencias |

## 3. Qué datos NO recoge la aplicación

AuraView **no** recoge, transmite ni almacena fuera de tu dispositivo:

- Ninguna identidad tuya: no hay registro, ni cuenta, ni correo, ni teléfono.
- Ninguna analítica de uso: qué canales ves, cuánto tiempo o cuándo.
- Ningún informe de fallos ni telemetría.
- Ninguna publicidad ni identificador publicitario.
- Ninguna ubicación, agenda, cámara, micrófono ni ficheros ajenos a los que tú
  elijas.

**No existe ningún servidor de AuraView.** Aunque quisiéramos, no habría dónde
enviar nada.

**Lo que sí puede llegarme, y no depende de la aplicación.** Google Play puede
darme, de forma agregada y anónima, estadísticas de instalaciones y de fallos de
los usuarios que lo han permitido en su dispositivo. No incluyen tus listas, tus
credenciales ni lo que ves.

## 4. Con quién se comunica la aplicación

AuraView abre conexiones a **dos sitios**, y a ninguno más:

1. **Tu proveedor de IPTV**, el que tú configuras. La aplicación le pide la
   lista, la guía y los propios canales. Ese proveedor ve tu dirección IP, tus
   credenciales y qué canales reproduces, exactamente igual que con cualquier
   otro reproductor. **Esa relación es tuya con él**, y se rige por la política
   de privacidad de tu proveedor, no por esta.
2. **Los servidores de los logotipos de canal**, si tu lista incluye enlaces a
   imágenes. Cada uno ve tu dirección IP al descargarse el logotipo.

Hay además unos pocos sitios a los que **tu navegador** —no la aplicación— se
conecta cuando eliges abrirlos desde Ajustes: esta política, los términos de uso
y las licencias de código abierto, alojados en GitHub Pages, y la ficha de la
aplicación en Google Play. Esos sitios pueden registrar tu visita (por ejemplo,
tu dirección IP) según su propia política. La aplicación no hace esas conexiones
por su cuenta.

## 5. Tráfico sin cifrar

Muchos proveedores de IPTV sirven sus listas por `http://` en lugar de
`https://`. Cuando detectamos que una dirección va sin cifrar, **la aplicación te
avisa antes de guardarla**: en Xtream, tu usuario y tu contraseña viajan dentro
de la propia dirección y son legibles por cualquiera que comparta tu red.

La aplicación permite ignorar el certificado TLS **de una lista concreta** cuando
tu proveedor usa uno mal configurado. Nunca se desactiva la verificación de forma
global.

## 6. Permisos

La versión publicada solicita estos permisos y ningún otro:

- **Internet** y **estado de la red**: descargar tus listas y reproducir.
- **Servicio en primer plano** y **mantener despierto**: que la reproducción no
  se corte al apagarse la pantalla.
- **Notificaciones**: mostrar los controles de reproducción mientras suena un
  canal. Android 13 o superior te pide permiso al abrir un canal; si lo rechazas,
  la reproducción funciona igual, sin esa notificación.

No se piden permisos de almacenamiento: para elegir una lista guardada en tu
dispositivo se usa el selector del sistema, que da acceso **solo** al fichero que
tú elijas.

## 7. Contenido

**AuraView no distribuye, aloja ni proporciona ningún canal ni contenido
audiovisual.** Es un reproductor vacío: todo lo que se ve procede de las listas
que tú aportas. La responsabilidad sobre la legalidad de esas fuentes es de quien
las aporta y de quien las emite.

## 8. Copias de seguridad

La copia de seguridad automática de Android está **desactivada** para esta
aplicación. Tus credenciales no salen del dispositivo ni siquiera en una copia de
seguridad de Google.

## 9. Menores

La aplicación no está dirigida a menores de edad y no recoge datos de nadie,
sea cual sea su edad.

## 10. Tus derechos

Como AuraView no recibe ningún dato tuyo, no hay nada que solicitar, rectificar
ni suprimir por nuestra parte. **Para borrar todo lo que la aplicación guarda,
desinstálala** o borra sus datos desde los ajustes de Android: se elimina la base
de datos, las credenciales cifradas y las preferencias.

Los datos que tenga tu proveedor de IPTV debes reclamárselos a él.

Si aun así crees que se están tratando tus datos de forma indebida, puedes
presentar una reclamación ante la Agencia Española de Protección de Datos
(https://www.aepd.es).

## 11. Cambios en esta política

Si cambia, la fecha de arriba cambiará con ella. Si el cambio afectara a qué
datos se manejan —hoy, ninguno fuera de tu dispositivo— se avisará dentro de la
aplicación.
