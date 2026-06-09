---
title: Política de Privacidad de Retami
description: Política de privacidad de la aplicación móvil Retami.
---

# Política de Privacidad de Retami

**Última actualización:** 6 de junio de 2026

Retami ("la app", "nosotros") es una aplicación móvil para retos de fitness en grupo desarrollada por **Alejandro Rubio** ("el desarrollador"). Esta política explica qué datos recogemos, por qué los recogemos, con quién los compartimos y cómo puedes ejercer tus derechos sobre ellos.

## 1. Responsable del tratamiento

- **Responsable:** Alejandro Rubio
- **Contacto:** [privacy@retami.app](mailto:privacy@retami.app)
- **Ámbito:** Esta política aplica a todos los usuarios de la app Retami en iOS, Android y web.

## 2. Datos que recogemos

**(a) Datos que tú nos proporcionas directamente:**

- **Cuenta:** email y contraseña al registrarte. La contraseña se almacena cifrada (hash) en nuestro proveedor de autenticación; nadie del equipo de Retami puede leerla.
- **Perfil:** nombre de usuario (username), nombre a mostrar (display name), foto de perfil opcional, bio opcional, fecha de nacimiento (obligatoria, para verificar edad mínima de 16 años), zona horaria.
- **Contenido:** mensajes de chat de grupo, mensajes directos, fotos de portada de tus grupos, fotos y descripciones de actividades que registras, reglas de los grupos que creas, reacciones a mensajes y actividades.

**(b) Datos que se generan automáticamente al usar la app:**

- **Identificadores:** un ID único interno por cada cuenta (UUID generado por Supabase Auth, no es público).
- **Token de notificaciones push:** un identificador del dispositivo proporcionado por Apple (APNs) o Google (FCM) a través de Expo. Lo usamos exclusivamente para enviarte notificaciones de la app.
- **Última conexión** ("activo hace X minutos"): timestamp que se actualiza al abrir la app, visible para otros usuarios.
- **Histórico de actividades:** las actividades que registras (nombre, puntos, foto opcional), asociadas a tu cuenta y al grupo correspondiente.

**(c) Datos que NO recogemos:**

- Tu ubicación (ni precisa ni aproximada).
- Datos de tu libreta de contactos.
- Tu historial de navegación o de búsqueda fuera de la app.
- Información financiera, de pago, ni de tarjetas.
- Datos sensibles según el RGPD (origen étnico, religión, orientación sexual, salud médica, biometría).
- Datos para perfiles publicitarios o tracking de terceros.

## 3. Fines del tratamiento

Usamos tus datos exclusivamente para:

- **Hacer funcionar la app:** crear y mantener tu cuenta, mostrarte tus grupos, registrar actividades, contar puntos, mostrar el ranking, entregar mensajes y notificaciones.
- **Comunicación esencial:** enviarte notificaciones push relacionadas con tu actividad (alguien te ha seguido, hay un mensaje en tu grupo, etc.). Puedes desactivarlas en tus ajustes.
- **Seguridad y moderación:** detectar abusos, gestionar reportes de usuarios, prevenir cuentas duplicadas o de menores de 16 años.
- **Cumplir obligaciones legales:** responder a requerimientos legítimos de autoridades cuando proceda.

**No usamos tus datos para publicidad, ni los vendemos ni cedemos a terceros para fines comerciales.**

## 4. Base legal (RGPD)

- **Consentimiento** (art. 6.1.a RGPD): para crear tu cuenta, registrar actividades, enviar mensajes.
- **Ejecución de contrato** (art. 6.1.b RGPD): el uso de la app requiere procesar tus datos para entregarte el servicio.
- **Interés legítimo** (art. 6.1.f RGPD): seguridad, prevención de fraude, mantenimiento del servicio.
- **Cumplimiento legal** (art. 6.1.c RGPD): respuesta a autoridades cuando aplique.

## 5. Con quién compartimos tus datos (proveedores)

Retami se apoya en infraestructura de terceros para funcionar. Estos proveedores **procesan datos en nuestro nombre** y bajo nuestro contrato; no tienen permiso para usarlos para sus propios fines:

- **Supabase** ([supabase.com](https://supabase.com)) — base de datos, autenticación y almacenamiento de archivos. Servidores ubicados en la Unión Europea (Irlanda). Política de privacidad: [supabase.com/privacy](https://supabase.com/privacy)
- **Expo / Expo Push Service** ([expo.dev](https://expo.dev)) — servicio que enruta nuestras notificaciones push hacia los servicios de Apple (APNs) y Google (FCM). Política: [expo.dev/privacy](https://expo.dev/privacy)
- **Apple Push Notification service (APNs)** y **Firebase Cloud Messaging (FCM)** — para entrega física de la notificación al dispositivo. Solo reciben el token del dispositivo y el contenido de la notificación.

No cedemos tus datos a anunciantes, data brokers, ni redes sociales.

## 6. Conservación de datos

- **Datos de cuenta y contenido:** mientras tu cuenta esté activa. Al solicitar el borrado, la eliminación es inmediata y no conservamos ninguna copia de tus datos personales (excepto, en algunos casos, registros de auditoría sobre acciones de moderación de grupos que llevaste a cabo, anonimizados sin que puedan vincularse a ti).
- **Fotos de actividad:** caducan automáticamente a las 36 horas desde su subida, hayan sido vistas o no. Después se borran definitivamente del almacenamiento.
- **Mensajes:** persisten mientras los grupos / conversaciones existan. Si un miembro borra un mensaje, se marca como borrado pero el evento se conserva en el log de auditoría del grupo.
- **Tokens de notificación:** se actualizan en cada login. Si dejas de usar la app, el token caduca por inactividad en APNs/FCM tras semanas.
- **Logs de auditoría:** acciones administrativas en grupos (vetos, expulsiones, cambios de rol) se conservan indefinidamente como evidencia de moderación.

## 7. Tus derechos (RGPD)

Tienes derecho a:

- **Acceso:** saber qué datos tuyos tenemos.
- **Rectificación:** corregir datos incorrectos.
- **Supresión** ("derecho al olvido"): pedirnos que borremos tu cuenta y datos asociados.
- **Limitación del tratamiento.**
- **Portabilidad:** recibir tus datos en formato estructurado.
- **Oposición.**

**Borrado de cuenta desde la app:** puedes solicitar el borrado de tu cuenta desde **Perfil → Editar perfil → Borrar mi cuenta**. La eliminación es **definitiva, inmediata e irreversible**. Se borran todos tus datos sin dejar rastro: cuenta de autenticación, perfil, mensajes de grupo, conversaciones privadas, actividades registradas, fotos y reacciones. Quienes tuvieran conversaciones contigo verán huecos donde estaban tus mensajes. Los grupos que tú hayas creado siguen existiendo (los demás miembros continúan usándolos) pero pasan a no tener creador asignado.

Para otras solicitudes escríbenos a [privacy@retami.app](mailto:privacy@retami.app). Responderemos en un plazo máximo de 30 días.

Si crees que no hemos respetado tus derechos puedes reclamar a la **Agencia Española de Protección de Datos** ([aepd.es](https://www.aepd.es)).

## 8. Menores

Retami **requiere edad mínima de 16 años**. Verificamos la fecha de nacimiento durante el onboarding y la mantenemos inmutable después. Si detectamos que un menor de 16 años se ha registrado, eliminaremos su cuenta.

## 9. Seguridad

- Las contraseñas se almacenan únicamente como hash bcrypt vía Supabase Auth.
- La sesión de auth en el dispositivo se guarda cifrada en el llavero seguro del sistema (`expo-secure-store`: iOS Keychain, Android EncryptedSharedPreferences).
- Comunicación cliente-servidor exclusivamente por HTTPS.
- Las consultas a la base de datos están protegidas por Row Level Security: cada usuario solo puede leer y modificar sus propios datos y los de los grupos donde es miembro.
- Las fotos de actividad son **view-once** y caducan en 36h.

## 10. Cambios en esta política

Si actualizamos esta política, te lo notificaremos por email o a través de la app antes de que los cambios entren en vigor. Mantenemos versiones anteriores accesibles bajo solicitud.

## 11. Contacto

- **Privacidad:** [privacy@retami.app](mailto:privacy@retami.app)
- **Soporte:** [support@retami.app](mailto:support@retami.app)
