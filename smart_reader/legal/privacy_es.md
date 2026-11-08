---
title: Política de privacidad
---

# Política de privacidad

**Última actualización:** 2026-11-08 · **Vigencia:** 2026-11-08

## 1. Quiénes somos

Smart Reader (la «App») es una aplicación de lectura y estudio que funciona en local. El responsable del tratamiento de tus datos personales es **songshangkun** («nosotros»), con dirección de contacto: **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**.

Para cualquier pregunta, solicitud o reclamación sobre privacidad, escríbenos a **13808875@qq.com**.

## 2. En resumen

- Tu biblioteca de lectura, los documentos importados, las notas, los resúmenes y los ajustes se guardan **en tu dispositivo**. No gestionamos cuentas ni tenemos un servidor que almacene tus datos de lectura.
- **No vendemos** tus datos personales y **no** los usamos para publicidad conductual.
- Esta versión de la App **no incluye SDK de publicidad ni de analítica** y **no tiene compras dentro de la app**.
- La App **solo solicita el permiso de micrófono**, usado exclusivamente para la entrada de voz opcional y las grabaciones de notas, que se transcriben **en tu dispositivo** con el modelo de reconocimiento de voz en streaming. El audio nunca se sube. No se solicitan permisos de cámara, fototeca ni ubicación. Los documentos e imágenes se importan mediante el selector de archivos del sistema, y el OCR se ejecuta **íntegramente en tu dispositivo**.
- Las funciones de IA se ejecutan en un **servidor LLM que tú mismo configuras** o con un **modelo local que descargas en tu dispositivo**; consulta la sección 4.

## 3. Información que tratamos

Como la App funciona en local, casi toda la información no sale de tu dispositivo.

### 3.1 Información almacenada en tu dispositivo

| Contenido | Finalidad | Dónde se guarda |
|---|---|---|
| Documentos importados (PDF, EPUB, Office, texto, imágenes) y el texto extraído | Abrirlos, reajustarlos y volver a leerlos | Sandbox de la App (directorio de soporte) |
| Registros de la biblioteca: títulos, formatos, fecha de importación, posición de lectura | Mostrar tu biblioteca y retomar donde lo dejaste | Base de datos del dispositivo |
| Índice local de texto completo/recuperación y caché de resultados de IA (explicaciones, resúmenes, preguntas y respuestas) | Buscar en tus documentos y evitar llamadas repetidas a la IA | Base de datos y directorio de índices del dispositivo |
| Ajustes de lectura y apariencia (tema, idioma, fuente, modo de pasar páginas, acciones rápidas) | Recordar tus preferencias | Preferencias del dispositivo |
| Modelos de voz (TTS) descargados | Leer documentos en voz alta sin conexión | Sandbox de la App (directorio de modelos) |
| Dirección del servidor LLM, nombre del modelo y clave de API, si los configuras | Llamar a las funciones de IA que actives | En el dispositivo, almacenados de forma ofuscada; no podemos leerlos |
| Modelos de reconocimiento de voz (ASR), LLM local y embeddings descargados | Entrada de voz, preguntas y respuestas sin conexión y búsqueda semántica | Sandbox de la App (directorio de modelos) |
| Grabaciones de notas, historial de chat, resúmenes y notas compartidas | Reproducir grabaciones y seguir estudiando | Base de datos del dispositivo y sandbox de la App |

No conservamos ninguna copia de lo anterior en servidores y no podemos recuperarlo por ti. Haz tus propias copias de seguridad.

### 3.2 Información tratada solo al usar una función concreta

- **Archivos / Documentos (opcional).** Al importar un documento o una imagen, la App lee únicamente los archivos que eliges en el selector del sistema. Nada se sube a un servidor nuestro.
- **Reconocimiento de texto en el dispositivo (OCR).** Las imágenes y las páginas escaneadas de PDF se reconocen localmente con el componente de reconocimiento de texto de ML Kit en el dispositivo. Las imágenes nunca salen de tu dispositivo.
- **Síntesis de voz en el dispositivo (TTS).** Los documentos se leen con modelos de voz que descargas y ejecutas localmente. El texto no se envía a ninguna parte.
- **Entrada de voz y grabaciones de notas (opcional).** Cuando dictas texto o adjuntas una grabación a una nota, la App usa el micrófono y un modelo de reconocimiento de voz en streaming que se ejecuta **íntegramente en tu dispositivo**. El audio se convierte en texto localmente y no se sube. Puedes rechazar el permiso de micrófono; la lectura, la IA y las demás funciones siguen funcionando.
- **Modelos en el dispositivo (opcional).** Puedes descargar modelos de reconocimiento de voz, síntesis de voz, embeddings y modelos de lenguaje pequeños (GGUF). Estos archivos se guardan en el sandbox de la App y se ejecutan localmente; tu texto y audio no se envían a nosotros ni a un proveedor de modelos.

### 3.3 Información que sale de tu dispositivo

Solo en estos casos:

1. **Procesamiento con IA (opcional).** Cuando usas explicaciones, resúmenes, preguntas de seguimiento o acciones rápidas con IA, el texto seleccionado o el fragmento relevante se envía al **servidor LLM que tú has configurado** en Ajustes → Servicio de IA. El destinatario es el proveedor que elijas; no lo operamos, no podemos leer la dirección ni la clave que configures y no conservamos copia de lo que envíes. Revisa la política de privacidad de ese proveedor.
2. **Configuración remota y entrega de documentos.** La App obtiene archivos de configuración, textos legales y la lista opcional de apps recomendadas de las GitHub Pages del desarrollador, y descarga modelos de voz, reconocimiento de voz, embeddings y modelos de lenguaje locales del repositorio de modelos (Hugging Face / hf-mirror). Estas solicitudes no incluyen el contenido de tus documentos, tu historial de lectura, audio ni identificadores personales.
3. **Accesos a la red que tú inicias.** Abrir una imagen o un enlace dentro de un documento no sube nada por sí mismo; la App no incluye componentes de navegación, seguimiento ni publicidad.

## 4. Funciones de IA, en palabras sencillas

- **Servidor LLM configurado por el usuario (BYOK):** las explicaciones, los resúmenes, las traducciones y las preguntas y respuestas se generan enviando el texto seleccionado a la **dirección y la clave del LLM que tú mismo introduces**. El proveedor lo eliges tú: no lo operamos ni podemos leer la dirección o la clave que configures. Revisa la política de privacidad y retención de ese proveedor y no envíes por este canal información que consideres confidencial.
- **Modelo LLM local (opcional):** las explicaciones, los resúmenes y las preguntas y respuestas también pueden generarse con un modelo GGUF pequeño que descargues y ejecutes localmente. En ese modo, el texto permanece en tu dispositivo y no se envía a ninguna parte.
- **Procesamiento en el dispositivo:** la extracción de texto, el OCR, la indexación de texto completo y semántica, la síntesis de voz, el reconocimiento de voz y la inferencia de modelos locales se ejecutan localmente en tu dispositivo. **Estas funciones no suben tus documentos, imágenes ni audio.**

Puedes desactivar las funciones de IA en cualquier momento; la lectura, la búsqueda y la lectura en voz alta sin conexión siguen funcionando.

## 5. Por qué tratamos tu información

Tratamos la información únicamente para: importar y mostrar tus documentos; extraer y reajustar el texto; permitirte buscar, anotar y organizar tu biblioteca; ejecutar el OCR y la síntesis de voz que solicitas en el dispositivo; llamar al servidor de IA que configures; y mantener la App operativa y segura.

No usamos tus documentos ni tu historial de lectura para entrenar modelos, elaborar perfiles ni mostrar publicidad dirigida.

## 6. Terceros que pueden recibir información

| Destinatario | Recibe | Finalidad |
|---|---|---|
| El proveedor LLM que tú configures | El texto que envías para explicaciones, resúmenes o preguntas y respuestas | El procesamiento con IA que solicitas |
| GitHub Pages / GitHub (desarrollador) | Solicitudes de configuración, textos legales y apps recomendadas (sin contenido de documentos) | Configuración remota, entrega de documentos y promoción de apps |
| Hugging Face / hf-mirror | Solicitudes de descarga de modelos de voz, reconocimiento de voz, embeddings y LLM locales (sin contenido de documentos) | Entrega de modelos para el dispositivo |

Cada destinatario se rige por su propia política de privacidad. No vendemos ni alquilamos datos personales a nadie.

## 7. Cuánto tiempo conservamos la información

Tus documentos, índices, notas, cachés de IA y ajustes permanecen en tu dispositivo hasta que los borres, elimines el documento de la biblioteca o desinstales la App. Eliminar un documento de la biblioteca borra su registro, su archivo original y sus entradas de índice. La desinstalación lo elimina todo de forma permanente; no conservamos copia y no podemos recuperarlo.

El contenido que envíes a tu proveedor LLM se conserva según la política de retención de ese proveedor.

## 8. Seguridad

Tus datos se guardan en el sandbox de la App, protegidos por la seguridad del propio dispositivo (código de acceso, cifrado del disco). La dirección y la clave del LLM se almacenan de forma ofuscada en el dispositivo y nunca se nos transmiten. Ningún método de almacenamiento es perfectamente seguro; protege tu dispositivo y haz copias de seguridad.

## 9. Menores

La App no está dirigida a menores. No recopilamos a sabiendas datos personales de menores por debajo de la edad de consentimiento digital de su jurisdicción (13 años en Estados Unidos, 16 en gran parte del EEE y según la normativa local en otros lugares). Si crees que un menor nos ha facilitado información, contáctanos y te ayudaremos a eliminarla.

## 10. Tus derechos

Tus derechos dependen de dónde residas. Allí donde estés, puedes en cualquier momento: rechazar o revocar permisos opcionales; borrar documentos y sus datos desde la App; dejar de usar las funciones de IA; o dirigirnos una solicitud.

Como tus datos son locales, la forma más rápida de ejercer el acceso, la rectificación, la portabilidad o el borrado es directamente en la App.

## 11. Cambios en esta política

Podemos actualizar esta política. Cuando lo hagamos, cambiaremos la fecha indicada arriba y, si el cambio es sustancial, te avisaremos en la App. Seguir usando la App tras una actualización significa que aceptas la política revisada.

## 12. Contacto

Preguntas y solicitudes de privacidad: **13808875@qq.com**
Dirección postal: **中国河南省郑州市高新区科学大道银屏路正弘高新数码港熙园**
