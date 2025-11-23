<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>Sitio Fútbol — Noticias, Equipos y Resultados</title>
  <style>
    :root{--accent:#e33;--bg:#0f1724;--card:#0b1220;--muted:#9aa4b2}
    body{font-family:Inter, system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; margin:0; background:linear-gradient(180deg,#071127 0%, #041022 100%); color:#eef2f7}
    a{color:var(--accent); text-decoration:none}
    header{padding:28px 20px; display:flex; align-items:center; justify-content:space-between; gap:16px}
    .brand{display:flex; align-items:center; gap:12px}
    .logo{width:52px; height:52px; border-radius:8px; background:linear-gradient(135deg,#ff6b6b,#ffb86b); display:flex; align-items:center; justify-content:center; font-weight:700}
    nav a{margin:0 10px; color:#cfe7ff}
    .hero{padding:36px 20px; display:grid; grid-template-columns:1fr 360px; gap:24px}
    .card{background:rgba(255,255,255,0.03); border-radius:12px; padding:18px}
    h1{margin:0 0 8px 0; font-size:28px}
    p.lead{margin:0; color:var(--muted)}
    .latest{display:grid; gap:14px}
    .article{display:flex; gap:12px; align-items:flex-start}
    .thumb{width:110px; height:70px; background:#123; border-radius:6px; flex-shrink:0}
    .meta{font-size:13px; color:var(--muted)}
    .grid-3{display:grid; grid-template-columns:repeat(3,1fr); gap:14px}
    table{width:100%; border-collapse:collapse}
    th,td{padding:8px; text-align:left; border-bottom:1px solid rgba(255,255,255,0.04)}
    footer{padding:18px 20px; color:var(--muted); font-size:13px}
    .cta{display:inline-block; padding:8px 12px; background:var(--accent); color:white; border-radius:8px}
    @media (max-width:900px){.hero{grid-template-columns:1fr} .grid-3{grid-template-columns:1fr} nav{display:none}}
  </style>
</head>
<body>
  <header>
    <div class="brand">
      <div class="logo">F</div>
      <div>
        <div style="font-weight:700">Sitio Fútbol</div>
        <div style="font-size:13px;color:var(--muted)">Noticias, estadísticas y calendario</div>
      </div>
    </div>
    <nav>
      <a href="#ultimas">Últimas</a>
      <a href="#equipos">Equipos</a>
      <a href="#resultados">Resultados</a>
      <a href="#contacto">Contacto</a>
    </nav>
  </header>

  <main>
    <section class="hero">
      <div class="card">
        <h1>Todo sobre fútbol — noticias, análisis y calendario</h1>
        <p class="lead">Cobertura diaria de partidos, fichajes, estadísticas y artículos pensados para aficionados y emprendedores deportivos.</p>

        <section id="ultimas" style="margin-top:18px">
          <h3 style="margin:0 0 10px 0">Últimas noticias</h3>
          <div class="latest">
            <article class="article">
              <div class="thumb"></div>
              <div>
                <div style="font-weight:600">Victoria agónica en la jornada 12</div>
                <div class="meta">23 Nov 2025 · Resumen del partido, alineaciones y análisis táctico</div>
              </div>
            </article>

            <article class="article">
              <div class="thumb"></div>
              <div>
                <div style="font-weight:600">Fichajes: mercado de invierno en foco</div>
                <div class="meta">21 Nov 2025 · Rumores verificados y el impacto en la tabla</div>
              </div>
            </article>

            <article class="article">
              <div class="thumb"></div>
              <div>
                <div style="font-weight:600">Jóvenes promesas a seguir</div>
                <div class="meta">19 Nov 2025 · Perfiles y estadísticas clave</div>
              </div>
            </article>
          </div>
        </section>

        <section id="equipos" style="margin-top:18px">
          <h3 style="margin:0 0 10px 0">Equipos destacados</h3>
          <div class="grid-3">
            <div class="card" style="padding:12px">
              <strong>Club A</strong>
              <div class="meta">Entrenador: Juan Pérez • Estadio: El Gran Campo</div>
              <p class="meta" style="margin-top:8px">Breve descripción: estilo de juego ofensivo, promesa en juveniles.</p>
            </div>
            <div class="card" style="padding:12px">
              <strong>Club B</strong>
              <div class="meta">Entrenador: Ana Gómez • Estadio: Ciudad Arena</div>
              <p class="meta" style="margin-top:8px">Breve descripción: defensa sólida y buenos contraataques.</p>
            </div>
            <div class="card" style="padding:12px">
              <strong>Club C</strong>
              <div class="meta">Entrenador: Marco Ruiz • Estadio: Olímpico</div>
              <p class="meta" style="margin-top:8px">Breve descripción: cantera fuerte y tácticas modernas.</p>
            </div>
          </div>
        </section>

      </div>

      <aside style="display:flex;flex-direction:column;gap:14px">
        <div class="card">
          <h4 style="margin:0 0 8px 0">Próximos partidos</h4>
          <table>
            <tr><th>Fecha</th><th>Partido</th></tr>
            <tr><td>25 Nov 2025</td><td>Club A vs Club B — 18:00</td></tr>
            <tr><td>26 Nov 2025</td><td>Club C vs Club D — 20:00</td></tr>
          </table>
          <div style="margin-top:10px"><a class="cta" href="#resultados">Ver calendario completo</a></div>
        </div>

        <div class="card">
          <h4 style="margin:0 0 8px 0">Tabla de posiciones (ejemplo)</h4>
          <table>
            <tr><th>Pos</th><th>Equipo</th><th>Pts</th></tr>
            <tr><td>1</td><td>Club A</td><td>34</td></tr>
            <tr><td>2</td><td>Club B</td><td>30</td></tr>
            <tr><td>3</td><td>Club C</td><td>27</td></tr>
          </table>
        </div>

        <div class="card">
          <h4 style="margin:0 0 8px 0">Redes</h4>
          <p class="meta">Síguenos en redes para actualizaciones en vivo.</p>
          <p style="margin:8px 0"><a href="#">Twitter</a> · <a href="#">Instagram</a> · <a href="#">YouTube</a></p>
        </div>

      </aside>
    </section>

    <section id="resultados" style="padding:18px 20px">
      <div class="card">
        <h3>Resultados recientes</h3>
        <table>
          <tr><th>Fecha</th><th>Partido</th><th>Resultado</th></tr>
          <tr><td>23 Nov 2025</td><td>Club A vs Club D</td><td>2 - 1</td></tr>
          <tr><td>22 Nov 2025</td><td>Club B vs Club C</td><td>1 - 1</td></tr>
        </table>
      </div>
    </section>

    <section id="contacto" style="padding:18px 20px">
      <div class="card">
        <h3>Contacto</h3>
        <p class="meta">¿Tienes una noticia, sugerencia o quieres colaborar? Escríbenos:</p>
        <p style="margin:8px 0">email: <a href="mailto:info@sitiofutbol.example">info@sitiofutbol.example</a></p>
      </div>
    </section>
  </main>

  <footer>
    © 2025 Sitio Fútbol — Creado para Google Sites. Usa este HTML como plantilla o copia los textos en los bloques de Google Sites. 
  </footer>
</body>
</html>
