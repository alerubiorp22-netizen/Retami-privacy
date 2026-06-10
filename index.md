<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Política de Privacidad — Retami</title>
  <meta name="description" content="Política de privacidad de Retami: qué datos recogemos, para qué los usamos, y cómo borrar tu cuenta.">
  <meta name="theme-color" content="#0a0a0a">
  <link rel="icon" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='22' fill='%230a0a0a'/%3E%3Ctext x='50' y='72' font-family='system-ui,sans-serif' font-size='62' font-weight='900' text-anchor='middle' fill='%23e8ff00'%3ER%3C/text%3E%3C/svg%3E">
  <style>
    :root {
      --bg: #0a0a0a;
      --bg-card: #111;
      --border: #252525;
      --text-primary: #f0f0f0;
      --text-secondary: #b5b5b5;
      --text-muted: #777;
      --accent: #e8ff00;
      --accent-low: rgba(232, 255, 0, 0.1);
      --accent-mid: rgba(232, 255, 0, 0.2);
      --max-w: 760px;
    }
    * { box-sizing: border-box; margin: 0; padding: 0; }
    html { scroll-behavior: smooth; }
    body {
      background: var(--bg);
      color: var(--text-primary);
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", system-ui, sans-serif;
      line-height: 1.65;
      -webkit-font-smoothing: antialiased;
      overflow-x: hidden;
    }
    a { color: var(--accent); text-decoration: none; transition: opacity 0.15s; }
    a:hover { opacity: 0.7; }

    body::before {
      content: "";
      position: fixed; inset: 0;
      background:
        radial-gradient(circle at 50% 0%, rgba(232,255,0,0.05), transparent 50%),
        linear-gradient(rgba(232,255,0,0.015) 1px, transparent 1px),
        linear-gradient(90deg, rgba(232,255,0,0.015) 1px, transparent 1px);
      background-size: 100% 100%, 60px 60px, 60px 60px;
      pointer-events: none;
      z-index: 0;
    }

    /* NAV */
    header.nav {
      position: sticky; top: 0; z-index: 50;
      backdrop-filter: blur(20px); -webkit-backdrop-filter: blur(20px);
      background: rgba(10,10,10,0.7);
      border-bottom: 1px solid var(--border);
    }
    .nav-inner {
      max-width: var(--max-w);
      margin: 0 auto;
      padding: 14px 24px;
      display: flex; align-items: center; justify-content: space-between;
    }
    .logo {
      display: flex; align-items: center; gap: 10px;
      font-size: 18px; font-weight: 900; letter-spacing: -0.5px;
      color: var(--text-primary);
    }
    .logo:hover { opacity: 1; }
    .logo-mark {
      width: 32px; height: 32px; border-radius: 8px;
      background: var(--accent); color: var(--bg);
      display: flex; align-items: center; justify-content: center;
      font-size: 18px; font-weight: 900; line-height: 1;
    }
    .nav-back {
      padding: 8px 14px; font-size: 14px; color: var(--text-secondary);
      border-radius: 8px;
    }
    .nav-back:hover { color: var(--text-primary); opacity: 1; background: var(--bg-card); }

    /* ARTICLE */
    article {
      position: relative; z-index: 1;
      max-width: var(--max-w);
      margin: 0 auto;
      padding: 70px 24px 80px;
    }
    .eyebrow {
      display: inline-flex; align-items: center; gap: 8px;
      font-size: 11px; font-weight: 700; color: var(--accent);
      letter-spacing: 2px; padding: 6px 12px;
      background: var(--accent-low); border: 1px solid var(--accent-mid);
      border-radius: 99px; margin-bottom: 22px;
    }
    .eyebrow::before {
      content: ""; width: 6px; height: 6px; border-radius: 50%;
      background: var(--accent); box-shadow: 0 0 8px var(--accent);
    }
    h1 {
      font-size: clamp(32px, 5vw, 46px);
      font-weight: 900; line-height: 1.08; letter-spacing: -1.2px;
      margin-bottom: 14px;
    }
    .meta {
      color: var(--text-muted); font-size: 13px;
      letter-spacing: 0.5px; margin-bottom: 40px;
      text-transform: uppercase; font-weight: 700;
    }
    .intro {
      font-size: 17px; color: var(--text-secondary);
      margin-bottom: 50px; padding-bottom: 40px;
      border-bottom: 1px solid var(--border);
    }
    .intro strong { color: var(--text-primary); }

    h2 {
      font-size: clamp(22px, 3vw, 26px);
      font-weight: 800; letter-spacing: -0.4px;
      margin-top: 48px; margin-bottom: 14px;
      color: var(--text-primary);
      display: flex; align-items: baseline; gap: 10px;
    }
    h2::before {
      content: "§";
      color: var(--accent);
      font-size: 0.75em;
      font-weight: 900;
    }
    h3 {
      font-size: 16px; font-weight: 700;
      margin-top: 24px; margin-bottom: 8px;
      color: var(--text-primary);
    }
    p, ul, ol {
      margin-bottom: 16px;
      color: var(--text-secondary);
      font-size: 15.5px;
    }
    ul, ol { padding-left: 22px; }
    li { margin-bottom: 8px; }
    li::marker { color: var(--accent); }
    strong { color: var(--text-primary); font-weight: 700; }

    /* CALLOUT */
    .callout {
      background: var(--bg-card);
      border: 1px solid var(--border);
      border-left: 3px solid var(--accent);
      padding: 18px 22px;
      border-radius: 10px;
      margin: 28px 0;
    }
    .callout p { margin-bottom: 0; color: var(--text-primary); }

    /* FOOTER */
    footer {
      position: relative; z-index: 1;
      max-width: var(--max-w);
      margin: 0 auto;
      padding: 30px 24px 60px;
      border-top: 1px solid var(--border);
      color: var(--text-muted);
      font-size: 13px;
      display: flex; justify-content: space-between;
      flex-wrap: wrap; gap: 16px;
    }
    footer a { color: var(--text-secondary); }
    footer a:hover { color: var(--accent); }

    @media (max-width: 600px) {
      .nav-inner { padding: 12px 18px; }
      article { padding: 40px 20px 60px; }
      h2 { margin-top: 36px; }
      footer { padding: 24px 20px 50px; flex-direction: column; gap: 10px; }
    }
  </style>
</head>
<body>

  <header class="nav">
    <div class="nav-inner">
      <a class="logo" href="https://retami.app">
        <span class="logo-mark">R</span>
        <span>Retami</span>
      </a>
      <a class="nav-back" href="https://retami.app">← Volver</a>
    </div>
  </header>

  <article>
    <span class="eyebrow">POLÍTICA DE PRIVACIDAD</span>
    <h1>Tus datos, en claro.</h1>
    <p class="meta">Última actualización · 9 de junio de 2026</p>

    <p class="intro">
      Retami es una app de retos en grupo desarrollada por <strong>Alejandro Rubio</strong>.
      Aquí te explicamos qué datos recogemos y para qué, sin letra pequeña ni tecnicismos.
      Para dudas: <a href="mailto:privacy@retami.app">privacy@retami.app</a>.
    </p>

    <h2>Qué datos recogemos</h2>
    <p>Solo lo necesario para que la app funcione:</p>
    <ul>
      <li><strong>Cuenta:</strong> email y contraseña (cifrada — nadie en Retami puede verla).</li>
      <li><strong>Perfil:</strong> nombre de usuario, nombre a mostrar, foto opcional, bio opcional, fecha de nacimiento, zona horaria.</li>
      <li><strong>Contenido que tú creas:</strong> mensajes, actividades, fotos, reglas de los grupos.</li>
      <li><strong>Token de notificaciones</strong> del dispositivo, solo para enviarte avisos de la app.</li>
      <li><strong>Última conexión</strong>, para mostrar "activo hace X minutos" a tu grupo.</li>
    </ul>

    <h2>Lo que NO recogemos</h2>
    <ul>
      <li>Tu ubicación.</li>
      <li>Tu agenda de contactos.</li>
      <li>Información financiera o de pago.</li>
      <li>Datos sensibles (salud, religión, política, orientación sexual, biometría).</li>
      <li>Nada para perfiles publicitarios ni para tracking de terceros.</li>
    </ul>
    <div class="callout">
      <p><strong>No vendemos tus datos. No los cedemos a anunciantes.</strong> Punto.</p>
    </div>

    <h2>Para qué los usamos</h2>
    <ul>
      <li>Hacer funcionar la app: tu cuenta, tus grupos, el ranking, los mensajes, las notificaciones.</li>
      <li>Seguridad y moderación: detectar abusos, gestionar reportes.</li>
      <li>Cumplir obligaciones legales cuando proceda.</li>
    </ul>

    <h2>Con quién los compartimos</h2>
    <p>
      Usamos proveedores técnicos para que la app funcione (autenticación, almacenamiento, envío de notificaciones push).
      Procesan tus datos <strong>en nuestro nombre</strong> bajo contrato, no para sus propios fines, y no
      pueden usarlos para publicidad.
    </p>

    <h2>Cuánto los guardamos</h2>
    <ul>
      <li><strong>Mientras tu cuenta esté activa:</strong> conservamos tu perfil y contenido.</li>
      <li><strong>Si borras tu cuenta:</strong> eliminación inmediata e irreversible. Sin copias.</li>
      <li><strong>Fotos de actividad:</strong> caducan automáticamente a las 36 horas.</li>
      <li><strong>Token de notificaciones:</strong> caduca por sí solo al dejar de usar la app.</li>
    </ul>

    <h2>Tus derechos</h2>
    <p>
      Tienes derecho a acceder, rectificar, borrar, limitar y oponerte al tratamiento de tus
      datos, y a recibirlos en formato portable.
    </p>

    <h3>Borrar tu cuenta desde la app</h3>
    <p>
      <strong>Perfil → Editar perfil → Borrar mi cuenta.</strong>
      Es inmediato e irreversible: se borra todo (cuenta, perfil, mensajes, conversaciones,
      actividades y fotos). Los grupos que tú hayas creado siguen existiendo para los demás miembros,
      pero pasan a no tener creador asignado.
    </p>

    <h3>Para el resto de solicitudes</h3>
    <p>
      Escríbenos a <a href="mailto:privacy@retami.app">privacy@retami.app</a> y te respondemos en
      un máximo de 30 días. Si crees que no respetamos tus derechos puedes reclamar a la
      <a href="https://www.aepd.es" target="_blank" rel="noopener">Agencia Española de Protección de Datos</a>.
    </p>

    <h2>Menores</h2>
    <p>
      Retami requiere <strong>edad mínima de 16 años</strong>. Verificamos la fecha de
      nacimiento al registrarse. Si detectamos un menor de 16 años, eliminamos la cuenta.
    </p>

    <h2>Seguridad</h2>
    <ul>
      <li>Las contraseñas se guardan cifradas. Nadie las ve, ni siquiera nosotros.</li>
      <li>Toda la comunicación entre app y servidor va por HTTPS.</li>
      <li>El acceso a la base de datos está restringido: cada cuenta solo lee lo suyo y lo de sus grupos.</li>
      <li>Las fotos de actividad son de visualización única y caducan en 36h.</li>
    </ul>

    <h2>Cambios en esta política</h2>
    <p>
      Si la actualizamos, te avisaremos por email o desde la app antes de que el cambio entre en vigor.
    </p>

  </article>

  <footer>
    <div>© 2026 Retami · Alejandro Rubio</div>
    <div>
      <a href="mailto:privacy@retami.app">privacy@retami.app</a> ·
      <a href="mailto:support@retami.app">support@retami.app</a>
    </div>
  </footer>

</body>
</html>
