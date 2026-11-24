<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Catajoma | Productos de Belleza y Cuidado Personal en Cotoca, Santa Cruz</title>
  <meta name="description" content="Descubre la selección exclusiva de productos de belleza, cuidado facial y cosmética de Catajoma en Cotoca, Santa Cruz, Bolivia. Asesoría personalizada y pedidos directos por WhatsApp.">

  <!-- SEO JSON-LD ESTRUCTURADO -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "LocalBusiness",
    "name": "Catajoma",
    "description": "Productos de belleza, cuidado de la piel y cosmética con atención personalizada en Cotoca, Santa Cruz, Bolivia.",
    "telephone": "+59176694062",
    "address": {
      "@type": "PostalAddress",
      "addressLocality": "Cotoca",
      "addressRegion": "Santa Cruz",
      "addressCountry": "BO"
    },
    "areaServed": "Cotoca, Santa Cruz, Bolivia"
  }
  </script>

  <style>
    /* 1. RESET Y VARIABLES GLOBALES (TOKENS CSS) */
    *, *::before, *::after {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    :root {
      /* Tríada cromática Sector Moda, Belleza, Lujo (Contraste WCAG AA >= 4.5:1) */
      --primary: #18181b;
      --accent: #d97706;
      --accent-dark: #b45309;
      --bg: #fafaf9;
      --surface: #ffffff;
      --surface-alt: #f4f4f5;
      --text: #18181b;
      --text-muted: #52525b;
      --border: #e4e4e7;

      /* Tipografía y Espaciado Fluido (clamp) */
      --font-h1: clamp(1.9rem, 1.8vw + 1.4rem, 3.25rem);
      --font-h2: clamp(1.45rem, 1.2vw + 1.1rem, 2.25rem);
      --font-h3: clamp(1.15rem, 0.5vw + 1rem, 1.35rem);
      --font-body: clamp(1rem, 0.25vw + 0.95rem, 1.125rem);
      --space-section: clamp(3rem, 5vw + 1.5rem, 5.5rem);
      --gutter: clamp(1rem, 2vw + 0.5rem, 2rem);

      /* Elevaciones y Transiciones */
      --shadow-sm: 0 1px 3px rgba(24, 24, 27, 0.08);
      --shadow-md: 0 6px 16px -4px rgba(24, 24, 27, 0.1);
      --shadow-lg: 0 14px 28px -6px rgba(24, 24, 27, 0.14);
      --transition: 200ms cubic-bezier(0.4, 0, 0.2, 1);
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      font-size: var(--font-body);
      line-height: 1.6;
      color: var(--text);
      background-color: var(--bg);
      text-rendering: optimizeLegibility;
      -webkit-font-smoothing: antialiased;
    }

    /* 2. TIPOGRAFÍA Y JERARQUÍA */
    h1, h2, h3 {
      line-height: 1.2;
      font-weight: 700;
      color: var(--text);
      letter-spacing: -0.02em;
    }

    h1 { font-size: var(--font-h1); }
    h2 { font-size: var(--font-h2); }
    h3 { font-size: var(--font-h3); }

    /* 3. LAYOUTS FLUIDOS E INTRÍNSECOS */
    .container {
      width: min(100% - (var(--gutter) * 2), 1160px);
      margin-inline: auto;
    }

    section {
      padding-block: var(--space-section);
    }

    .section-header {
      text-align: center;
      max-width: 680px;
      margin-inline: auto;
      margin-block-end: clamp(2rem, 3vw, 3rem);
    }

    .section-eyebrow {
      display: inline-block;
      font-size: 0.85rem;
      font-weight: 700;
      text-transform: uppercase;
      letter-spacing: 0.08em;
      color: var(--accent-dark);
      margin-block-end: 0.5rem;
    }

    .section-subtitle {
      color: var(--text-muted);
      margin-block-start: 0.75rem;
    }

    .grid-auto {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(min(100%, 270px), 1fr));
      gap: var(--gutter);
    }

    /* 4. BOTONES Y CONTROLES TÁCTILES ACCESIBLES (>= 44x44px) */
    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 0.625rem;
      min-height: 48px;
      min-width: 48px;
      padding: 0.85rem 1.75rem;
      border-radius: 0.5rem;
      font-size: 1rem;
      font-weight: 600;
      text-decoration: none;
      cursor: pointer;
      border: 2px solid transparent;
      transition: transform var(--transition), background-color var(--transition), box-shadow var(--transition);
    }

    .btn:focus-visible,
    button:focus-visible,
    select:focus-visible,
    input:focus-visible,
    a:focus-visible {
      outline: 3px solid var(--accent);
      outline-offset: 3px;
    }

    .btn-primary {
      background-color: var(--primary);
      color: #ffffff;
      box-shadow: var(--shadow-md);
    }

    .btn-primary:hover {
      background-color: #27272a;
      transform: translateY(-2px);
      box-shadow: var(--shadow-lg);
    }

    .btn-accent {
      background-color: var(--accent-dark);
      color: #ffffff;
      box-shadow: var(--shadow-md);
    }

    .btn-accent:hover {
      background-color: #92400e;
      transform: translateY(-2px);
    }

    .btn-outline {
      background-color: transparent;
      color: var(--text);
      border-color: var(--border);
    }

    .btn-outline:hover {
      border-color: var(--primary);
      background-color: var(--surface);
    }

    /* 5. NAVEGACIÓN SUPERIOR */
    .site-header {
      position: sticky;
      top: 0;
      z-index: 100;
      background-color: rgba(250, 250, 249, 0.92);
      backdrop-filter: blur(10px);
      border-bottom: 1px solid var(--border);
      padding-block: 0.85rem;
    }

    .nav-bar {
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 1rem;
    }

    .brand-logo {
      display: inline-flex;
      align-items: center;
      gap: 0.6rem;
      text-decoration: none;
      color: var(--primary);
      font-weight: 800;
      font-size: 1.35rem;
      letter-spacing: -0.03em;
    }

    .brand-badge {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      width: 36px;
      height: 36px;
      border-radius: 0.5rem;
      background-color: var(--primary);
      color: var(--accent);
    }

    /* 6. HERO SECTION (REGLA DE LOS 3 SEGUNDOS) */
    .hero {
      padding-block: clamp(2.5rem, 5vw, 4.5rem);
    }

    .hero-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(min(100%, 440px), 1fr));
      align-items: center;
      gap: clamp(2rem, 4vw, 3.5rem);
    }

    .hero-tag {
      display: inline-flex;
      align-items: center;
      gap: 0.5rem;
      background-color: var(--surface);
      border: 1px solid var(--border);
      padding: 0.4rem 0.9rem;
      border-radius: 999px;
      font-size: 0.875rem;
      font-weight: 600;
      color: var(--text);
      margin-block-end: 1.25rem;
      box-shadow: var(--shadow-sm);
    }

    .hero-tag-dot {
      width: 8px;
      height: 8px;
      border-radius: 50%;
      background-color: var(--accent-dark);
    }

    .hero-title span {
      color: var(--accent-dark);
    }

    .hero-subtitle {
      color: var(--text-muted);
      margin-block: 1.25rem 1.75rem;
      max-width: 56ch;
    }

    .hero-actions {
      display: flex;
      flex-wrap: wrap;
      gap: 0.875rem;
      margin-block-end: 1.5rem;
    }

    .hero-proof {
      display: flex;
      align-items: center;
      gap: 0.75rem;
      font-size: 0.9rem;
      color: var(--text-muted);
    }

    .stars {
      color: var(--accent-dark);
      letter-spacing: 0.05em;
      font-weight: 700;
    }

    .hero-visual {
      background: linear-gradient(145deg, #18181b 0%, #27272a 100%);
      border-radius: 1.25rem;
      padding: clamp(1.5rem, 3vw, 2.5rem);
      box-shadow: var(--shadow-lg);
      display: flex;
      align-items: center;
      justify-content: center;
      aspect-ratio: 4 / 3;
      position: relative;
      overflow: hidden;
    }

    .hero-visual svg {
      width: 100%;
      height: auto;
      max-height: 340px;
    }

    /* 7. BARRA DE VALIDACIÓN SOCIAL / GARANTÍAS */
    .trust-strip {
      background-color: var(--surface);
      border-block: 1px solid var(--border);
      padding-block: 1.75rem;
    }

    .trust-items {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(min(100%, 220px), 1fr));
      gap: 1.25rem;
    }

    .trust-item {
      display: flex;
      align-items: center;
      gap: 0.75rem;
      font-weight: 600;
      font-size: 0.95rem;
      color: var(--text);
    }

    .trust-icon {
      flex-shrink: 0;
      width: 40px;
      height: 40px;
      border-radius: 0.5rem;
      background-color: var(--surface-alt);
      color: var(--accent-dark);
      display: inline-flex;
      align-items: center;
      justify-content: center;
    }

    /* 8. MATRIZ DE BENEFICIOS CON CONTAINER QUERIES */
    .card-container {
      container-type: inline-size;
      container-name: benefit-card;
    }

    .card {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 1rem;
      padding: 1.75rem;
      height: 100%;
      box-shadow: var(--shadow-sm);
      transition: transform var(--transition), box-shadow var(--transition);
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }

    .card:hover {
      transform: translateY(-4px);
      box-shadow: var(--shadow-lg);
    }

    .card-icon {
      width: 48px;
      height: 48px;
      border-radius: 0.75rem;
      background-color: var(--primary);
      color: var(--accent);
      display: inline-flex;
      align-items: center;
      justify-content: center;
      flex-shrink: 0;
    }

    .card p {
      color: var(--text-muted);
      font-size: 0.975rem;
    }

    @container benefit-card (min-width: 420px) {
      .card {
        flex-direction: row;
        align-items: flex-start;
      }
    }

    /* 9. ACORDEÓN FAQ ACCESIBLE */
    .faq-list {
      max-width: 780px;
      margin-inline: auto;
      display: flex;
      flex-direction: column;
      gap: 0.875rem;
    }

    .faq-item {
      background-color: var(--surface);
      border: 1px solid var(--border);
      border-radius: 0.75rem;
      overflow: hidden;
    }

    .faq-trigger {
      width: 100%;
      min-height: 54px;
      padding: 1rem 1.25rem;
      background: none;
      border: none;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 1rem;
      text-align: start;
      font-family: inherit;
      font-size: 1.05rem;
      font-weight: 600;
      color: var(--text);
      cursor: pointer;
    }

    .faq-trigger:hover {
      background-color: var(--surface-alt);
    }

    .faq-chevron {
      flex-shrink: 0;
      transition: transform var(--transition);
      color: var(--accent-dark);
    }

    .faq-trigger[aria-expanded="true"] .faq-chevron {
      transform: rotate(180deg);
    }

    .faq-panel {
      padding: 0 1.25rem 1.25rem;
      color: var(--text-muted);
      border-top: 1px solid var(--border);
      padding-block-start: 0.875rem;
    }

    .faq-panel[hidden] {
      display: none;
    }

    /* 10. CAJA DE CONVERSIÓN DIRECTA WHATSAPP */
    .cta-box {
      background-color: var(--primary);
      color: #ffffff;
      border-radius: 1.25rem;
      padding: clamp(2rem, 4vw, 3.5rem);
      box-shadow: var(--shadow-lg);
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(min(100%, 340px), 1fr));
      gap: 2rem;
      align-items: center;
    }

    .cta-box h2 {
      color: #ffffff;
      margin-block-end: 0.75rem;
    }

    .cta-box p {
      color: #d4d4d8;
    }

    .cta-form {
      background-color: var(--surface);
      color: var(--text);
      padding: 1.5rem;
      border-radius: 0.875rem;
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }

    .form-group {
      display: flex;
      flex-direction: column;
      gap: 0.4rem;
    }

    .form-group label {
      font-size: 0.9rem;
      font-weight: 600;
      color: var(--text);
    }

    .form-control {
      min-height: 46px;
      padding: 0.65rem 0.9rem;
      border: 1px solid var(--border);
      border-radius: 0.5rem;
      font-family: inherit;
      font-size: 1rem;
      color: var(--text);
      background-color: var(--bg);
    }

    /* 11. FOOTER MINIMALISTA */
    .site-footer {
      border-top: 1px solid var(--border);
      padding-block: 2rem;
      text-align: center;
      color: var(--text-muted);
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <!-- ENCABEZADO -->
  <header class="site-header">
    <div class="container nav-bar">
      <a href="#" class="brand-logo" aria-label="Inicio Catajoma">
        <span class="brand-badge" aria-hidden="true">
          <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round">
            <path d="M12 3l1.9 5.8L20 10.7l-6.1 1.9L12 18.4l-1.9-5.8L4 10.7l6.1-1.9L12 3z"/>
          </svg>
        </span>
        <span>Catajoma</span>
      </a>

      <a href="#contacto-whatsapp" class="btn btn-primary" aria-label="Solicitar asesoría de belleza por WhatsApp">
        <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
          <path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.38 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8v.5z"/>
        </svg>
        <span>Pedir por WhatsApp</span>
      </a>
    </div>
  </header>

  <main>
    <!-- HERO SECTION -->
    <section class="hero" aria-labelledby="hero-heading">
      <div class="container hero-grid">
        <div>
          <div class="hero-tag">
            <span class="hero-tag-dot" aria-hidden="true"></span>
            <span>Cotoca, Santa Cruz • Bolivia</span>
          </div>

          <h1 id="hero-heading" class="hero-title">
            Realza tu belleza natural con <span>productos seleccionados</span> para tu piel
          </h1>

          <p class="hero-subtitle">
            En <strong>Catajoma</strong> encuentras cosmética, cuidado facial y artículos de belleza listos para transformar tu rutina diaria, con asesoría personalizada y entrega coordinada en Cotoca y Santa Cruz.
          </p>

          <div class="hero-actions">
            <a href="#contacto-whatsapp" class="btn btn-accent">
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
                <path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.38 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8v.5z"/>
              </svg>
              <span>Consultar Catálogo por WhatsApp</span>
            </a>
            <a href="#beneficios" class="btn btn-outline">Ver Beneficios</a>
          </div>

          <div class="hero-proof">
            <span class="stars" aria-label="Calificación cinco estrellas">★★★★★</span>
            <span>Atención directa y asesoría personalizada sin compromiso</span>
          </div>
        </div>

        <!-- ILUSTRACIÓN VECTORIAL HERO (LCP OPTIMIZADO SIN LAZY LOAD) -->
        <div class="hero-visual">
          <svg width="480" height="360" viewBox="0 0 480 360" fill="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Ilustración estética de frascos de cuidado facial y belleza Catajoma" fetchpriority="high">
            <circle cx="240" cy="180" r="135" fill="#d97706" fill-opacity="0.14"/>
            <circle cx="240" cy="180" r="95" stroke="#d97706" stroke-width="1.5" stroke-dasharray="6 6"/>
            <!-- Frasco Sérum Principal -->
            <rect x="175" y="135" width="76" height="125" rx="14" fill="#fafaf9"/>
            <rect x="175" y="175" width="76" height="52" fill="#d97706" fill-opacity="0.2"/>
            <rect x="196" y="108" width="34" height="27" rx="4" fill="#d97706"/>
            <rect x="205" y="84" width="16" height="24" rx="8" fill="#e4e4e7"/>
            <line x1="192" y1="195" x2="234" y2="195" stroke="#18181b" stroke-width="3" stroke-linecap="round"/>
            <line x1="198" y1="206" x2="228" y2="206" stroke="#71717a" stroke-width="2" stroke-linecap="round"/>
            <!-- Crema Facial Complementaria -->
            <rect x="265" y="190" width="74" height="70" rx="12" fill="#e4e4e7"/>
            <rect x="262" y="172" width="80" height="20" rx="6" fill="#d97706"/>
            <line x1="282" y1="224" x2="322" y2="224" stroke="#18181b" stroke-width="3" stroke-linecap="round"/>
            <!-- Destellos -->
            <path d="M136 112L141 126L155 131L141 136L136 150L131 136L117 131L131 126L136 112Z" fill="#fbbf24"/>
            <path d="M342 96L345 105L354 108L345 111L342 120L339 111L330 108L339 105L342 96Z" fill="#fbbf24"/>
          </svg>
        </div>
      </div>
    </section>

    <!-- BARRA DE VALIDACIÓN Y GARANTÍAS -->
    <section class="trust-strip" aria-label="Garantías de servicio">
      <div class="container trust-items">
        <div class="trust-item">
          <span class="trust-icon" aria-hidden="true">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10z"/></svg>
          </span>
          <span>Productos 100% Originales</span>
        </div>
        <div class="trust-item">
          <span class="trust-icon" aria-hidden="true">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"/><circle cx="12" cy="10" r="3"/></svg>
          </span>
          <span>Entregas en Cotoca y Santa Cruz</span>
        </div>
        <div class="trust-item">
          <span class="trust-icon" aria-hidden="true">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M20.84 4.61a5.5 5.5 0 0 0-7.78 0L12 5.67l-1.06-1.06a5.5 5.5 0 0 0-7.78 7.78l1.06 1.06L12 21.23l7.78-7.78 1.06-1.06a5.5 5.5 0 0 0 0-7.78z"/></svg>
          </span>
          <span>Asesoría Según tu Tipo de Piel</span>
        </div>
        <div class="trust-item">
          <span class="trust-icon" aria-hidden="true">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="12" cy="12" r="10"/><polyline points="12 6 12 12 16 14"/></svg>
          </span>
          <span>Respuesta Rápida por WhatsApp</span>
        </div>
      </div>
    </section>

    <!-- MATRIZ DE BENEFICIOS -->
    <section id="beneficios" aria-labelledby="benefits-heading">
      <div class="container">
        <div class="section-header">
          <span class="section-eyebrow">Por qué elegir Catajoma</span>
          <h2 id="benefits-heading">Resultados visibles y una experiencia de compra sin complicaciones</h2>
          <p class="section-subtitle">
            Seleccionamos cada línea de belleza pensando en la salud de tu piel, tu comodidad y la seguridad de comprar localmente.
          </p>
        </div>

        <div class="grid-auto">
          <div class="card-container">
            <article class="card">
              <div class="card-icon" aria-hidden="true">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                  <path d="M12 2.69l5.66 5.66a8 8 0 1 1-11.31 0z"/>
                </svg>
              </div>
              <div>
                <h3>Cuidado Facial Efectivo</h3>
                <p>Fórmulas diseñadas para hidratar, limpiar y revitalizar tu rostro frente al clima cálido de Santa Cruz.</p>
              </div>
            </article>
          </div>

          <div class="card-container">
            <article class="card">
              <div class="card-icon" aria-hidden="true">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                  <polygon points="12 2 15.09 8.26 22 9.27 17 14.14 18.18 21.02 12 17.77 5.82 21.02 7 14.14 2 9.27 8.91 8.26 12 2"/>
                </svg>
              </div>
              <div>
                <h3>Cosmética de Alto Acabado</h3>
                <p>Maquillaje y accesorios de belleza seleccionados por su durabilidad, pigmentación y suavidad al aplicar.</p>
              </div>
            </article>
          </div>

          <div class="card-container">
            <article class="card">
              <div class="card-icon" aria-hidden="true">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                  <path d="M17 21v-2a4 4 0 0 0-4-4H5a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M23 21v-2a4 4 0 0 0-3-3.87"/><path d="M16 3.13a4 4 0 0 1 0 7.75"/>
                </svg>
              </div>
              <div>
                <h3>Recomendación Personalizada</h3>
                <p>Te ayudamos a elegir exactamente lo que necesitas según tu piel y presupuesto, evitando compras innecesarias.</p>
              </div>
            </article>
          </div>
        </div>
      </div>
    </section>

    <!-- PREGUNTAS FRECUENTES (ACORDEÓN ACCESIBLE) -->
    <section id="faq" aria-labelledby="faq-heading">
      <div class="container">
        <div class="section-header">
          <span class="section-eyebrow">Resolvemos tus dudas</span>
          <h2 id="faq-heading">Preguntas Frecuentes</h2>
        </div>

        <div class="faq-list" id="faq-accordion">
          <div class="faq-item">
            <h3>
              <button type="button" class="faq-trigger" aria-expanded="false" aria-controls="faq-panel-1" id="faq-btn-1">
                <span>¿Cómo puedo ver los productos disponibles y sus precios?</span>
                <svg class="faq-chevron" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
                  <polyline points="6 9 12 15 18 9"/>
                </svg>
              </button>
            </h3>
            <div id="faq-panel-1" class="faq-panel" role="region" aria-labelledby="faq-btn-1" hidden>
              <p>Al escribirnos a nuestro WhatsApp oficial, te enviamos de inmediato el catálogo actualizado con disponibilidad y precios vigentes para que elijas con total claridad.</p>
            </div>
          </div>

          <div class="faq-item">
            <h3>
              <button type="button" class="faq-trigger" aria-expanded="false" aria-controls="faq-panel-2" id="faq-btn-2">
                <span>¿Realizan entregas en Cotoca y Santa Cruz de la Sierra?</span>
                <svg class="faq-chevron" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
                  <polyline points="6 9 12 15 18 9"/>
                </svg>
              </button>
            </h3>
            <div id="faq-panel-2" class="faq-panel" role="region" aria-labelledby="faq-btn-2" hidden>
              <p>Sí, coordinamos entregas rápidas dentro de Cotoca y envíos hacia Santa Cruz de la Sierra en horarios convenientes para ti.</p>
            </div>
          </div>

          <div class="faq-item">
            <h3>
              <button type="button" class="faq-trigger" aria-expanded="false" aria-controls="faq-panel-3" id="faq-btn-3">
                <span>¿Puedo pedir recomendación si no sé qué producto elegir?</span>
                <svg class="faq-chevron" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
                  <polyline points="6 9 12 15 18 9"/>
                </svg>
              </button>
            </h3>
            <div id="faq-panel-3" class="faq-panel" role="region" aria-labelledby="faq-btn-3" hidden>
              <p>Por supuesto. Cuéntanos qué buscas mejorar o qué tipo de rutina deseas armar y te orientaremos paso a paso antes de confirmar tu pedido.</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- CAJA DE CONVERSIÓN DIRECTA A WHATSAPP -->
    <section id="contacto-whatsapp" aria-labelledby="cta-heading">
      <div class="container">
        <div class="cta-box">
          <div>
            <span class="section-eyebrow" style="color: #fbbf24;">Atención Directa</span>
            <h2 id="cta-heading">Recibe hoy el catálogo de Catajoma en tu WhatsApp</h2>
            <p>
              Selecciona qué categoría de productos de belleza te interesa y abre una conversación directa con nuestro equipo en Cotoca, Santa Cruz.
            </p>
          </div>

          <form class="cta-form" id="whatsapp-lead-form">
            <div class="form-group">
              <label for="lead-name">Tu nombre (opcional)</label>
              <input type="text" id="lead-name" class="form-control" placeholder="Ej. Camila" maxlength="60" autocomplete="given-name">
            </div>

            <div class="form-group">
              <label for="lead-interest">¿Qué productos buscas?</label>
              <select id="lead-interest" class="form-control">
                <option value="Catálogo completo de productos de belleza">Catálogo completo de belleza</option>
                <option value="Cuidado facial y skincare">Cuidado facial y skincare</option>
                <option value="Maquillaje y cosmética">Maquillaje y cosmética</option>
                <option value="Cuidado capilar y corporal">Cuidado capilar y corporal</option>
                <option value="Asesoría personalizada para mi rutina">Asesoría personalizada</option>
              </select>
            </div>

            <button type="submit" class="btn btn-accent">
              <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" aria-hidden="true">
                <path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.38 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8v.5z"/>
              </svg>
              <span>Continuar a WhatsApp</span>
            </button>
          </form>
        </div>
      </div>
    </section>
  </main>

  <!-- FOOTER -->
  <footer class="site-footer">
    <div class="container">
      <p><strong>Catajoma</strong> — Productos de Belleza en Cotoca, Santa Cruz, Bolivia.</p>
      <p style="margin-block-start: 0.35rem;">© <span id="current-year"></span> Catajoma. Todos los derechos reservados.</p>
    </div>
  </footer>

  <script>
    document.addEventListener('DOMContentLoaded', () => {
      // Año actual seguro mediante textContent
      const yearEl = document.getElementById('current-year');
      if (yearEl) {
        yearEl.textContent = String(new Date().getFullYear());
      }

      // Acordeón FAQ accesible con delegación de eventos
      const faqContainer = document.getElementById('faq-accordion');
      if (faqContainer) {
        faqContainer.addEventListener('click', (event) => {
          const trigger = event.target.closest('.faq-trigger');
          if (!trigger) return;

          const isExpanded = trigger.getAttribute('aria-expanded') === 'true';
          const panelId = trigger.getAttribute('aria-controls');
          const panel = panelId ? document.getElementById(panelId) : null;

          // Cerrar otros paneles abiertos para mantener limpieza visual
          faqContainer.querySelectorAll('.faq-trigger').forEach((btn) => {
            btn.setAttribute('aria-expanded', 'false');
            const otherPanelId = btn.getAttribute('aria-controls');
            const otherPanel = otherPanelId ? document.getElementById(otherPanelId) : null;
            if (otherPanel) otherPanel.hidden = true;
          });

          if (!isExpanded && panel) {
            trigger.setAttribute('aria-expanded', 'true');
            panel.hidden = false;
          }
        });
      }

      // Despacho seguro a WhatsApp
      const whatsappForm = document.getElementById('whatsapp-lead-form');
      if (whatsappForm) {
        whatsappForm.addEventListener('submit', (event) => {
          event.preventDefault();

          const phone = '59176694062';
          const nameInput = document.getElementById('lead-name');
          const interestSelect = document.getElementById('lead-interest');

          const rawName = nameInput ? nameInput.value.trim() : '';
          const interest = interestSelect ? interestSelect.value : 'Productos de belleza';

          const greeting = rawName
            ? `Hola Catajoma, soy ${rawName}.`
            : 'Hola Catajoma.';

          const message = `${greeting} Me interesa recibir información sobre: ${interest}. (Desde Cotoca / Santa Cruz)`;
          const targetUrl = `https://wa.me/${phone}?text=${encodeURIComponent(message)}`;

          if (targetUrl.startsWith('https://wa.me/')) {
            window.open(targetUrl, '_blank', 'noopener,noreferrer');
          }
        });
      }
    });
  </script>
</body>
</html>
