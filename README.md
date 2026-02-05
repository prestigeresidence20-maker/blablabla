# blablabla<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Prestige Residence — Conciergerie & Nettoyage</title>
  <meta name="description" content="Conciergerie et nettoyage haut de gamme à Ajaccio, Porticcio et Coti-Chiavari. Gestion d’annonces, ménage, linge, entretien et services sur mesure." />

  <style>
    :root{
      --bg-wood-1:#e7e1d8;
      --bg-wood-2:#d9d1c6;<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Prestige Residence — Conciergerie & Nettoyage</title>
  <meta name="description" content="Conciergerie et nettoyage haut de gamme à Ajaccio, Porticcio et Coti-Chiavari. Gestion d’annonces, ménage, linge, entretien et services sur mesure." />

  <style>
    :root{
      --bg-wood-1:#e7e1d8;
      --bg-wood-2:#d9d1c6;
      --ink:#141414;
      --muted:#4b4b4b;
      --bar:#111214;
      --barText:#e9ecef;
      --accent:#1f6f6a;
      --card:#ffffffcc;
      --shadow: 0 10px 30px rgba(0,0,0,.10);
      --radius: 18px;
      --max: 1080px;
    }

    /* --- Faux bois (CSS) --- */
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji","Segoe UI Emoji";
      color:var(--ink);
      background:
        linear-gradient(0deg, rgba(255,255,255,.25), rgba(255,255,255,.25)),
        repeating-linear-gradient(
          90deg,
          var(--bg-wood-1) 0px,
          var(--bg-wood-1) 10px,
          var(--bg-wood-2) 22px,
          var(--bg-wood-1) 34px
        );
      background-attachment: fixed;
    }

    a{ color:inherit; text-decoration:none; }
    .container{ width:min(var(--max), calc(100% - 40px)); margin:0 auto; }

    /* --- Header --- */
    header{
      position:sticky; top:0; z-index:20;
      backdrop-filter: blur(10px);
      background: rgba(255,255,255,.55);
      border-bottom: 1px solid rgba(0,0,0,.08);
    }
    .topbar{
      display:flex; align-items:center; justify-content:space-between;
      padding:12px 0;
      gap:14px;
    }
    .brandline{
      display:flex; align-items:center; gap:12px;
      min-width: 220px;
    }
    .logo{
      width:42px; height:42px;
      display:grid; place-items:center;
      border-radius: 999px;
      background: rgba(255,255,255,.65);
      border:1px solid rgba(0,0,0,.12);
      box-shadow: 0 6px 16px rgba(0,0,0,.08);
    }
    .brandtext strong{
      display:block;
      font-weight: 800;
      letter-spacing: .08em;
      text-transform: uppercase;
      font-size: 12px;
      line-height: 1.05;
    }
    .brandtext span{
      font-size: 12px;
      color: var(--muted);
    }
    nav{
      display:flex; gap:14px; flex-wrap:wrap; justify-content:flex-end;
    }
    nav a{
      font-size: 14px;
      padding:8px 10px;
      border-radius: 999px;
      border:1px solid rgba(0,0,0,.10);
      background: rgba(255,255,255,.45);
    }
    nav a:hover{ background: rgba(255,255,255,.75); }

    .cta{
      display:flex; gap:10px; align-items:center; justify-content:flex-end;
      min-width: 240px;
    }
    .btn{
      border:0;
      border-radius:999px;
      padding:10px 14px;
      font-weight:700;
      cursor:pointer;
      box-shadow: 0 10px 22px rgba(0,0,0,.10);
      transition: transform .08s ease;
      display:inline-flex; align-items:center; gap:8px;
      white-space: nowrap;
    }
    .btn:active{ transform: translateY(1px); }
    .btn-primary{ background: var(--bar); color: var(--barText); }
    .btn-ghost{
      background: rgba(255,255,255,.65);
      border:1px solid rgba(0,0,0,.12);
      box-shadow:none;
      color: var(--ink);
    }

    /* --- Hero --- */
    .hero{ padding: 38px 0 22px; }
    .hero-grid{
      display:grid;
      grid-template-columns: 1.2fr .8fr;
      gap: 18px;
      align-items: stretch;
    }
    .hero-card{
      background: var(--card);
      border: 1px solid rgba(0,0,0,.10);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      padding: 26px;
      position: relative;
      overflow:hidden;
    }
    .tagline{
      display:flex; align-items:center; gap:14px;
      justify-content: space-between;
      font-weight:700;
      letter-spacing:.08em;
      text-transform: uppercase;
      color: var(--muted);
      font-size: 12px;
      margin-bottom: 14px;
    }
    .tagline .line{
      height: 1px; flex:1;
      background: rgba(0,0,0,.15);
      border-radius: 999px;
    }
    h1{
      margin:0;
      font-size: clamp(28px, 4.2vw, 44px);
      letter-spacing: .06em;
      text-transform: uppercase;
      line-height: 1.05;
    }
    .zones{
      margin: 10px 0 0;
      font-size: 18px;
      color: var(--muted);
    }
    .hero p{
      margin: 14px 0 0;
      font-size: 16px;
      color: #2a2a2a;
      line-height: 1.6;
      max-width: 58ch;
    }

    .contact-card{
      display:flex;
      flex-direction:column;
      gap: 14px;
      justify-content: space-between;
    }
    .pill{
      display:flex; gap:10px; align-items:center;
      padding: 12px 14px;
      background: rgba(255,255,255,.72);
      border:1px solid rgba(0,0,0,.10);
      border-radius: 14px;
    }
    .pill small{ display:block; color: var(--muted); font-weight:700; letter-spacing:.04em; }
    .pill strong{ display:block; font-size: 16px; }
    .icon{
      width:40px; height:40px;
      border-radius: 14px;
      background: rgba(0,0,0,.06);
      display:grid; place-items:center;
      border:1px solid rgba(0,0,0,.10);
      flex: 0 0 auto;
    }

    /* --- Bandeau "Nos services" --- */
    .section-bar{
      margin: 18px 0 0;
      background: var(--bar);
      color: var(--barText);
      padding: 16px 0;
    }
    .bar-title{
      display:flex; align-items:center; justify-content:center; gap:18px;
      letter-spacing:.14em;
      text-transform:uppercase;
      font-weight:800;
      font-size: 18px;
    }
    .bar-title::before,.bar-title::after{
      content:"";
      height: 2px;
      width: 70px;
      background: rgba(255,255,255,.35);
      border-radius: 999px;
    }

    /* --- Services --- */
    .services{ padding: 26px 0 34px; }
    .grid{
      display:grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 14px;
      margin-top: 18px;
    }
    .service{
      background: var(--card);
      border: 1px solid rgba(0,0,0,.10);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      padding: 18px;
      display:flex;
      gap: 14px;
      align-items:flex-start;
    }
    .service h3{
      margin:0;
      font-size: 16px;
      letter-spacing:.02em;
    }
    .service p{
      margin:6px 0 0;
      color: var(--muted);
      line-height: 1.5;
      font-size: 14px;
    }
    .service .icon{
      width:46px; height:46px;
      border-radius: 16px;
      background: rgba(255,255,255,.65);
    }

    /* --- À propos / Process --- */
    .about{
      padding: 0 0 34px;
    }
    .about-wrap{
      display:grid;
      grid-template-columns: 1fr 1fr;
      gap: 14px;
    }
    .panel{
      background: var(--card);
      border: 1px solid rgba(0,0,0,.10);
      border-radius: var(--radius);
      box-shadow: var(--shadow);
      padding: 20px;
    }
    .panel h2{
      margin:0 0 10px;
      letter-spacing: .08em;
      text-transform: uppercase;
      font-size: 16px;
    }
    ul.steps{
      margin: 0;
      padding-left: 18px;
      color: var(--muted);
      line-height: 1.7;
    }

    /* --- Contact --- */
    .contact{
      padding: 0 0 40px;
    }
    form{
      display:grid;
      gap: 10px;
      margin-top: 12px;
    }
    input, textarea{
      width:100%;
      padding: 12px 12px;
      border-radius: 14px;
      border: 1px solid rgba(0,0,0,.12);
      background: rgba(255,255,255,.75);
      font: inherit;
      outline: none;
    }
    textarea{ min-height: 110px; resize: vertical; }

    footer{
      background: rgba(0,0,0,.85);
      color: rgba(255,255,255,.88);
      padding: 18px 0;
    }
    .footer{
      display:flex; flex-wrap:wrap; gap:10px;
      align-items:center; justify-content:space-between;
      font-size: 14px;
    }
    .footer a{ text-decoration: underline; text-underline-offset: 3px; }

    /* --- Responsive --- */
    @media (max-width: 900px){
      .hero-grid{ grid-template-columns: 1fr; }
      .cta{ min-width: auto; }
      .grid{ grid-template-columns: 1fr; }
      .about-wrap{ grid-template-columns: 1fr; }
      nav{ display:none; } /* simplifié mobile */
    }
  </style>
</head>

<body>
  <header>
    <div class="container topbar">
      <div class="brandline">
        <div class="logo" aria-hidden="true">
          <!-- Logo arbre minimal (SVG) -->
          <svg width="26" height="26" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
            <circle cx="32" cy="32" r="29" stroke="#111214" stroke-width="4"/>
            <path d="M32 54V30" stroke="#111214" stroke-width="5" stroke-linecap="round"/>
            <path d="M32 30C24 20 16 18 14 14" stroke="#111214" stroke-width="4" stroke-linecap="round"/>
            <path d="M32 30C40 20 48 18 50 14" stroke="#111214" stroke-width="4" stroke-linecap="round"/>
            <path d="M32 30C28 18 26 14 22 10" stroke="#111214" stroke-width="4" stroke-linecap="round"/>
            <path d="M32 30C36 18 38 14 42 10" stroke="#111214" stroke-width="4" stroke-linecap="round"/>
            <path d="M24 54H40" stroke="#111214" stroke-width="5" stroke-linecap="round"/>
          </svg>
        </div>
        <div class="brandtext">
          <strong>Conciergerie · Nettoyage</strong>
          <span>Prestige Residence</span>
        </div>
      </div>

      <nav aria-label="Navigation">
        <a href="#services">Services</a>
        <a href="#apropos">Fonctionnement</a>
        <a href="#contact">Contact</a>
      </nav>

      <div class="cta">
        <a class="btn btn-ghost" href="tel:+33682916874" aria-label="Appeler Prestige Residence">📞 Appeler</a>
        <a class="btn btn-primary" href="#contact">Devis gratuit</a>
      </div>
    </div>
  </header>

  <main>
    <!-- HERO -->
    <section class="hero">
      <div class="container hero-grid">
        <div class="hero-card">
          <div class="tagline">
            <span>Conciergerie & Nettoyage</span><span class="line"></span><span>Haut de gamme</span>
          </div>

          <h1>Prestige Residence</h1>
          <div class="zones">Ajaccio · Porticcio · Coti-Chiavari</div>

          <p>
            Nous prenons en charge votre logement de A à Z : gestion des annonces, accueil,
            ménage professionnel, linge, entretien intérieur/extérieur et services sur mesure.
            Objectif : une expérience irréprochable pour vos voyageurs et une tranquillité totale pour vous.
          </p>
        </div>

        <aside class="hero-card contact-card" aria-label="Coordonnées">
          <div class="pill">
            <div class="icon" aria-hidden="true">📞</div>
            <div>
              <small>Téléphone</small>
              <strong><a href="tel:+33682916874">06 82 91 68 74</a></strong>
            </div>
          </div>

          <div class="pill">
            <div class="icon" aria-hidden="true">✉️</div>
            <div>
              <small>Email</small>
              <strong><a href="mailto:prestige.residence20@gmail.com">prestige.residence20@gmail.com</a></strong>
            </div>
          </div>

          <div class="pill">
            <div class="icon" aria-hidden="true">✅</div>
            <div>
              <small>Devis</small>
              <strong>Gratuit & sans engagement</strong>
            </div>
          </div>

          <a class="btn btn-primary" href="#contact">Demander un devis</a>
        </aside>
      </div>
    </section>

    <!-- BANDEAU -->
    <div class="section-bar" role="presentation">
      <div class="container">
        <div class="bar-title">Nos services</div>
      </div>
    </div>

    <!-- SERVICES -->
    <section class="services" id="services">
      <div class="container">
        <div class="grid">
          <article class="service">
            <div class="icon" aria-hidden="true">🗂️</div>
            <div>
              <h3>Gestion complète des annonces</h3>
              <p>Airbnb, Booking, etc. Optimisation, calendrier, messages voyageurs, check-in / check-out.</p>
            </div>
          </article>

          <article class="service">
            <div class="icon" aria-hidden="true">🧼</div>
            <div>
              <h3>Nettoyage professionnel</h3>
              <p>Préparation haut de gamme du logement, contrôle qualité et réassort au quotidien.</p>
            </div>
          </article>

          <article class="service">
            <div class="icon" aria-hidden="true">🧺</div>
            <div>
              <h3>Fourniture & gestion du linge</h3>
              <p>Draps, serviettes, repassage, rotation et suivi pour un rendu impeccable.</p>
            </div>
          </article>

          <article class="service">
            <div class="icon" aria-hidden="true">🏡</div>
            <div>
              <h3>Entretien intérieur & extérieur</h3>
              <p>Petite maintenance, jardin/terrasse, gardiennage et passages réguliers.</p>
            </div>
          </article>

          <article class="service">
            <div class="icon" aria-hidden="true">🚗</div>
            <div>
              <h3>Courses, transports & livraisons</h3>
              <p>Services pratiques : courses avant arrivée, livraisons, transferts selon besoins.</p>
            </div>
          </article>

          <article class="service">
            <div class="icon" aria-hidden="true">🤝</div>
            <div>
              <h3>Service sur mesure</h3>
              <p>Une conciergerie flexible : on s’adapte à votre logement et à vos attentes.</p>
            </div>
          </article>
        </div>
      </div>
    </section>

    <!-- A PROPOS / PROCESS -->
    <section class="about" id="apropos">
      <div class="container about-wrap">
        <div class="panel">
          <h2>Notre promesse</h2>
          <p style="margin:0;color:var(--muted);line-height:1.7;">
            Une présentation irréprochable, des voyageurs bien accompagnés,
            et un suivi rigoureux entre chaque séjour.
          </p>
        </div>

        <div class="panel">
          <h2>Comment ça marche</h2>
          <ul class="steps">
            <li>Échange & visite du logement (si nécessaire).</li>
            <li>Proposition claire : prestations + fréquence + tarifs.</li>
            <li>Mise en place : accès, checklists, linge, standards qualité.</li>
            <li>Suivi continu : rapports, photos, recommandations.</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- CONTACT -->
    <section class="contact" id="contact">
      <div class="container">
        <div class="panel">
          <h2>Demander un devis gratuit</h2>
          <p style="margin:0;color:var(--muted);line-height:1.7;">
            Décris ton logement (type, nombre de couchages, localisation, besoins) et on te répond rapidement.
          </p>

          <!-- Formulaire: envoi mail via "mailto" (simple). Pour un vrai site, on branchera un formulaire serveur. -->
          <form id="devisForm">
            <input name="nom" placeholder="Votre nom" autocomplete="name" required />
            <input name="tel" placeholder="Téléphone" autocomplete="tel" />
            <input name="email" placeholder="Email" type="email" autocomplete="email" required />
            <textarea name="message" placeholder="Votre demande (logement, services souhaités, dates, etc.)" required></textarea>
            <div style="display:flex; gap:10px; flex-wrap:wrap;">
              <button class="btn btn-primary" type="submit">Envoyer la demande</button>
              <a class="btn btn-ghost" href="mailto:prestige.residence20@gmail.com">Écrire un email</a>
              <a class="btn btn-ghost" href="tel:+33682916874">Appeler</a>
            </div>
            <small style="color:var(--muted);">
              Astuce : pour un traitement plus rapide, ajoute si possible l’adresse (ou quartier) et des photos.
            </small>
          </form>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <div class="container footer">
      <div>© <span id="year"></span> Prestige Residence — Conciergerie · Nettoyage</div>
      <div>
        <a href="tel:+33682916874">06 82 91 68 74</a> ·
        <a href="mailto:prestige.residence20@gmail.com">prestige.residence20@gmail.com</a>
      </div>
    </div>
  </footer>

  <script>
    // Année auto
    document.getElementById("year").textContent = new Date().getFullYear();

    // Formulaire -> compose un mail (simple, sans serveur)
    const form = document.getElementById("devisForm");
    form.addEventListener("submit", (e) => {
      e.preventDefault();
      const data = new FormData(form);
      const nom = data.get("nom");
      const tel = data.get("tel");
      const email = data.get("email");
      const message = data.get("message");

      const subject = encodeURIComponent("Demande de devis — Prestige Residence");
      const body = encodeURIComponent(
`Nom: ${nom}
Téléphone: ${tel || "-"}
Email: ${email}

Message:
${message}
`
      );

      window.location.href = `mailto:prestige.residence20@gmail.com?subject=${subject}&body=${body}`;
    });
  </script>
</body>
</html>
      --ink:#141414;
      --muted:#4b4b4b;
      --bar:#111214;
      --barText:#e9ecef;
      --accent:#1f6f6a;
      --card:#ffffffcc;
      --shadow: 0 10px 30px rgba(0,0,0,.10);
      --radius: 18px;
      --max: 1080px;
    }

    /* --- Faux bois (CSS) --- */
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji","Segoe UI Emoji";
      color:var(--ink);
      background:
        linear-gradient(0deg, rgba(255,255,255,.25), rgba(255,255,255,.25)),
        repeating-linear-gradient(
          90deg,
          var(--bg-wood-1) 0px,
          var(--bg-wood-1) 10px,
          var(--bg-wood-2) 22px,
          var(--bg-wood-1) 34px
        );
      background-attachment: fixed;
    }

    a{ color:inherit; text-decoration:none; }
    .container{ width:min(var(--max), calc(100% - 40px)); margin:0 auto; }

    /* --- Header --- */
    header{
      position:sticky; top:0; z-index:20;
      backdrop-filter: blur(10px);
      background: rgba(255,255,255,.55);
      border-bottom: 1px solid rgba(0,0,0,.08);
    }
    .topbar{
      display:flex; align-items:center; justify-content:space-between;
      padding:12px 0;
      gap:14px;
    }
    .brandline{
      display:flex; align-items:center; gap:12px;
      min-width: 220px;
    }
    .logo{
      width:42px; height:42px;
      display:grid; place-items:center;
      border-radius: 999px;
      background: rgba(255,255,255,.65);
      border:1px solid rgba(0,0,0,.12);
      box-shadow: 0 6px 16px rgba(0,0,0,.08);
    }
    .brandtext strong{
      display:block;
