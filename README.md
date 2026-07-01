<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>İrem & Yasin — Nişan Davetiyesi</title>

<meta property="og:title" content="İrem & Yasin — Nişan Davetiyesi">
<meta property="og:description" content="Mutluluğumuzu paylaşmanız dileğiyle… 3 Ağustos 2026 Pazartesi günü nişanımıza davetlisiniz.">
<meta property="og:image" content="https://yeces46.github.io/onizleme.jpg">
<meta property="og:url" content="https://yeces46.github.io/">
<meta property="og:type" content="website">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,500;0,600;0,700;1,400;1,500&family=Marcellus&family=Montserrat:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root{
    --ivory: #FBF6EC;
    --ivory-deep: #F1E6CF;
    --ink: #211D17;
    --ink-soft: #6B6052;
    --gold: #B6884F;
    --gold-light: #E3C17E;
    --gold-deep: #8C652F;
    --gold-pale: #ECDCAE;
    --sage: #6F8A55;
    --space-2: 16px;
    --space-3: 28px;
    --space-4: 48px;
    --space-5: 64px;
  }

  *{ box-sizing: border-box; }
  html{ scroll-behavior: smooth; }

  body{
    margin: 0;
    background: var(--ivory);
    color: var(--ink);
    font-family: 'Cormorant Garamond', serif;
    -webkit-font-smoothing: antialiased;
    overflow-x: hidden;
  }

  .stage{
    position: relative;
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: var(--space-4) var(--space-3);
    background:
      repeating-linear-gradient(135deg, transparent 0 18px, rgba(182,136,79,0.07) 18px 19px),
      radial-gradient(ellipse at 50% 0%, var(--ivory-deep) 0%, var(--ivory) 62%);
  }

  .card{
    position: relative;
    width: 100%;
    max-width: 660px;
    background: var(--ivory);
    padding: 0 0 var(--space-5);
    text-align: center;
    box-shadow:
      0 0 0 1px rgba(182,136,79,0.35),
      0 40px 110px -45px rgba(33, 29, 23, 0.65),
      0 0 90px -30px rgba(182,136,79,0.45);
    opacity: 0;
    transform: translateY(18px);
    animation: rise 1.1s cubic-bezier(.22,.61,.36,1) 0.15s forwards;
    overflow: hidden;
  }

  /* Gilded Corners */
  .corner-decor {
    position: absolute;
    width: 90px;
    height: 90px;
    pointer-events: none;
    z-index: 10;
    opacity: 0.8;
  }
  .corner-tl { top: 15px; left: 15px; }
  .corner-tr { top: 15px; right: 15px; transform: scaleX(-1); }
  .corner-bl { bottom: 15px; left: 15px; transform: scaleY(-1); }
  .corner-br { bottom: 15px; right: 15px; transform: scale(-1, -1); }

  @keyframes rise{ to{ opacity: 1; transform: translateY(0); } }

  .hero{ position: relative; width: 100%; line-height: 0; background: #110D08; border-bottom: 2px solid var(--gold-deep); }
  .hero svg{ display: block; width: 100%; height: auto; }

  .content{ position: relative; z-index: 2; padding: var(--space-4) var(--space-4) 0; }

  .eyebrow{
    font-family: 'Montserrat', sans-serif;
    font-size: 12px;
    letter-spacing: 6px;
    color: var(--gold-deep);
    text-transform: uppercase;
    margin: 0 0 var(--space-3);
    text-shadow: 0 1px 3px rgba(182,136,79,0.2);
    font-weight: 500;
  }

  .monogram{ width: 115px; margin: -85px auto var(--space-3); position: relative; z-index: 3; opacity: 0; animation: fadeIn 1.2s ease 0.4s forwards; filter: drop-shadow(0 10px 15px rgba(0,0,0,0.15)); }

  @keyframes fadeIn{ to{ opacity: 1; } }

  .names{
    font-family: 'Cormorant Garamond', serif;
    font-size: clamp(38px, 8vw, 56px);
    font-weight: 700;
    line-height: 1.16;
    letter-spacing: 3px;
    text-transform: uppercase;
    margin: 0 0 var(--space-2);
    background: linear-gradient(100deg, var(--gold-deep) 0%, #F5D79B 25%, var(--ink) 45%, var(--ink) 55%, #F5D79B 75%, var(--gold-deep) 100%);
    background-size: 220% auto;
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
    animation: shimmer 6s ease-in-out infinite;
    text-shadow: 0px 4px 20px rgba(182, 136, 79, 0.35);
  }
  @keyframes shimmer{ 0%{ background-position: 0% 50%; } 50%{ background-position: 100% 50%; } 100%{ background-position: 0% 50%; } }

  .names-row{ display: flex; align-items
