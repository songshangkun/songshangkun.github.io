---
title: Política de privacidad
---

# Política de Privacidad

**Última actualización:** 2026-09-09 · **En vigor:** 2026-09-09

## 1. Quiénes somos

NotePay es una aplicación de registro de gastos de almacenamiento local («la App»). El responsable del tratamiento de sus datos personales es **songshangkun** («nosotros», «nuestra»), con domicilio en **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**.

Para cualquier duda, solicitud o reclamación relativa a la privacidad, contáctenos en **13808875@qq.com**.

## 2. La versión resumida

- Su libro de cuentas vive **en su dispositivo**. No operamos ningún sistema de cuentas ni servidor posterior que almacene sus datos contables.
- **No vendemos** su información personal y **no** la utilizamos para publicidad comportamental.
- Esta versión de la App **no contiene ningún SDK de publicidad ni de analítica**.
- La ubicación, la cámara, la biblioteca de fotos y el micrófono son **opcionales** y se usan únicamente cuando usted invoca la función correspondiente. Nunca rastreamos su ubicación en segundo plano.
- Las funciones de IA opcionales pueden enviar lo que usted escribe, dice o fotografía a una plataforma LLM pública preconfigurada por el desarrollador para su región — véase la sección 4. Usted no configura esa dirección ni esa clave usted mismo y no puede hacerlo. Puede desactivarlas.

## 3. Información que tratamos

Dado que la App es de almacenamiento local, la mayor parte de la información nunca abandona su dispositivo.

### 3.1 Información almacenada en su dispositivo

| Qué | Por qué | Dónde permanece |
|---|---|---|
| Asientos: importe, categoría, nota, fecha, nombre del lugar | Para mostrar su libro de cuentas, estadísticas y presupuestos | Base de datos en el dispositivo |
| Libros de cuentas y categorías que usted cree | Para organizar sus registros | Base de datos en el dispositivo |
| Ajustes de la App, incluido el idioma y la región | Para recordar sus preferencias | Preferencias en el dispositivo |
| Programaciones de recordatorios | Para avisarle a la hora que usted fije | Base de datos en el dispositivo y notificaciones locales |
| Clave del proveedor de IA (preconfigurada por el desarrollador según la región) | Para invocar las funciones de IA que usted habilite | En el dispositivo, **cifrada**; no podemos leerla |

No conservamos ninguna copia en servidor de lo anterior y no podemos restaurársela. Conserve por su cuenta sus propias copias de seguridad.

### 3.2 Información tratada solo cuando usa una función concreta

- **Ubicación (opcional).** Cuando adjunta un lugar a un registro, la App lee sus coordenadas para resolver un nombre de lugar. La resolución la realiza AMap (Gaode) en la China continental y Google Maps en las demás regiones, según la región configurada. Solicitamos la ubicación **solo mientras usa la App** — **nunca en segundo plano**. Puede denegar el permiso o desactivar por completo la función de mapa; el resto de la App sigue funcionando.
- **Cámara y biblioteca de fotos (opcionales).** Cuando fotografía o selecciona un recibo, la imagen se lee para su reconocimiento. Los originales no se cargan en ningún servidor nuestro.
- **Micrófono (opcional).** Cuando usa la entrada por voz, se captura y transcribe el audio. La transcripción se realiza **en su dispositivo** mediante modelos de voz sin conexión que usted descarga; el audio no se transmite a nuestros servidores.

### 3.3 Información enviada fuera de su dispositivo

Solo en estos casos:

1. **Geocodificación inversa** — la coordenada que usted selecciona se envía a AMap o a Google Maps para obtener un nombre de lugar.
2. **Tratamiento de IA** — si habilita la IA remota, el texto, la transcripción o la imagen del recibo que usted envía se transmiten a una plataforma LLM pública preconfigurada por el desarrollador para su región (por ejemplo, la serie Qwen alojada en ModelScope). Ese proveedor trata el contenido conforme a su propia política de privacidad. Usted no configura esa dirección ni esa clave usted mismo y no puede hacerlo.
3. **Verificación de compra** — las compras integradas las verifican Apple o Google. Solo recibimos una confirmación de compra, nunca los datos de su tarjeta de pago.
4. **Configuración remota y descargas de modelos** — la App obtiene archivos de configuración, modelos de voz y, cuando proceda, documentos legales actualizados. Estas solicitudes no llevan el contenido de su libro de cuentas.

No operamos SDK de publicidad ni de analítica, por lo que ningún identificador se comparte con redes publicitarias.

## 4. Funciones de IA, en pocas palabras

La App puede ejecutar IA **en su dispositivo** o a través de un **punto final remoto**.

- **Modo en el dispositivo:** su contenido permanece en su dispositivo. Nada se transmite.
- **Modo remoto:** su contenido se transmite a la plataforma LLM pública preconfigurada por el desarrollador para su región. Ese punto final puede estar ubicado en un país distinto del suyo. El proveedor actúa como encargado del tratamiento conforme a sus propias condiciones; revise su política. No envíe en modo remoto información que considere confidencial. **La App no opera ningún backend privado y no retiene ninguno de sus contenidos.**

Puede cambiar al modo en el dispositivo o dejar de usar las funciones de IA en cualquier momento en Ajustes.

## 5. Por qué tratamos su información

Tratamos la información únicamente para: registrar y mostrar sus gastos; generar estadísticas, presupuestos y recordatorios; resolver nombres de lugares; reconocer recibos y voz cuando usted lo solicite; verificar compras; y mantener la App en funcionamiento y segura.

No usamos el contenido de su libro de cuentas para entrenar modelos, para perfilarlo ni para dirigirle publicidad.

## 6. Terceros que pueden recibir información

| Destinatario | Qué recibe | Finalidad |
|---|---|---|
| AMap (Gaode) — región de la China continental | Coordenada que usted selecciona | Geocodificación inversa |
| Google Maps — demás regiones | Coordenada que usted selecciona | Geocodificación inversa |
| La plataforma LLM pública preconfigurada por el desarrollador para su región | Texto, transcripción o imagen que usted envía | Tratamiento de IA que usted solicitó |
| Apple App Store / Google Play | Testigo de compra | Verificación de compra |

Cada destinatario se rige por su propia política de privacidad. No vendemos ni alquilamos información personal a nadie.

## 7. Por cuánto tiempo conservamos la información

Su libro de cuentas y sus ajustes permanecen en su dispositivo hasta que usted elimine el registro, borre los datos o desinstale la App. Eliminarlos o desinstalarla los elimina de forma permanente; no conservamos ninguna copia ni podemos recuperarlos.

El contenido enviado a un punto final de IA remoto se conserva según la política de retención de ese proveedor.

## 8. Seguridad

Sus datos se almacenan en una base de datos local protegida por la propia seguridad de su dispositivo (código de acceso del dispositivo, cifrado de disco). Su clave del proveedor de IA, en su caso, se almacena cifrada en el dispositivo y nunca se transmite a nosotros. Ningún método de almacenamiento es totalmente seguro, así que proteja su dispositivo y conserve copias de seguridad.

## 9. Menores

La App no está dirigida a menores. No recopilamos a sabiendas información personal de menores por debajo de la edad de consentimiento digital en su jurisdicción (13 en Estados Unidos, 16 en gran parte del EEE, y según la normativa local en otros lugares). Si cree que un menor nos ha facilitado información, contáctenos y le ayudaremos a eliminarla.

## 10. Sus derechos

Sus derechos dependen de dónde resida; la sección específica por región que aparece al final de este documento los explica en detalle. Allá donde se encuentre, podrá en cualquier momento: denegar o revocar permisos opcionales; exportar o eliminar sus datos desde la propia App; dejar de usar las funciones de IA; o contactarnos con una solicitud.

Dado que sus datos son locales, la forma más rápida de ejercer el acceso, la rectificación, la portabilidad o la supresión es directamente en la App.

## 11. Cambios en esta política

Podemos actualizar esta política. Cuando lo hagamos, cambiamos la fecha indicada arriba y, en caso de cambios sustanciales, le avisamos en la App. El uso continuado de la App tras una actualización implica que acepta la política revisada.

## 12. Contacto

Dudas y solicitudes de privacidad: **13808875@qq.com**
Domicilio postal: **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**

---

*Este documento es una plantilla preparada para NotePay. Hágalo revisar por un asesor jurídico cualificado antes de su publicación.*
