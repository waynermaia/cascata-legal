> Esta es una traducción de la versión en portugués, que prevalece en caso de divergencia; pendiente de revisión legal.

# Política de Privacidad de Cascata

**Versión:** 1.2 · **Última actualización:** 14 de noviembre de 2026

---

## 1. Resumen en pocas líneas

- Tu perfil y tu progreso se quedan **en tu dispositivo**. Si entras con Google, también se guardan en tu cuenta para llegar a tus otros dispositivos.
- El **micrófono** se usa solo para reconocer las notas, **en el dispositivo y al instante**. El sonido no se graba ni se envía.
- Enviamos **datos de uso** (por ejemplo, "terminó una lección") a un servicio de estadísticas, vinculados a un código aleatorio de la app, **sin tu nombre, correo ni lo que escribes, y sin deducir tu ubicación**. Puedes desactivarlo en Ajustes.
- El **profesor por IA** y la **voz natural** funcionan **en el propio dispositivo**: la conversación no sale del teléfono.
- No vendemos tus datos ni los usamos para publicidad.
- Puedes pedir acceso, corrección o eliminación de tus datos en cualquier momento.

## 2. Quién cuida tus datos

**Controlador:** Wayner Maia, desarrollador persona física, Brasil.

**Encargado del tratamiento de datos personales:** Wayner Maia, por correo a waynermaia@gmail.com.

## 3. A quién se aplica esta política

A todas las personas que usan la app Cascata en iPhone, iPad o Android, en Brasil o en otro país, y a los responsables de niños y adolescentes que usan la app. Sigue la Ley General de Protección de Datos de Brasil (LGPD, Lei 13.709/2018) y fue pensada para cumplir también, en lo esencial, el GDPR (Europa) y las leyes de privacidad de EE. UU., como la CCPA/CPRA (California) y la COPPA (niños).

## 4. Qué datos tratamos, para qué y por cuánto tiempo

### 4.1 Datos que se quedan solo en tu dispositivo

Estos datos **no se nos envían**. Se guardan en la app y desaparecen cuando la desinstalas (o cuando borras los datos de la app).

| Dato | Para qué | Dónde está |
|---|---|---|
| Respuestas del inicio (nombre o apodo para el saludo, experiencia, objetivo, instrumento, tiempo por día, primera canción) | Personalizar el saludo y armar tu ruta | En el dispositivo |
| Progreso, racha de días, resultados de las prácticas, preferencias | Mostrar tu avance y continuar desde donde quedaste | En el dispositivo |
| Archivos MIDI que importas | Generar lecciones a partir de ellos | En el dispositivo |
| Audio del micrófono | Reconocer las notas tocadas, en tiempo real | Solo en la memoria, durante la práctica. No se graba |
| Notas del teclado MIDI (cable o Bluetooth) | Saber qué tocaste | Solo en la memoria, durante la práctica |
| Conversación con el profesor por IA e informe de la práctica | Generar la respuesta del profesor en el dispositivo | En el dispositivo |
| Modelos del profesor y de la voz, si los descargas | Hacer que el profesor y la voz funcionen sin internet | En el dispositivo, fuera de la copia de seguridad |
| Historial reciente de eventos de uso (hasta 300) | Enviarse junto con el reporte de problema, si quieres | En el dispositivo |

**Copia de seguridad del sistema:** en el iPhone, iCloud puede incluir los datos de la app en las copias de seguridad que activaste en el dispositivo; esas copias las hace Apple, bajo tu cuenta y sus reglas. En Android, los datos de la app quedan fuera de la copia de seguridad de Google.

### 4.2 Datos que tratamos fuera del dispositivo

| Dato | Finalidad | Base legal (LGPD) | Dónde está | Por cuánto tiempo |
|---|---|---|---|---|
| **Eventos de uso**: lo que haces en la app (por ejemplo, abriste la app, empezaste o terminaste una práctica, desbloqueaste una etapa, cambiaste el idioma), con detalles de la práctica (como canción, precisión, tempo) | Entender cómo se usa la app, corregir problemas, mejorar las lecciones | Interés legítimo (art. 7º, IX). Para niños, ver la sección 7 | PostHog, en EE. UU. | 12 meses |
| **Identificador de instalación** (código aleatorio creado por la app, no es el identificador de publicidad) | Contar instalaciones y vincular los eventos del mismo dispositivo | Interés legítimo | PostHog | Mismo plazo que los eventos |
| **Datos técnicos**: versión de la app, sistema y versión, idioma, grupo de pruebas A/B | Corregir errores y comparar versiones de la app | Interés legítimo | PostHog | Mismo plazo que los eventos |
| **Dirección IP** (recibida automáticamente en la conexión) | Entregar los datos. La app le pide a PostHog que **no deduzca la ubicación** a partir de la IP | Interés legítimo | PostHog | No se guarda como ubicación |
| **Cuenta**, si entras con Google: identificador de la cuenta, nombre, correo y foto de tu cuenta de Google | Crear y mantener tu cuenta y sincronizar el progreso | Ejecución de contrato (art. 7º, V) | Firebase Authentication (Google, EE. UU.) | Mientras exista la cuenta, más hasta 30 días después de la eliminación |
| **Progreso sincronizado**, solo si inicias sesión: de cada perfil de la cuenta, nombre del perfil, respuestas del onboarding, pasos del camino (estrellas, intentos, cuándo lo dominaste), canciones tocadas (precisión, estrellas, veces), sesiones recientes, canciones guardadas y bucles, XP, tiempo practicado por día, meta diaria y ajustes (voz, metrónomo, partitura, efectos, recordatorio). No incluye audio, grabaciones, claves ni la conversación con el profesor | Llevar tu progreso a los otros dispositivos en los que inicies sesión con la misma cuenta | Ejecución de contrato (art. 7º, V) | Cloud Firestore (Google), en São Paulo, Brasil | Mientras exista la cuenta. Al eliminar la cuenta desde la app, se borra en el acto |
| **Vínculo entre la cuenta y los eventos de uso**, si entras en tu cuenta | Ver el uso de la misma persona en más de un dispositivo | Interés legítimo | PostHog | Mismo plazo que los eventos |
| **Reporte de problema**: el texto que escribes, la captura de pantalla (si la adjuntas), versión de la app, dispositivo, sistema, idioma, pantalla, identificador de instalación y últimos eventos | Responder y corregir el problema | Interés legítimo y ejecución de contrato | Llega a través de la app de correo o mensajes que elijas, a nuestra bandeja de soporte | 2 años después de la resolución |
| **Tu correo y lo que escribas** al pedir soporte o la eliminación de la cuenta | Atender tu solicitud y comprobar que la atendimos | Ejecución de contrato; cumplimiento de obligación legal (art. 7º, II) | Bandeja de soporte | 5 años (plazo de prescripción del Código de Defensa del Consumidor de Brasil) |
| **Datos de la suscripción**, si la hay: estado de la suscripción, plan, fechas, país de la tienda. **No recibimos datos de la tarjeta** | Desbloquear el contenido de pago | Ejecución de contrato | Apple / Google | Mientras exista la suscripción, más el plazo legal fiscal |
| **Descarga de los modelos del profesor y de la voz**, si los descargas | Traer los archivos al dispositivo | Ejecución de contrato | Hugging Face (EE. UU.), que recibe la dirección IP, como en cualquier descarga | Según la política de Hugging Face |

**Lo que no enviamos al servicio de estadísticas:** el texto que escribes (ni en el reporte de problema, ni en el profesor por IA, ni en tu nombre), tu nombre, correo, teléfono, tu ubicación ni el audio del micrófono. Del reporte de problema registramos solo que se envió, la pantalla, la longitud del texto y si tenía captura de pantalla.

**Recordatorios locales:** los recordatorios de práctica se programan en el propio dispositivo y no pasan por nosotros.

**Funciones futuras:** si lanzamos funciones que envíen datos fuera del dispositivo (por ejemplo, generar lecciones a partir de audio o enlaces), esta política se actualizará antes, indicando qué se envía, a dónde y por cuánto tiempo.

### 4.3 Lo que no hacemos

- No vendemos ni alquilamos datos personales.
- No usamos datos para publicidad ni los compartimos con redes de anuncios.
- No usamos el identificador de publicidad del dispositivo ni te rastreamos en apps y sitios de otras empresas.
- No tomamos decisiones automatizadas que produzcan efectos jurídicos sobre ti.
- No usamos tus conversaciones ni el contenido que envías para entrenar modelos de IA.

## 5. Con quién compartimos

Usamos empresas que tratan datos **en nuestro nombre y siguiendo nuestras instrucciones** (encargados del tratamiento):

| Empresa | Qué hace | Dónde |
|---|---|---|
| PostHog Inc. | Estadísticas de uso | EE. UU. |
| Google (Firebase Authentication), solo para quien entra en su cuenta | Inicio de sesión con Google | EE. UU. |
| Google (Cloud Firestore), solo para quien inició sesión | Guardar el progreso sincronizado entre dispositivos | Brasil (São Paulo) |
| Apple y Google | Distribución de la app, pagos, notificaciones, inicio de sesión con Google | EE. UU. y otros países |
| Hugging Face | Aloja los archivos del profesor y de la voz que descargas | EE. UU. |

También podemos compartir datos cuando la ley o una orden de autoridad lo exija, para defender nuestros derechos en un proceso, o en caso de venta o reorganización de la app (con la misma protección de esta política).

## 6. Transferencia internacional

Algunos de los encargados mencionados están fuera de Brasil, principalmente en EE. UU. Cuando eso ocurre, hacemos la transferencia con base en las cláusulas contractuales estándar aprobadas por la ANPD (Resolución CD/ANPD nº 19/2024) o en otro mecanismo previsto en el art. 33 de la LGPD y, para datos de personas en Europa, en las cláusulas contractuales tipo de la Comisión Europea o en el EU-US Data Privacy Framework, cuando el encargado participe en él.

## 7. Niños y adolescentes

Cascata puede ser usada por niños y adolescentes, **siempre con autorización y acompañamiento de un responsable**.

- Tratamos los datos de niños y adolescentes **siempre en su mejor interés** (art. 14 de la LGPD) y recopilamos solo lo necesario para que la app funcione.
- Para **niños (menores de 12 años)**, el uso debe estar autorizado por al menos uno de los padres o el responsable. En EE. UU., la regla se aplica a menores de 13 años (COPPA). En Europa, hasta la edad definida por cada país (de 13 a 16 años).
- El responsable puede desactivar las estadísticas de uso en **Ajustes > Privacidad**. El profesor y la voz en el dispositivo no envían la conversación fuera del teléfono.
- No hacemos publicidad ni perfilamiento comercial de niños y adolescentes.
- El responsable puede, en cualquier momento, ver, corregir o pedir la eliminación de los datos del niño y retirar el consentimiento, por correo a waynermaia@gmail.com.
- Si nos damos cuenta de que tratamos datos de un niño sin la autorización necesaria, los borraremos.

## 8. Tus derechos

Tú (o el responsable, en el caso de menores) puedes, en cualquier momento y sin costo:

- confirmar si tratamos tus datos y acceder a ellos;
- corregir datos incompletos o incorrectos;
- pedir la anonimización, el bloqueo o la eliminación de datos innecesarios o tratados en desacuerdo con la ley;
- pedir la portabilidad de los datos;
- pedir la eliminación de los datos tratados con base en el consentimiento;
- saber con quién compartimos tus datos;
- ser informado sobre la posibilidad de no dar el consentimiento y sus consecuencias;
- retirar el consentimiento;
- oponerte a un tratamiento basado en el interés legítimo;
- pedir la revisión de decisiones automatizadas;
- presentar un reclamo ante la **Autoridad Nacional de Protección de Datos (ANPD)** de Brasil, en gov.br/anpd, o ante la autoridad de protección de datos de tu país.

Si vives en Europa, también tienes los derechos del GDPR (incluida la limitación del tratamiento). Si vives en California, tienes derecho a saber, borrar, corregir y a no ser discriminado por ejercer tus derechos. **No vendemos ni "compartimos" datos personales para publicidad conductual** en el sentido de la CCPA/CPRA.

### Cómo ejercerlos

- **Desactivar las estadísticas:** Ajustes > Privacidad > Enviar datos de uso.
- **Borrar el profesor y la voz descargados:** Ajustes > Profesor en el dispositivo > Borrar.
- **Borrar los datos del dispositivo:** desinstala la app o borra sus datos en los ajustes del sistema.
- **Eliminar la cuenta y los datos fuera del dispositivo:** Ajustes > Eliminar cuenta. Con sesión iniciada, la cuenta y el progreso sincronizado se borran en el acto, y la app abre también un correo listo para enviarnos.
- **Cualquier otra solicitud:** escribe a waynermaia@gmail.com.

Podemos pedirte información para confirmar que la solicitud es tuya. Respondemos en un plazo de hasta **15 días**, o en el plazo menor que exija la ley de tu país.

**Importante sobre la eliminación:** como hoy los eventos de uso están vinculados a un código de instalación y no a un nombre, para borrarlos necesitamos ese código. La app lo incluye automáticamente en el correo de eliminación y en el reporte de problema.

## 9. Seguridad

- Las comunicaciones entre la app y los servicios usan una conexión cifrada (HTTPS/TLS).
- Los archivos del profesor y de la voz se verifican con una firma digital (SHA-256) después de la descarga.
- Damos acceso a los datos solo a quien lo necesita y exigimos lo mismo a los encargados.
- Ningún sistema es totalmente seguro. Si ocurre un incidente que pueda implicar un riesgo o daño relevante para ti, te avisaremos a ti y a la ANPD, conforme a la ley.

## 10. Por cuánto tiempo guardamos

Por los plazos de la tabla de la sección 4.2. Después, borramos o anonimizamos los datos, salvo cuando la ley exija guardarlos por más tiempo (por ejemplo, obligaciones fiscales o de defensa en un proceso).

## 11. Cookies

La app no usa cookies.

## 12. Cambios en esta política

Podemos actualizar esta política. Si el cambio es relevante, te avisaremos en la app antes de que entre en vigor y, cuando la ley lo exija, volveremos a pedir tu consentimiento.

## 13. Contacto

- **Controlador y encargado:** Wayner Maia, waynermaia@gmail.com
