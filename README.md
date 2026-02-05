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
