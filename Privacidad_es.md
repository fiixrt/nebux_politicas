# Política de Privacidad de Nebux

*Última actualización: Octubre 2026*

Nebux es un bot multifuncional para Discord diseñado para proporcionar diversas funciones y utilidades dentro de los servidores de Discord. Nos tomamos muy en serio la privacidad de nuestros usuarios y queremos asegurarnos de que comprendas cómo tratamos tus datos.

---

## 1. Datos que Recopilamos

Nebux aplica el principio de **minimización de datos**: solo recopilamos lo estrictamente necesario para el funcionamiento del bot. Los datos que almacenamos son:

- **IDs de servidor (Guild ID):** Para guardar la configuración de cada servidor (bienvenidas, autorole, niveles, verificación, etc.).
- **IDs de usuario (User ID):** Para el sistema de niveles/XP, warns y otras funciones de seguimiento dentro del servidor.
- **IDs de canal (Channel ID):** Para dirigir mensajes automáticos al canal correcto (bienvenidas, logs, etc.).
- **IDs de rol (Role ID):** Para la configuración de autoroles, verificación y sistemas de roles automáticos.

**No recopilamos ni almacenamos:**
- Contenido de mensajes de usuario.
- Información personal identificable (nombre real, email, dirección, etc.).
- Datos de pago o financieros.
- Datos de presencia o actividad de voz.

> **Nota sobre el comando Snipe:** El comando `/mod snipe` guarda temporalmente el último mensaje eliminado **únicamente en la memoria del bot** (RAM). Este dato nunca se escribe en ninguna base de datos y se pierde permanentemente al reiniciar el bot. Se procesa de forma efímera y exclusivamente para mostrarlo al solicitarlo.

---

## 2. Cómo Usamos los Datos

Los datos recopilados se utilizan **exclusivamente** para:

- Gestionar la configuración de las funciones del bot en cada servidor (bienvenidas, despedidas, autorole, verificación, niveles, tickets, sorteos, etc.).
- Mantener el progreso de XP y nivel de los usuarios en los servidores donde el sistema de niveles esté activo.
- Registrar advertencias (warns) de moderación por servidor.
- Mejorar el funcionamiento y la estabilidad del bot.

Los datos **no se usan** para publicidad, venta a terceros, entrenamiento de modelos de inteligencia artificial, ni ningún otro propósito fuera del funcionamiento directo del bot.

---

## 3. Compartición de Datos

**Nebux no comparte, vende ni transfiere tus datos a terceros** bajo ninguna circunstancia. Los datos están almacenados exclusivamente en nuestra infraestructura privada y no son accesibles por entidades externas.

---

## 4. Retención de Datos

Los datos se almacenan mientras el bot esté activo en el servidor o mientras el usuario tenga actividad registrada:

- **Datos de configuración del servidor:** Se conservan mientras Nebux permanezca en el servidor. Al expulsar al bot, los datos quedan inactivos y pueden ser eliminados bajo solicitud.
- **Datos de niveles/XP de usuarios:** Se conservan de forma indefinida para mantener el progreso del usuario, o hasta que el usuario o administrador solicite su eliminación.
- **Warns de moderación:** Se conservan de forma indefinida o hasta que el administrador del servidor los elimine manualmente.

---

## 5. Seguridad de los Datos

Nos comprometemos a proteger los datos recopilados mediante las siguientes medidas:

- Los datos se almacenan en una base de datos **MongoDB** protegida con autenticación y acceso restringido.
- El acceso a la base de datos está limitado únicamente al equipo de desarrollo de Nebux.
- No se almacenan contraseñas ni datos sensibles de ningún tipo.
- Se realizan revisiones periódicas de seguridad para prevenir accesos no autorizados.

---

## 6. Derechos de los Usuarios

Tienes los siguientes derechos sobre tus datos:

- **Derecho de acceso:** Puedes solicitar información sobre qué datos tiene Nebux vinculados a tu ID de usuario.
- **Derecho de eliminación:** Puedes solicitar la eliminación de todos tus datos en cualquier momento.
- **Derecho de oposición:** Si no deseas que tus datos sean almacenados, puedes solicitar la exclusión de los sistemas que lo requieran.

### ¿Cómo solicitar la eliminación de tus datos?

Contacta con el equipo de Nebux a través de nuestro **servidor oficial de soporte en Discord**: [Únete aquí](https://discord.gg/c8zCBhrNm) y abre un ticket indicando tu solicitud. Procesaremos tu petición en un plazo máximo de **30 días**.

---

## 7. Intents Privilegiados de Discord

Para ofrecer sus funciones, Nebux utiliza los siguientes **Privileged Gateway Intents** de Discord:

- **Server Members Intent:** Necesario para detectar la entrada y salida de miembros (bienvenidas, despedidas, autorole, asignación masiva de roles, verificación y sistema de niveles). No se almacena información de los miembros más allá de su User ID para las funciones que así lo requieran.
- **Message Content Intent:** Necesario para detectar comandos de prefijo y ejecutar comandos personalizados configurados por los administradores. El contenido de los mensajes se procesa en tiempo real y **nunca se almacena**.

---

## 8. Cambios en la Política de Privacidad

Cualquier cambio en esta política se comunicará a través de nuestro servidor de Discord ([Únete aquí](https://discord.gg/c8zCBhrNm)). El uso continuado del bot tras la publicación de cambios implica la aceptación de la nueva política.

---

## 9. Contacto

Si tienes alguna pregunta o inquietud sobre esta política de privacidad, puedes contactarnos a través de nuestro **servidor de soporte oficial en Discord**: [https://discord.gg/c8zCBhrNm](https://discord.gg/c8zCBhrNm)
