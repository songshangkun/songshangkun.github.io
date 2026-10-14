---
title: Política de privacidad
---

# Política de privacidad

**Última actualización:** 2026-10-13 · **Vigencia:** 2026-10-13

## 1\. Quiénes somos

Smart Video es un reproductor multimedia inteligente de almacenamiento local («la App») para estudiantes de idiomas. El responsable del tratamiento de sus datos personales es **songshangkun** («nosotros»), al que puede contactar en **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**.

Para cualquier duda, solicitud o reclamación relacionada con la privacidad, contáctenos en **13808875@qq.com**.

## 2\. La versión resumida

  * Su biblioteca multimedia, subtítulos, notas y registros de estudio permanecen **en su dispositivo**. No operamos ningún sistema de cuentas ni ningún servidor posterior que almacene sus datos de estudio.
  * No **vendemos** su información personal y **no** la utilizamos para publicidad comportamental.
  * Esta versión de la App **no contiene SDK de publicidad ni SDK de analítica**.
  * El acceso a la biblioteca de fotos y a archivos es **opcional** y se utiliza únicamente cuando usted importa o exporta contenido multimedia. Nunca accedemos a la cámara, al micrófono ni a su ubicación.
  * Las funciones de IA envían el texto que selecciona a un **punto de conexión de LLM que usted configura** — véase la sección 4. El reconocimiento de voz en el dispositivo nunca sale de este.



## 3\. Información que tratamos

Como la App es de almacenamiento local, la mayor parte de la información nunca sale de su dispositivo.

### 3.1 Información almacenada en su dispositivo

Qué | Por qué | Dónde permanece  
---|---|---  
Entradas de la biblioteca multimedia: referencias de archivos, nombres, URL importadas / enlaces HLS, posición de reproducción | Para permitirle reabrir y reanudar su contenido multimedia de estudio | Base de datos en el dispositivo (sandbox de la app)  
Archivos de subtítulos y caché de transcripción | Para mostrar subtítulos y habilitar la búsqueda de palabras | Base de datos en el dispositivo  
Caché de explicaciones y resúmenes de IA (palabras, frases, resúmenes de contenido) | Para mostrar resultados previos sin volver a llamar a la IA | Base de datos en el dispositivo  
Registros de estudio de palabras / tarjetas de memoria y calendarios de repaso | Para impulsar el repaso por repetición espaciada | Base de datos en el dispositivo  
Notas que usted crea | Para conservar sus notas de estudio | En el dispositivo (memoria / almacenamiento local)  
Configuración de la app, incluido el tema, el idioma y el estilo de subtítulos | Para recordar sus preferencias | Preferencias en el dispositivo  
Dirección y clave del punto de conexión LLM, si configura uno | Para llamar a las funciones de IA que habilita | En el dispositivo, **cifrado** ; no podemos leerlo  
  
No conservamos ninguna copia en servidor de lo anterior y no podemos restaurársela. Por favor, realice sus propias copias de seguridad.

### 3.2 Información tratada solo cuando usa una función concreta

  * **Biblioteca de fotos (opcional).** Cuando importa contenido multimedia, la App lee los vídeos / audios que selecciona de su Biblioteca de fotos. Cuando exporta material de estudio, la App escribe en su Biblioteca de fotos. Nunca exploramos su biblioteca en segundo plano. Puede denegar el permiso; el resto de la App sigue funcionando.
  * **Archivos / Documentos (opcional).** Cuando importa contenido multimedia o documentos locales, la App lee los archivos que elige en la app Archivos / En mi iPhone. Nada se carga en un servidor que nosotros operamos.
  * **Sin micrófono, sin cámara, sin ubicación.** Smart Video no solicita ni utiliza el micrófono, la cámara ni los servicios de ubicación. El reconocimiento de voz se ejecuta sobre audio _ya presente en su archivo multimedia importado_ mediante modelos en el dispositivo; nunca graba desde el micrófono.
  * **Diagnóstico opcional (desactivado por defecto).** La App ofrece un interruptor opcional "Compartir diagnóstico" en Ajustes. Permanece desactivado hasta que lo encienda. Cuando está activado, la App puede preparar un breve informe de diagnóstico no personal y ayudarle a enviarlo por correo al desarrollador — véase el punto 5 de la sección 3.3.



### 3.3 Información enviada fuera de su dispositivo

Solo en estos casos:

  1. **Procesamiento de IA.** Cuando usa funciones de IA (traducción de subtítulos, explicación de palabras y frases, resumen y preguntas y respuestas de seguimiento), el texto que selecciona se envía al **punto de conexión LLM que usted configura** en Ajustes → Biblioteca de modelos → Servidor LLM. El destinatario es el proveedor que usted elige; nosotros no lo operamos, no podemos leer la dirección ni la clave que configure, y no conservamos copia de lo que envía. Revise la política de privacidad de ese proveedor.
  2. **Reconocimiento de voz (en el dispositivo).** La transcripción se ejecuta localmente con modelos sherpa que usted descarga en la Biblioteca de modelos. El audio y el texto **no** se envían a ningún lugar.
  3. **Verificación de compras.** Las compras dentro de la app las verifica la tienda de aplicaciones en su dispositivo (actualmente la Apple App Store). Solo recibimos una confirmación de compra, nunca los datos de su tarjeta de pago.
  4. **Configuración remota y descargas de modelos.** La App obtiene archivos de configuración y modelos ASR (sherpa) en el dispositivo desde las GitHub Pages / GitHub del desarrollador. Estas solicitudes no transportan su contenido multimedia ni de estudio.
  5. **Diagnóstico opcional (solo si lo activa).** Si activa "Compartir diagnóstico" en Ajustes, la App puede recopilar a lo sumo cada 7 días una instantánea mínima y no personal — versión de la app, versión del sistema operativo, idioma del dispositivo, un identificador anónimo aleatorio, el tipo de evento y una marca de tiempo — y abrir un borrador de correo prellenado en su app de correo dirigido al buzón del desarrollador. **Nada se transmite automáticamente: el correo se envía solo cuando usted pulsa explícitamente enviar.** Nunca recopilamos su dirección de correo, dirección IP, ubicación GPS, identificador publicitario, número de serie del dispositivo o información de cuenta, y no operamos ningún servidor que reciba estos datos.



No operamos SDK de publicidad ni de analítica, por lo que ningún identificador se comparte con redes publicitarias.

## 4\. Funciones de IA, en palabras sencillas

Smart Video ofrece dos tipos de procesamiento de IA:

  * **Reconocimiento de voz en el dispositivo (ASR):** la transcripción se ejecuta en su dispositivo con un modelo sherpa que usted descarga. **Su audio y su texto nunca salen de su dispositivo — nada se transmite.**
  * **Punto de conexión LLM configurado por el usuario (BYOK):** la traducción, la explicación y el resumen se generan enviando el texto seleccionado a la **dirección y clave LLM que usted introduce** en Ajustes → Biblioteca de modelos → Servidor LLM. El proveedor lo elige usted — nosotros ni lo operamos ni podemos leer la dirección o la clave que configure. Revise la política de privacidad y de retención de ese proveedor, y no envíe información que considere confidencial a través de este canal.



Puede desactivar las funciones de IA en cualquier momento en Ajustes; el reproductor, los subtítulos y las herramientas de estudio locales siguen funcionando sin IA.

## 5\. Por qué tratamos su información

Tratamos la información únicamente para: importar y reproducir su contenido multimedia; mostrar subtítulos y habilitar la búsqueda de palabras; ejecutar la transcripción en el dispositivo que usted solicita; llamar al punto de conexión de IA que configure; verificar compras; y mantener la App funcionando y segura.

No utilizamos su contenido de estudio para entrenar modelos, para perfilarle, ni para dirigir publicidad.

## 6\. Terceros que pueden recibir información

Destinatario | Qué recibe | Finalidad  
---|---|---  
El proveedor LLM que usted configura | El texto que envía para traducción / explicación / resumen | Procesamiento de IA que usted solicitó  
Apple App Store | Token de compra | Verificación de compras  
GitHub Pages / GitHub (desarrollador) | Solicitudes de configuración y descarga de modelos (sin contenido multimedia) | Configuración remota y entrega de modelos ASR en el dispositivo  
  
Cada destinatario se rige por su propia política de privacidad. No vendemos ni alquilamos información personal a nadie.

## 7\. Cuánto tiempo conservamos la información

Su biblioteca, subtítulos, notas y registros de estudio permanecen en su dispositivo hasta que los elimine, borre los datos o desinstale la App. Eliminar o desinstalar los elimina de forma permanente; no conservamos ninguna copia y no podemos recuperarlos.

El contenido que envía a su proveedor LLM configurado se conserva según la política de retención de ese proveedor.

## 8\. Seguridad

Sus datos se almacenan en una base de datos local protegida por la seguridad propia de su dispositivo (contraseña del dispositivo, cifrado de disco). La dirección y la clave del punto de conexión LLM se almacenan cifradas en el dispositivo y nunca se transmiten a nosotros. Ningún método de almacenamiento es totalmente seguro, así que proteja su dispositivo y mantenga copias de seguridad.

## 9\. Menores

La App no está dirigida a menores. No recopilamos a sabiendas información personal de menores por debajo de la edad de consentimiento digital en su jurisdicción (13 en Estados Unidos, 16 en gran parte del EEE, y según lo definido localmente en otros lugares). Si cree que un menor nos ha proporcionado información, contáctenos y le ayudaremos a eliminarla.

## 10\. Sus derechos

Sus derechos dependen de dónde viva; la sección específica por región que aparece al final de este documento los explica en detalle. Dondequiera que se encuentre, puede en cualquier momento: denegar o revocar permisos opcionales; exportar o eliminar sus datos desde la propia App; dejar de usar las funciones de IA; o contactarnos con una solicitud.

Como sus datos son locales, la forma más rápida de ejercer el acceso, la rectificación, la portabilidad o la supresión es directamente en la App.

## 11\. Cambios en esta política

Podemos actualizar esta política. Cuando lo hagamos, cambiamos la fecha indicada arriba y, para cambios sustanciales, le notificamos dentro de la App. El uso continuado de la App tras una actualización implica que acepta la política revisada.

## 12\. Contacto

Dudas y solicitudes de privacidad: **13808875@qq.com**  
Dirección postal: **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**
