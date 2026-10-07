---
layout: default
title: Licencias de código abierto
permalink: /licencias/
---

# Licencias de código abierto de AuraView IPTV

**Última actualización:** 7 de octubre de 2026

AuraView IPTV se apoya en software libre de terceros. Esta página lo enumera, dice
bajo qué licencia se usa cada pieza y dónde está su código fuente y el texto de su
licencia. Los derechos de autor de cada componente pertenecen a sus autores.

---

## libVLC — reproductor alternativo

AuraView puede reproducir con **libVLC**, el motor de VLC, además de con Media3.

- **Licencia:** GNU Lesser General Public License, versión 2.1 (LGPL 2.1).
- **Cómo se usa:** sin modificar, como bibliotecas dinámicas separadas dentro de la
  aplicación. AuraView no incluye código de libVLC en su propio código.
- **Código fuente:** https://www.videolan.org/developers/vlc.html
- **Texto de la licencia:** https://www.gnu.org/licenses/old-licenses/lgpl-2.1.html

## Componentes bajo licencia Apache 2.0

Todos los siguientes se distribuyen bajo la **Apache License, versión 2.0**, cuyo
texto está en https://www.apache.org/licenses/LICENSE-2.0

| Componente | Para qué lo usa AuraView |
| :--- | :--- |
| Android Jetpack (AndroidX): Core, Activity, Lifecycle, Navigation, Room, DataStore, Paging, SavedState, Startup, Profile Installer y relacionados | Estructura de la aplicación, base de datos local, navegación y paginación |
| Jetpack Compose (AndroidX) y Compose Multiplatform runtime | Interfaz |
| Media3 (ExoPlayer) | Reproductor principal |
| Kotlin y kotlinx (coroutines y serialization) | Lenguaje, concurrencia y lectura de datos |
| Coil 3 | Carga de logotipos de canal |
| OkHttp y Okio | Conexiones de red |
| Dagger y Hilt | Inyección de dependencias |
| Guava | Utilidades de Google |
| Accompanist (drawablepainter) | Pintar imágenes en Compose |
| JetBrains annotations, JSpecify, javax.inject, jakarta.inject, JSR-305 | Anotaciones |

## Tipografías

Se usan estas tipografías, bajo la **SIL Open Font License, versión 1.1**
(https://openfontlicense.org):

- **Plus Jakarta Sans**
- **Space Grotesk**
- **JetBrains Mono**
- **Montserrat**, solo en la palabra «AuraView» del logotipo, convertida a trazos.

---

Si ves un componente que falte o una licencia mal indicada, escribe a
arturobernabeu.dev@gmail.com y se corrige.
